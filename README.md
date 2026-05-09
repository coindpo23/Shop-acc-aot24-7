<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KK Shop - Acc Game Zenless Zone Zero, Wuthering Waves</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            background: #0a0a0a;
            color: #fff;
        }
       .header {
            background: linear-gradient(180deg, #1a1a1a 0%, #0a0a0a 100%);
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #333;
            position: sticky;
            top: 0;
            z-index: 100;
        }
       .menu-icon {
            font-size: 1.8rem;
            cursor: pointer;
        }
       .user-info {
            background: rgba(255, 193, 7, 0.1);
            border: 1px solid #ffc107;
            padding: 6px 15px;
            border-radius: 6px;
            font-size: 0.9rem;
        }
       .user-info span {
            color: #ffc107;
            font-weight: 700;
        }
       .title-banner {
            text-align: center;
            padding: 20px;
            background: linear-gradient(135deg, #2d1b00 0%, #0a0a0a 100%);
            font-size: 1.8rem;
            font-weight: 800;
            color: #ffc107;
            text-shadow: 0 0 20px rgba(255, 193, 7, 0.5);
        }
       .container {
            padding: 15px;
            max-width: 600px;
            margin: auto;
        }
       .product-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 12px;
        }
       .product-card {
            background: #141414;
            border: 2px solid #2a2a2a;
            border-radius: 8px;
            overflow: hidden;
            transition: all 0.3s;
        }
       .product-card:hover {
            border-color: #ffc107;
            transform: translateY(-3px);
        }
       .product-img {
            width: 100%;
            height: 120px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.8rem;
            text-align: center;
            padding: 10px;
            font-weight: 700;
        }
       .product-img.zzz {
            background: linear-gradient(135deg, #00d4ff 0%, #090979 100%);
        }
       .product-img.ww {
            background: linear-gradient(135deg, #00ff88 0%, #003d1a 100%);
        }
       .product-img.zzz-reroll {
            background: linear-gradient(135deg, #ff6b00 0%, #7a2d00 100%);
        }
       .product-img.ww-reroll {
            background: linear-gradient(135deg, #ff0044 0%, #4a0000 100%);
        }
       .product-body {
            padding: 15px 10px;
            text-align: center;
        }
       .product-name {
            color: #ffc107;
            font-size: 1.1rem;
            font-weight: 700;
            margin-bottom: 12px;
            line-height: 1.3;
            min-height: 45px;
        }
       .stats {
            margin: 12px 0;
        }
       .stats-label {
            color: #888;
            font-size: 0.75rem;
            text-transform: uppercase;
        }
       .stats-value {
            color: #fff;
            font-size: 1.4rem;
            font-weight: 700;
            margin: 2px 0 8px;
        }
       .btn-explore {
            width: 100%;
            background: #ffc107;
            color: #000;
            border: none;
            padding: 12px;
            border-radius: 6px;
            font-size: 1rem;
            font-weight: 700;
            cursor: pointer;
            transition: 0.2s;
        }
       .btn-explore:hover {
            background: #ffdb4d;
        }
       .floating-btns {
            position: fixed;
            right: 15px;
            bottom: 80px;
            display: flex;
            flex-direction: column;
            gap: 10px;
            z-index: 99;
        }
       .float-btn {
            width: 55px;
            height: 55px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            text-decoration: none;
            box-shadow: 0 4px 15px rgba(0,0,0,0.4);
        }
       .fb-btn {
            background: #1877f2;
        }
       .call-btn {
            background: #25d366;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="menu-icon">☰</div>
        <div class="user-info">[514857] <span>kk: 0đ</span></div>
    </div>

    <div class="title-banner">
        ZENLESS ZONE ZERO - WUTHERING WAVES
    </div>

    <div class="container">
        <div class="product-grid">
            
            <div class="product-card">
                <div class="product-img zzz">ACC VIP<br>ZENLESS ZONE ZERO</div>
                <div class="product-body">
                    <div class="product-name">ACC VIP<br>ZENLESS</div>
                    <div class="stats">
                        <div class="stats-label">Số tài khoản</div>
                        <div class="stats-value">66</div>
                        <div class="stats-label">Đã bán</div>
                        <div class="stats-value">2,721</div>
                    </div>
                    <button class="btn-explore" onclick="alert('Chuyển đến trang ACC VIP ZZZ')">Khám Phá</button>
                </div>
            </div>

            <div class="product-card">
                <div class="product-img ww">TÀI KHOẢN VIP<br>WUTHERING WAVES</div>
                <div class="product-body">
                    <div class="product-name">ACC<br>WUTHERING<br>WAVES</div>
                    <div class="stats">
                        <div class="stats-label">Số tài khoản</div>
                        <div class="stats-value">636</div>
                        <div class="stats-label">Đã bán</div>
                        <div class="stats-value">1,471</div>
                    </div>
                    <button class="btn-explore" onclick="alert('Chuyển đến trang ACC VIP WW')">Khám Phá</button>
                </div>
            </div>

            <div class="product-card">
                <div class="product-img zzz-reroll">ACC REROLL<br>ZENLESS ZONE ZERO</div>
                <div class="product-body">
                    <div class="product-name">ACC REROLL<br>ZENLESS</div>
                    <div class="stats">
                        <div class="stats-label">Số tài khoản</div>
                        <div class="stats-value">120</div>
                        <div class="stats-label">Đã bán</div>
                        <div class="stats-value">5,832</div>
                    </div>
                    <button class="btn-explore" onclick="alert('Chuyển đến trang REROLL ZZZ')">Khám Phá</button>
                </div>
            </div>

            <div class="product-card">
                <div class="product-img ww-reroll">REROLL<br>WUTHERING WAVES</div>
                <div class="product-body">
                    <div class="product-name">REROLL<br>WUTHERING<br>WAVES</div>
                    <div class="stats">
                        <div class="stats-label">Số tài khoản</div>
                        <div class="stats-value">450</div>
                        <div class="stats-label">Đã bán</div>
                        <div class="stats-value">3,109</div>
                    </div>
                    <button class="btn-explore" onclick="alert('Chuyển đến trang REROLL WW')">Khám Phá</button>
                </div>
            </div>

        </div>
    </div>

    <div class="floating-btns">
        <a href="https://facebook.com" class="float-btn fb-btn">f</a>
        <a href="tel:09xxxxxxx" class="float-btn call-btn">📞</a>
    </div>

</body>
</html>
