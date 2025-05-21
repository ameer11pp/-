<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قائمة الإيموجي 🍔🍕🍰</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f9fa;
            color: #343a40;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            direction: rtl; /* للعربية */
            text-align: center;
        }

        .menu-container {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            max-width: 700px;
            width: 100%;
            margin-bottom: 30px;
        }

        h1 {
            color: #007bff;
            margin-bottom: 25px;
            font-size: 2.8em;
        }

        .menu-category {
            margin-bottom: 30px;
            border-bottom: 2px solid #e9ecef;
            padding-bottom: 20px;
        }

        .menu-category:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }

        h2 {
            color: #28a745; /* لون أخضر جميل للفئات */
            font-size: 2em;
            margin-bottom: 20px;
        }

        .menu-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
            border-top: 1px solid #e2e6ea;
        }

        .menu-item:first-of-type {
            border-top: none;
        }

        .item-details {
            text-align: right;
            flex-grow: 1;
        }

        .item-details h3 {
            margin: 0;
            font-size: 1.5em;
            color: #495057;
            display: flex;
            align-items: center;
            justify-content: flex-end; /* لترتيب الإيموجي والاسم لليمين */
        }

        .item-details h3 .emoji {
            font-size: 1.2em; /* حجم أكبر للإيموجي */
            margin-left: 10px; /* مسافة بين الإيموجي والنص */
        }

        .item-details p {
            margin: 5px 0 0 0;
            color: #6c757d;
            font-size: 1em;
            line-height: 1.5;
        }

        .item-price {
            font-size: 1.6em;
            font-weight: bold;
            color: #dc3545; /* لون أحمر للسعر */
            margin-right: 20px;
            white-space: nowrap; /* لمنع كسر السعر على سطرين */
        }

        footer {
            margin-top: 40px;
            font-size: 0.9em;
            color: #6c757d;
        }

        /* تنسيق لتجربة زر بسيط (يمكن حذفه إذا لم يكن مطلوبًا) */
        .btn-customize {
            background-color: #ffc107;
            color: #343a40;
            padding: 12px 25px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 1.1em;
            font-weight: bold;
            transition: background-color 0.3s ease;
            margin-top: 30px;
        }

        .btn-customize:hover {
            background-color: #e0a800;
        }
    </style>
</head>
<body>
    <div class="menu-container">
        <h1>قائمة اليوم 😋</h1>

        <div class="menu-category">
            <h2>الوجبات الرئيسية 🍽️</h2>
            <div class="menu-item">
                <div class="item-details">
                    <h3><span class="emoji">🍔</span> برجر لحم بقري</h3>
                    <p>برجر لحم فاخر مع جبنة، خس، طماطم، ومخلل.</p>
                </div>
                <div class="item-price">35 SAR</div>
            </div>
            <div class="menu-item">
                <div class="item-details">
                    <h3><span class="emoji">🍕</span> بيتزا مارجريتا</h3>
                    <p>صلصة طماطم، جبنة موزاريلا، وأوراق الريحان الطازجة.</p>
                </div>
                <div class="item-price">40 SAR</div>
            </div>
            <div class="menu-item">
                <div class="item-details">
                    <h3><span class="emoji">🍝</span> باستا الفريدو</h3>
                    <p>مكرونة فيتوتشيني مع صلصة كريمة غنية بالدجاج والفطر.</p>
                </div>
                <div class="item-price">45 SAR</div>
            </div>
        </div>

        <div class="menu-category">
            <h2>المشروبات 🥤</h2>
            <div class="menu-item">
                <div class="item-details">
                    <h3><span class="emoji">🥤</span> كولا</h3>
                    <p>مشروب غازي منعش.</p>
                </div>
                <div class="item-price">10 SAR</div>
            </div>
            <div class="menu-item">
                <div class="item-details">
                    <h3><span class="emoji">🍊</span> عصير برتقال</h3>
                    <p>عصير برتقال طازج 100%.</p>
                </div>
                <div class="item-price">15 SAR</div>
            </div>
        </div>

        <div class="menu-category">
            <h2>الحلويات 🍰</h2>
            <div class="menu-item">
                <div class="item-details">
                    <h3><span class="emoji">🍰</span> كعكة الشوكولاتة</h3>
                    <p>طبقات من كعكة الشوكولاتة الغنية مع كريمة الجناش.</p>
                </div>
                <div class="item-price">25 SAR</div>
            </div>
            <div class="menu-item">
                <div class="item-details">
                    <h3><span class="emoji">🍦</span> آيس كريم فانيليا</h3>
                    <p>آيس كريم فانيليا كريمي مع صوص الشوكولاتة.</p>
                </div>
                <div class="item-price">20 SAR</div>
            </div>
        </div>

        <button class="btn-customize" onclick="alert('هنا يمكن إضافة وظيفة التخصيص أو طلب! 🛠️');">
            تخصيص قائمتك!
        </button>
    </div>

    <footer>
        <p>✨ تصميم بسيط لقائمة باستخدام الإيموجي ✨</p>
        <p>© 2024 جميع الحقوق محفوظة</p>
    </footer>

    </body>
</html>
