‏<DOCTYPE html>
‏<html lang="ar" dir="rtl">
‏<head>
‏  <meta charset="UTF-8">
‏  <title>متجر بريق</title>
‏  <style>
‏    body {
‏      font-family: 'Arial', sans-serif;
‏      background-color: #fff0f5;
‏      margin: 0;
‏      scroll-behavior: smooth;
    }

‏    header {
‏      background-color: #f8c8dc;
‏      display: flex;
‏      align-items: center;
‏      justify-content: space-between;
‏      padding: 10px 30px;
    }

‏    .logo {
‏      width: 80px;
‏      height: 80px;
‏      border-radius: 50%;
‏      box-shadow: 0 0 15px #ffb6c1;
    }

‏    nav a {
‏      margin: 0 10px;
‏      text-decoration: none;
‏      color: #5a2a41;
‏      font-weight: bold;
‏      transition: 0.3s;
‏      cursor: pointer;
    }

‏    nav a:hover {
‏      color: #d94f8a;
    }

‏    section {
‏      padding: 60px 20px;
‏      text-align: center;
    }

‏    #home .main-banner {
‏      max-width: 90%;
‏      border-radius: 20px;
‏      box-shadow: 0 0 20px #ffc0cb;
‏      margin-bottom: 40px;
    }

‏    .products {
‏      display: flex;
‏      flex-wrap: wrap;
‏      justify-content: center;
‏      gap: 30px;
    }

‏    .product {
‏      background-color: #fff;
‏      border-radius: 15px;
‏      box-shadow: 0 0 10px rgba(0,0,0,0.1);
‏      width: 270px;
‏      padding: 20px;
    }

‏    .product img {
‏      width: 100%;
‏      border-radius: 10px;
    }

‏    .product h3 {
‏      color: #c71585;
    }

‏    .description {
‏      font-size: 14px;
‏      color: #333;
‏      margin: 10px 0;
    }

‏    .buy-button {
‏      background-color: #d57fa4;
‏      color: #fff;
‏      padding: 10px 20px;
‏      border-radius: 8px;
‏      text-decoration: none;
‏      display: inline-block;
‏      margin-top: 10px;
    }

‏    form {
‏      max-width: 400px;
‏      margin: 20px auto;
‏      text-align: right;
    }

‏    input, textarea {
‏      width: 100%;
‏      padding: 10px;
‏      margin: 10px 0;
‏      border-radius: 8px;
‏      border: 1px solid #ccc;
    }

‏    input[type="submit"] {
‏      background-color: #d57fa4;
‏      color: white;
‏      border: none;
‏      cursor: pointer;
    }

‏    input[type="submit"]:hover {
‏      background-color: #c14e86;
    }

‏    footer {
‏      background-color: #f8c8dc;
‏      padding: 20px;
‏      text-align: center;
‏      color: #5a2a41;
‏      margin-top: 40px;
    }

‏    .hidden-section {
‏      display: none;
‏      background-color: #fff;
‏      border-radius: 15px;
‏      margin: 20px auto;
‏      max-width: 800px;
‏      padding: 30px;
‏      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
‏  </style>
‏</head>
‏<body>

‏<header>
‏  <img src="https://i.ibb.co/84fYZX0X/18-CA4-AB3-B553-420-B-97-D8-0-DEE51-CB7925.png" alt="شعار" class="logo">
‏  <nav>
  
‏  <a onclick="showSection('home')">الرئيسية</a>
  
‏    <a onclick="showSection('about')">من نحن</a>
‏    <a onclick="showSection('login')">تسجيل الدخول</a>
‏    <a onclick="showSection('register')">إنشاء حساب</a>
‏    <a onclick="showSection('privacy')">سياسة الخصوصية</a>
‏  </nav>
‏</header>

‏<section id="home">
‏<section id="home">
‏  <h1 style="color: #c71585; text-align: center; margin: 30px 0 20px; font-size: 28px;">
    اكتشفي سر إشراقتك مع بريق
‏  </h1>
 
 



‏  <img src="https://i.ibb.co/kVNsGb6s/1511-C089-1418-4939-8845-829-BE20-F99-B8.png" class="main-banner" alt="صورة ترحيبية">

‏  <div class="products">
‏    <div class="product">
‏      <img src="https://i.ibb.co/Tn6z0Fz/IMG-3423.jpg" alt="روج وردي">
‏      <h3>أحمر شفاه وردي</h3>
‏      <p class="description">يمنح شفاهك لوناً أنثوياً ناعماً ولمسة مخملية تدوم طوال اليوم، مع ترطيب عميق.</p>
‏      <a href="#" class="buy-button">شراء الآن</a>
‏    </div>
‏    <div class="product">
‏      <img src="https://i.ibb.co/QtLsG3v/2f7dafd9-e8eb-4f4e-a133-0722ff112442.jpg" alt="ماسكارا">
‏      <h3>ماسكارا سوداء كثيفة</h3>
‏      <p class="description">تعزز من كثافة الرموش وتمنحك نظرة آسرة بثبات يدوم طوال اليوم دون تكتل. 
‏</p>
‏      <a href="#" class="buy-button">شراء الآن</a>
‏    </div>
‏    <div class="product">
‏      <img src="https://i.ibb.co/4gmfz1wp/IMG-3425.jpg" alt="هايلايتر">
‏      <h3>هايلايتر لامع</h3>
‏      <p class="description">يضيف لمسة إشراق طبيعية على الوجنتين والعينين، مناسب لجميع أنواع البشرة.</p>
‏      <a href="#" class="buy-button">شراء الآن</a>
‏    </div>
‏  </div>
‏</section>

<!-- الأقسام المخفية -->
‏<section id="about" class="hidden-section">
‏  <h2>من نحن</h2>
‏  <p>نحن متجر "بريق"، نؤمن بأن الجمال ينبع من التفاصيل البسيطة. نقدم لك منتجات تجميل مختارة بعناية لتواكبي كل جديد وتبرزي بأناقتك الفريدة. هدفنا هو توفير تجربة تسوق مريحة، ممتعة وآمنة تلهم ثقتك بنفسك.</p>
‏</section>

‏<section id="login" class="hidden-section">
‏  <h2>تسجيل الدخول</h2>
‏  <form>
‏    <label for="email">البريد الإلكتروني:</label>
‏    <input type="email" id="email" required>

‏    <label for="password">كلمة المرور:</label>
‏    <input type="password" id="password" required>

‏    <input type="submit" value="دخول">
‏  </form>
‏</section>

‏<section id="register" class="hidden-section">
‏  <h2>إنشاء حساب</h2>
‏  <form>
‏    <label for="name">الاسم الكامل:</label>
‏    <input type="text" id="name" required>

‏    <label for="emailReg">البريد الإلكتروني:</label>
‏    <input type="email" id="emailReg" required>

‏    <label for="passwordReg">كلمة المرور:</label>
‏    <input type="password" id="passwordReg" required>

‏    <label for="confirmPassword">تأكيد كلمة المرور:</label>
‏    <input type="password" id="confirmPassword" required>

‏    <input type="submit" value="تسجيل">
‏  </form>
‏</section>

‏<section id="privacy" class="hidden-section">
‏  <h2>سياسة الخصوصية</h2>
‏  <p>نحن نحترم خصوصيتك وملتزمون بحماية بياناتك. جميع المعلومات التي يتم جمعها من المستخدمين تُستخدم فقط لأغراض تحسين تجربة التسوق ولن يتم مشاركتها مع أي طرف ثالث دون إذن مسبق. باستخدامك لموقعنا، فإنك توافق على سياسة الخصوصية هذه.</p>
‏</section>

‏<footer>
  جميع الحقوق محفوظة &copy; 2025 متجر بريق | البريد الإلكتروني: bariq@gmail.com
‏</footer>

‏<script>
‏  function showSection(id) {
‏    const sections = ['about', 'login', 'register', 'privacy'];
‏    sections.forEach(sec => {
‏      document.getElementById(sec).style.display = 'none';
    });
‏    document.getElementById(id).style.display = 'block';
‏    document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
  }
‏</script>

‏</body>
‏</html>
