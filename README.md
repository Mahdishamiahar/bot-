# bot-
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>سایت شخصی FIRE</title>
  <style>
    :root{
      --red: #b40000;
      --yellow: #ffd400;
      --black: #111;
      --light: #f9f9f9;
    }
    *{box-sizing:border-box;margin:0;padding:0;scroll-behavior:smooth}
    body{
      font-family: system-ui, "Segoe UI", Tahoma, sans-serif;
      background: var(--red);
      color: var(--light);
      line-height:1.8;
    }
    /* نوار بالا */
    nav{
      position:fixed;top:0;right:0;left:0;
      background: rgba(0,0,0,.7);
      backdrop-filter: blur(8px);
      padding:12px 20px;
      display:flex;justify-content:center;gap:20px;
      z-index:1000;
    }
    nav a{
      color:var(--yellow);
      text-decoration:none;
      font-weight:700;
    }
    nav a:hover{color:white}
    /* عکس هدر */
    header img{
      width:100%;height:100vh;object-fit:cover;
      display:block;
    }
    header .overlay{
      position:absolute;top:0;left:0;width:100%;height:100vh;
      background:rgba(0,0,0,.4);
      display:flex;flex-direction:column;
      justify-content:center;align-items:center;
      text-align:center;
      color:var(--yellow);
    }
    header h1{font-size:clamp(28px,6vw,48px);margin-bottom:10px}
    header h2{font-size:clamp(18px,3vw,26px)}
    section{padding:80px 20px;max-width:1000px;margin:auto}
    section h3{color:var(--yellow);font-size:28px;margin-bottom:20px;text-align:center}
    .card{
      background:rgba(0,0,0,.3);
      border:1px solid rgba(255,255,255,.2);
      border-radius:16px;
      padding:20px;
      margin-top:20px;
      animation:fadeIn 1s ease;
    }
    /* مهارت‌ها */
    .skill{margin-bottom:15px}
    .skill-name{margin-bottom:6px;font-weight:700}
    .bar{
      background:#333;border-radius:10px;overflow:hidden;
    }
    .bar span{
      display:block;height:12px;background:var(--yellow);
    }
    /* لینک‌ها */
    .links a{
      display:inline-block;
      margin:8px;
      padding:10px 20px;
      border-radius:12px;
      background:var(--yellow);
      color:var(--black);
      font-weight:700;
      text-decoration:none;
      transition:.3s;
    }
    .links a:hover{background:white}
    footer{
      text-align:center;
      padding:20px;
      background:#111;
      color:var(--yellow);
    }
    @keyframes fadeIn{
      from{opacity:0;transform:translateY(20px)}
      to{opacity:1;transform:translateY(0)}
    }
  </style>
</head>
<body>
  <!-- منو -->
  <nav>
    <a href="#about">درباره من</a>
    <a href="#skills">مهارت‌ها</a>
    <a href="#contact">ارتباط</a>
  </nav>

  <!-- هدر -->
  <header>
    <img src="header.jpg" alt="FIRE">
    <div class="overlay">
      <h1>سلام خوش آمدید</h1>
      <h2>من محمد جواد حاجی زاده معروف به ꜰɪʀᴇ</h2>
    </div>
  </header>

  <!-- درباره من -->
  <section id="about">
    <h3>درباره من</h3>
    <div class="card">
      <p>ساکن مشهد و با سن ۱۶ سالگی در حوزه هک و امنیت درحال فعالیت هستم. عاشق یادگیری، تست نفوذ و امنیت شبکه هستم.</p>
    </div>
  </section>

  <!-- مهارت‌ها -->
  <section id="skills">
    <h3>مهارت‌ها</h3>
    <div class="card">
      <div class="skill">
        <div class="skill-name">هک و امنیت</div>
        <div class="bar"><span style="width:90%"></span></div>
      </div>
      <div class="skill">
        <div class="skill-name">شبکه</div>
        <div class="bar"><span style="width:75%"></span></div>
      </div>
      <div class="skill">
        <div class="skill-name">برنامه نویسی</div>
        <div class="bar"><span style="width:65%"></span></div>
      </div>
    </div>
  </section>

  <!-- ارتباط -->
  <section id="contact">
    <h3>ارتباط با من</h3>
    <div class="card links">
      <a href="https://rubika.ir/Rubika1Bot" target="_blank">روبیکا</a>
      <a href="https://t.me/KING12340003" target="_blank">تلگرام</a>
    </div>
  </section>

  <footer>
    © FIRE — ۱۴۰۴ | طراحی شده با ❤️
  </footer>
</body>
</html>
