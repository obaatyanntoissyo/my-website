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

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Compleight Homepage | サービス</title>
  <link rel="stylesheet" href="assets/css/style.css"/>
</head>
<body>
  <!-- ヘッダー -->
  <header class="header">
    <div class="container">
      <h1 class="logo">Compleight Homepage</h1>
      <nav class="nav">
        <ul>
          <li><a href="index.html">トップ</a></li>
          <li><a href="service.html" class="active">サービス</a></li>
          <li><a href="pricing.html">料金プラン</a></li>
          <li><a href="support.html">サポート</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- サービスイメージ -->
  <section class="service-hero" style="background-image: url('assets/images/content-rich.jpg');">
    <div class="hero-overlay">
      <div class="hero-content">
        <h2>プロ品質のコンテンツをいつでもすぐに利用</h2>
        <p>「撮影もライティングも、もう悩まない。」それがCompleight Homepageの強みです。</p>
      </div>
    </div>
  </section>

  <!-- サービスの特徴 -->
  <section class="service-features container">
    <h3>主要機能・特徴</h3>
    <ul>
      <li><strong>写真＆文章ライブラリ</strong>：美容・不動産・飲食など多ジャンルに対応</li>
      <li><strong>簡単更新機能</strong>：管理画面のUIがシンプルで誰でも手軽に修正可能</li>
      <li><strong>プロ仕様テンプレート</strong>：スマホ対応・SEOを考慮したデザイン</li>
      <li><strong>サポート体制</strong>：メールやチャットで質問・相談が可能</li>
    </ul>
  </section>

  <!-- 利用メリット -->
  <section class="benefits container">
    <h3>利用メリット</h3>
    <div class="benefit-list">
      <div class="benefit-item">
        <h4>手間とコストを削減</h4>
        <p>外注すると高額になりがちな撮影やライティングを一括でカバー。</p>
      </div>
      <div class="benefit-item">
        <h4>更新頻度が高いほどお得</h4>
        <p>頻繁に写真を差し替える業種（美容・建築など）に最適です。</p>
      </div>
      <div class="benefit-item">
        <h4>安心のサポート</h4>
        <p>ITに苦手意識があっても大丈夫。専門チームがしっかりフォロー。</p>
      </div>
    </div>
  </section>

  <!-- 導入ステップ -->
  <section class="steps container">
    <h3>導入ステップ</h3>
    <ol>
      <li><strong>お申し込み</strong>：基本情報や業種をヒアリング</li>
      <li><strong>素材選定</strong>：当社の写真＆文章ライブラリからベースを構築</li>
      <li><strong>管理画面で調整</strong>：顧客自身でカンタン最終修正</li>
      <li><strong>公開</strong>：サイトが完成し、すぐに運用を開始</li>
      <li><strong>更新サポート</strong>：月額費用に含まれる範囲で継続サポート</li>
    </ol>
  </section>

  <!-- 簡易FAQ -->
  <section class="faq container">
    <h3>FAQ（一部抜粋）</h3>
    <div class="faq-item">
      <button class="faq-question">Q. 初期費用と月額料金の内訳は？</button>
      <div class="faq-answer">
        <p>初期費用は撮影・文章準備のコストやテンプレート作成費にあたり、月額料金はシステム維持・共有コンテンツの追加などを賄っています。</p>
      </div>
    </div>
    <div class="faq-item">
      <button class="faq-question">Q. 写真や文章はすべて自由に使えますか？</button>
      <div class="faq-answer">
        <p>当社が購入や制作した素材をライブラリから利用可能です。利用範囲は契約プランに準じますので、詳細はお問合せください。</p>
      </div>
    </div>
    <!-- FAQを増やす場合はさらに追加 -->
  </section>

  <!-- CTA -->
  <section class="cta container">
    <p>より詳しい情報やサンプルサイトを見たい方は、料金プランや導入事例をチェック！</p>
    <a href="pricing.html" class="btn btn-primary">料金プラン</a>
    <a href="support.html" class="btn btn-secondary">サポートについて</a>
  </section>

  <!-- フッター -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2023 Compleight Homepage</p>
    </div>
  </footer>

  <script src="assets/js/main.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Compleight Homepage | 料金プラン</title>
  <link rel="stylesheet" href="assets/css/style.css"/>
</head>
<body>
  <!-- ヘッダー -->
  <header class="header">
    <div class="container">
      <h1 class="logo">Compleight Homepage</h1>
      <nav class="nav">
        <ul>
          <li><a href="index.html">トップ</a></li>
          <li><a href="service.html">サービス</a></li>
          <li><a href="pricing.html" class="active">料金プラン</a></li>
          <li><a href="support.html">サポート</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- 料金プラン ヒーロー -->
  <section class="pricing-hero">
    <div class="container">
      <h2>料金プラン</h2>
      <p>「撮影＆文章の外注を別々に頼むより圧倒的にお得」を目指しています。</p>
    </div>
  </section>

  <!-- 料金テーブル -->
  <section class="pricing-table container">
    <h3>プラン概要</h3>
    <div class="plan-box">
      <h4>スタンダードプラン</h4>
      <p class="price">初期費用: <strong>59,800円</strong>（税別）<br>月額: <strong>5,980円</strong>（税別）</p>
      <ul>
        <li>写真＆テキストのライブラリ利用</li>
        <li>基本テンプレート全種使用可</li>
        <li>管理画面での更新サポート</li>
        <li>メール・チャットでの問い合わせ対応</li>
      </ul>
      <a href="support.html" class="btn btn-primary">申し込み・相談</a>
    </div>

    <!-- 必要に応じて他のプランやオプションも追加 -->
    <!--
    <div class="plan-box">
      <h4>プレミアムプラン</h4>
      <p class="price">初期費用: 79,800円 / 月額: 9,980円</p>
      <ul>
        <li>～プレミアム機能 例～</li>
      </ul>
      <a href="support.html" class="btn btn-primary">申し込み・相談</a>
    </div>
    -->
  </section>

  <!-- 比較表が必要な場合の例 -->
  <section class="comparison-table container">
    <h3>DIYやフルカスタムとの比較</h3>
    <table>
      <thead>
        <tr>
          <th></th>
          <th>Compleight<br>Homepage</th>
          <th>DIY（自作）</th>
          <th>フルカスタム<br>（制作会社）</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>初期費用</td>
          <td>59,800円</td>
          <td>～0円（テーマ購入等）</td>
          <td>数十万～</td>
        </tr>
        <tr>
          <td>月額</td>
          <td>5,980円</td>
          <td>サーバー＋ドメイン料程度</td>
          <td>保守費用/月</td>
        </tr>
        <tr>
          <td>写真・文章</td>
          <td>ライブラリ使い放題</td>
          <td>自力手配</td>
          <td>撮影・ライティング外注</td>
        </tr>
        <tr>
          <td>更新のしやすさ</td>
          <td>管理画面UIがシンプル</td>
          <td>WordPressなど慣れが必要</td>
          <td>都度依頼＆費用発生</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- 料金に関するFAQ抜粋 -->
  <section class="faq container">
    <h3>よくある質問（料金関連）</h3>
    <div class="faq-item">
      <button class="faq-question">Q. 初期費用を値下げするキャンペーンはありますか？</button>
      <div class="faq-answer">
        <p>キャンペーンの実施予定があればサイトのトップなどでお知らせします。値下げが目的ではなく、写真＆文章の準備コストをまとめているため、この料金でも十分にコスパが高いと考えています。</p>
      </div>
    </div>
    <!-- 必要に応じてさらに追加 -->
  </section>

  <!-- CTA -->
  <section class="cta container">
    <p>プラン内容についてご不明点があれば、お気軽にお問い合わせください。</p>
    <a href="support.html" class="btn btn-primary">サポートページへ</a>
  </section>

  <!-- フッター -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2023 Compleight Homepage</p>
    </div>
  </footer>

  <script src="assets/js/main.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Compleight Homepage | サポート</title>
  <link rel="stylesheet" href="assets/css/style.css"/>
</head>
<body>
  <!-- ヘッダー -->
  <header class="header">
    <div class="container">
      <h1 class="logo">Compleight Homepage</h1>
      <nav class="nav">
        <ul>
          <li><a href="index.html">トップ</a></li>
          <li><a href="service.html">サービス</a></li>
          <li><a href="pricing.html">料金プラン</a></li>
          <li><a href="support.html" class="active">サポート</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- サポート概要 -->
  <section class="support-hero">
    <div class="container">
      <h2>サポート</h2>
      <p>Compleight Homepageをより快適にご利用いただくために、さまざまなサポート体制をご用意しています。</p>
    </div>
  </section>

  <!-- FAQセクション -->
  <section class="faq container">
    <h3>よくある質問</h3>

    <div class="faq-category">
      <h4>アカウント・ログイン関連</h4>
      <div class="faq-item">
        <button class="faq-question">Q. ログインIDやパスワードを忘れました。</button>
        <div class="faq-answer">
          <p>管理画面の「パスワードをお忘れですか？」リンクから再設定いただけます。それでも解決しない場合はお問い合わせフォームよりご連絡ください。</p>
        </div>
      </div>
      <!-- 他のQA項目を追加 -->
    </div>

    <div class="faq-category">
      <h4>更新作業・管理画面の操作</h4>
      <div class="faq-item">
        <button class="faq-question">Q. 写真を差し替える方法が分かりません。</button>
        <div class="faq-answer">
          <p>管理画面にログイン後、「コンテンツ管理」→「写真差し替え」から操作できます。詳しい手順は下記の操作マニュアルをご覧ください。</p>
        </div>
      </div>
    </div>
    <!-- 必要に応じてさらにFAQを追加 -->
  </section>

  <!-- 操作ガイド (簡易例) -->
  <section class="manual container">
    <h3>操作ガイド</h3>
    <p>以下の動画・スクリーンショットを参考に、管理画面での作業手順をご確認いただけます。</p>
    <!-- スクリーンショット例 -->
    <img src="assets/images/homepage-design.jpg" alt="管理画面のイメージ" class="manual-img" />

    <!-- 動画埋め込み例 -->
    <!--
    <iframe width="560" height="315" src="https://www.youtube.com/embed/dummyID" frameborder="0" allowfullscreen></iframe>
    -->
  </section>

  <!-- 問い合わせフォーム -->
  <section class="support-contact container">
    <h3>お問い合わせフォーム</h3>
    <form action="#" method="POST" class="contact-form">
      <label for="name">お名前</label>
      <input type="text" id="name" name="name" required />

      <label for="email">メールアドレス</label>
      <input type="email" id="email" name="email" required />

      <label for="subject">件名</label>
      <input type="text" id="subject" name="subject" required />

      <label for="message">お問い合わせ内容</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit" class="btn btn-primary">送信</button>
    </form>
    <p class="note">※通常、平日10～18時の間に順次返信しております。</p>
  </section>

  <!-- 追加サポート案内 -->
  <section class="support-options container">
    <h3>追加サポートのご案内</h3>
    <p>更新代行や写真撮影代行、文章ライティングなど、有料オプションサービスもございます。詳細はお問い合わせください。</p>
  </section>

  <!-- フッター -->
  <footer class="footer">
    <div class="container">
      <p>&copy; 2023 Compleight Homepage</p>
    </div>
  </footer>

  <script src="assets/js/main.js"></script>
</body>
</html>

/* assets/css/style.css */

/* ベース設定 */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: "Helvetica", "Arial", sans-serif;
  color: #333;
  background-color: #fff;
  line-height: 1.6;
}
img {
  max-width: 100%;
  height: auto;
}
a {
  text-decoration: none;
  color: #0066cc; /* 青系 */
}

/* コンテナや共通レイアウト */
.container {
  width: 90%;
  max-width: 1100px;
  margin: 0 auto;
  padding: 2rem 0;
}

/* ヘッダー */
.header {
  background-color: #f2f8fc; /* 薄い水色の背景 */
  padding: 1rem 0;
}
.logo {
  font-size: 1.5rem;
  color: #0066cc;
  font-weight: bold;
}
.nav ul {
  display: flex;
  gap: 1rem;
  list-style: none;
}
.nav ul li a {
  color: #0066cc;
  font-weight: 500;
}
.nav ul li a.active {
  text-decoration: underline;
}

/* ヒーローセクション */
.hero,
.service-hero,
.pricing-hero,
.support-hero {
  position: relative;
  color: #fff;
  text-align: center;
  min-height: 300px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.hero-overlay {
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0, 102, 204, 0.5); /* 半透明の青 */
}
.hero-content {
  position: relative;
  max-width: 700px;
  z-index: 1;
}
.hero-content h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  line-height: 1.2;
}
.hero-content p {
  font-size: 1.1rem;
  margin-bottom: 1.5rem;
}

/* 共通見出し */
h3 {
  font-size: 1.6rem;
  color: #0066cc;
  margin-bottom: 1rem;
}

/* ボタン */
.btn {
  display: inline-block;
  padding: 0.8rem 1.2rem;
  border-radius: 4px;
  font-weight: bold;
  text-align: center;
}
.btn-primary {
  background-color: #0066cc;
  color: #fff;
}
.btn-secondary {
  background-color: #00aaff;
  color: #fff;
}
.btn:hover {
  opacity: 0.9;
}

/* 特徴・メリットなど */
.features, .service-features, .benefits, .cta {
  padding: 2rem 0;
}
.feature-list,
.benefit-list {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
}
.feature-item,
.benefit-item {
  flex: 1 1 30%;
  background-color: #f2f8fc;
  padding: 1rem;
  border-radius: 5px;
}

/* CTAセクション */
.cta {
  text-align: center;
  background-color: #eaf4fa;
  margin: 2rem 0;
  padding: 2rem;
}
.cta p {
  margin-bottom: 1rem;
}

/* 料金テーブル */
.pricing-table {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
}
.plan-box {
  flex: 1 1 300px;
  background-color: #f2f8fc;
  padding: 1.5rem;
  border-radius: 5px;
  text-align: center;
}
.plan-box h4 {
  font-size: 1.4rem;
  margin-bottom: 1rem;
}
.plan-box .price {
  font-size: 1.2rem;
  margin-bottom: 1rem;
}

/* 比較表 */
.comparison-table table {
  width: 100%;
  border-collapse: collapse;
}
.comparison-table th,
.comparison-table td {
  border: 1px solid #ccc;
  padding: 0.8rem;
  text-align: center;
}
.comparison-table thead {
  background-color: #f2f8fc;
}

/* FAQ */
.faq-item {
  margin-bottom: 1rem;
}
.faq-question {
  display: block;
  width: 100%;
  background: #0066cc;
  color: #fff;
  text-align: left;
  padding: 0.8rem;
  border: none;
  cursor: pointer;
}
.faq-answer {
  display: none; /* 最初は非表示 */
  background-color: #f2f8fc;
  padding: 1rem;
}
.faq-item.active .faq-answer {
  display: block; /* ボタンを押すと表示 */
}

/* 問い合わせフォーム */
.contact-form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  max-width: 600px;
}
.contact-form label {
  font-weight: bold;
}
.contact-form input,
.contact-form textarea {
  padding: 0.6rem;
  border: 1px solid #ccc;
  border-radius: 4px;
}
.contact-form button {
  align-self: flex-start;
}

/* フッター */
.footer {
  background-color: #f2f8fc;
  text-align: center;
  padding: 1rem 0;
  margin-top: 2rem;
}

/* レスポンシブ例 */
@media (max-width: 768px) {
  .feature-list, .benefit-list, .pricing-table {
    flex-direction: column;
  }
  .nav ul {
    flex-direction: column;
    gap: 0.5rem;
  }
  .nav ul li {
    margin: 0.5rem 0;
  }
  .comparison-table table {
    font-size: 0.9rem;
  }
  .cta, .features, .benefits, .service-features, .faq, .manual {
    padding: 1rem 0;
  }
}

/* assets/js/main.js */

// FAQアコーディオン
document.addEventListener('DOMContentLoaded', () => {
  const faqItems = document.querySelectorAll('.faq-item');

  faqItems.forEach(item => {
    const questionBtn = item.querySelector('.faq-question');
    questionBtn.addEventListener('click', () => {
      // すでにactiveの場合は閉じる
      if (item.classList.contains('active')) {
        item.classList.remove('active');
      } else {
        // 他のactiveを閉じる
        faqItems.forEach(i => i.classList.remove('active'));
        // 自分だけactiveに
        item.classList.add('active');
      }
    });
  });
});

// (例) アニメーションの簡易サンプル: スクロール時にフェードイン
window.addEventListener('scroll', () => {
  const fadeIns = document.querySelectorAll('.fade-in');
  fadeIns.forEach(el => {
    const rect = el.getBoundingClientRect();
    const windowHeight = window.innerHeight;
    // 要素が画面の6割程度に入ったら表示
    if (rect.top < windowHeight * 0.6) {
      el.classList.add('visible');
    }
  });
});
