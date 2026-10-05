index.html
<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ہفتہ وار بچت بازار | Weekly Bachat Bazaar</title>
  <style>
    * { box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Arial, sans-serif; }
    body { margin: 0; padding: 0; background-color: #f4f6f9; color: #333; }
    header { background: #1b5e20; color: #fff; padding: 15px 20px; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; }
    .brand { display: flex; align-items: center; gap: 15px; }
    .brand img { height: 50px; background: #fff; padding: 3px; border-radius: 5px; }
    .brand h1 { margin: 0; font-size: 1.4rem; }
    nav a { color: #fff; text-decoration: none; margin: 0 10px; font-weight: bold; }
    .lang-btn { background: #ffeb3b; color: #000; border: none; padding: 8px 16px; border-radius: 20px; cursor: pointer; font-weight: bold; }
    .hero { background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('logo.png'); background-size: cover; color: white; text-align: center; padding: 60px 20px; }
    .container { max-width: 1200px; margin: 20px auto; padding: 0 15px; }
    .section-title { text-align: center; margin-bottom: 30px; color: #1b5e20; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
    .card { background: #fff; border-radius: 10px; padding: 20px; box-shadow: 0 4px 10px rgba(0,0,0,0.08); border-top: 4px solid #1b5e20; }
    .card h3 { margin-top: 0; color: #2e7d32; }
    .map-btn { display: inline-block; margin-top: 10px; background: #28a745; color: white; padding: 8px 12px; border-radius: 5px; text-decoration: none; font-size: 0.9rem; }
    .rates-table { width: 100%; border-collapse: collapse; margin-top: 15px; background: white; }
    .rates-table th, .rates-table td { border: 1px solid #ddd; padding: 10px; text-align: center; }
    .rates-table th { background: #2e7d32; color: white; }
    footer { background: #111; color: #bbb; text-align: center; padding: 20px; margin-top: 40px; }
  </style>
</head>
<body>

<header>
  <div class="brand">
    <img src="logo.png" alt="بچت بازار ایسوسی ایشن">
    <div>
      <h1 class="lang" data-en="Weekly Bachat Bazaar" data-ur="ہفتہ وار بچت بازار">ہفتہ وار بچت بازار</h1>
      <small class="lang" data-en="Bachat Bazaar Welfare Association" data-ur="بچت بازار ویلفیئر ایسوسی ایشن">بچت بازار ویلفیئر ایسوسی ایشن</small>
    </div>
  </div>
  <nav>
    <a href="#bazaars" class="lang" data-en="Explore Bazaars" data-ur="بازار تلاش کریں">بازار تلاش کریں</a>
    <a href="#rates" class="lang" data-en="Daily Rates" data-ur="روزانہ کے نرخ">روزانہ کے نرخ</a>
    <a href="#officials" class="lang" data-en="Officials Messages" data-ur="اہم پیغامات">اہم پیغامات</a>
    <a href="https://sboss.business.gos.pk/" target="_blank">SBOSS Portal ↗</a>
  </nav>
  <button class="lang-btn" onclick="toggleLanguage()">English</button>
</header>

<section class="hero">
  <h2 class="lang" data-en="Good Finds. Better Prices." data-ur="بہترین اشیاء، مناسب قیمتیں">بہترین اشیاء، مناسب قیمتیں</h2>
  <p class="lang" data-en="Find weekly markets near you across Karachi & Pakistan" data-ur="کراچی اور سندھ بھر کے ہفتہ وار بچت بازاروں کی مکمل معلومات">کراچی اور سندھ بھر کے ہفتہ وار بچت بازاروں کی مکمل معلومات</p>
</section>

<div class="container">
  
  <!-- سرکاری نرخ نامے -->
  <section id="rates">
    <h2 class="section-title lang" data-en="Official Commissioner Rates" data-ur="کمشنر کراچی کے روزانہ کے سرکاری نرخ نامے">کمشنر کراچی کے روزانہ کے سرکاری نرخ نامے</h2>
    <table class="rates-table">
      <thead>
        <tr>
          <th class="lang" data-en="Item" data-ur="اشیاء">اشیاء</th>
          <th class="lang" data-en="Wholesale Rate" data-ur="ہول سیل ریٹ">ہول سیل ریٹ</th>
          <th class="lang" data-en="Retail Rate" data-ur="ریٹیل ریٹ">ریٹیل ریٹ</th>
          <th class="lang" data-en="Bachat Bazaar Rate" data-ur="بچت بازار خصوصی ریٹ">بچت بازار خصوصی ریٹ</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>آلو (Potato)</td>
          <td>Rs. 50 / kg</td>
          <td>Rs. 60 / kg</td>
          <td><strong>Rs. 52 / kg</strong></td>
        </tr>
        <tr>
          <td>پیاز (Onion)</td>
          <td>Rs. 80 / kg</td>
          <td>Rs. 95 / kg</td>
          <td><strong>Rs. 85 / kg</strong></td>
        </tr>
        <tr>
          <td>زندہ مرغی (Live Chicken)</td>
          <td>Rs. 380 / kg</td>
          <td>Rs. 410 / kg</td>
          <td><strong>Rs. 395 / kg</strong></td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- اہم شخصیات کے پیغامات -->
  <section id="officials" style="margin-top: 50px;">
    <h2 class="section-title lang" data-en="Official Messages & Offices" data-ur="اہم شخصیات کے پیغامات اور دفاتر کی لوکیشن">اہم شخصیات کے پیغامات اور دفاتر کی لوکیشن</h2>
    <div class="grid">
      <div class="card">
        <h3>وزیراعلیٰ سندھ</h3>
        <p>"بچت بازار عوام کو سستے اور معیار پر مبنی اشیائے خورونوش فراہم کرنے کا بہترین ذریعہ ہیں۔"</p>
        <p>📍 <strong>دفتر:</strong> وزیراعلیٰ ہاؤس، ڈاکٹر ضیاء الدین احمد روڈ، کراچی</p>
        <a href="https://maps.google.com/?q=Chief+Minister+House+Karachi" target="_blank" class="map-btn">گوگل نقشہ دیکھیں ↗</a>
      </div>
      <div class="card">
        <h3>کمشنر کراچی</h3>
        <p>"روزانہ کی بنیاد پر سرکاری نرخ ناموں کا اجراء اور مانیٹرنگ ہماری ترجیح ہے۔"</p>
        <p>📍 <strong>دفتر:</strong> کمشنر آفس، کلب روڈ، سول لائنز، کراچی</p>
        <a href="https://maps.google.com/?q=Commissioner+Office+Karachi" target="_blank" class="map-btn">گوگل نقشہ دیکھیں ↗</a>
      </div>
      <div class="card">
        <h3>ڈی جی بیورو آف سپلائی اینڈ پرائزز</h3>
        <p>"گرانفروشی کے خاتمے کے لیے ٹیمیں متحرک ہیں۔"</p>
        <p>📍 <strong>دفتر:</strong> این ایس سی بلڈنگ، ایم ٹی خان روڈ، کراچی</p>
        <a href="https://maps.google.com/?q=Bureau+of+Supply+and+Prices+Karachi" target="_blank" class="map-btn">گوگل نقشہ دیکھیں ↗</a>
      </div>
    </div>
  </section>

  <!-- بچت بازار لسٹ -->
  <section id="bazaars" style="margin-top: 50px;">
    <h2 class="section-title lang" data-en="Explore Weekly Bazaars" data-ur="کراچی کے بچت بازاروں کی لسٹ">کراچی کے بچت بازاروں کی لسٹ</h2>
    <div class="grid">
      <div class="card">
        <h3>علادین پارک اتوار/بدھ بازار</h3>
        <p>📍 مین راشد منہاس روڈ، گلشن اقبال، کراچی</p>
        <p>🗓️ <strong>دن:</strong> بدھ / اتوار | 🏢 <strong>ضلع:</strong> East</p>
        <a href="https://maps.google.com/?q=Aladin+Park+Rashid+Minhas+Road+Karachi" target="_blank" class="map-btn">میپ لوکیشن ↗</a>
      </div>
      <div class="card">
        <h3>یو پی موڑ کار بازار گراؤنڈ</h3>
        <p>📍 کار بازار گراؤنڈ، یو پی موڑ، نارتھ کراچی</p>
        <p>🗓️ <strong>دن:</strong> بدھ | 🏢 <strong>ضلع:</strong> Central</p>
        <a href="https://maps.google.com/?q=UP+Morr+New+Karachi" target="_blank" class="map-btn">میپ لوکیشن ↗</a>
      </div>
      <div class="card">
        <h3>کلفٹن بوٹ بیسن بچت بازار</h3>
        <p>📍 بوٹ بیسن، بلاک 7، کلفٹن، کراچی</p>
        <p>🗓️ <strong>دن:</strong> جمعرات | 🏢 <strong>ضلع:</strong> Saddar</p>
        <a href="https://maps.google.com/?q=Boat+Basin+Block+7+Clifton+Karachi" target="_blank" class="map-btn">میپ لوکیشن ↗</a>
      </div>
    </div>
  </section>

</div>

<footer>
  <p>© 2026 Weekly Bachat Bazaar · بچت بازار ویلفیئر ایسوسی ایشن</p>
</footer>

<script>
  let currentLang = 'ur';
  function toggleLanguage() {
    const btn = document.querySelector('.lang-btn');
    const elements = document.querySelectorAll('.lang');
    if (currentLang === 'ur') {
      currentLang = 'en';
      document.body.dir = 'ltr';
      btn.textContent = 'اردو';
      elements.forEach(el => { if (el.dataset.en) el.textContent = el.dataset.en; });
    } else {
      currentLang = 'ur';
      document.body.dir = 'rtl';
      btn.textContent = 'English';
      elements.forEach(el => { if (el.dataset.ur) el.textContent = el.dataset.ur; });
    }
  }
</script>

</body>
</html>
