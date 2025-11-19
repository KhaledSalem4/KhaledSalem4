<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Khaled Ahmed Salem — Software Engineer (Full-Stack .NET)</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent:#00bcd4;
      --muted:#94a3b8;
      --text:#e6eef6;
      --glass: rgba(255,255,255,0.03);
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#071027 0%, #06122a 100%);color:var(--text)}
    .container{max-width:900px;margin:48px auto;padding:28px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:12px;box-shadow:0 8px 30px rgba(2,6,23,0.6);}
    header{display:flex;gap:20px;align-items:center}
    .avatar{
      width:96px;height:96px;border-radius:14px;background:var(--glass);display:flex;align-items:center;justify-content:center;font-size:40px;
      border:1px solid rgba(255,255,255,0.04);
    }
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 0;color:var(--muted)}
    .section{margin-top:22px;padding-top:12px;border-top:1px dashed rgba(255,255,255,0.03)}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:14px;margin-top:12px}
    .card{background:var(--card);padding:14px;border-radius:10px;border:1px solid rgba(255,255,255,0.02)}
    .card h3{margin:0 0 8px;font-size:15px}
    ul{margin:0;padding-left:18px;color:var(--muted)}
    .meta{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
    .badge{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;font-size:13px;border:1px solid rgba(255,255,255,0.02)}
    .cta{margin-top:18px}
    .btn{
      display:inline-block;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:600;
      background:linear-gradient(90deg,var(--accent), #007ea7);color:#022;box-shadow:0 6px 18px rgba(0,188,212,0.12);
    }
    footer{margin-top:22px;color:var(--muted);font-size:13px}
    @media (max-width:520px){
      header{flex-direction:column;align-items:flex-start}
      .avatar{width:80px;height:80px}
    }
  </style>
</head>
<body>
  <main class="container" role="main">
    <header>
      <div class="avatar" aria-hidden="true">👨‍💻</div>
      <div>
        <h1>Khaled Ahmed Salem</h1>
        <p class="lead">Software Engineer — Full-Stack .NET</p>
        <div class="meta">
          <span class="badge">Full-Stack Developer</span>
          <span class="badge">.NET / C#</span>
        </div>
      </div>
    </header>

    <section class="section">
      <h2 style="margin:0;font-size:18px">About</h2>
      <p style="color:var(--muted);margin-top:8px">
        I am a passionate Software Engineer specializing in Full-Stack .NET development. I build scalable backends with ASP.NET Core,
        implement data access using Entity Framework, and create modern frontends using JavaScript and TypeScript.
      </p>
    </section>

    <section class="section">
      <h2 style="margin:0;font-size:18px">Technical Skills</h2>

      <div class="grid">
        <div class="card">
          <h3>Languages</h3>
          <ul>
            <li>C#</li>
            <li>JavaScript (ES6+)</li>
            <li>TypeScript</li>
            <li>SQL</li>
            <li>HTML5 &amp; CSS3</li>
          </ul>
        </div>

        <div class="card">
          <h3>Frameworks & Libraries</h3>
          <ul>
            <li>ASP.NET Core</li>
            <li>Entity Framework Core</li>
            <li>Blazor / Razor Pages</li>
            <li>React / Next.js</li>
            <li>SignalR</li>
          </ul>
        </div>

        <div class="card">
          <h3>Tools</h3>
          <ul>
            <li>Git & GitHub</li>
            <li>Docker</li>
            <li>Postman / Swagger</li>
            <li>Azure DevOps</li>
          </ul>
        </div>

        <div class="card">
          <h3>Practices</h3>
          <ul>
            <li>Clean Architecture</li>
            <li>SOLID Principles</li>
            <li>Unit/Integration Testing</li>
            <li>REST API Design</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="section">
      <h2 style="margin:0;font-size:18px">Contact</h2>
      <p style="color:var(--muted);margin-top:8px">
        GitHub: <a href="https://github.com/YourUser" target="_blank" style="color:var(--accent)">github.com/YourUser</a><br>
        LinkedIn: <a href="https://www.linkedin.com/in/khaled-salem-121a94260/" target="_blank" style="color:var(--accent)">linkedin.com/in/khaled-salem</a><br>
        Email: <a href="mailto:youremail@example.com" style="color:var(--accent)">youremail@example.com</a>
      </p>
    </section>

    <footer>
      <small>Made with ❤️ by Khaled Salem — Full-Stack .NET Developer</small>
    </footer>
  </main>
</body>
</html>
