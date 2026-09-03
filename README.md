<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>✨ เดลิเวอรี่ความอร่อย - Food Order</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            background-color: #f8fafc;
            color: #334155;
            margin: 0;
            padding: 40px 20px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
        }

        h2 {
            font-size: 2.5rem;
            color: #1e293b;
            text-align: center;
            margin-bottom: 10px;
            font-weight: 700;
        }

        .subtitle {
            text-align: center;
            color: #ef4444;
            font-size: 1.1rem;
            margin-bottom: 40px;
            font-weight: 500;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .menu-card {
            background: #ffffff;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03);
            transition: all 0.3s ease;
            border: 1px solid #e2e8f0;
        }

        .menu-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }

        .menu-image {
            width: 100%;
            height: 220px;
            object-fit: cover;
            background-color: #e2e8f0;
        }

        .menu-content {
            padding: 24px;
        }

        .menu-title {
            font-size: 1.4rem;
            font-weight: 600;
            margin: 0 0 15px 0;
            color: #0f172a;
        }

        .order-action {
            display: flex;
            align-items: center;
            gap: 12px;
            margin-top: 20px;
        }

        .qty-input {
            width: 70px;
            padding: 10px;
            border: 2px solid #cbd5e1;
            border-radius: 10px;
            font-size: 1rem;
            text-align: center;
            outline: none;
            transition: border-color 0.2s;
        }

        .qty-input:focus {
            border-color: #ef4444;
        }

        .order-btn {
            background-color: #ef4444;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 10px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            width: 100%;
            transition: background-color 0.2s;
        }

        .order-btn:hover {
            background-color: #dc2626;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>My Food Order Page</h2>
        <p class="subtitle">✨ The style is attribute of paragraph tag</p>

        <div class="menu-grid">
            
            <!-- เมนูที่ 1: ข้าวผัดปู (ใส่ชื่อไฟล์รูปภาพของคุณเรียบร้อยแล้ว) -->
            <div class="menu-card">
                <img src="https://unsplash.com" alt="Crab fried rice" class="menu-image">
rice" class="menu-image">
                <div class="menu-content">
                    <h3 class="menu-title">Crab Fried Rice 🦀</h3>
                    <div class="order-action">
                        <input type="number" class="qty-input" min="1" value="1" placeholder="Qty">
                        <button class="order-btn">สั่งซื้อเลย</button>
                    </div>
                </div>
            </div>

            <!-- เมนูที่ 2: เส้นหมี่ -->
            <div class="menu-card">
                <img src="https://unsplash.com" alt="Small rice noodles" class="menu-image">
                <div class="menu-content">
                    <h3 class="menu-title">Small Rice Noodles 🍜</h3>
                    <div class="order-action">
                        <input type="number" class="qty-input" min="1" value="1" placeholder="Qty">
                        <button class="order-btn">สั่งซื้อเลย</button>
                    </div>
                </div>
            </div>

        </div>
    </div>

</body>
</html>




