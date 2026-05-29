---
layout: home
title: Home
---

<style>
  /* Reduce blank space above the name */
  .academic-hero {
    padding-top: 0 !important;
    margin-top: -1.2rem !important;
    align-items: flex-start;
    gap: 2rem;
  }

  /* Remove extra top margin from the name */
  .hero-copy h1 {
    margin-top: 0 !important;
    margin-bottom: 0.6rem;
  }

  /* Make the profile photo slightly smaller */
  .profile-img {
    max-width: 230px !important;
    width: 100%;
    height: auto;
  }

  .hero-profile {
    max-width: 260px;
  }

  /* Put research areas directly under the name */
  .hero-research-areas {
    margin: 0.4rem 0 1rem 0;
  }

  .hero-research-areas p {
    margin: 0 0 0.35rem 0;
    font-size: 0.82rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--muted-text, #6b7280);
  }

  .hero-research-areas ul {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .hero-research-areas li {
    font-size: 0.92rem;
    padding: 0.32rem 0.65rem;
    border-radius: 999px;
    background: rgba(0, 0, 0, 0.04);
  }

  /* Enlarge education institution/degree text */
  .timeline-item p {
    font-size: 1.15rem;
    font-weight: 650;
    line-height: 1.65;
  }

  /* Enlarge presentation/conference text */
  .presentation-grid p {
    font-size: 1.12rem;
    font-weight: 650;
    line-height: 1.65;
  }
</style>

<section class="academic-hero" id="top">
  <div class="hero-copy">
    <h1>Linjia (Alex) Song <span>宋琳甲</span></h1>

    <div class="hero-research-areas" aria-label="Research areas">
      <p>Research areas</p>
      <ul>
        <li>Empirical Asset Pricing</li>
        <li>Derivatives</li>
        <li>Real Estate Finance</li>
        <li>Supply Chain</li>
      </ul>
    </div>

    <p class="hero-subtitle">Assistant Professor of Finance </p>
    <p class="hero-subtitle">School of Management, Xiamen University.</p>
    <p class="hero-intro">
      My research interests are in empirical asset pricing, derivatives, real estate finance, and supply chain.
      Feel free to connect.
    </p>

    <div class="hero-actions" aria-label="Profile links">
      <a class="button-link primary" href="mailto:songlinjia@xmu.edu.cn">Email</a>
      <a class="button-link" href="https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=3160827" target="_blank" rel="noopener">SSRN</a>
      <a class="button-link" href="https://smr.xmu.edu.cn/TeacherWeb/Teacher_Details_2022.aspx?User_ID=1234" target="_blank" rel="noopener">Official Page</a>
    </div>
  </div>

  <aside class="hero-profile" aria-label="Profile photo and contact">
    <img src="/assets/img/profile_picture.jpg" alt="Linjia Song profile picture" class="profile-img">
    <div class="contact-panel" id="contact">
      <p class="panel-label">Contact</p>
      <a href="mailto:songlinjia@xmu.edu.cn">songlinjia@xmu.edu.cn</a>
      <a href="mailto:songlinjia@hotmail.com">songlinjia@hotmail.com</a>
    </div>
  </aside>
</section>

<section class="content-section" id="education">
  <div class="section-heading">
    <p class="section-kicker">Background</p>
    <h2>Education</h2>
  </div>
  <div class="timeline-list">
    <div class="timeline-item">
      <span>2018.09 - 2022.07</span>
      <p>The Chinese University of Hong Kong, PhD in Business Administration</p>
    </div>
    <div class="timeline-item">
      <span>2014.09 - 2018.07</span>
      <p>Xi'an Jiaotong University, BSc in Economics</p>
    </div>
  </div>
</section>

<section class="content-section" id="research">
  <div class="section-heading">
    <p class="section-kicker">Current projects</p>
    <h2>Working Papers</h2>
  </div>
  <ol class="paper-list">
    <li>Real Activities and Uncertainty: Evidence from Real Estate Market <span>with Jie Cao, Sheridan Titman, and Xintong Zhan</span></li>
    <li>Opioid Crisis Along the Supply Chain <span>with Jie Cao, Xintong Zhan, and Weiming Zhang</span></li>
    <li>Forecasting Corporate Bond Index Returns with Firm Characteristics and Macro Variables <span>with Jie Cao, Ruijing Yang, and Xintong Zhan</span></li>
    <li>Media Coverage and Option Returns <span>with Ruijing Yang</span></li>
    <li>Demand Shocks and Product Quality: Evidence from Hospitals <span>with Jie Cao, Lei Lei, and Xinong Zhan</span></li>
    <li>The Cost of Care: Paid Family Leave and Bank Loan Pricing <span>with Si Li, Jianglong Liu, and Xintong Zhan</span></li>
    <li>Information Processing Costs and Supply Chain Formation: Evidence from Local IPOs <span>with Jie Cao, Michael Hertzel, Xinqi Yu, and Xintong Zhan</span></li>
  </ol>
</section>

<section class="content-section" id="publications">
  <div class="section-heading">
    <p class="section-kicker">Published work</p>
    <h2>Publications</h2>
  </div>
  <div class="publication-list">
    <article>
      <p class="pub-title">Option Price Implied Information and REIT Returns</p>
      <p>with Jie Cao, Bing Han, and Xintong Zhan. <em>Journal of Empirical Finance</em>, 2023, 71, 13-28.</p>
    </article>
    <article>
      <p class="pub-title">Smart Beta, "Smarter" Flows</p>
      <p>with Jie Cao, Jason Hsu, Zhanbing Xiao, and Xintong Zhan. <em>Journal of Empirical Finance</em>, 2025.</p>
      <p>ETF Research Academy Award of the Paris-Dauphine House of Finance</p>
    </article>
    <article>
      <p class="pub-title">A Conditional Factor Model for REIT Returns</p>
      <p>with Jie Cao and Xintong Zhan. <em>Real Estate Economics</em>, 2026.</p>
    </article>
  </div>
</section>

<section class="content-section" id="presentations">
  <div class="section-heading">
    <p class="section-kicker">Seminars and conferences</p>
    <h2>Presentations</h2>
  </div>
  <div class="presentation-grid">
    <div><span>2026</span><p>The Chinese University of Hong Kong, AAA GNP Midyear Conference (New Hampshire)*, AREUEA National 
      (Washington D.C)* </p></div>
    <div><span>2025</span><p>Alliance for Research on Corporate Sustainability (Paris), Annual Conference on Asia-Pacific Financial Markets (Seoul), MRS International Risk Conference (Boston, Online), SFS Cavalcade AP (Beijing)*, FMA Annual Meeting (Vancouver)*, FMA Asia-Pacific (Taipei)*</p></div>
    <div><span>2024</span><p>Xiamen University, Chinese Finance Annual Meeting, East China Normal University*, Hong Kong Institute for Monetary and Financial Research*</p></div>
    <div><span>2023</span><p>AsRes-GCREC(Hong Kong),  China International Conference in Finance (CICF, Shanghai)*, The Federal Reserve Board*, University of Sussex*, University of Minnesota*, Virtual Derivatives Workshop*</p></div>
    <div><span>2022</span><p>The 4th Derivatives Youth Forum (Suzhou, Online), APAD Annual Conference (Busan, Online), ASSA-AREUEA Annual Meeting (Boston, Online), FMCG</p></div>
    <div><span>2021</span><p>AREUEA-International Annual Meeting (Singapore, Online), APAD Annual Conference (Busan, Online)</p></div>
  </div>
  <p class="presentation-note">* Presented by coauthor.</p>
</section>

<section class="content-section grants-section" id="grants">
  <div class="section-heading">
    <p class="section-kicker">Support</p>
    <h2>Research Grants</h2>
  </div>
  <div class="grant-list">
    <p><strong>The National Natural Science Foundation of China (NSFC)</strong>, Youth Science Fund, Principal Investigator, RMB 300,000</p>
    <p><strong>Fundamental Research Funds for the Central Universities</strong>, Principal Investigator, RMB 100,000</p>
  </div>
</section>
