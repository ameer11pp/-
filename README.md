<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IM Studio - استوديو التصوير الخاص بك 📸</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5;
            color: #333;
            margin: 0;
            padding: 0;
            direction: rtl; /* اتجاه النص من اليمين لليسار */
            text-align: right; /* محاذاة النص لليمين */
            line-height: 1.6;
        }

        .header {
            background-color: #007bff; /* أزرق جذاب */
            color: white;
            padding: 30px 20px;
            text-align: center;
        }

        .header h1 {
            margin: 0;
            font-size: 3em;
            letter-spacing: 2px;
        }

        .header p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        section {
            padding: 30px 0;
            border-bottom: 1px solid #eee;
        }

        section:last-child {
            border-bottom: none;
        }

        h2 {
            color: #007bff;
            font-size: 2.2em;
            margin-bottom: 25px;
            text-align: center;
            position: relative;
            padding-bottom: 10px;
        }

        h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            right: 50%;
            transform: translateX(50%);
            width: 80px;
            height: 3px;
            background-color: #28a745; /* خط أخضر تحت العنوان */
        }

        /* About Us Section */
        .about-us p {
            font-size: 1.1em;
            text-align: justify;
        }

        /* Gallery Section */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .gallery-grid img {
            width: 100%;
            height: 180px; /* ارتفاع ثابت للصور */
            object-fit: cover; /* لضمان تغطية الصورة للمساحة دون تشويه */
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .gallery-grid img:hover {
            transform: scale(1.03);
        }

        /* Services Section */
        .services-list {
            list-style: none;
            padding: 0;
            margin-top: 20px;
        }

        .services-list li {
            background-color: #e9f7ef; /* خلفية خضراء فاتحة للخدمات */
            margin-bottom: 10px;
            padding: 15px;
            border-radius: 8px;
            font-size: 1.1em;
            display: flex;
            align-items: center;
        }

        .services-list li .emoji {
            font-size: 1.5em;
            margin-left: 10px; /* مسافة بين الإيموجي والنص */
        }

        /* Contact Section */
        .contact-info p {
            font-size: 1.1em;
            margin-bottom: 10px;
        }

        .contact-info a {
            color: #007bff;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .social-links {
            margin-top: 20px;
        }

        .social-links a {
            font-size: 2em;
            color: #555;
            margin: 0 10px;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .social-links a:hover {
            color: #007bff;
        }

        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            background-color: #343a40; /* خلفية داكنة للفوتر */
            color: white;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>IM Studio 📸</h1>
        <p>لحظات لا تُنسى، صور تحكي قصة.</p>
    </header>

    <div class="container">
        <section class="about-us">
            <h2>نبذة عنا ✨</h2>
            <p>
                في IM Studio، نؤمن بأن كل لحظة تستحق أن تُخلد. نحن استوديو تصوير متخصص نقدم خدمات تصوير فوتوغرافي وفيديو عالية الجودة، ملتزمون بتحويل لحظاتكم الثمينة إلى ذكريات بصرية خالدة. فريقنا من المصورين المحترفين والمبدعين يستخدم أحدث التقنيات لتقديم صور وفيديوهات تحكي قصصكم بصدق وجمال.
            </p>
            <p>
                سواء كانت مناسبة خاصة، جلسة تصوير شخصية، أو مشروع تجاري، نحن هنا لنجعل رؤيتكم واقعًا.
            </p>
        </section>

        <section class="gallery">
            <h2>أعمالنا المميزة 🌟</h2>
            <div class="gallery-grid">
                <img src="https://via.placeholder.com/250x180?text=صورة+1" alt="صورة عمل 1">
                <img src="https://via.placeholder.com/250x180?text=صورة+2" alt="صورة عمل 2">
                <img src="https://via.placeholder.com/250x180?text=صورة+3" alt="صورة عمل 3">
                <img src="https://via.placeholder.com/250x180?text=صورة+4" alt="صورة عمل 4">
                <img src="https://via.placeholder.com/250x180?text=صورة+5" alt="صورة عمل 5">
                <img src="https://via.placeholder.com/250x180?text=صورة+6" alt="صورة عمل 6">
            </div>
        </section>

        <section class="services">
            <h2>خدماتنا المتنوعة 💖</h2>
            <ul class="services-list">
                <li><span class="emoji">👰</span> تصوير حفلات الزفاف والمناسبات.</li>
                <li><span class="emoji">👨‍👩‍👧‍👦</span> جلسات التصوير العائلية والشخصية.</li>
                <li><span class="emoji">👶</span> تصوير الأطفال والمواليد الجدد.</li>
                <li><span class="emoji">🏢</span> تصوير المنتجات والإعلانات التجارية.</li>
                <li><span class="emoji">🏞️</span> تصوير المناظر الطبيعية والسفر.</li>
                <li><span class="emoji">🎬</span> خدمات تصوير الفيديو والمونتاج.</li>
            </ul>
        </section>

        <section class="contact-us">
            <h2>تواصل معنا 📞</h2>
            <div class="contact-info">
                <p><span class="emoji">📞</span> الهاتف: <a href="tel:+9647XXXXXXXXX">+964 7XXXXXXXXX</a></p>
                <p><span class="emoji">📧</span> البريد الإلكتروني: <a href="mailto:info@imstudio.com">info@imstudio.com</a></p>
                <p><span class="emoji">📍</span> العنوان: بغداد، العراق (مثال: شارع الرشيد، بالقرب من ساحة التحرير)</p>
            </div>
            <div class="social-links">
                <a href="#" target="_blank" title="فيسبوك"><span class="emoji">📘</span></a>
                <a href="#" target="_blank" title="انستغرام"><span class="emoji">📸</span></a>
                <a href="#" target="_blank" title="تويتر/X"><span class="emoji">🐦</span></a>
            </div>
        </section>
    </div>

    <footer>
        <p>كل الحقوق محفوظة لـ IM Studio &copy; 2024</p>
        <p>تم التصميم بواسطة @LPD_o</p>
    </footer>
</body>
</html>
