<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>言語聴覚士・心理カウンセラーによる相談窓口 - ホームページ案</title>
  <style>
    :root{
      --bg: #fff8e5;
      --primary:#ffd166;       /* 明るい黄色系 */
      --accent:#6ee7b7;          /* 明るいミント系 */
      --text:#333;
      --muted:#555;
      --card:#fff;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font-family:Inter,system-ui,-apple-system,Segoe UI,Arial,"Hiragino Sans",Meiryo,sans-serif}
    a{color:inherit;text-decoration:none}
    .container{max-width:1100px;margin:0 auto;padding:0 20px}
    header{background:linear-gradient(135deg, #fff 0%, #fff5d1 100%);border-bottom:2px solid #f0d27a}
    .site-header{padding:20px 0}
    .logo{font-weight:800;font-size:1.25rem;color:#111}
    nav{margin-top:8px}
    nav a{margin-right:18px;color:#333;font-weight:600}
    .lang-switch{float:right}
    .lang-btn{border:1px solid #ccc;background:#fff;padding:6px 10px;margin-left:8px;border-radius:6px;cursor:pointer}
    .lang-btn[aria-pressed="true"]{background:#ffe680;border-color:#e0b21a}
    .hero{padding:40px 0 20px;text-align:left}
    .hero h1{font-size:1.75rem;margin:0 0 8px}
    .hero p{margin:6px 0 0;color:var(--muted)}
    .section{padding:28px 0}
    .section h2{font-size:1.4rem;margin-bottom:12px}
    .cards{display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:16px}
    .card{background:var(--card);border:1px solid #eee;border-radius:12px;padding:16px;box-shadow:0 2px 6px rgba(0,0,0,.04)}
    ul{margin:0;padding-left:20px}
    .price{font-weight:700;color:#111}
    .blue{color:#0b5bd3}
    .cta{display:inline-block;background:var(--primary);color:#2b2b2b;padding:12px 18px;border-radius:8px;margin-top:12px;font-weight:700}
    .grid-2{display:grid;grid-template-columns:1fr 1fr;gap:20px}
    @media (max-width: 800px){
      .grid-2{grid-template-columns:1fr}
      .lang-switch{float:none;margin:0 0 8px 0}
    }
    /* 言語別の表示制御用クラス */
    .lang-ja{display:block}
    .lang-en{display:none}
  </style>
</head>
<body>

<header class="site-header" role="banner">
  <div class="container" style="overflow:hidden">
    <div class="logo" aria-label="サイト名">
      言語聴覚士・心理カウンセラー 総合病院勤務15年以上
    </div>
    <div class="lang-switch" aria-label="言語切替">
      <button class="lang-btn" data-lang="ja" aria-pressed="true">日本語</button>
      <button class="lang-btn" data-lang="en" aria-pressed="false">English</button>
    </div>
  </div>
  <nav class="container" aria-label="トップナビ">
    <a href="#home-ja">ホーム</a>
    <a href="#services-ja">サービス</a>
    <a href="#fees-ja">料金とお支払い</a>
    <a href="#contact-ja">お問い合わせ</a>
    <a href="#overseas-ja">海外在住の方へ</a>
  </nav>
</header>

<main id="home" class="container" role="main">

  <!-- ホーム（日本語） -->
  <section class="hero lang-ja" id="home-ja" aria-label="ホーム日本語">
    <h1>言葉とこころの専門家が、お子さんから高齢の方々へのサポートをいたします。</h1>
    <p>言語聴覚士と心理カウンセラーの資格をもち、総合病院勤務15年以上の経験。お子さんの発達・吃音・不登校、小学生～大人の方の言葉についての相談、ご家族の方のご相談まで幅広く対応いたします。オンライン対応は日本国内はもちろん海外在住の方もご利用いただけます。</p>
    <a href="#contact-ja" class="cta" aria-label="お問い合わせへ">まずはメールでご相談ください</a>
  </section>

  <!-- ホーム（英語） -->
  <section class="hero lang-en" id="home-en" aria-label="Home English" style="padding-top:0">
    <h1>Language and Counseling Experts Supporting from Children to Seniors</h1>
    <p>With qualifications as a Speech-Language Pathologist and Psychotherapist, and over 15 years of hospital experience, we address a wide range of needs—from child development, stuttering, school-related concerns, and school refusal to adult speech rehabilitation after stroke, plus family support. Online sessions are available for both domestic and overseas residents.</p>
    <a href="#contact-en" class="cta" aria-label="Contact us">Contact us via email</a>
  </section>

  <!-- サービス -->
  <section class="section" id="services-ja" aria-label="サービス日本語">
    <h2>👶 お子さん向けサポート</h2>
    <div class="cards">
      <div class="card">
        <strong>言葉の発達サポート</strong>
        <p>お子さんの言葉の発達を見守り、必要な対策方法等についての相談を承ります。</p>
      </div>
      <div class="card">
        <strong>学習面・不登校等の相談</strong>
        <p>学校での学習面や不登校に関する現状把握と対策をご一緒に検討していきます。</p>
      </div>
      <div class="card">
        <strong>吃音のアプローチ</strong>
        <p>吃音が気になっているお子さんとその保護者様への具体的なサポート方法をお伝えします。</p>
      </div>
    </div>
  </section>

  <section class="section" id="services-en" aria-label="Services English" style="display:none">
    <h2>👶 Services for Children</h2>
    <div class="cards">
      <div class="card">
        <strong>Language Development Support</strong>
        <p>Carefully monitor language growth and offer appropriate therapy recommendations.</p>
      </div>
      <div class="card">
        <strong>Learning & School Attendance</strong>
        <p>Assess current状況 and plan strategies for learning and school attendance.</p>
      </div>
      <div class="card">
        <strong>Stuttering Approach</strong>
        <p>Provide stuttering rehabilitation and practical guidance for families.</p>
      </div>
    </div>
  </section>

  <section class="section" id="services-ja-2" aria-label="サービス日本語2">
    <h2>👩‍🦳 大人の方向けサポート</h2>
    <div class="cards">
      <div class="card">
        <strong>吃音・発語等について</strong>
        <p>大人の吃音や脳血管疾患後の言葉の困難さに対するご相談を承ります。</p>
      </div>
      <div class="card">
        <strong>幼少期からの不安の相談</strong>
        <p>子どもの頃から気になっていた言葉や発達の悩みについて、成人の方へのご相談を承ります。</p>
      </div>
    </div>
  </section>

  <section class="section" id="services-en-2" aria-label="Services English 2" style="display:none">
    <h2>👩‍🦳 Services for Adults</h2>
    <div class="cards">
      <div class="card">
        <strong>Speech & Language Rehabilitation</strong>
        <p>Rehabilitation for adult stuttering and speech difficulties after stroke.</p>
      </div>
      <div class="card">
        <strong>Adult Consultations</strong>
        <p>Address concerns about language and development from childhood in adulthood.</p>
      </div>
    </div>
  </section>

  <!-- オンライン言語相談 -->
  <section class="section" id="online-ja" aria-label="オンライン言語相談日本語">
    <h2>💻 オンライン言語相談</h2>
    <div class="grid-2">
      <div class="card">
        <strong>対象となる方</strong>
        <p>自宅などから受けられる言語相談。日本国内だけでなく海外在住の方もご利用いただけます。</p>
      </div>
      <div class="card">
        <strong>料金</strong>
        <p>10分: 1,000円<br>20分: 2,000円<br>40分: 4,000円</p>
      </div>
    </div>
    <p style="margin-top:8px;color:var(--muted)">お支払いは先払い銀行振込のみ。振込先は申込後メールでご案内いたします。その後、具体的な日時について決めさせていただきます。</p>
  </section>

  <section class="section" id="online-en" aria-label="Online Rehabilitation English" style="display:none">
    <h2>💻 Online Rehabilitation</h2>
    <div class="grid-2">
      <div class="card">
        <strong>Target</strong>
        <p>Rehabilitation from home; available for domestic and overseas residents.</p>
      </div>
      <div class="card">
        <strong>Fees</strong>
        <p>10 minutes: 1,000 JPY<br>20 minutes: 2,000 JPY<br>40 minutes: 4,000 JPY</p>
      </div>
    </div>
    <p style="margin-top:8px;color:var(--muted)">Payment via bank transfer only. Bank details will be sent by email after you submit your request.</p>
  </section>

  <!-- 料金とお支払い（日本語） -->
  <section class="section" id="fees-ja" aria-label="料金とお支払い日本語">
    <h2>💳 料金とお支払い</h2>
    <div class="grid-2">
      <div class="card">
        <strong>銀行振り込み</strong>
        <p>お支払いは先払い銀行振込のみです。申込後、銀行振込先情報をメールでご案内します。</p>
        <p>振込手数料は別途ご負担ください。振込確認後、サービスを提供します。</p>
      </div>
      <div class="card">
        <strong>メール相談のみも承ります。</strong>
        <p>1回のやりとり: 500円<br>2回のやりとり: 1000円<br>　5回以上のやりとり: 5000円</p>
      </div>
    </div>
    <p class="price" style="margin-top:8px">オンラインでの料金は上記参照。日時はご相談のうえ決定します。</p>
  </section>

  <!-- 料金とお支払い（英語） -->
  <section class="section" id="fees-en" aria-label="Fees and payments English" style="display:none">
    <h2>💳 Fees & Payments</h2>
    <div class="grid-2">
      <div class="card">
        <strong>Bank Transfer</strong>
        <p>Payment is by bank transfer only. Bank details will be emailed after you submit your request.</p>
        <p>Please note bank transfer fees are the responsibility of the payer. Services commence after transfer confirmation.</p>
      </div>
      <div class="card">
        <strong>Email Consultation (text-based)</strong>
        <p>100 characters: 100 JPY<br>400 characters: 300 JPY<br>1000+ characters: 500 JPY</p>
      </div>
    </div>
    <p class="price" style="margin-top:8px">Online rehabilitation fees are as above. Date/time will be decided after consultation.</p>
  </section>

  <!-- お問い合わせ -->
  <section class="section" id="contact-ja" aria-label="お問い合わせ日本語">
    <h2>📩 お問い合わせフォーム</h2>
    <p>以下のフォームを送信後、銀行振り込み情報は申込フォームを受け取り次第、メールで直接お伝えします。オンライン内容のご案内や日程調整、領収書の発行も併せてご案内します。</p>
    <form action="mailto:marrmaid012947@gmail.com" method="post" enctype="text/plain" class="contact-form" aria-label="日本語お問い合わせフォーム">
      <div style="display:flex;flex-wrap:wrap;gap:12px">
        <label for="name-ja" style="flex:1 1 240px">お名前</label>
        <input id="name-ja" name="お名前" type="text" required style="flex:1 1 240px;padding:10px;border:1px solid #ccc;border-radius:6px">
      </div>
      <div style="display:flex;flex-wrap:wrap;gap:12px;margin-top:8px">
        <label for="email-ja" style="flex:1 1 240px">メールアドレス</label>
        <input id="email-ja" name="メールアドレス" type="email" required style="flex:1 1 240px;padding:10px;border:1px solid #ccc;border-radius:6px">
      </div>
      <div style="margin-top:8px">
        <label for="service-ja">相談内容</label><br/>
        <textarea id="service-ja" name="相談内容" rows="6" style="width:100%;padding:10px;border:1px solid #ccc;border-radius:6px" placeholder="サービスの希望内容を詳しくご記入ください"></textarea>
      </div>
      <div style="margin-top:8px">
        <label for="notes-ja">文字数（任意）</label>
        <input id="notes-ja" name="文字数目安" type="text" placeholder="例: 約400文字" style="width:100%;padding:8px;border:1px solid #ccc;border-radius:6px">
      </div>
      <button type="submit" class="cta" style="margin-top:10px">送信</button>
      <p style="margin-top:6px;color:var(--muted)">銀行振り込み情報は申込フォームを受け取り次第、メールで直接お伝えします。</p>
    </form>
  </section>

  <!-- お問い合わせ（英語） -->
  <section class="section" id="contact-en" aria-label="Contact English" style="display:none">
    <h2>📬 Contact Form</h2>
    <p>After you submit the form, bank transfer details will be sent to you by email. We will also provide guidance for online rehab scheduling and receipt issuance.</p>
    <form action="mailto:marrmaid012947@gmail.com" method="post" enctype="text/plain" class="contact-form" aria-label="English contact form">
      <div style="display:flex;flex-wrap:wrap;gap:12px">
        <label for="name-en" style="flex:1 1 240px">Name</label>
        <input id="name-en" name="Name" type="text" required style="flex:1 1 240px;padding:10px;border:1px solid #ccc;border-radius:6px">
      </div>
      <div style="display:flex;flex-wrap:wrap;gap:12px;margin-top:8px">
        <label for="email-en" style="flex:1 1 240px">Email</label>
        <input id="email-en" name="Email" type="email" required style="flex:1 1 240px;padding:10px;border:1px solid #ccc;border-radius:6px">
      </div>
      <div style="margin-top:8px">
        <label for="service-en">Inquiry</label><br/>
        <textarea id="service-en" name="Inquiry" rows="6" style="width:100%;padding:10px;border:1px solid #ccc;border-radius:6px" placeholder="Please describe your needs in detail"></textarea>
      </div>
      <div style="margin-top:8px">
        <label for="notes-en">Characters (optional)</label>
        <input id="notes-en" name="CharacterCount" type="text" placeholder="e.g., about 400 characters" style="width:100%;padding:8px;border:1px solid #ccc;border-radius:6px">
      </div>
      <button type="submit" class="cta" style="margin-top:10px">Submit</button>
      <p style="margin-top:6px;color:var(--muted)">Bank transfer details will be sent by email after you submit the form.</p>
    </form>
  </section>

  <!-- 海外在住の方へ -->
  <section class="section" id="overseas-ja" aria-label="海外在住日本語" style="scroll-margin-top:60px">
    <h2>🌍 海外在住の方へ</h2>
    <p>日本語を母国語とする海外在住の方へのご相談・言葉についての対応方法などについて受け付けております。オンライン対応を中心に、日本国内と同様のサービスを提供いたします。</p>
  </section>

  <section class="section" id="overseas-en" aria-label="Overseas English" style="display:none">
    <h2>🌍 For Overseas Residents</h2>
    <p>We welcome overseas residents who are native Japanese speakers. Online-based services are available and aligned with domestic offerings.</p>
  </section>

  <!-- プライバシーと安全 -->
  <section class="section" id="privacy" aria-label="プライバシーポリシー日本語">
    <h2>🛡️ プライバシーと安全</h2>
    <p>個人情報の取り扱い・相談内容はプライバシーポリシーに従い、厳密に管理します。第三者へ不適切に開示しません。</p>
  </section>

  <section class="section" id="privacy-en" aria-label="Privacy English" style="display:none">
    <h2>🛡️ Privacy & Security</h2>
    <p>Personal data is managed in accordance with our privacy policy. Confidentiality is maintained for all consultations.</p>
  </section>

</main>

<footer class="container" style="padding:20px 0 40px" aria-label="サイトフッター">
  <p style="color:var(--muted); font-size:0.9rem">
    お問い合わせ先メール: <a href="mailto:marrmaid012947@gmail.com">marrmaid012947@gmail.com</a>
  </p>
</footer>

<script>
  // 簡易言語切替
  document.addEventListener('DOMContentLoaded', function(){
    const jaBtns = document.querySelectorAll('[data-lang="ja"]');
    const enBtns = document.querySelectorAll('[data-lang="en"]');
    function showLang(lang){
      const jaEls = document.querySelectorAll('.lang-ja');
      const enEls = document.querySelectorAll('.lang-en');
      if(lang==='ja'){
        jaEls.forEach(el=>el.style.display='block');
        enEls.forEach(el=>el.style.display='none');
        jaBtns.forEach(b=>b.setAttribute('aria-pressed','true'));
        enBtns.forEach(b=>b.setAttribute('aria-pressed','false'));
      }else{
        jaEls.forEach(el=>el.style.display='none');
        enEls.forEach(el=>el.style.display='block');
        jaBtns.forEach(b=>b.setAttribute('aria-pressed','false'));
        enBtns.forEach(b=>b.setAttribute('aria-pressed','true'));
      }
    }
    jaBtns.forEach(btn=>{
      btn.addEventListener('click', ()=>showLang('ja'));
    });
    enBtns.forEach(btn=>{
      btn.addEventListener('click', ()=>showLang('en'));
    });
    // 初期表示は日本語
    showLang('ja');
  });

  // 簡易連携：英語セクションの切替表示をボタンからも即時反映
  // 追加のUI要素を使って表示切替を行う場合はここに拡張可能です
</script>

</body>
</html>
