<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>โปรไฟล์ของ วันชนะ สิงห์ชมภู</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 40px auto;
            background: #ffffff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        .profile-header {
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 30px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #4A90E2;
            margin-bottom: 15px;
        }

        .profile-header h1 {
            font-size: 2.2rem;
            color: #2c3e50;
            margin-bottom: 5px;
        }

        .profile-header p {
            font-size: 1.1rem;
            color: #7f8c8d;
            font-weight: 500;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            font-size: 1.4rem;
            color: #4A90E2;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }

        .section h2::after {
            content: '';
            flex: 1;
            margin-left: 15px;
            height: 2px;
            background-color: #e0e0e0;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }

        .info-item {
            background: #f8fafc;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #4A90E2;
        }

        .info-item strong {
            display: block;
            color: #555;
            font-size: 0.9rem;
            margin-bottom: 3px;
        }

        .skills-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .tag {
            background: #e1f5fe;
            color: #0288d1;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
        }

        @media (max-width: 600px) {
            .container {
                padding: 20px;
                margin: 10px auto;
            }
            .profile-header h1 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- ส่วนหัวโปรไฟล์ -->
        <div class="profile-header">
            <!-- เปลี่ยนลิงก์รูปภาพใน src เป็นรูปของคุณจุ๊ยได้เลยครับ -->
            <img src="https://via.placeholder.com/150" alt="รูปโปรไฟล์" class="profile-img">
            <h1>วันชนะ สิงห์ชมภู (จุ๊ย)</h1>
            <p>นักศึกษา สาขาวิชาวิทยาการคอมพิวเตอร์</p>
        </div>

        <!-- ข้อมูลส่วนตัว -->
        <div class="section">
            <h2>ข้อมูลส่วนตัว (About Me)</h2>
            <div class="info-grid">
                <div class="info-item">
                    <strong>รหัสนักศึกษา</strong>
                    694245011
                </div>
                <div class="info-item">
                    <strong>อีเมล</strong>
                    694245011@mcru.ac.th
                </div>
                <div class="info-item">
                    <strong>เบอร์โทรศัพท์</strong>
                    061-521-6217
                </div>
                <div class="info-item">
                    <strong>คณะ</strong>
                    วิทยาศาสตร์และเทคโนโลยี
                </div>
            </div>
        </div>

        <!-- ประวัติการศึกษา -->
        <div class="section">
            <h2>ประวัติการศึกษา (Education)</h2>
            <div class="info-item">
                <strong>กำลังศึกษา</strong>
                <p>สาขาวิชา วิทยาการคอมพิวเตอร์ คณะวิทยาศาสตร์และเทคโนโลยี</p>
                <p style="color: #7f8c8d; font-size: 0.95rem;">มหาวิทยาลัยราชภัฏหมู่บ้านจอมบึง</p>
            </div>
        </div>

        <!-- ทักษะความสามารถ (คุณจุ๊ยสามารถมาปรับแก้เพิ่มทักษะคอมพิวเตอร์ที่ถนัดได้เลยครับ) -->
        <div class="section">
            <h2>ทักษะความสามารถ (Skills)</h2>
            <div class="skills-tags">
                <span class="tag">Computer Science</span>
                <span class="tag">HTML5 / CSS3</span>
                <span class="tag">Programming</span>
                <span class="tag">Problem Solving</span>
                <span class="tag">Teamwork</span>
            </div>
        </div>
    </div>

</body>
</html>
