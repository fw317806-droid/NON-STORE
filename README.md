<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NON STORE | متجرك الأنيق للملابس</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

    <header class="main-header">
        <div class="container">
            <h1 class="logo">NON STORE</h1>
            <nav class="main-nav">
                <ul>
                    <li><a href="#hero">الرئيسية</a></li>
                    <li><a href="#products">المنتجات</a></li>
                    <li><a href="#about">من نحن</a></li>
                    <li><a href="#contact">تواصل معنا</a></li>
                </ul>
            </nav>
            <div class="social-icons">
                <a href="https://www.facebook.com/share/17uVMRTBfN/?mibextid=wwXIfr" target="_blank"><i class="fab fa-facebook-f"></i></a>
                <a href="https://www.instagram.com/non.store_7?igsh=cmIycmViNzI2bXYw" target="_blank"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </header>

    <section id="hero" class="hero-section">
        <div class="container">
            <h2>مرحباً بكِ في عالم **NON STORE**</h2>
            <p>اكتشفي أحدث صيحات الموضة التي تناسب ذوقك الرفيع. جودة، أناقة، وتميز في كل قطعة.</p>
            <a href="#products" class="btn">تسوقي الآن</a>
        </div>
    </section>

    <section id="products" class="products-section">
        <div class="container">
            <h3 class="section-title">أحدث المنتجات</h3>
            <div class="product-grid">

                <div class="product-card">
                    <img src="1000084841.png" alt="هودي أسود Strong Current">
                    <h4>هودي Strong Current</h4>
                    <p class="description">هودي أنيق باللون الأسود مبطن ببطانة وردية، مثالي للأجواء الباردة. بطباعة عصرية "STRONG CURRENT NORTH SHORE HAWAII 89".</p>
                    <p class="price">السعر: **650 ج.م**</p>
                    <div class="sizes">
                        <p>المقاسات المتاحة: S, M, L, XL</p>
                    </div>
                </div>

                <div class="product-card">
                    <img src="1000084842.png" alt="هودي وردي Strong Current">
                    <h4>هودي Strong Current الوردي</h4>
                    <p class="description">نسخة باللون الوردي الزاهي من الهودي العصري "Strong Current". يمنحك إطلالة جريئة ومريحة.</p>
                    <p class="price">السعر: **650 ج.م**</p>
                    <div class="sizes">
                        <p>المقاسات المتاحة: S, M, L, XL</p>
                    </div>
                </div>
                
                <div class="product-card">
                    <img src="1000084839.png" alt="هودي بني بعبارة">
                    <h4>هودي الشوكولاتة الأوفر سايز</h4>
                    <p class="description">هودي أوفر سايز بلون الشوكولاتة الداكنة، مطبوع بعبارة "find what you like and never let go". مريح ومناسب للحجاب.</p>
                    <p class="price">السعر: **720 ج.م**</p>
                    <div class="sizes">
                        <p>المقاسات المتاحة: One Size (Oversize)</p>
                    </div>
                </div>

                 <div class="product-card">
                    <img src="1000084857.png" alt="هودي أبيض وردي Strong Current">
                    <h4>هودي أبيض ببطانة وردية</h4>
                    <p class="description">هودي مميز باللون الأبيض النقي، مزود ببطانة وردية جريئة. طباعة "STRONG CURRENT NORTH SHORE HAWAII 89".</p>
                    <p class="price">السعر: **680 ج.م**</p>
                    <div class="sizes">
                        <p>المقاسات المتاحة: M, L</p>
                    </div>
                </div>

                <div class="product-card">
                    <img src="1000084860.png" alt="هودي أنمي أبيض">
                    <h4>هودي الأنمي (Tokyo Ghoul)</h4>
                    <p class="description">هودي لمحبي الأنمي بلون أبيض، بطبعة شخصية من سلسلة Tokyo Ghoul. تصميم شبابي عصري.</p>
                    <p class="price">السعر: **599 ج.م**</p>
                    <div class="sizes">
                        <p>المقاسات المتاحة: M, L, XL</p>
                    </div>
                </div>
                
                <div class="product-card">
                    <img src="1000084859.png" alt="هودي أنمي أسود">
                    <h4>هودي الأنمي (Tokyo Ghoul) الأسود</h4>
                    <p class="description">نسخة باللون الأسود الداكن لمحبي الأنمي. تصميم مميز بخلفية نيون وطباعة يابانية.</p>
                    <p class="price">السعر: **599 ج.م**</p>
                    <div class="sizes">
                        <p>المقاسات المتاحة: M, L, XL</p>
                    </div>
                </div>
                
                </div>
        </div>
    </section>

    <footer class="main-footer">
        <div class="container">
            <p>&copy; 2025 NON STORE. جميع الحقوق محفوظة.</p>
            <div class="footer-links">
                <a href="#privacy">سياسة الخصوصية</a>
                <a href="#shipping">الشحن والتوصيل</a>
            </div>
        </div>
    </footer>

</body>
</html>
/* تنسيقات عامة */
:root {
    --primary-color: #000; /* لون النص الأساسي */
    --secondary-color: #f72585; /* لون التمييز الوردي/الساخن */
    --background-light: #f4f4f4; /* لون خلفية فاتح */
    --background-dark: #222; /* لون خلفية غامق */
    --text-light: #fff; /* لون النص الفاتح */
    --card-bg: #fff; /* لون خلفية بطاقة المنتج */
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    direction: rtl; /* لجعل التنسيق من اليمين لليسار */
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: var(--background-light);
    color: var(--primary-color);
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
    overflow: hidden;
}

a {
    text-decoration: none;
    color: var(--primary-color);
}

ul {
    list-style: none;
}

/* شريط التنقل (Header) */
.main-header {
    background: var(--card-bg);
    padding: 1rem 0;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.main-header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.8rem;
    font-weight: bold;
    color: var(--secondary-color);
}

.main-nav ul {
    display: flex;
}

.main-nav ul li a {
    padding: 0 15px;
    font-weight: 600;
    transition: color 0.3s;
}

.main-nav ul li a:hover {
    color: var(--secondary-color);
}

.social-icons a {
    font-size: 1.2rem;
    margin-right: 15px;
    color: var(--primary-color);
    transition: color 0.3s;
}

.social-icons a:hover {
    color: var(--secondary-color);
}

/* القسم الترحيبي (Hero Section) */
.hero-section {
    background: url('hero-bg.jpg') no-repeat center center/cover; /* يمكنك تغيير الصورة */
    background-color: var(--background-dark);
    color: var(--text-light);
    height: 40vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    margin-bottom: 20px;
}

.hero-section h2 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.hero-section p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

.btn {
    display: inline-block;
    background: var(--secondary-color);
    color: var(--text-light);
    padding: 10px 30px;
    border-radius: 5px;
    font-weight: bold;
    transition: opacity 0.3s;
}

.btn:hover {
    opacity: 0.9;
}

/* قسم المنتجات */
.products-section {
    padding: 40px 0;
}

.section-title {
    text-align: center;
    font-size: 2rem;
    margin-bottom: 30px;
    color: var(--primary-color);
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.product-card {
    background: var(--card-bg);
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 15px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}

.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

.product-card img {
    width: 100%;
    height: auto;
    max-height: 400px;
    object-fit: contain; /* للحفاظ على نسب الصورة دون قصها */
    border-radius: 6px;
    margin-bottom: 15px;
}

.product-card h4 {
    font-size: 1.4rem;
    color: var(--primary-color);
    margin-bottom: 5px;
}

.product-card .description {
    color: #666;
    font-size: 0.9rem;
    margin-bottom: 10px;
    min-height: 40px; /* لضمان ثبات ارتفاع البطاقات */
}

.product-card .price {
    font-size: 1.3rem;
    color: var(--secondary-color);
    font-weight: bold;
    margin-bottom: 10px;
}

.product-card .sizes p {
    font-size: 0.9rem;
    color: #333;
}

/* تذييل الصفحة (Footer) */
.main-footer {
    background: var(--background-dark);
    color: var(--text-light);
    padding: 20px 0;
    text-align: center;
    margin-top: 40px;
}

.main-footer .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.main-footer p {
    font-size: 0.9rem;
}

.main-footer .footer-links a {
    color: var(--text-light);
    margin-right: 20px;
    transition: color 0.3s;
}

.main-footer .footer-links a:hover {
    color: var(--secondary-color);
}
<div class="social-icons">
    <a href="https://www.facebook.com/share/17uVMRTBfN/?mibextid=wwXIfr" target="_blank"><i class="fab fa-facebook-f"></i></a>
    <a href="https://www.instagram.com/non.store_7?igsh=cmIycmViNzI2bXYw" target="_blank"><i class="fab fa-instagram"></i></a>
</div>
<section id="products" class="products-section">
    <div class="container">
        <h3 class="section-title">أحدث المنتجات وهوديز الكابلز</h3>
        <div class="product-grid">

            <div class="product-card">
                <img src="1000084841.png" alt="هودي أسود Strong Current">
                <h4>هودي Strong Current</h4>
                <p class="description">هودي أنيق باللون الأسود مبطن ببطانة وردية، مثالي للأجواء الباردة. بطباعة عصرية "STRONG CURRENT NORTH SHORE HAWAII 89".</p>
                <p class="price">السعر: **650 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: S, M, L, XL</p>
                </div>
            </div>

            <div class="product-card">
                <img src="1000084842.png" alt="هودي وردي Strong Current">
                <h4>هودي Strong Current الوردي</h4>
                <p class="description">نسخة باللون الوردي الزاهي من الهودي العصري. يمنحك إطلالة جريئة ومريحة.</p>
                <p class="price">السعر: **650 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: S, M, L, XL</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="1000084839.png" alt="هودي بني بعبارة">
                <h4>هودي الشوكولاتة الأوفر سايز</h4>
                <p class="description">هودي أوفر سايز بلون الشوكولاتة الداكنة، مطبوع بعبارة "find what you like and never let go". مريح ومناسب للحجاب.</p>
                <p class="price">السعر: **720 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: One Size (Oversize)</p>
                </div>
            </div>

             <div class="product-card">
                <img src="1000084857.png" alt="هودي أبيض وردي Strong Current">
                <h4>هودي أبيض ببطانة وردية</h4>
                <p class="description">هودي مميز باللون الأبيض النقي، مزود ببطانة وردية جريئة. طباعة "STRONG CURRENT NORTH SHORE HAWAII 89".</p>
                <p class="price">السعر: **680 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: M, L</p>
                </div>
            </div>

            <div class="product-card">
                <img src="1000084860.png" alt="هودي أنمي أبيض">
                <h4>هودي الأنمي (Tokyo Ghoul)</h4>
                <p class="description">هودي لمحبي الأنمي بلون أبيض، بطبعة شخصية من سلسلة Tokyo Ghoul. تصميم شبابي عصري.</p>
                <p class="price">السعر: **599 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: M, L, XL</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="1000084859.png" alt="هودي أنمي أسود">
                <h4>هودي الأنمي (Tokyo Ghoul) الأسود</h4>
                <p class="description">نسخة باللون الأسود الداكن لمحبي الأنمي. تصميم مميز بخلفية نيون وطباعة يابانية.</p>
                <p class="price">السعر: **599 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: M, L, XL</p>
                </div>
            </div>

            <hr>
            
            <div class="product-card couples-set">
                <img src="1000084848.png" alt="هودي كابلز توم وجيري أبيض">
                <h4>طقم كابلز: توم وجيري (أبيض)</h4>
                <p class="description">هوديز كابلز بلون أبيض، بتطريز شخصيتي توم (الشيطان) وجيري (الملاك). هدية مثالية للأزواج.</p>
                <p class="price">السعر للطقم (2 هودي): **1400 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: M, L, XL (لكلا الهوديين)</p>
                </div>
            </div>

            <div class="product-card couples-set">
                <img src="1000084851.png" alt="هودي كابلز توم وجيري أسود">
                <h4>طقم كابلز: توم وجيري (أسود)</h4>
                <p class="description">نسخة بلون أسود أنيق من طقم توم وجيري الكابلز. رسومات مطرزة عالية الجودة.</p>
                <p class="price">السعر للطقم (2 هودي): **1400 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: M, L, XL (لكلا الهوديين)</p>
                </div>
            </div>

            <div class="product-card couples-set">
                <img src="1000084854.png" alt="هودي كابلز دراجون أبيض">
                <h4>طقم كابلز: How to Train Your Dragon (أبيض)</h4>
                <p class="description">هوديز كابلز بلون أبيض، بطبعة شخصيتي Toothless & Light Fury اللطيفتين. لمحبي أفلام الكرتون.</p>
                <p class="price">السعر للطقم (2 هودي): **1350 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: S, M, L, XL (لكلا الهوديين)</p>
                </div>
            </div>
            
            <div class="product-card couples-set">
                <img src="1000084855.png" alt="هودي كابلز دراجون أسود">
                <h4>طقم كابلز: How to Train Your Dragon (أسود)</h4>
                <p class="description">نفس التصميم اللطيف لشخصيات الدراجون الشهيرة باللون الأسود. تصميم صغير على الصدر.</p>
                <p class="price">السعر للطقم (2 هودي): **1350 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: S, M, L, XL (لكلا الهوديين)</p>
                </div>
            </div>

             <div class="product-card couples-set">
                <img src="1000084853.png" alt="هودي كابلز ستيتش أبيض">
                <h4>طقم كابلز: Lilo & Stitch (أبيض)</h4>
                <p class="description">هوديز بيضاء بعبارة "You will always and forever be the most beautiful part of my heart" وطبعة ستيتش وأنجيل وقلبين متكاملين.</p>
                <p class="price">السعر للطقم (2 هودي): **1450 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: One Size</p>
                </div>
            </div>

            <div class="product-card couples-set">
                <img src="1000084856.png" alt="هودي كابلز ستيتش بني">
                <h4>طقم كابلز: Lilo & Stitch (بني خردلي)</h4>
                <p class="description">تصميم ستيتش وأنجيل الرومانسي باللون البني الخردلي الدافئ. مثالي لهدية عيد الحب أو الذكرى السنوية.</p>
                <p class="price">السعر للطقم (2 هودي): **1450 ج.م**</p>
                <div class="sizes">
                    <p>المقاسات المتاحة: One Size</p>
                </div>
            </div>


        </div>
    </div>
</section>
/* تنسيق خاص لمنتجات الكابلز */
.couples-set {
    border: 2px solid var(--secondary-color); /* إطار بلون التمييز */
    background-color: #ffeef2; /* خلفية فاتحة تميزها */
}

/* يمكنك أيضاً إضافة خط فاصل مرئي بين الأقسام */
hr {
    border: none;
    border-top: 3px solid #ddd;
    margin: 40px 0;
    grid-column: 1 / -1; /* لجعل الخط يمتد عبر شبكة المنتجات */
}
<section id="products" class="products-section">
    <div class="container">
        <h3 class="section-title">أحدث المنتجات وهوديز الكابلز</h3>
        <div class="product-grid">

            <div class="product-card">
                <img src="1000084841.png" alt="هودي أسود Strong Current">
                <h4>هودي Strong Current (أسود)</h4>
                <p class="description">هودي أنيق باللون الأسود مبطن ببطانة وردية، مثالي للأجواء الباردة. بطباعة عصرية "STRONG CURRENT NORTH SHORE HAWAII 89".</p>
                <p class="price">السعر: **650 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: S, M, L, XL</p></div>
            </div>

            <div class="product-card">
                <img src="1000084842.png" alt="هودي وردي Strong Current">
                <h4>هودي Strong Current (وردي)</h4>
                <p class="description">نسخة باللون الوردي الزاهي من الهودي العصري "Strong Current". يمنحك إطلالة جريئة ومريحة.</p>
                <p class="price">السعر: **650 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: S, M, L, XL</p></div>
            </div>
            
            <div class="product-card">
                <img src="1000084839.png" alt="هودي بني بعبارة">
                <h4>هودي الشوكولاتة الأوفر سايز</h4>
                <p class="description">هودي أوفر سايز بلون الشوكولاتة الداكنة، مطبوع بعبارة "find what you like and never let go". تصميم واسع ومريح.</p>
                <p class="price">السعر: **720 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: One Size (Oversize)</p></div>
            </div>

             <div class="product-card">
                <img src="1000084840.png" alt="هودي بني بعبارة من الخلف">
                <h4>هودي الشوكولاتة الأوفر سايز (خلفي)</h4>
                <p class="description">نفس الهودي الأوفر سايز، تصميم خلفي مميز بعبارة "Break The Rules" و "find what you like and never let go".</p>
                <p class="price">السعر: **720 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: One Size (Oversize)</p></div>
            </div>

             <div class="product-card">
                <img src="1000084857.png" alt="هودي أبيض وردي Strong Current">
                <h4>هودي أبيض ببطانة وردية</h4>
                <p class="description">هودي مميز باللون الأبيض النقي، مزود ببطانة وردية جريئة. طباعة "STRONG CURRENT NORTH SHORE HAWAII 89".</p>
                <p class="price">السعر: **680 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: M, L</p></div>
            </div>
            
            <div class="product-card">
                <img src="1000084860.png" alt="هودي أنمي أبيض">
                <h4>هودي الأنمي (Tokyo Ghoul)</h4>
                <p class="description">هودي لمحبي الأنمي بلون أبيض، بطبعة شخصية من سلسلة Tokyo Ghoul.</p>
                <p class="price">السعر: **599 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: M, L, XL</p></div>
            </div>

            <div class="product-card">
                <img src="1000084859.png" alt="هودي أنمي أسود">
                <h4>هودي الأنمي (Tokyo Ghoul) الأسود</h4>
                <p class="description">نسخة باللون الأسود الداكن لمحبي الأنمي. تصميم مميز بخلفية نيون وطباعة يابانية.</p>
                <p class="price">السعر: **599 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: M, L, XL</p></div>
            </div>

            <div class="product-card">
                <img src="1000084858.png" alt="هودي أنمي Tokyo Revengers">
                <h4>هودي الأنمي (Tokyo Revengers)</h4>
                <p class="description">هودي أبيض بطبعات شخصيات Tokyo Revengers. تصميم أنيق باللونين الأبيض والأسود.</p>
                <p class="price">السعر: **620 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: M, L, XL</p></div>
            </div>

            <hr>
            
            <div class="product-card couples-set">
                <img src="1000084848.png" alt="هودي كابلز توم وجيري أبيض">
                <h4>طقم كابلز: توم وجيري (أبيض)</h4>
                <p class="description">هوديز بيضاء، بتطريز شخصيتي توم (الشيطان) وجيري (الملاك). تصميم لطيف ومرح.</p>
                <p class="price">السعر للطقم (2 هودي): **1400 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: M, L, XL (لكلا الهوديين)</p></div>
            </div>

            <div class="product-card couples-set">
                <img src="1000084851.png" alt="هودي كابلز توم وجيري أسود">
                <h4>طقم كابلز: توم وجيري (أسود)</h4>
                <p class="description">نسخة باللون الأسود الداكن من طقم توم وجيري الكابلز. رسومات مطرزة عالية الجودة.</p>
                <p class="price">السعر للطقم (2 هودي): **1400 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: M, L, XL (لكلا الهوديين)</p></div>
            </div>
            
            <div class="product-card couples-set">
                <img src="1000084852.png" alt="هودي كابلز توم وجيري بني خردلي">
                <h4>طقم كابلز: توم وجيري (خردلي)</h4>
                <p class="description">طقم بلون بني خردلي مميز، بطبعة توم وجيري (شيطان وملاك). لإطلالة كابلز مختلفة.</p>
                <p class="price">السعر للطقم (2 هودي): **1450 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: M, L</p></div>
            </div>

            <div class="product-card couples-set">
                <img src="1000084854.png" alt="هودي كابلز دراجون أبيض">
                <h4>طقم كابلز: Toothless & Light Fury (أبيض)</h4>
                <p class="description">هوديز كابلز بلون أبيض، بطبعة شخصيتي Toothless & Light Fury اللطيفتين. لمحبي أفلام الكرتون.</p>
                <p class="price">السعر للطقم (2 هودي): **1350 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: S, M, L, XL (لكلا الهوديين)</p></div>
            </div>
            
            <div class="product-card couples-set">
                <img src="1000084855.png" alt="هودي كابلز دراجون أسود">
                <h4>طقم كابلز: Toothless & Light Fury (أسود)</h4>
                <p class="description">نفس التصميم اللطيف لشخصيات الدراجون الشهيرة باللون الأسود. تصميم صغير على الصدر.</p>
                <p class="price">السعر للطقم (2 هودي): **1350 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: S, M, L, XL (لكلا الهوديين)</p></div>
            </div>
            
            <div class="product-card couples-set">
                <img src="1000084849.png" alt="هودي كابلز دراجون بني خردلي">
                <h4>طقم كابلز: Toothless & Light Fury (خردلي)</h4>
                <p class="description">تصميم الدراجون الكرتوني باللون البني الخردلي. تصميم جذاب ومميز.</p>
                <p class="price">السعر للطقم (2 هودي): **1400 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: M, L, XL</p></div>
            </div>

            <div class="product-card couples-set">
                <img src="1000084853.png" alt="هودي كابلز ستيتش أبيض">
                <h4>طقم كابلز: Lilo & Stitch (أبيض - قلبين)</h4>
                <p class="description">هوديز بيضاء بطباعة ستيتش وأنجيل ونصفي قلب متكاملين. مع عبارة "You will always and forever be the most beautiful part of my heart".</p>
                <p class="price">السعر للطقم (2 هودي): **1450 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: One Size</p></div>
            </div>
            
            <div class="product-card couples-set">
                <img src="1000084847.png" alt="هودي كابلز ستيتش أسود">
                <h4>طقم كابلز: Lilo & Stitch (أسود)</h4>
                <p class="description">نسخة باللون الأسود من تصميم ستيتش وأنجيل الرومانسي.</p>
                <p class="price">السعر للطقم (2 هودي): **1450 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: One Size</p></div>
            </div>

            <div class="product-card couples-set">
                <img src="1000084856.png" alt="هودي كابلز ستيتش بني خردلي">
                <h4>طقم كابلز: Lilo & Stitch (خردلي)</h4>
                <p class="description">تصميم ستيتش وأنجيل باللون البني الخردلي الدافئ. مثالي لهدية كابلز مميزة.</p>
                <p class="price">السعر للطقم (2 هودي): **1450 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: One Size</p></div>
            </div>
            
             <div class="product-card couples-set">
                <img src="1000084850.png" alt="هودي كابلز Light & Night">
                <h4>طقم كابلز: Light & Night (أسود وأبيض)</h4>
                <p class="description">هوديز كابلز بتصميم عصري يجمع بين الأسود والأبيض وعبارتي "NIGHT" و "LIGHT". (يُباعان معًا).</p>
                <p class="price">السعر للطقم (2 هودي): **1400 ج.م**</p>
                <div class="sizes"><p>المقاسات المتاحة: M, L, XL</p></div>
            </div>
        </div>
    </div>
</section> 
