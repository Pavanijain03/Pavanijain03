<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pavani Jain | AI Engineer – LLMs, Agents & RAG</title>
  <meta name="description" content="Pavani Jain – MS in AI at Northeastern. Applied AI engineer building LLM agents, RAG pipelines, and LLM evaluation systems.">

  <link rel="shortcut icon" href="./assets/images/logo.ico" type="image/x-icon">
  <link rel="stylesheet" href="./assets/css/style.css">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

  <!-- Small additions for the new skills layout and experience bullets.
       Move these into style.css whenever you like. -->
  <style>
    .skills-group { margin-bottom: 18px; }
    .skills-group:last-child { margin-bottom: 0; }
    .skills-group .h5 { margin-bottom: 10px; }
    .skills-tags { display: flex; flex-wrap: wrap; gap: 8px; }
    .timeline-bullets { margin-top: 6px; padding-left: 18px; list-style: disc; }
    .timeline-bullets li { margin-bottom: 4px; }
  </style>
</head>

<body>

  <main>

    <!-- SIDEBAR -->
    <aside class="sidebar" data-sidebar>

      <div class="sidebar-info">
        <figure class="avatar-box">
          <img src="./assets/images/memoji.jpg" alt="Pavani Jain" width="80">
        </figure>

        <div class="info-content">
          <h1 class="name">Pavani Jain</h1>
          <p class="title">AI Engineer | LLMs, Agents & RAG</p>
        </div>

        <button class="info_more-btn" data-sidebar-btn>
          <span>Show Contacts</span>
          <ion-icon name="chevron-down"></ion-icon>
        </button>
      </div>

      <div class="sidebar-info_more">

        <div class="separator"></div>

        <ul class="contacts-list">

          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="mail-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Email</p>
              <a href="mailto:jain.pav@northeastern.edu" class="contact-link">
                jain.pav@northeastern.edu
              </a>
            </div>
          </li>

          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="phone-portrait-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Phone</p>
              <a href="tel:+16175169584" class="contact-link">
                +1 (617) 516-9584
              </a>
            </div>
          </li>

          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="school-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Seeking</p>
              <p>Co-op now · Full-time from Spring 2028</p>
            </div>
          </li>

          <li class="contact-item">
            <div class="icon-box">
              <ion-icon name="location-outline"></ion-icon>
            </div>
            <div class="contact-info">
              <p class="contact-title">Location</p>
              <address>Boston, MA, USA</address>
            </div>
          </li>

        </ul>

        <div class="separator"></div>

        <ul class="social-list">
          <li class="social-item">
            <a href="https://github.com/Pavanijain03" target="_blank" rel="noopener noreferrer" class="social-link" aria-label="GitHub">
              <ion-icon name="logo-github"></ion-icon>
            </a>
          </li>
          <li class="social-item">
            <a href="https://www.linkedin.com/in/pavani-jain-ab6488204/" target="_blank" rel="noopener noreferrer" class="social-link" aria-label="LinkedIn">
              <ion-icon name="logo-linkedin"></ion-icon>
            </a>
          </li>
        </ul>

      </div>
    </aside>

    <!-- MAIN CONTENT -->
    <div class="main-content">

      <!-- NAVBAR -->
      <nav class="navbar">
        <ul class="navbar-list">
          <li class="navbar-item">
            <button class="navbar-link active" data-nav-link data-target="about">About</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link data-target="resume">Resume</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link data-target="portfolio">Projects</button>
          </li>
          <li class="navbar-item">
            <button class="navbar-link" data-nav-link data-target="contact">Contact</button>
          </li>
        </ul>
      </nav>

      <!-- ABOUT -->
      <article class="about active" data-page="about">

        <header>
          <h2 class="h2 article-title">About Me</h2>
        </header>

        <section class="about-text">
          <p>
            I'm an MS in Artificial Intelligence student at Northeastern University and a Graduate Teaching
            Assistant for Information Retrieval. I build applied LLM systems: agentic workflows, retrieval
            pipelines, and the evaluation frameworks that show whether they actually work.
          </p>
          <p>
            As an AI Engineer Intern at Thinqr, I worked on production LLM systems, including agentic LangGraph
            workflows, a RAG pipeline reaching ~90% top-5 accuracy, and an LLM-as-judge evaluation framework
            covering 6 dimensions and 50+ signals. I'm currently looking for co-op roles, and for full-time
            roles starting Spring 2028, in applied LLM and agent engineering.
          </p>
        </section>

        <section class="service">
          <h3 class="h3 service-title">What I Work On</h3>

          <ul class="service-list">

            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-dev.svg" alt="" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">LLM Agents</h4>
                <p class="service-item-text">Multi-step agentic workflows with LangGraph.</p>
              </div>
            </li>

            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-design.svg" alt="" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">RAG &amp; Retrieval</h4>
                <p class="service-item-text">Retrieval pipelines, dense retrieval, and ranking fairness.</p>
              </div>
            </li>

            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">LLM Evaluation</h4>
                <p class="service-item-text">LLM-as-judge frameworks and retrieval metrics.</p>
              </div>
            </li>

            <li class="service-item">
              <div class="service-icon-box">
                <img src="./assets/images/icon-photo.svg" alt="" width="40">
              </div>
              <div class="service-content-box">
                <h4 class="h4 service-item-title">Deep Learning</h4>
                <p class="service-item-text">Model training and fine-tuning in PyTorch.</p>
              </div>
            </li>

          </ul>
        </section>

      </article>

      <!-- RESUME -->
      <article class="resume" data-page="resume">

        <header>
          <h2 class="h2 article-title">Resume</h2>
        </header>

        <!-- EXPERIENCE -->
        <section class="timeline">
          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="briefcase-outline"></ion-icon>
            </div>
            <h3 class="h3">Experience</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Graduate Teaching Assistant – Information Retrieval</h4>
              <span>Northeastern University · Sep 2026 – Present</span>
              <ul class="timeline-text timeline-bullets">
                <li>Support a 100+ student cohort with grading, assignments, and weekly office hours.</li>
                <li>Contribute to course design for the Information Retrieval curriculum.</li>
              </ul>
            </li>

            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">AI Engineer Intern</h4>
              <span>Thinqr · Austin, TX · May – Aug 2026</span>
              <ul class="timeline-text timeline-bullets">
                <li>Built agentic LangGraph workflows for production LLM systems.</li>
                <li>Developed a RAG pipeline reaching ~90% top-5 retrieval accuracy.</li>
                <li>Designed an LLM-as-judge evaluation framework spanning 6 dimensions and 50+ signals.</li>
              </ul>
            </li>

            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">ML Researcher</h4>
              <span>Northeastern University · Oct – Dec 2025</span>
              <!-- TODO: add 1–2 bullets with real details/metrics -->
            </li>

            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Data Analyst</h4>
              <span>Verve Bridge · Jun – Sep 2024</span>
              <!-- TODO: add 1–2 bullets with real details/metrics -->
            </li>

          </ol>
        </section>

        <!-- EDUCATION -->
        <section class="timeline">
          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>
            <h3 class="h3">Education</h3>
          </div>

          <ol class="timeline-list">
            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">MS in Artificial Intelligence</h4>
              <span>Northeastern University · Expected December 2027</span>
              <p class="timeline-text">
                GPA 3.54/4.00. Coursework includes Information Retrieval (CS 6200).
              </p>
            </li>

            <li class="timeline-item">
              <h4 class="h4 timeline-item-title">Bachelor of Computer Applications (BCA)</h4>
              <span>VIPS, GGSIPU · Graduated June 2025</span>
              <p class="timeline-text">
                GPA 3.64. Programming, Data Structures, Analytics, and Databases.
              </p>
            </li>
          </ol>
        </section>

        <!-- SKILLS -->
        <section class="skill">
          <h3 class="h3 skills-title">Skills</h3>

          <div class="skills-list content-card">

            <div class="skills-group">
              <h5 class="h5">LLMs &amp; Agents</h5>
              <div class="skills-tags">
                <span class="tag">LangGraph</span>
                <span class="tag">RAG</span>
                <span class="tag">LLM-as-judge evaluation</span>
                <span class="tag">Dense retrieval</span>
                <span class="tag">LLM pretraining</span>
              </div>
            </div>

            <div class="skills-group">
              <h5 class="h5">Machine Learning &amp; Deep Learning</h5>
              <div class="skills-tags">
                <span class="tag">PyTorch</span>
                <span class="tag">TensorFlow</span>
                <span class="tag">scikit-learn</span>
                <span class="tag">XGBoost</span>
                <span class="tag">Transfer learning</span>
                <span class="tag">Topic modeling</span>
              </div>
            </div>

            <div class="skills-group">
              <h5 class="h5">Languages</h5>
              <div class="skills-tags">
                <span class="tag">Python</span>
                <span class="tag">SQL</span>
                <span class="tag">R</span>
                <span class="tag">Java</span>
                <span class="tag">C</span>
                <span class="tag">Bash</span>
                <span class="tag">HTML/CSS</span>
              </div>
            </div>

            <div class="skills-group">
              <h5 class="h5">Data &amp; Tools</h5>
              <div class="skills-tags">
                <span class="tag">MySQL</span>
                <span class="tag">ETL</span>
                <span class="tag">Tableau</span>
                <span class="tag">Streamlit</span>
                <span class="tag">AWS</span>
                <span class="tag">Git</span>
                <span class="tag">Linux</span>
              </div>
            </div>

          </div>
        </section>

        <div class="resume-download-wrapper">
          <a href="./assets/files/CV_resume.pdf" download class="resume-download-btn">
            <ion-icon name="download-outline"></ion-icon>
            <span>Download Resume</span>
          </a>
        </div>

      </article>

      <!-- PROJECTS -->
      <article class="portfolio" data-page="portfolio">

        <header>
          <h2 class="h2 article-title">Projects</h2>
        </header>

        <ul class="project-list project-grid">

          <!-- Nanochat -->
          <li class="project-item active">
            <a href="https://github.com/Pavanijain03/nanochat_architect" target="_blank" rel="noopener noreferrer" class="project-card">
              <figure class="project-img">
                <div class="project-item-icon-box">
                  <ion-icon name="eye-outline"></ion-icon>
                </div>
                <img src="./assets/images/nanochat2.png" loading="lazy" alt="Nanochat – GPT Pretraining & LLM Systems Optimization">
              </figure>
              <div class="project-content">
                <h3 class="project-title">Nanochat – GPT Pretraining &amp; LLM Systems Optimization</h3>
                <p class="project-category">LLM Pretraining • Scaling Laws • Distributed PyTorch</p>
                <p class="project-desc">
                  <!-- REVIEW: confirm these numbers are from your own training run (see notes) -->
                  Built an end-to-end GPT pretraining framework to reproduce GPT-2-grade capability
                  in ~3 hours on 8×H100 GPUs (~$72 cost) by optimizing depth scaling, hyperparameter automation,
                  and distributed training. Includes tokenization, evaluation (CORE), inference, and a web UI.
                </p>
                <div class="project-tags">
                  <span class="tag">PyTorch</span>
                  <span class="tag">LLMs</span>
                  <span class="tag">Scaling</span>
                </div>
                <div class="project-actions">
                  <span class="btn-mini">View Repo</span>
                </div>
              </div>
            </a>
          </li>

          <!-- FairSearch-arXiv -->
          <li class="project-item active">
            <a href="https://github.com/PratyushTyagi/IR-FairSearch-arXiv-Team6" target="_blank" rel="noopener noreferrer" class="project-card">
              <figure class="project-img">
                <div class="project-item-icon-box">
                  <ion-icon name="eye-outline"></ion-icon>
                </div>
                <!-- TODO: add a screenshot of the fairness scorecard at this path -->
                <img src="./assets/images/fairsearch.png" loading="lazy" alt="FairSearch-arXiv fairness scorecard">
              </figure>
              <div class="project-content">
                <h3 class="project-title">FairSearch-arXiv – Prestige Bias in Retrieval &amp; LLM Generation</h3>
                <p class="project-category">Information Retrieval • Fairness • RAG Evaluation</p>
                <p class="project-desc">
                  Team project (CS 6200) auditing institutional prestige bias in dense retrieval and LLM generation
                  over a ~50K-paper arXiv corpus. I owned corpus enrichment and fairness evaluation. SPD confidence
                  intervals spanned zero at every k, and Fair-Top-K preserved precision while MMR cost 2–5 precision
                  points with no measurable fairness gain. Results ship in a Streamlit fairness scorecard.
                </p>
                <div class="project-tags">
                  <span class="tag">Dense Retrieval</span>
                  <span class="tag">Fairness</span>
                  <span class="tag">Streamlit</span>
                </div>
                <div class="project-actions">
                  <span class="btn-mini">View Repo</span>
                </div>
              </div>
            </a>
          </li>

          <!-- NU Hacks RAG Clinical Q&A -->
          <li class="project-item active">
            <!-- TODO: replace # with the repo or Devpost URL -->
            <a href="#" target="_blank" rel="noopener noreferrer" class="project-card">
              <figure class="project-img">
                <div class="project-item-icon-box">
                  <ion-icon name="eye-outline"></ion-icon>
                </div>
                <!-- TODO: add a screenshot at this path -->
                <img src="./assets/images/nuhacks.png" loading="lazy" alt="RAG clinical Q&A tool">
              </figure>
              <div class="project-content">
                <h3 class="project-title">RAG Clinical Q&amp;A – 1st Runner-Up, NU Hacks 2026</h3>
                <p class="project-category">RAG • LLMs • Healthcare AI</p>
                <p class="project-desc">
                  Built a retrieval-augmented clinical question-answering tool with a team of 4 during a 48-hour
                  hackathon (March 2026), placing 1st Runner-Up.
                  <!-- TODO: add what it retrieved over, the stack, and how answers were grounded -->
                </p>
                <div class="project-tags">
                  <span class="tag">RAG</span>
                  <span class="tag">LLMs</span>
                  <span class="tag">Hackathon</span>
                </div>
                <div class="project-actions">
                  <span class="btn-mini">View Repo</span>
                </div>
              </div>
            </a>
          </li>

          <!-- OCT Retinal Disease Detection -->
          <li class="project-item active">
            <a href="https://github.com/Pavanijain03/oct_retinal_disease_detection" target="_blank" rel="noopener noreferrer" class="project-card">
              <figure class="project-img">
                <div class="project-item-icon-box">
                  <ion-icon name="eye-outline"></ion-icon>
                </div>
                <img src="./assets/images/oct-scan.png" loading="lazy" alt="OCT Retinal Disease Detection">
              </figure>
              <div class="project-content">
                <h3 class="project-title">OCT Retinal Disease Detection</h3>
                <p class="project-category">Deep Learning • Medical Imaging • Transfer Learning</p>
                <p class="project-desc">
                  Fine-tuned a DenseNet-121 (ImageNet transfer learning) to classify retinal disease from
                  100K+ OCT scans, reaching 95.4% test accuracy and 98.8% ROC-AUC. Deployed as an interactive
                  Streamlit inference app.
                </p>
                <div class="project-tags">
                  <span class="tag">PyTorch</span>
                  <span class="tag">DenseNet-121</span>
                  <span class="tag">Medical AI</span>
                </div>
                <div class="project-actions">
                  <span class="btn-mini">View Repo</span>
                </div>
              </div>
            </a>
          </li>

          <!-- Genomic Text Curation -->
          <li class="project-item active">
            <a href="https://github.com/Pavanijain03/nlp_system_genomics" target="_blank" rel="noopener noreferrer" class="project-card">
              <figure class="project-img">
                <div class="project-item-icon-box">
                  <ion-icon name="eye-outline"></ion-icon>
                </div>
                <img src="./assets/images/genomic.png" loading="lazy" alt="Genomic Text Curation & Topic Grouping">
              </figure>
              <div class="project-content">
                <h3 class="project-title">Genomic Text Curation &amp; Topic Grouping</h3>
                <p class="project-category">NLP • Topic Modeling • Information Extraction</p>
                <p class="project-desc">
                  Built an NLP pipeline to extract variants, genes, and diseases from genomics literature
                  (84% extraction precision, 78% recall), generate relation triples, and cluster texts using
                  TF-IDF, K-Means, NMF, and LDA.
                </p>
                <div class="project-tags">
                  <span class="tag">Python</span>
                  <span class="tag">NLP</span>
                  <span class="tag">Topic Modeling</span>
                </div>
                <div class="project-actions">
                  <span class="btn-mini">View Repo</span>
                </div>
              </div>
            </a>
          </li>

          <!-- Amazon -->
          <li class="project-item active">
            <a href="https://github.com/Pavanijain03/amazon-product-recommendation" target="_blank" rel="noopener noreferrer" class="project-card">
              <figure class="project-img">
                <div class="project-item-icon-box">
                  <ion-icon name="eye-outline"></ion-icon>
                </div>
                <img src="./assets/images/amazon-product.png" loading="lazy" alt="Amazon Product Recommendation">
              </figure>
              <div class="project-content">
                <h3 class="project-title">Amazon Product Recommendation</h3>
                <p class="project-category">Machine Learning • Recommender Systems</p>
                <p class="project-desc">
                  Built a collaborative filtering recommender to suggest products using user-item interactions,
                  evaluated with RMSE/MAE for recommendation quality.
                </p>
                <div class="project-tags">
                  <span class="tag">Python</span>
                  <span class="tag">Collaborative Filtering</span>
                  <span class="tag">Recommenders</span>
                </div>
                <div class="project-actions">
                  <span class="btn-mini">View Repo</span>
                </div>
              </div>
            </a>
          </li>

          <!-- Bank Loan Analysis -->
          <li class="project-item active">
            <a href="https://github.com/Pavanijain03/bank_loan_analysis" target="_blank" rel="noopener noreferrer" class="project-card">
              <figure class="project-img">
                <div class="project-item-icon-box">
                  <ion-icon name="eye-outline"></ion-icon>
                </div>
                <img src="./assets/images/bank-loan.png" loading="lazy" alt="Bank Loan Analysis">
              </figure>
              <div class="project-content">
                <h3 class="project-title">Bank Loan Report – Lending KPIs &amp; Portfolio Quality Dashboard</h3>
                <p class="project-category">Data Analysis • Tableau • BI Dashboard</p>
                <p class="project-desc">
                  Built a 3-view interactive Tableau dashboard (Summary, Overview, Details) on a 38.6K-loan,
                  $435.7M-funded portfolio — tracking KPIs (interest rate, DTI, MTD/MoM trends), portfolio
                  quality (86.2% good vs 13.8% bad), and drill-down across grade, purpose, state, and home ownership.
                </p>
                <div class="project-tags">
                  <span class="tag">Tableau</span>
                  <span class="tag">SQL</span>
                  <span class="tag">BI Dashboard</span>
                </div>
                <div class="project-actions">
                  <span class="btn-mini">View Repo</span>
                </div>
              </div>
            </a>
          </li>

          <!-- Credit Card -->
          <li class="project-item active">
            <a href="https://github.com/Pavanijain03/credit-card-fraud-detection" target="_blank" rel="noopener noreferrer" class="project-card">
              <figure class="project-img">
                <div class="project-item-icon-box">
                  <ion-icon name="eye-outline"></ion-icon>
                </div>
                <img src="./assets/images/credit-card-fraud.jpg" loading="lazy" alt="Credit Card Fraud Detection">
              </figure>
              <div class="project-content">
                <h3 class="project-title">Credit Card Fraud Detection</h3>
                <p class="project-category">Anomaly Detection • Deep Learning</p>
                <p class="project-desc">
                  <!-- TODO: replace "strong" with your actual recall and ROC-AUC numbers -->
                  Trained and compared models (LogReg, Random Forest, XGBoost, Autoencoders) to detect fraudulent
                  transactions with strong recall and ROC-AUC performance.
                </p>
                <div class="project-tags">
                  <span class="tag">XGBoost</span>
                  <span class="tag">Autoencoders</span>
                  <span class="tag">Fraud</span>
                </div>
                <div class="project-actions">
                  <span class="btn-mini">View Repo</span>
                </div>
              </div>
            </a>
          </li>

          <!-- Netflix -->
          <li class="project-item active">
            <a href="https://github.com/Pavanijain03/netflix-usage-analysis" target="_blank" rel="noopener noreferrer" class="project-card">
              <figure class="project-img">
                <div class="project-item-icon-box">
                  <ion-icon name="eye-outline"></ion-icon>
                </div>
                <img src="./assets/images/dashboard-1.png" loading="lazy" alt="Netflix Usage Analysis">
              </figure>
              <div class="project-content">
                <h3 class="project-title">Netflix Usage Analysis</h3>
                <p class="project-category">Data Analysis • Tableau</p>
                <p class="project-desc">
                  Built an interactive Tableau dashboard to explore Netflix titles by country, genre, and year,
                  highlighting content trends and growth patterns.
                </p>
                <div class="project-tags">
                  <span class="tag">Tableau</span>
                  <span class="tag">EDA</span>
                  <span class="tag">Dashboard</span>
                </div>
                <div class="project-actions">
                  <span class="btn-mini">View Repo</span>
                </div>
              </div>
            </a>
          </li>

        </ul>

      </article>

      <!-- CONTACT -->
      <article class="contact" data-page="contact">

        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>

        <section class="contact-list" style="margin-bottom: 30px;">
          <ul class="contacts-list">

            <li class="contact-item">
              <div class="icon-box">
                <ion-icon name="mail-outline"></ion-icon>
              </div>
              <div class="contact-info">
                <p class="contact-title">Email</p>
                <a href="mailto:jain.pav@northeastern.edu" class="contact-link">
                  jain.pav@northeastern.edu
                </a>
              </div>
            </li>

            <li class="contact-item">
              <div class="icon-box">
                <ion-icon name="logo-linkedin"></ion-icon>
              </div>
              <div class="contact-info">
                <p class="contact-title">LinkedIn</p>
                <a href="https://www.linkedin.com/in/pavani-jain-ab6488204/" target="_blank" rel="noopener noreferrer" class="contact-link">
                  linkedin.com/in/pavani-jain-ab6488204
                </a>
              </div>
            </li>

            <li class="contact-item">
              <div class="icon-box">
                <ion-icon name="logo-github"></ion-icon>
              </div>
              <div class="contact-info">
                <p class="contact-title">GitHub</p>
                <a href="https://github.com/Pavanijain03" target="_blank" rel="noopener noreferrer" class="contact-link">
                  github.com/Pavanijain03
                </a>
              </div>
            </li>

          </ul>
        </section>

        <section class="contact-form">
          <h3 class="h3 form-title">Send a Message</h3>

          <form action="https://formspree.io/f/xpqdajnr" method="POST" class="form">

            <div class="input-wrapper">
              <input type="text" name="name" class="form-input" placeholder="Full Name" aria-label="Full Name" required>
              <input type="email" name="email" class="form-input" placeholder="Email Address" aria-label="Email Address" required>
            </div>

            <textarea name="message" class="form-input" placeholder="Your Message" aria-label="Your Message" required></textarea>

            <input type="hidden" name="_subject" value="New Portfolio Contact Message">
            <input type="text" name="_gotcha" style="display:none" tabindex="-1" autocomplete="off">

            <button class="form-btn" type="submit">
              <ion-icon name="paper-plane"></ion-icon>
              <span>Send Message</span>
            </button>

          </form>
        </section>

      </article>

    </div>
  </main>

  <script src="./assets/js/script.js"></script>
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
