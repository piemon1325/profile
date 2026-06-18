# profile
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>โปรไฟล์ - วันชนะ สิงห์ชมภู</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Sarabun', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #eef2f3 0%, #8e9eab 100%);
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .profile-card {
            background: #ffffff;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            width: 100%;
            max-width: 500px;
            overflow: hidden;
            position: relative;
        }

        .card-header {
            background: linear-gradient(135deg, #104f55 0%, #32746D 100%);
            height: 120px;
        }

        .card-body {
            padding: 0 30px 35px 30px;
            text-align: center;
        }

        .profile-img-container {
            margin-top: -65px;
            margin-bottom: 15px;
        }

        .profile-img {
            width: 130px;
            height: 130px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #ffffff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            background-color: #f4f4f4;
        }

        .name-container {
            margin-bottom: 25px;
        }

        .name {
            font-size: 24px;
            font-weight: bold;
            color: #104f55;
        }

        .nickname {
            font-size: 18px;
            color: #bd922b;
            font-weight: 600;
            margin-top: 2px;
        }

        .info-table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 30px;
            text-align: left;
            font-size: 15px;
        }

        .info-table tr {
            border-bottom: 1px solid #f0f0f0;
        }

        .info-table tr:last-child {
            border-bottom: none;
        }

        .info-table td {
            padding: 12px 8px;
            vertical-align: top;
        }

        .info-table td.label {
            font-weight: bold;
            color: #555;
            width: 35%;
        }

        .info-table td.value {
            color: #222;
        }

        .contact-buttons {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 12px;
        }

        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            padding: 12px;
            border-radius: 10px;
            font-size: 14px;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        .btn-phone {
            background-color: #28a745;
            color: white;
        }

        .btn-email {
            background-color: #dc3545;
            color: white;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 10px rgba(0,0,0,0.15);
            opacity: 0.9;
        }
    </style>
</head>
<body>

    <div class="profile-card">
        <div class="card-header"></div>
        
        <div class="card-body">
            <!-- รูปโปรไฟล์จากลิงก์ Discord ของคุณจุ๊ย -->
            <div class="profile-img-container">
                <img src="https://cdn.discordapp.com/attachments/1422274727019417733/1517135198343532624/IMG_20260618_185126.jpg?ex=6a352dc2&is=6a33dc42&hm=35ff14e145a4b77c52a5df36df655600e2259354d9e4eb9351e6c81443237d51&" alt="วันชนะ สิงห์ชมภู" class="profile-img">
            </div>
            
            <div class="name-container">
                <div class="name">นายวันชนะ สิงห์ชมภู</div>
                <div class="nickname">(จุ๊ย)</div>
            </div>

            <table class="info-table">
                <tr>
                    <td class="label">รหัสนักศึกษา:</td>
                    <td class="value">694245011</td>
                </tr>
                <tr>
                    <td class="label">สาขาวิชา:</td>
                    <td class="value">วิทยาการคอมพิวเตอร์</td>
                </tr>
                <tr>
                    <td class="label">คณะ:</td>
                    <td class="value">วิทยาศาสตร์และเทคโนโลยี</td>
                </tr>
                <tr>
                    <td class="label">มหาวิทยาลัย:</td>
                    <td class="value">มหาวิทยาลัยราชภัฏหมู่บ้านจอมบึง</td>
                </tr>
            </table>
            
            <div class="contact-buttons">
                <a href="tel:0615216217" class="btn btn-phone">📞 โทร: 061-521-6217</a>
                <a href="mailto:694245011@mcru.ac.th" class="btn btn-email">📧 ส่งอีเมล</a>
            </div>
        </div>
    </div>

</body>
</html>
