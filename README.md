<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .from-box {
            width: 450px;
            margin: 30px auto;
            padding: 20px;
            border: 2px solid #444;
            border-radius: 5px;
            font-family: Arial;
        }
        .from-box h2 {
            text-align: center;
            margin-top: 0;
        }
        label {
            display: inline-block;
            width: 120px;
            margin-bottom: 8px;
        }
        input[type="text"],
        input[type="number"],
        input[type="date"],
        select{
            width: 250px;
            padding: 5px;
        }
        .radio-group, checkbox-group {
            margin-left: 120px;
            margin-bottom: 10px;
        }
        button {
            margin-left: 120px;
            padding: 7px 15px;
        }
    </style>
</head>
<body>
    <div class="from-box">
        <h2>Đăng kí môn thi tốt nghiệp</h2>
        <label>Họ và Tên:</label>
        <input type="text"> <br>
        <label>CCCD:</label>
        <input type="number"> <br>
        <label>Ngày sinh:</label>
        <input type="date"> <br>
        <label>Giới Tính:</label>
        <div class="radio-group">
            <input type="radio" name="gender"> Nam
            <input type="radio" name="gender"> Nữ
        </div>
        <label>Môn Thi:</label>
        <div class="checkbox-group">
            <input type="checkbox"> Toán 
            <input type="checkbox"> Ngữ Văn 
            <input type="checkbox"> Tiếng Anh
        </div>
        <label>Tổ Hợp</label>
        <select>
            <option>Khoa học tự nhiên</option>
            <option>Khoa học xã hội</option>
        </select> <br> <br>
        <button>Gửi thông tin</button>
    </div>
    <!-- 2 nút ở ngoài khung-->
     <div class="nav-buttons">
        <button onclick="history.back()">Về trang trước</button>
        <button onclick="location.href='trang-ke-tiep.html'">Trang sau</button>
     </div>
</body>
</html>
