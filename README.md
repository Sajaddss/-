<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قالب وب‌سایت تبلیغاتی</title>
    <style>
        /* تنظیمات عمومی */
        body {
            font-family: "Arial", sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            color: #333;
        }

        /* هدر */
        header {
            background-color: #0078D7;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            margin: 5px 0 0;
        }

        /* منوی ناوبری */
        nav {
            display: flex;
            justify-content: center;
            background-color: #005bb5;
        }

        nav a {
            text-decoration: none;
            color: white;
            padding: 15px 20px;
            font-size: 1.2rem;
        }

        nav a:hover {
            background-color: #004494;
        }

        /* بخش اصلی */
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        /* کارت تبلیغات */
        .ad-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .ad-card:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .ad-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .ad-card .content {
            padding: 15px;
            text-align: center;
        }

        .ad-card h3 {
            margin: 0 0 10px;
            font-size: 1.5rem;
            color: #0078D7;
        }

        .ad-card p {
            margin: 0 0 15px;
            color: #555;
        }

        .ad-card a {
            display: inline-block;
            padding: 10px 15px;
            background-color: #0078D7;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
        }

        .ad-card a:hover {
            background-color: #005bb5;
        }

        /* فوتر */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <!-- هدر -->
    <header>
        <h1>وب‌سایت تبلیغاتی</h1>
        <p>نمایش بهترین تبلیغات شما</p>
    </header>

    <!-- منوی ناوبری -->
    <nav>
        <a href="#ads">تبلیغات</a>
        <a href="#about">درباره ما</a>
        <a href="#contact">تماس با ما</a>
    </nav>

    <!-- بخش تبلیغات -->
    <section id="ads" class="container">
        <!-- تبلیغ 1 -->
        <div class="ad-card">
            <img src="https://via.placeholder.com/300x200" alt="تبلیغ 1">
            <div class="content">
                <h3>محصول شماره 1</h3>
                <p>توضیحات کوتاه درباره محصول یا خدمت شماره 1.</p>
                <a href="#">مشاهده جزئیات</a>
            </div>
        </div>

        <!-- تبلیغ 2 -->
        <div class="ad-card">
            <img src="https://via.placeholder.com/300x200" alt="تبلیغ 2">
            <div class="content">
                <h3>محصول شماره 2</h3>
                <p>توضیحات کوتاه درباره محصول یا خدمت شماره 2.</p>
                <a href="#">مشاهده جزئیات</a>
            </div>
        </div>

        <!-- تبلیغ 3 -->
        <div class="ad-card">
            <img src="https://via.placeholder.com/300x200" alt="تبلیغ 3">
            <div class="content">
                <h3>محصول شماره 3</h3>
                <p>توضیحات کوتاه درباره محصول یا خدمت شماره 3.</p>
                <a href="#">مشاهده جزئیات</a>
            </div>
        </div>
    </section>

    <!-- بخش درباره ما -->
    <section id="about" class="container">
        <div style="grid-column: span 2; text-align: center;">
            <h2>درباره ما</h2>
            <p>ما در وب‌سایت تبلیغاتی، بهترین بستر را برای تبلیغ محصولات و خدمات شما فراهم می‌کنیم. با ما دیده شوید و فروش خود را افزایش دهید!</p>
        </div>
    </section>

    <!-- فوتر -->
    <footer>
        <p>© 2024 تمامی حقوق محفوظ است. طراحی شده توسط تیم شما.</p>
    </footer>

</body>
</html>
