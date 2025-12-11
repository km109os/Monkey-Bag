<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Monkey Bag - روابط التواصل</title>
  <style>
    :root{
      --bg:#fff6fb;
      --card:#fff;
      --accent:#ff6fa3;
      --muted:#6b6b6b;
      --shadow: 0 6px 18px rgba(0,0,0,0.08);
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }
    body{background:var(--bg);margin:0;display:flex;min-height:100vh;align-items:center;justify-content:center;padding:24px}
    .container{width:100%;max-width:720px;background:var(--card);border-radius:18px;box-shadow:var(--shadow);padding:24px}
    .header{display:flex;gap:16px;align-items:center}
    .logo{width:86px;height:86px;border-radius:12px;object-fit:cover;border:4px solid rgba(255,111,139,0.08)}
    h1{margin:0;font-size:1.6rem;color:#333}
    p.lead{margin:4px 0 0;color:var(--muted)}

    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(120px,1fr));gap:18px;margin-top:22px}
    .card-btn{background:linear-gradient(180deg,rgba(255,255,255,0.9),#fff);border-radius:14px;padding:14px;display:flex;flex-direction:column;align-items:center;justify-content:center;text-decoration:none;color:inherit;box-shadow:0 6px 14px rgba(0,0,0,0.06);transition:transform .15s ease, box-shadow .15s ease}
    .card-btn:hover{transform:translateY(-6px);box-shadow:0 10px 26px rgba(0,0,0,0.12)}
    .icon-circle{width:64px;height:64px;border-radius:50%;display:flex;align-items:center;justify-content:center;margin-bottom:10px;background:linear-gradient(180deg,rgba(255,255,255,0.6),rgba(0,0,0,0.02))}
    .app-name{font-weight:600;margin-top:6px}
    .small{font-size:0.85rem;color:var(--muted)}

    /* icon colors */
    .facebook .icon-circle{background:linear-gradient(180deg,#3b5998,#2e4a86);}
    .facebook-group .icon-circle{background:linear-gradient(45deg,#feda75,#d62976,#405de6);}
    .telegram .icon-circle{background:linear-gradient(180deg,#2AABEE,#1E9FD6);}
    .tiktok .icon-circle{background:linear-gradient(180deg,#010101,#3a3a3a);}

    .footer{margin-top:18px;text-align:center;color:var(--muted);font-size:0.9rem}

    @media (max-width:420px){.logo{width:64px;height:64px}.container{padding:16px}}
    /* تحسين شكل الموقع */
    body{background:linear-gradient(180deg,#ffe4f1,#fff6fb);}
    .container{border-radius:26px;padding:32px;box-shadow:0 8px 26px rgba(0,0,0,0.12)}
    h1{font-size:2rem;color:#ff4f92;font-weight:700}
    .card-btn{border-radius:18px;padding:18px}
    .icon-circle{width:72px;height:72px;border:3px solid rgba(255,255,255,0.35)}
  </style>
</head>
<body>
  <div class="container" role="main">
    <div class="header" style="flex-direction:column; text-align:center;">
          <h1>Monkey Bag</h1>
      <p class="lead">متجر Monkey Bag - تابعنا على تطبيقات التواصل الاجتماعي</p>
    </div>
    </div>

    <!-- قم بتبديل href إلى روابط صفحاتك الحقيقية -->
    <div class="grid" aria-label="روابط التواصل">

      <a class="card-btn facebook" href="https://www.facebook.com/share/1A9ku5bBst/" target="_blank" rel="noopener noreferrer">
        <div class="icon-circle" aria-hidden="true">
          <!-- Facebook SVG -->
          <svg width="36" height="36" viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path d="M22 12.073C22 6.486 17.523 2 12 2S2 6.486 2 12.073C2 17.095 5.656 21.128 10.438 21.984v-6.99H7.898v-2.9h2.54V9.797c0-2.507 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.772-1.63 1.562v1.875h2.773l-.443 2.9h-2.33V21.98C18.344 21.128 22 17.095 22 12.073z"/>
          </svg>
        </div>
        <div class="app-name">فيسبوك</div>
        <div class="small">صفحتنا على فيسبوك</div>
      </a>

      <a class="card-btn instagram" href="https://www.facebook.com/share/ttmMwthDdaYjYDJ1/?mibextid=A7sQZp" target="_blank" rel="noopener noreferrer">
        <div class="icon-circle" aria-hidden="true">
          <!-- Instagram SVG -->
          <svg width="36" height="36" viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
            <path d="M7 2h10a5 5 0 015 5v10a5 5 0 01-5 5H7a5 5 0 01-5-5V7a5 5 0 015-5zm5 5.9a4.1 4.1 0 100 8.2 4.1 4.1 0 000-8.2zm5.2-.8a1.2 1.2 0 11-2.4 0 1.2 1.2 0 012.4 0zM12 9.5a2.5 2.5 0 110 5 2.5 2.5 0 010-5z"/>
          </svg>
        </div>
        <div class="app-name">جروب فيسبوك</div>
        <div class="small">ادخل جروبنا الرسمي</div>
      </a>

      <a class="card-btn telegram" href="https://t.me/+sisGEPbMKZU3NTBk" target="_blank" rel="noopener noreferrer">
        <div class="icon-circle" aria-hidden="true">
          <!-- Telegram SVG -->n
          <svg width="36" height="36" viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
            <path d="M21.447 2.5L2.866 9.088c-.88.314-.869 1.206.184 1.49l4.01 1.15 1.633 5.16c.304.94 1.047 1.32 1.94.96l2.69-1.12 4.314 3.39c1.07.6 1.838.28 2.214-.975l2.74-12.76c.36-1.67-.6-2.54-2.45-1.87z"/>
          </svg>
        </div>
        <div class="app-name">تيليجرام</div>
        <div class="small">انضم لقناتنا</div>
      </a>

      <a class="card-btn tiktok" href="https://www.tiktok.com/@monkey.bag.store?_r=1&_t=ZS-927x580sZYz" target="_blank" rel="noopener noreferrer">
        <div class="icon-circle" aria-hidden="true">
          <!-- TikTok SVG (stylized musical note) -->
          <svg width="36" height="36" viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
            <path d="M12 2v12.2A4.8 4.8 0 1 1 9.2 9V3h2.8zM15 4.5v3.6a6.5 6.5 0 1 0 2-5.1V4.5h-2z"/>
          </svg>
        </div>
        <div class="app-name">تيك توك</div>
        <div class="small">شاهِد مقاطعنا القصيرة</div>
      </a>

    </div>

    
  </div>
</body>
</html>
