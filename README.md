<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">   
    <title>Food Shop - Đồ Ăn Vặt</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to bottom, #ff9a9e, #fad0c4);
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background: linear-gradient(to right, #ff6f61, #ff8566);
            color: white;
            padding: 15px 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            margin: 0;
            animation: fadeIn 2s;
        }
        nav {
            background-color: #ff8566;
            padding: 10px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: transform 0.3s ease;
        }
        nav a:hover {
            text-decoration: underline;
            transform: scale(1.1);
        }
        .menu {
            margin: 20px;
            padding: 15px;
            border: 3px solid #ff8566;
            border-radius: 15px;
            background-color: #ffffff;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            animation: slideIn 1.5s;
        }
        .menu h2 {
            text-align: center;
            color: #ff6f61;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            animation: fadeIn 1.5s;
        }
        table, th, td {
            border: 2px solid #ff9a9e;
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
        th {
            background: linear-gradient(to right, #ff8566, #ff6f61);
            color: white;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin: 20px;
        }
        .gallery img {
            width: 200px;
            height: 150px;
            border-radius: 15px;
            border: 3px solid #ddd;
            transition: transform 0.5s ease, box-shadow 0.5s ease;
        }
        .gallery img:hover {
            transform: scale(1.2);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
            border-color: #ff6f61;
        }
        .offer {
            margin: 20px;
            padding: 20px;
            border: 3px dashed #ff6f61;
            border-radius: 15px;
            background: linear-gradient(to right, #fff4f2, #ffe6e6);
            text-align: center;
            animation: pulse 2s infinite;
        }
        .offer p {
            font-size: 20px;
            color: #ff6f61;
            font-weight: bold;
        }
        .survey {
            margin: 20px;
            padding: 15px;
            border: 3px solid #ff8566;
            border-radius: 15px;
            background-color: #ffffff;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        .survey h2 {
            text-align: center;
            color: #ff6f61;
        }
        .survey label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .survey input, .survey textarea, .survey select, .survey button {
            width: 100%;
            margin-bottom: 10px;
            padding: 10px;
            border: 2px solid #ddd;
            border-radius: 8px;
        }
        .survey button {
            background: linear-gradient(to right, #ff6f61, #ff8566);
            color: white;
            border: none;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        .survey button:hover {
            background: linear-gradient(to right, #ff8566, #ff6f61);
        }
        .contact {
            margin: 20px;
            padding: 20px;
            border: 3px solid #ff8566;
            border-radius: 15px;
            background-color: #ffffff;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            text-align: center;
        }
        .contact p {
            margin: 10px 0;
            font-size: 18px;
        }
        .contact a {
            color: #ff6f61;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        .contact a:hover {
            color: #ff8566;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideIn {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
    </style>
</head>
<body>
    <header>
        <h1>Food Shop - Đồ Ăn Vặt Ngon</h1>
    </header>
    <nav>
        <a href="#menu">Menu</a>
        <a href="#gallery">Hình Ảnh</a>
        <a href="#survey">Khảo Sát</a>
        <a href="https://shopeefood.vn" target="_blank">Shopee Food</a>
    </nav>

    <section class="menu" id="menu">
        <h2>Thực Đơn</h2>
        <table>
            <thead>
                <tr>
                    <th>Món Ăn</th>
                    <th>Giá</th>
                    <th>Mô Tả</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Trà Sữa Trân Châu</td>
                    <td>30,000 VND</td>
                    <td>Thức uống giải khát, ngọt ngào.</td>
                </tr>
                <tr>
                    <td>Khoai Tây Chiên</td>
                    <td>20,000 VND</td>
                    <td>Khoai tây chiên giòn, ngon miệng.</td>
                </tr>
                <tr>
                    <td>Bánh Tráng Trộn</td>
                    <td>25,000 VND</td>
                    <td>Bánh tráng dai, vị đậm đà.</td>
                </tr>
                <tr>
                    <td>Gà Rán</td>
                    <td>40,000 VND</td>
                    <td>Gà rán giòn tan, thơm ngon.</td>
                </tr>
                <tr>
                    <td>Chè Thái</td>
                    <td>35,000 VND</td>
                    <td>Chè Thái thơm ngon, ngọt lịm.</td>
                </tr>
                <tr>
                    <td>Pizza Mini</td>
                    <td>50,000 VND</td>
                    <td>Pizza nhỏ xinh, đủ vị thơm ngon.</td>
                </tr>
                <tr>
                    <td>Sushi Cuộn</td>
                    <td>60,000 VND</td>
                    <td>Sushi cuộn tươi ngon, hấp dẫn.</td>
                </tr>
                <tr>
                    <td>Nem Chua Rán</td>
                    <td>30,000 VND</td>
                    <td>Nem chua rán giòn, đậm đà.</td>
                </tr>
                <tr>
                    <td>Bánh Bao</td>
                    <td>15,000 VND</td>
                    <td>Bánh bao nhân thịt thơm ngon.</td>
                </tr>
                <tr>
                    <td>Chân Gà Sả Tắc</td>
                    <td>40,000 VND</td>
                    <td>Chân gà sả tắc chua cay hấp dẫn.</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section class="gallery" id="gallery">
        <h2>Hình Ảnh Món Ăn</h2>
        <img src="image1.jpg" alt="Trà Sữa Trân Châu">
        <img src="image2.jpg" alt="Khoai Tây Chiên">
        <img src="image3.jpg" alt="Bánh Tráng Trộn">
        <img src="image4.jpg" alt="Gà Rán">
        <img src="image5.jpg" alt="Chè Thái">
        <img src="image6.jpg" alt="Pizza Mini">
        <img src="image7.jpg" alt="Sushi Cuộn">
        <img src="image8.jpg" alt="Nem Chua Rán">
        <img src="image9.jpg" alt="Bánh Bao">
        <img src="image10.jpg" alt="Chân Gà Sả Tắc">
    </section>

    <section class="offer">
        <p>Ưu Đãi Đặc Biệt: Giảm 10% cho hóa đơn trên 100,000 VND!</p>
    </section>

    <section class="survey" id="survey">
        <h2>Khảo Sát Sự Hài Lòng</h2>
        <form action="#" method="post">
            <label for="name">Tên của bạn:</label>
            <input type="text" id="name" name="name" required>

            <label for="rating">Bạn đánh giá thế nào về chất lượng món ăn?</label>
            <select id="rating" name="rating">
                <option value="excellent">Tuyệt vời</option>
                <option value="good">Tốt</option>
                <option value="average">Bình thường</option>
                <option value="poor">Kém</option>
            </select>

            <label for="feedback">Ý kiến đóng góp:</label>
            <textarea id="feedback" name="feedback" rows="4"></textarea>

            <button type="submit">Gửi Khảo Sát</button>
        </form>
    </section>

    <section class="contact">
        <h2>Liên Hệ</h2>
        <p>Số điện thoại: 0853534500</p>
        <p>Facebook: <a href="https://www.facebook.com/share/14tfycsk2a/" target="_blank">Chủ Quán</a></p>
    </section>
</body>
</html>
