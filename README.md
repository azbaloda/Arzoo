<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Arzoo Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #fff;
      color: #111827;
      line-height: 1.6;
    }

    .page {
      max-width: 1220px;
      margin: 0 auto;
      padding: 20px 30px 40px 30px;
    }

    h1.site-title {
      color: #0b63d8;
      font-size: 38px;
      margin: 0 0 10px 0;
      font-weight: 700;
    }

    hr {
      border: none;
      border-top: 1px solid #e5e7eb;
      margin: 10px 0 28px 0;
    }

    h1.main-title {
      font-size: 38px;
      font-weight: 700;
      margin: 0 0 12px 0;
    }

    .company-strip {
      display: flex;
      align-items: center;
      gap: 16px;
      margin: 8px 0 8px 0;
      flex-wrap: wrap;
    }

    .company-strip a img {
      display: block;
      height: 52px;
      width: auto;
      object-fit: contain;
    }

    .main-layout {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      gap: 24px;
      margin-top: 20px;
    }

    .left-content {
      flex: 1;
      min-width: 0;
    }

    .right-photo {
      width: 350px;
      flex-shrink: 0;
      margin-top: 0;
    }

    .right-photo img {
      width: 100%;
      height: auto;
      display: block;
      object-fit: cover;
      border-radius: 6px;
    }

    h2.section-title {
      font-size: 28px;
      font-weight: 700;
      margin: 26px 0 6px 0;
    }

    .section-line {
      border-top: 1px solid #e5e7eb;
      margin: 0 0 18px 0;
    }

    table {
      border-collapse: collapse;
      margin-bottom: 24px;
      font-size: 20px;
      width: 100%;
    }

    td, th {
      border: 1px solid #d1d5db;
      padding: 10px 16px;
      text-align: left;
      vertical-align: middle;
    }

    .work-header {
      display: flex;
      align-items: center;
      gap: 16px;
      margin-top: 18px;
      margin-bottom: 6px;
      flex-wrap: wrap;
    }

    .work-header h2 {
      font-size: 28px;
      font-weight: 700;
      margin: 0;
    }

    .work-logo img {
      width: 92px;
      height: auto;
      display: block;
      object-fit: contain;
    }

    .role {
      font-size: 22px;
      font-weight: 600;
      margin: 22px 0 8px 0;
    }

    ul {
      margin: 12px 0 0 18px;
      padding-left: 22px;
      font-size: 20px;
    }

    li {
      margin-bottom: 12px;
    }

    .cert-table td, .cert-table th {
      text-align: center;
    }

    .cert-table img {
      height: 45px;
      width: auto;
      object-fit: contain;
    }

    .project {
      margin-bottom: 28px;
    }

    .project h3 {
      font-size: 24px;
      margin-bottom: 8px;
    }

    .project a {
      color: #0b63d8;
      text-decoration: none;
    }

    .project a:hover {
      text-decoration: underline;
    }

    @media (max-width: 1000px) {
      .main-layout {
        flex-direction: column;
      }

      .right-photo {
        width: 280px;
      }
    }
  </style>
</head>
<body>
  <div class="page">
    <h1 class="site-title">Arzoo</h1>
    <hr>

    <h1 class="main-title">Data Analyst at Vaibhav Vyapaar Pvt. Ltd.</h1>

    <div class="company-strip">
      <a href="https://in.linkedin.com/company/vaibhav-vyapaar" target="_blank" title="Vaibhav Vyapaar Pvt. Ltd. LinkedIn">
        <img src="Photos/vvpl logo.png" alt="Vaibhav Vyapaar Pvt. Ltd. Logo">
      </a>

      <a href="https://www.loanfront.in/" target="_blank" title="LoanFront Website">
        <img src="Photos/LoanFront App Logo.png" alt="LoanFront App Logo">
      </a>
    </div>

    <hr>

    <div class="main-layout">
      <div class="left-content">
        <h2 class="section-title">Education</h2>
        <div class="section-line"></div>

        <table>
          <tr>
            <td><strong>B.Tech</strong></td>
            <td><strong>IIT Guwahati</strong></td>
            <td><strong>Chemical Engineering</strong></td>
            <td><strong>7.75</strong></td>
          </tr>
          <tr>
            <td><strong>M.Tech</strong></td>
            <td><strong>IIT Kanpur</strong></td>
            <td><strong>Chemical Engineering</strong></td>
            <td><strong>9.67</strong></td>
          </tr>
        </table>

        <div class="work-header">
          <h2>Work Experience at Galaxy Surfactants Ltd.</h2>
          <a class="work-logo" href="https://galaxysurfactants.com/" target="_blank" title="Galaxy Surfactants Website">
            <img src="Photos/GSL New Logo.png" alt="Galaxy Surfactants Ltd. Logo">
          </a>
        </div>
        <div class="section-line"></div>

        <div class="role">Trainee Plant Engineer (Sept-2020 to Sept-2021)</div>
        <div class="role">Plant Officer (Sept-2021 to May-2023)</div>
        <div class="role">Senior Plant Officer (May-2023 to Oct-2023)</div>

        <ul>
          <li>Reduced operational cost by washing 2 dryers simultaneously using hot water with savings of 10.54 Lakhs/annum and reduced HIRA score from 384 to 64</li>
          <li>Modified the caustic-dosing system for dryer washing which reduced the HIRA score of the activity from 144 to 36 with savings of 2 Lakhs/annum</li>
          <li>Reduced packing cost by 2.8 Lakhs/annum by changing bag dimensions</li>
          <li>Installed camlock coupling in tanker unloading line which won 2nd prize (Jury Championship) in CII Kaizen competition</li>
          <li>Budgeted, monitored & analysed variable overheads (Power & Fuel) of the drying plant</li>
        </ul>
      </div>

      <div class="right-photo">
        <img src="Photos/Arzoo.jpeg" alt="Profile Picture">
      </div>
    </div>

    <h2 class="section-title">Certifications</h2>
    <div class="section-line"></div>

    <table class="cert-table">
      <tr>
        <th colspan="5">Skill Certificates</th>
      </tr>
      <tr>
        <td>
          <a href="https://moonshot.scaler.com/s/sl/S5H5tOyZM3" target="_blank">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">
          </a>
          <br>
          <a href="https://moonshot.scaler.com/s/sl/S5H5tOyZM3" target="_blank">Python Libraries</a>
        </td>
        <td>
          <a href="https://moonshot.scaler.com/s/sl/UbvSt91s1H" target="_blank">
            <img src="https://github.com/azbaloda/Arzoo_portfolio/assets/161424775/e0eea195-6b5c-4fc8-93dc-503d33e9b07a" alt="SQL">
          </a>
          <br>
          <a href="https://moonshot.scaler.com/s/sl/UbvSt91s1H" target="_blank">SQL</a>
        </td>
        <td>
          <a href="https://moonshot.scaler.com/s/sl/2KNZRl4RqV" target="_blank">
            <img src="https://github.com/azbaloda/Arzoo_portfolio/assets/161424775/abc23f76-7593-4b95-8e70-a3b5eaf9d654" alt="EDA">
          </a>
          <br>
          <a href="https://moonshot.scaler.com/s/sl/2KNZRl4RqV" target="_blank">EDA</a>
        </td>
        <td>
          <a href="https://moonshot.scaler.com/s/li/rKD3Tz8_ne" target="_blank">
            <img src="https://github.com/azbaloda/azbaloda/blob/main/Supervised-Machine-Learning_2.jpeg?raw=true" alt="Supervised Learning">
          </a>
          <br>
          <a href="https://moonshot.scaler.com/s/li/rKD3Tz8_ne" target="_blank">ML: Supervised Learning</a>
        </td>
        <td>
          <a href="https://moonshot.scaler.com/s/li/RigosLjVUB" target="_blank">
            <img src="https://github.com/azbaloda/azbaloda/blob/main/Unsupervised-Machine-Learning_1.jpg?raw=true" alt="Unsupervised Learning">
          </a>
          <br>
          <a href="https://moonshot.scaler.com/s/li/RigosLjVUB" target="_blank">ML: Unsupervised Learning</a>
        </td>
      </tr>
    </table>

    <h2 class="section-title">Projects</h2>
    <div class="section-line"></div>

    <div class="project">
      <h3><a href="https://github.com/azbaloda/SQL_Target_Analysis" target="_blank">Project 1: Target Business Analysis using SQL</a></h3>
      <ul>
        <li>Utilized BigQuery for systematic uploading and management of 8 datasets with about 100,000 orders.</li>
        <li>Performed SQL analysis on month-on-month orders, customer distribution, money movement, delivery time, and payments.</li>
        <li>Formulated actionable insights to improve operational efficiency and business strategy.</li>
      </ul>
    </div>

    <div class="project">
      <h3><a href="https://github.com/azbaloda/Netflix-Data-Exploration-and-Visualisation" target="_blank">Project 2: Netflix Data Exploration</a></h3>
      <ul>
        <li>Analyzed over 10,000 Movies and TV Shows available on Netflix.</li>
        <li>Used NumPy, Pandas, Matplotlib, and Seaborn for analysis and visualization.</li>
        <li>Performed preprocessing including missing value treatment, duplicate removal, and outlier handling.</li>
        <li>Created 8 plot types including bar, pie, count, dist, box, kde, heatmap, and pairplot.</li>
      </ul>
    </div>

    <div class="project">
      <h3><a href="https://github.com/azbaloda/Jamboree-Education---Linear-Regression" target="_blank">Project 3: Jamboree Linear Regression</a></h3>
      <ul>
        <li>Analyzed student data to identify key factors affecting graduate admissions.</li>
        <li>Built a Linear Regression model with Adjusted R² of 0.82.</li>
        <li>Recommended improvement areas such as CGPA, research, LOR, and SOP.</li>
      </ul>
    </div>

    <div class="project">
      <h3><a href="https://public.tableau.com/app/profile/arzoo.baloda/viz/SalesCustomerDashboards_17120333759470/SalesDashboard?publish=yes" target="_blank">Project 4: Tableau Dashboard - Sales & Customer</a></h3>
      <ul>
        <li>Built 2 dashboards for Sales and Customer analysis.</li>
        <li>Analyzed year-over-year sales performance and customer behavior.</li>
        <li>Added interactive filters by category, sub-category, region, state, and city.</li>
      </ul>
    </div>
  </div>
</body>
</html>
