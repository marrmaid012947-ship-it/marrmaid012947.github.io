```html
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>言語聴覚士・心理カウンセラー 総合クリニック</title>
  <style>
    :root{
      --bg: #fffbe6;
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
    }
    /* 固定的な英語要素を排除して、日本語のみ表示 */
  </style>
</head>
<body>

<header class="site-header" role="banner">
  <div class="container" style="overflow:hidden">
    <div class="logo" aria-label="サイト名">
      言語聴覚士・心理カウンセラー 総合病院勤務15年以上
    </div>
  </div>
  <nav class="container" aria-label="トップナビ">
    <a href="#home" >ホーム</a>
    <a href="#services" >サービス</a>
    <a href="#fees" >料金とお支払い</a>
    <a href="#contact" >お問い合わせ</a>
    <a href="#overseas" >海外在住の方へ</a>
    <a href="#privacy" >プライバシー</a>
  </nav>
</header>

<main id="home" class="container" role="main">

  <!-- ホーム（日本語のみ） -->
  <section class="hero" id="home" aria-label="ホーム日本語">
    <h1>言葉とこころの専門家が、子どもから高齢者までをサポートします。</h1>
    <p>言語聴覚士と心理カウンセラーの資格をもち、総合病院勤務15年以上の経験。お子さんの発達・吃音・不登校、小学生～大人の方の言葉のリハビリ、家族への相談まで幅広く対応します。オンライン対応は日本国内はもちろん海外在住の方もご利用いただけます。</p>
    <a href="#contact" class="cta" aria-label="お問い合わせへ">まずはメールでご相談ください</a>
  </section>

  <!-- サービス -->
  <section class="section" id="services" aria-label="サービス日本語">
    <h2>👶 お子さん向けサポート</h2>
    <div class="cards">
      <div class="card">
        <strong>言葉の発達サポート</strong>
        <p>お子さんの言葉の発達を丁寧に見守り、必要なリハビリを提案します。</p>
      </div>
      <div class="card">
        <strong>学習・不登校の相談</strong>
        <p>学校での学習や不登校に関する現状把握と対策をご一緒に検討します。</p>
      </div>
      <div class="card">
        <strong>吃音のアプローチ</strong>
        <p>吃音のリハビリと保護者様への具体的なサポート方法をお伝えします。</p>
      </div>
    </div>
  </section>

  <section class="section" id="services-2" aria-label="サービス日本語2">
    <h2>👩‍🦳 大人の方向けサポート</h2>
    <div class="cards">
      <div class="card">
        <strong>吃音・発語リハビリ</strong>
        <p>成人の吃音や脳血管疾患後の言葉の困難さに対するリハビリを実施します。</p>
      </div>
      <div class="card">
        <strong>幼少期からの不安の相談</strong>
        <p>子どもの頃から気になっていた言葉や発達の悩みについて、成人の方にも対応します。</p>
      </div>
    </div>
  </section>

  <!-- オンラインリハビリ -->
  <section class="section" id="online" aria-label="オンラインリハビリ日本語">
    <h2>💻 オンラインリハビリ</h2>
    <div class="grid-2">
      <div class="card">
        <strong>対象</strong>
        <p>自宅などから受けられるリハビリ。日本国内だけでなく海外在住の方もご利用いただけます。</p>
      </div>
      <div class="card">
        <strong>料金</strong>
        <p>10分: 1,000円<br>20分: 2,000円<br>40分: 4,000円</p>
      </div>
    </div>
    <p style="margin-top:8px;color:var(--muted)">支払いは銀行振込のみ。振込先情報は申込後メールでご案内します。</p>
  </section>

  <!-- 料金とお支払い -->
  <section class="section" id="fees" aria-label="料金とお支払い日本語">
    <h2>💳 料金とお支払い</h2>
    <div class="grid-2">
      <div class="card">
        <strong>銀行振り込み</strong>
        <p>お支払いは銀行振込のみです。申込後、銀行振込先情報をメールでご案内します。</p>
        <p>振込手数料は別途ご負担ください。振込確認後、サービスを提供します。</p>
      </div>
      <div class="card">
        <strong>メール相談（回数課金）</strong>
        <p>1回のやりとり: 500円<br>5回のやりとり: 2000円<br>10回までのやりとり: 5000円</p>
      </div>
    </div>
    <p class="price" style="margin-top:8px">オンラインリハビリ料金は上記参照。日程は相談のうえ決定します。</p>
  </section>

  <!-- お問い合わせ -->
  <section class="section" id="contact" aria-label="お問い合わせ日本語">
    <h2>📩 お問い合わせフォーム</h2>
    <p>以下のフォームを送信後、銀行振り込み情報は申込フォームを受け取り次第、メールで直接お伝えします。オンラインリハビリのご案内や日程調整、領収書の発行方法も併せてご案内します。</p>
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
      <p style="margin-top:6px;color:var(--muted)">銀行振り込み情報は申込後にメールで直接お伝えします。</p>
    </form>
  </section>

  <!-- 海外在住の方へ -->
  <section class="section" id="overseas" aria-label="海外在住日本語">
    <h2>🌍 海外在住の方へ</h2>
    <p>日本語を母国語とする海外在住の方もご相談・リハビリを受け付けています。オンライン対応を中心に、日本国内と同様のサービスを提供します。</p>
  </section>

  <!-- プライバシーと安全 -->
  <section class="section" id="privacy" aria-label="プライバシーポリシー日本語">
    <h2>🛡️ プライバシーと安全</h2>
    <p>個人情報の取り扱いはプライバシーポリシーに従い、厳格に管理します。相談内容は機密を守り、第三者へ不適切に開示しません。</p>
  </section>

</main>

<footer class="container" style="padding:20px 0 40px" aria-label="サイトフッター">
  <p style="color:var(--muted); font-size:0.9rem">
    お問い合わせ先メール: <a href="mailto:marrmaid012947@gmail.com">marrmaid012947@gmail.com</a>
  </p>
</footer>

</body>
</html>
```
