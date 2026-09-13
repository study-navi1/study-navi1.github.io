<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Study Navi | 勉強法・参考書紹介</title>

  <meta
    name="description"
    content="高校生向けに、勉強法・おすすめ参考書・科目別の学習ルートを紹介するStudy Naviです。"
  >

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family:
        -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        "Hiragino Kaku Gothic ProN",
        "Yu Gothic",
        sans-serif;

      background: #f7f9fc;
      color: #1f2937;
      line-height: 1.7;
    }

    header {
      background: white;
      border-bottom: 1px solid #e5e7eb;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .header-inner {
      max-width: 1000px;
      margin: auto;
      padding: 14px 20px;

      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 1.3rem;
      font-weight: 800;
      color: #2563eb;
    }

    nav a {
      margin-left: 16px;
      text-decoration: none;
      color: #4b5563;
      font-size: 0.95rem;
    }

    .hero {
      max-width: 1000px;
      margin: auto;
      padding: 80px 20px 60px;
      text-align: center;
    }

    .hero h1 {
      margin: 0 0 16px;
      font-size: clamp(2.2rem, 7vw, 4rem);
      line-height: 1.15;
    }

    .hero span {
      color: #2563eb;
    }

    .hero p {
      max-width: 650px;
      margin: auto;
      color: #6b7280;
      font-size: 1.05rem;
    }

    .button {
      display: inline-block;
      margin-top: 28px;
      padding: 12px 22px;

      background: #2563eb;
      color: white;

      text-decoration: none;
      font-weight: 700;

      border-radius: 10px;
    }

    main {
      max-width: 1000px;
      margin: auto;
      padding: 0 20px 70px;
    }

    section {
      margin-bottom: 60px;
    }

    h2 {
      margin-bottom: 6px;
      font-size: 1.8rem;
    }

    .section-text {
      margin-top: 0;
      margin-bottom: 24px;
      color: #6b7280;
    }

    .grid {
      display: grid;
      grid-template-columns:
        repeat(auto-fit, minmax(210px, 1fr));
      gap: 16px;
    }

    .card {
      background: white;
      padding: 22px;

      border: 1px solid #edf0f5;
      border-radius: 14px;

      box-shadow:
        0 6px 20px rgba(0, 0, 0, 0.05);
    }

    .card h3 {
      margin-top: 0;
      margin-bottom: 8px;
    }

    .card p {
      margin: 0;
      color: #6b7280;
      font-size: 0.95rem;
    }

    .tag {
      display: inline-block;

      margin-bottom: 8px;
      padding: 4px 10px;

      border-radius: 999px;

      background: #dbeafe;
      color: #1d4ed8;

      font-size: 0.78rem;
      font-weight: 700;
    }

    .about {
      padding: 30px;
      background: #eff6ff;
      border-radius: 16px;
    }

    footer {
      padding: 25px;
      text-align: center;

      background: white;
      border-top: 1px solid #e5e7eb;

      color: #9ca3af;
      font-size: 0.9rem;
    }

    @media (max-width: 640px) {
      nav a {
        margin-left: 10px;
        font-size: 0.85rem;
      }

      .hero {
        padding-top: 55px;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="header-inner">

    <div class="logo">
      Study Navi
    </div>

    <nav>
      <a href="#subjects">科目</a>
      <a href="#books">参考書</a>
      <a href="#about">このサイトについて</a>
    </nav>

  </div>
</header>


<section class="hero">

  <h1>
    勉強を、もっと
    <span>効率的に。</span>
  </h1>

  <p>
    高校生向けに、
    実際に使いやすい参考書や勉強法、
    科目別の学習ルートを分かりやすく紹介します。
  </p>

  <a class="button" href="#books">
    おすすめ参考書を見る
  </a>

</section>


<main>

<section id="subjects">

  <h2>
    科目から探す
  </h2>

  <p class="section-text">
    科目ごとの勉強法や参考書を紹介していきます。
  </p>

  <div class="grid">

    <div class="card">
      <h3>数学</h3>
      <p>
        基礎から難関大学対策まで、
        レベル別の学習法を紹介。
      </p>
    </div>

    <div class="card">
      <h3>英語</h3>
      <p>
        単語・英文解釈・長文・英作文の
        学習ルートを紹介。
      </p>
    </div>

    <div class="card">
      <h3>世界史</h3>
      <p>
        流れ・年代・因果関係を重視した
        勉強法を紹介。
      </p>
    </div>

    <div class="card">
      <h3>地理</h3>
      <p>
        地図・統計・因果関係から
        理解する地理学習。
      </p>
    </div>

  </div>

</section>


<section id="books">

  <h2>
    おすすめ参考書
  </h2>

  <p class="section-text">
    目的やレベルに合わせて参考書を紹介します。
  </p>

  <div class="grid">

    <article class="card">

      <span class="tag">
        数学
      </span>

      <h3>
        数学のおすすめ参考書
      </h3>

      <p>
        基礎・標準・難関大レベルに分けて
        おすすめ教材を紹介します。
      </p>

    </article>


    <article class="card">

      <span class="tag">
        英語
      </span>

      <h3>
        英語長文のおすすめ参考書
      </h3>

      <p>
        読解力と速読力を
        段階的に伸ばせる参考書を紹介します。
      </p>

    </article>


    <article class="card">

      <span class="tag">
        世界史
      </span>

      <h3>
        世界史のおすすめ参考書
      </h3>

      <p>
        通史・用語暗記・論述対策に分けて
        おすすめ教材を紹介します。
      </p>

    </article>

  </div>

</section>


<section id="about" class="about">

  <h2>
    このサイトについて
  </h2>

  <p>
    Study Navi は、
    「どの参考書を使えばいいのか」
    「どの順番で勉強すればいいのか」
    を分かりやすく整理する
    高校生向けの学習サイトです。
  </p>

</section>

</main>


<footer>
  © 2026 Study Navi
</footer>

</body>
</html>
