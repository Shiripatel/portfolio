<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shirish Patel (MS, MBA) | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet" />
  <style>
    :root{--gold:#ffcc33;--bg:#0d0d0d;--panel:#121212;--muted:#bbbbbb}
    html{scroll-behavior:smooth}
    *{box-sizing:border-box;margin:0;padding:0;font-family:'Poppins',sans-serif}
    body{background:var(--bg);color:#f5f5f5;display:flex;min-height:100vh}

    /* Sidebar */
    .sidebar{width:28%;background:var(--panel);padding:30px 25px;display:flex;flex-direction:column;align-items:center;position:sticky;top:18px;height:max-content;border-radius:16px;margin:18px;box-shadow:0 10px 30px rgba(0,0,0,.4)}
    .sidebar img{width:160px;height:160px;object-fit:cover;border-radius:14px;border:3px solid var(--gold);margin-bottom:15px}
    .sidebar h2{font-size:22px;font-weight:600;margin-bottom:8px}
    .badge{background:#222;padding:6px 14px;border-radius:8px;font-size:14px;color:var(--gold);margin-bottom:10px}
    .location{color:var(--muted);font-size:14px;margin-bottom:18px}

    .degrees{width:100%;margin-top:10px;padding:12px;border:1px solid #242424;background:#191919;border-radius:12px;text-align:center}
    .degrees h4{margin:0 0 8px;font-size:14px;color:#e6e6e6}
    .degrees ul{list-style:none;margin:0;padding:0;color:#cfcfcf;font-size:13px;line-height:1.8}

    .icons{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-top:15px}
    .icons a{color:var(--muted);font-size:14px;text-decoration:none;padding:10px 12px;border-radius:8px;background:#191919;border:1px solid #242424}
    .icons a:hover{color:var(--gold);border-color:#3a3a3a}

    .certs{width:100%;margin-top:16px;padding:14px;border:1px solid #242424;background:#191919;border-radius:12px;text-align:center}
    .certs h4{margin:0 0 10px;font-size:14px;color:#e6e6e6}
    .badge-list{display:flex;flex-wrap:wrap;gap:8px;justify-content:center}
    .badge-list span{background:rgba(255,204,51,.1);border:1px solid var(--gold);color:var(--gold);font-size:12px;padding:4px 8px;border-radius:8px}

    /* Main */
    .main{width:72%;padding:30px 28px 80px}
    .navbar{position:sticky;top:16px;display:flex;justify-content:flex-end;margin-bottom:22px;z-index:20}
    .pill{background:rgba(18,18,18,.85);border:1px solid #2a2a2a;padding:10px;border-radius:18px;backdrop-filter:blur(6px)}
    .pill a{color:var(--muted);margin:0 8px;text-decoration:none;font-size:14px;padding:6px 10px;border-radius:10px;transition:all .2s;display:inline-block}
    .pill a:hover{background:#222;color:var(--gold)}

    section{margin-bottom:64px;scroll-margin-top:90px}
    h2{font-size:26px;color:#fff;margin-bottom:16px}
    h2+.bar{width:72px;height:3px;background:var(--gold);border-radius:999px;margin:-6px 0 18px}
    p{color:#ccc;line-height:1.7;font-size:15px}

    /* Timeline */
    .timeline{position:relative;padding-left:36px}
    .timeline:before{content:"";position:absolute;left:14px;top:0;bottom:0;width:2px;background:#2a2a2a}
    .titem{position:relative;margin-bottom:22px;padding:16px;border:1px solid #232323;background:#151515;border-radius:14px;display:flex;align-items:flex-start;gap:12px}
    .titem:before{content:"";position:absolute;left:-28px;top:22px;width:12px;height:12px;background:var(--gold);border-radius:50%;box-shadow:0 0 0 4px rgba(255,204,51,.15)}
    .titem img.icon{width:80px;height:80px;object-fit:contain;border-radius:12px;background:#111;border:1px solid #2a2a2a;padding:6px;transition:all .3s ease}
    .titem img.icon:hover{box-shadow:0 0 18px rgba(255,204,51,.6);border-color:var(--gold);transform:scale(1.05)}
    .tcontent{flex:1}
    .tcontent h3{font-size:16px;margin:0 0 4px}
    .tcontent small{color:#999}
    .tcontent ul{margin-top:8px;padding-left:18px;color:#cfcfcf}

    /* Portfolio */
    .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:16px}
    .card{padding:16px;border:1px solid #232323;background:#151515;border-radius:14px}
    .card h3{font-size:16px;margin:0 0 6px}
    .tags{display:flex;flex-wrap:wrap;gap:6px;margin:10px 0}
    .tags span{font-size:11px;color:#bbb;border:1px solid #2a2a2a;padding:3px 6px;border-radius:6px;background:#101010}
    .btn-row{display:flex;gap:10px;margin-top:10px}
    .btn{display:inline-block;padding:8px 12px;border-radius:8px;border:1px solid #2a2a2a;background:#1a1a1a;color:#ddd;text-decoration:none;font-size:13px}
    .btn:hover{border-color:#3a3a3a;color:var(--gold)}

    /* Contact */
    form label{display:block;font-size:14px;color:#ddd;margin-bottom:8px}
    input,textarea{width:100%;display:block;margin-bottom:12px;padding:10px;border-radius:8px;border:1px solid #333;background:#111;color:#eee}
    button{padding:10px 18px;background:var(--gold);color:#111;border:none;border-radius:8px;cursor:pointer;font-weight:600}

    @media (max-width:1100px){body{flex-direction:column}.sidebar{width:auto;margin:16px}.main{width:auto;padding:20px}}
  </style>
</head>
<body>
  <!-- Sidebar -->
  <aside class="sidebar">
    <img src="assets/Picture1.png" alt="Shirish Patel" />
    <h2>Shirish Patel (MS, MBA)</h2>
    <div class="badge">Data & Analytics | AI Strategy & Governance</div>
    <div class="location">New York, NY, USA</div>

    <div class="degrees">
      <h4>Degrees</h4>
      <ul>
        <li>MS – Business Analytics</li>
        <li>MBA – Business Administration</li>
        <li>BE – Electrical & Communications</li>
      </ul>
    </div>

    <div class="icons">
      <a href="https://www.linkedin.com/in/shirish1611/" target="_blank" rel="noopener">LinkedIn</a>
      <a href="https://github.com/Shiripatel" target="_blank" rel="noopener">GitHub</a>
      <a href="assets/Shirish%20Patel_Resume_BA.pdf" download>Resume (PDF)</a>
      <a href="mailto:shirishpatel1611@gmail.com">Email</a>
    </div>

    <div class="certs">
      <h4>Certifications</h4>
      <div class="badge-list">
        <span>CISA (in progress)</span>
        <span>CIA (in progress)</span>
        <span>Microsoft Fabric DP-600 / DP-700 (prep)</span>
        <span>Databricks Fundamentals</span>
        <span>AWS Cloud Practitioner (prep)</span>
        <span>Snowflake Advanced Analytics</span>
        <span>Alteryx Designer Cloud Core</span>
        <span>Oracle Fusion Cloud SCM Foundations</span>
        <span>TM Forum eTOM Foundation</span>
        <span>TM Forum Frameworx Foundation</span>
        <span>ITIL v3 Foundation</span>
      </div>
    </div>
  </aside>

  <!-- Main -->
  <main class="main">
    <nav class="navbar">
      <div class="pill">
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#education">Education</a>
        <a href="#achievements">Organizations</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <section id="about">
      <h2>About Me</h2>
      <div class="bar"></div>
      <p>Consultant turned data & analytics leader with 9+ years across Deloitte, Protiviti, and Grant Thornton. I deliver KPI dashboards, SOX/ITGC analytics, and ERP-enabled operating models across Finance and Supply Chain. Currently completing an MS in Business Analytics at DePaul (’25) and holding an MBA, focusing on AI Strategy, Governance, and Data-Driven Decision Systems.</p>
      <p>Expertise: SQL, Python, Power BI, Tableau, SAP S/4HANA, Oracle Cloud ERP, Snowflake, Databricks, Azure, and Microsoft Fabric.</p>
    </section>

    <section id="experience">
      <h2>Experience</h2>
      <div class="bar"></div>
      <div class="timeline">
        <div class="titem">
          <img class="icon" src="assets/Depaul.png" alt="DePaul" />
          <div class="tcontent">
            <h3>Data & Business Intelligence Analyst — DePaul University</h3>
            <small>Jan 2025 — Present · Chicago, IL</small>
            <ul>
              <li>Develop advanced dashboards and predictive models to support institutional planning and student engagement.</li>
              <li>Tools: Power BI, SQL, Python, Snowflake.</li>
            </ul>
          </div>
        </div>
        <div class="titem">
          <img class="icon" src="assets/Deloitte-Emblem.png" alt="Deloitte" />
          <div class="tcontent">
            <h3>Manager — Digital Transformation & Data Analytics — Deloitte</h3>
            <small>Aug 2020 — Dec 2024</small>
            <ul>
              <li>Led ERP-enabled analytics initiatives across Finance, SOX, and Supply Chain for global clients.</li>
              <li>Architected automated KPI models and internal control dashboards (SAP / Oracle Cloud).</li>
            </ul>
          </div>
        </div>
        <div class="titem">
          <img class="icon" src="assets/Protiviti_logo.svg.png" alt="Protiviti" />
          <div class="tcontent">
            <h3>Senior Consultant — Data Analytics & Audit — Protiviti</h3>
            <small>Feb 2019 — Jul 2020</small>
            <ul>
              <li>Delivered data-driven SOX testing frameworks and reconciliations across multi-entity groups.</li>
            </ul>
          </div>
        </div>
        <div class="titem">
          <img class="icon" src="assets/Grant%20thornton.jpg" alt="Grant Thornton" />
          <div class="tcontent">
            <h3>Data Management Consultant — Grant Thornton</h3>
            <small>Apr 2016 — Jan 2019</small>
            <ul>
              <li>Implemented data governance and reconciliation frameworks for multi-country operations.</li>
            </ul>
          </div>
        </div>
        <div class="titem">
          <img class="icon" src="assets/reliance-communications-logo.png" alt="Reliance" />
          <div class="tcontent">
            <h3>Revenue Assurance Analyst — Reliance Communications (Intern)</h3>
            <small>Apr 2015 — Jun 2015</small>
            <ul>
              <li>Supported revenue leakage audits and process automation in telecom domain.</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section id="education">
      <h2>Education</h2>
      <div class="bar"></div>
      <div class="timeline">
        <div class="titem"><div class="tcontent"><h3>MS — Business Analytics</h3><small>DePaul University · 2024 — 2025</small></div></div>
        <div class="titem"><div class="tcontent"><h3>MBA — Business Administration</h3><small>Symbiosis International University</small></div></div>
        <div class="titem"><div class="tcontent"><h3>BE — Electrical & Communications</h3><small>Gujarat Technological University</small></div></div>
      </div>
    </section>

    <section id="achievements">
      <h2>Organizations & Achievements</h2>
      <div class="bar"></div>
      <div class="timeline">
        <div class="titem"><div class="tcontent"><h3>HackWithChicago 2025 — Winner</h3><small>Predictive maintenance using Databricks + Azure</small></div></div>
        <div class="titem"><div class="tcontent"><h3>DePaul Analytics Initiatives</h3><small>Blue Demon Engagement · FSL Council analytics</small></div></div>
      </div>
    </section>

    <section id="portfolio">
      <h2>Portfolio</h2>
      <div class="bar"></div>
      <div class="grid">
        <article class="card">
          <h3>Predictive Maintenance — Reyes Fleet</h3>
          <p>Databricks + Azure; telematics features; downtime reduction dashboard.</p>
          <div class="tags"><span>Databricks</span><span>Azure</span><span>Python</span></div>
          <div class="btn-row">
            <a class="btn" href="https://github.com/Shiripatel" target="_blank">View Repo</a>
            <a class="btn" href="#" target="_blank">Case Study</a>
          </div>
        </article>
        <article class="card">
          <h3>SOX/ITGC Analytics Toolkit</h3>
          <p>Access reviews, SOD, duplicate invoices & vendor advances with exportable RCMs.</p>
          <div class="tags"><span>SOX</span><span>Python</span><span>Power BI</span></div>
          <div class="btn-row">
            <a class="btn" href="https://github.com/Shiripatel" target="_blank">View Repo</a>
            <a class="btn" href="#" target="_blank">RCM Sample</a>
          </div>
        </article>
        <article class="card">
          <h3>Real‑Time ESG Dashboard</h3>
          <p>Streaming KPIs with alerting; exec scorecards & drilldowns.</p>
          <div class="tags"><span>Stream</span><span>Power BI</span><span>Azure</span></div>
          <div class="btn-row">
            <a class="btn" href="https://github.com/Shiripatel" target="_blank">View Repo</a>
            <a class="btn" href="#" target="_blank">Demo</a>
          </div>
        </article>
        <article class="card">
          <h3>Workforce Planning & Budgeting Model</h3>
          <p>Cost & capacity scenarios for post‑merger orgs; driver‑based modeling.</p>
          <div class="tags"><span>Finance</span><span>Python</span><span>Excel</span></div>
          <div class="btn-row">
            <a class="btn" href="https://github.com/Shiripatel" target="_blank">View Repo</a>
            <a class="btn" href="#" target="_blank">Case Study</a>
          </div>
        </article>
        <article class="card">
          <h3>Blockchain‑Enabled Inventory — Vodafone (Case)</h3>
          <p>Joined‑up inventory across partners; transparency & on‑demand connectivity.</p>
          <div class="tags"><span>Blockchain</span><span>Supply Chain</span></div>
          <div class="btn-row">
            <a class="btn" href="#" target="_blank">Write‑up</a>
          </div>
        </article>
        <article class="card">
          <h3>No‑Code AI Agent for Lease Analysis</h3>
          <p>Snowflake + LLM to extract key clauses and payment terms; export to BI.</p>
          <div class="tags"><span>Snowflake</span><span>LLM</span></div>
          <div class="btn-row">
            <a class="btn" href="https://github.com/Shiripatel" target="_blank">View Repo</a>
          </div>
        </article>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="bar"></div>
      <form onsubmit="sendMail(event)">
        <label>Name<input name="name" required placeholder="Your name" /></label>
        <label>Email<input type="email" name="email" required placeholder="you@example.com" /></label>
        <label>Message<textarea name="message" rows="4" required placeholder="How can I help?"></textarea></label>
        <button type="submit">Send Message</button>
        <p class="mono" style="color:#9d9d9d;margin-top:8px">This will open your email app (mailto:).</p>
      </form>
    </section>

    <footer class="mono" style="color:#9d9d9d">© <span id="year"></span> Shirish Patel · GitHub Pages</footer>
  </main>

  <script>
    function sendMail(e){
      e.preventDefault();
      const f=e.target;
      const body=encodeURIComponent(`From: ${f.name.value}\nEmail: ${f.email.value}\n\n${f.message.value}`);
      location.href=`mailto:shirishpatel1611@gmail.com?subject=Portfolio%20Inquiry&body=${body}`;
    }
    document.getElementById('year').textContent=new Date().getFullYear();
  </script>
</body>
</html>
