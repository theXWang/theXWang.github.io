---
# Display name
title: Xinlin Wang

# Name pronunciation (optional)
# name_pronunciation: Xinlin Wang

# Full name (for SEO)
first_name: Xinlin
last_name: Wang

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Postdoctoral Researcher

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of Luxembourg
    url: https://www.uni.lu/en/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:xinlin.wang.stats@gmail.com'
    label: E-mail Me
  # - icon: brands/x
  #   url: https://twitter.com/GetResearchDev
  # - icon: brands/instagram
  #   url: https://www.instagram.com/
  - icon: brands/github
    url: https://github.com/theXWang
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/xinlin-wang-ph-d-2745981aa/
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?user=NbdUYOoAAAAJ&hl=en
  - icon: academicons/orcid
    url: https://orcid.org/0000-0003-2275-9424

interests:
  - Artificial Intelligence
  - Large Language Model
  - Information Retrieval
  - Causal Inference
  - Fintech (Financial Risk Management)

education:
  - area: Ph.D. Computer Science
    institution: University of Luxembourg
    date_start: 2021-06-01
    date_end: 2025-02-10
    summary: |
      Thesis on _From Data to Decision: Enhancing SME Financial Health Prediction with Advanced Machine Learning Techniques_. Supervised by [Prof Mats Brorsson](https://https://www.uni.lu/snt-en/people/mats-hakan-brorsson/).
    button:
      text: 'Read Thesis'
      url: 'https://hdl.handle.net/10993/64305'
  - area: M.Sc. Marketing Analytics
    institution: University of Southampton
    date_start: 2016-09-01
    date_end: 2017-12-31
    summary: |
      GPA: 3.72/4.0 *Distinction*
      Thesis on _Measurement of Interest Rate Risk: An Analysis of Online P2P Lending Market in China_

  - area: B.Sc. Statistics
    institution: Liaoning University
    date_start: 2009-09-01
    date_end: 2013-07-31
    summary: |
      GPA: 83/100 *Top 10*
      
work:
  - position: Postdoctoral Researcher
    company_name: University of Luxembourg
    company_url: ''
    company_logo: ''
    date_start: 2025-02-11
    date_end: ''
    summary: |
      * LLM-Powered Chatbot Development: Built an interactive chatbot interface using Streamlit, supporting multiple LLM backends (e.g., GPT, Mistral, LLaMA, Qwen, Deepseek) with a custom RAG pipeline for querying and summarizing financial documents uploaded by users.
      * Multi-Agent & Tool-Use: Developed modular, agent-based workflows incorporating on-demand tool-calling for document parsing, query decomposition, retrieval planning, and answer synthesis. Used techniques such as function calling, react-style agents, and tool embedding to enhance interpretability and task accuracy.
      * Domain-Specific Fine-Tuning: Fine-tuned small and open-weight language models on proprietary financial datasets to improve document understanding, numerical reasoning, and task alignment in credit risk and financial health applications.
  - position: Data Scientist
    company_name: Beike Finance Ltd.
    company_url: ''
    company_logo: ''
    date_start: 2020-07-01
    date_end: 2021-05-31
    summary: |
      * Multimodal Feature Engineering: Cleaned and enriched data from structured data and unstructured text including property listings, user clickstreams, and customer reviews. Extracted semantic features from loan applications and collateral descriptions using pre-trained BERT, significantly boosting model signal quality for credit risk assessment.
      * Scalable ML Pipeline Development: Deployed models via Alibaba Cloud, designing and maintaining Airflow DAGs to automate end-to-end workflows — from data extraction and feature generation to model inference and monitoring. Iterated to achieve 0.87 AUC in production and implemented automated retraining triggers based on PSI and AUC thresholds.

  - position: Data Scientist
    company_name: Bairong Inc.
    company_url: ''
    company_logo: ''
    date_start: 2019-11-01
    date_end: 2020-07-31
    summary: |
      * Credit Risk & Fraud Modeling: Developed customized credit scoring models for financial clients using advanced models (logistic regression, LightGBM and DNN), tailored to diverse datasets including transaction records, telecom logs, and utility bills. Researched and applied anomaly detection techniques including unsupervised (Isolation Forest) and semi-supervised (PU learning) algorithms to improve fraud detection performance, resulting in a 25% lift in recall on historical fraud events.
      * Cross-Team Collaboration & Model Delivery: Collaborated with product, engineering, and client teams to align model pipelines with deployment infrastructure (batch scoring, APIs, scorecards). Took ownership of data extraction, feature engineering, and result formatting; delivered clear technical documentation and model outputs, and explained model behaviors to both technical and non-technical stakeholders using SHAP and intuitive visualizations. 
      
  - position: Algorithm Engineer
    company_name: Vcredit Ltd.
    company_url: ''
    company_logo: ''
    date_start: 2018-07-01
    date_end: 2019-10-31
    summary: |
      * Credit Risk Modeling (End-to-End): Developed full-cycle consumer credit risk scoring models using Python (scikit-learn, LightGBM, XGBoost), covering data preprocessing (PySpark, Hive), feature engineering (SMOTE for imbalanced data), hyperparameter tuning (Grid Search, Bayesian Optimization), performance validation (cross-validation, KS, AUC), and model deployment (Docker).
      * Model Monitoring & Calibration: Monitored model stability using drift metrics (PSI, KS, AUC) and recalibrated as needed to maintain performance and compliance with risk governance standards.
      * Third-Party Data Evaluation: Assessed external data sources using SHAP values and permutation importance to measure predictive uplift; integrated selected features into risk pipelines, enhancing AUC and KS (customize with exact metrics if available).    

  - position: Data Analyst
    company_name: China Telecom Ltd.
    company_url: ''
    company_logo: ''
    date_start: 2013-08-01
    date_end: 2016-08-31
    summary: |
      * KPI Monitoring & Dashboarding: Monitored the sales KPIs (GMV, new-subscriber growth, churn rate etc.) from Oracle database on 3 million users; built automated daily, weekly, and monthly reports using SQL, Power BI, and Excel VBA to support decision-making.
      * A/B Testing & Strategy Optimization: Implemented multi-dimensional analysis (cost, conversion, ROI) across different distributors to identify high-performing partners; designed and implemented A/B tests to optimize marketing spend and resource allocation, resulting in a 7% lift in new user acquisition.
      * Customer Segmentation: Built RFM models on different business to segment customers to identify high-value and at-risk users, and uncovering preferences to guide targeted marketing. 

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Python
        description: ''
        percent: 80
        icon: code-bracket
      - name: Data Science
        description: ''
        percent: 100
        icon: chart-bar
      - name: SQL
        description: ''
        percent: 40
        icon: circle-stack
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Hiking
        description: ''
        percent: 60
        icon: person-simple-walk
      - name: Cats
        description: ''
        percent: 100
        icon: cat
      - name: Photography
        description: ''
        percent: 80
        icon: camera

languages:
  - name: Chinese
    percent: 100
  - name: English
    percent: 85
  - name: French
    percent: 20

Awards:
  Add/remove as many awards below as you like.
  Only `title`, `awarder`, and `date` are required.
  Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  # - title: Neural Networks and Deep Learning
  #   url: https://www.coursera.org/learn/neural-networks-deep-learning
  #   date: '2023-11-25'
  #   awarder: Coursera
  #   icon: coursera
  #   summary: |
  #     I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.
  # - title: Blockchain Fundamentals
  #   url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #   date: '2023-07-01'
  #   awarder: edX
  #   icon: edx
  #   summary: |
  #     Learned:
  #     - Synthesize your own blockchain solutions
  #     - Gain an in-depth understanding of the specific mechanics of Bitcoin
  #     - Understand Bitcoin’s real-life applications and learn how to attack and destroy Bitcoin, Ethereum, smart contracts and Dapps, and alternatives to Bitcoin’s Proof-of-Work consensus algorithm
  # - title: 'Object-Oriented Programming in R'
  #   url: https://www.datacamp.com/courses/object-oriented-programming-with-s3-and-r6-in-r
  #   certificate_url: https://www.datacamp.com
  #   date: '2023-01-21'
  #   awarder: datacamp
  #   icon: datacamp
  #   summary: |
  #     Object-oriented programming (OOP) lets you specify relationships between functions and the objects that they can act on, helping you manage complexity in your code. This is an intermediate level course, providing an introduction to OOP, using the S3 and R6 systems. S3 is a great day-to-day R programming tool that simplifies some of the functions that you write. R6 is especially useful for industry-specific analyses, working with web APIs, and building GUIs.
---

## About Me

Results-driven Data Scientist with 7+ years of experience turning complex, high-volume data into actionable insights and production-ready machine-learning solutions. Skilled in Python, PyTorch, scikit-learn, Spark, and cloud-native MLOps (Docker, Airflow). My projects span NLP (BERT-based text classification, multi-agent RAG chatbots), tabular ML, time-series forecasting, and graph analytics, consistently delivering measurable lifts in accuracy and business value. Ph.D. in Computer Science with a strong foundation in statistical learning, causal inference, and model interpretability. Passionate about ethical AI, cross-functional collaboration, and continuous innovation to solve real-world problems at scale.
