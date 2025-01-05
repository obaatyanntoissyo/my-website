my-website/
├─ index.html            // トップページ
├─ service.html          // サービスページ
├─ pricing.html          // 料金プランページ
├─ support.html          // サポートページ
└─ assets/
   ├─ css/
   │   └─ style.css      // 共通スタイルシート
   ├─ js/
   │   └─ main.js        // 共通JavaScript
   └─ images/
       ├─ design-sample.jpg
       ├─ content-rich.jpg
       ├─ homepage-design.jpg
       └─ ... (その他、使用する画像)

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Compleight Homepage | トップ</title>
  <link rel="stylesheet" href="assets/css/style.css" />
</head>
<body>
  <!-- ヘッダー -->
  <header class="header">
    <div class="container">
      <h1 class="logo">Compleight Homepage</h1>
      <nav class="nav">
        <ul>
          <li><a href="index.html" class="active">トップ</a></li>
          <li><a href="service.html">サービス</a></li>
          <li><a href="pricing.html">料金プラン</a></li>
          <li><a href="support.html">サポート</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- メインビジュアル -->
  <section class="hero" style="background-image: url('assets/images/design-sample.jpg');">
    <div class="hero-overlay">
      <div class="hero-content">
        <h2>手間を削減して、<br>洗練されたホームページをすぐに。</h2>
        <p>写真＆文章が最初から揃っているから、もう悩まない。</p>
        <a href="service.html" class="btn btn-primary">サービスを詳しく見る</a>
      </div>
    </div>
  </section>

  <!-- コンテンツ例：特徴 -->
  <section class="features container">
    <h3>Compleight Homepageの特徴</h3>
    <div class="feature-list">
      <div class="feature-item">
        <h4>高品質の写真＆原稿付き</h4>
        <p>業種別の豊富なストックフォトやAI生成の文章がすでに用意されています。</p>
      </div>
      <div class="feature-item">
        <h4>更新のしやすさ</h4>
        <p>専用管理画面で写真や文章を簡単に差し替え。ITが苦手な方でも安心です。</p>
      </div>
      <div class="feature-item">
        <h4>プロが仕上げたデザイン</h4>
        <p>初心者感が出ない、洗練されたテンプレートデザインを用意しています。</p>
      </div>
    </div>
  </section>

  <!-- CTAセクション -->
  <section class="cta">
    <div class="cta-content">
      <h3>いますぐ始めてみませんか？</h3>
      <p>3分で完成…ではありませんが、高品質のホームページが圧倒的に早く仕上がります。</p>
      <a href="pricing.html" class="btn btn-secondary">料金プランを見る</a>
    </div>
  </section>

  <!-- フッター -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2023 Compleight Homepage. All rights reserved.</p>
    </div>
  </footer>

  <script src="assets/js/main.js"></script>
</body>
</html>
