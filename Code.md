# Wissarut.Det
<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>แนะนำตัว - DevPool 5</title>
    
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .card {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            max-width: 400px;
            text-align: center;
        }
        button {
            background-color: #7b2cbf;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 15px;
        }
        .hidden-text {
            display: none;
            margin-top: 15px;
            color: #666;
            font-style: italic;
        }
    </style>
</head>
<body>

    <div class="card">
        <h1>วิศรุต เดชโชติวณิชย์</h1>
        <p><strong>สังกัด:</strong> กฟส.ปทย.</p>
        
        <button id="toggle-btn">คลิกดูเหตุผลที่อยากเข้า DevPool</button>
        <p id="reason-text" class="hidden-text">
            อยากพัฒนาทักษะด้าน Digital Development เพื่อนำไปต่อยอดนวัตกรรมการตรวจจับการละเมิดใช้ไฟฟ้า และยกระดับระบบงานดิจิทัลของ กฟภ. ครับ
        </p>
    </div>

    <script>
        const btn = document.getElementById('toggle-btn');
        const text = document.getElementById('reason-text');

        btn.addEventListener('click', function() {
            if (text.style.display === 'block') {
                text.style.display = 'none';
                btn.textContent = 'คลิกดูเหตุผลที่อยากเข้า DevPool';
            } else {
                text.style.display = 'block';
                btn.textContent = 'ซ่อนข้อความ';
            }
        });
    </script>

</body>
</html>
