## About Me
I’m a machine learning engineer who loves building systems that make other people faster. Most of my work sits at the intersection of data, infrastructure, and experimentation — I enjoy turning messy inputs into clean pipelines, reusable tooling, and workflows that teams can trust.

Outside of work, I’m a part-time chef (strictly in my own kitchen) and an enthusiastic host. If you come over for dinner, there’s a good chance you’ll leave overstuffed, overly impressed, and with a playlist you didn’t ask for but secretly needed. I grew up in a family where music was always on, so it’s basically wired into how I think and work — pattern, rhythm, iteration, repeat.

When I’m not deep in a project, I’m usually outside chasing sun, near a beach if I’m lucky, or attempting to pet every cat and dog I see on the street. I’m also a globetrotter at heart — I once visited four countries in a single month and still claim it was for “research.”

Sundays are non-negotiable. Trader Joe’s run, a long gaming session, and the perfect soundtrack to match whatever world I’m exploring.

---

## Education
- **Northeastern University**, Boston, MA  
  *Master of Science in Data Science* (Graduated May 2025)  
  **Graduate Teaching Assistant, Khoury College of Computer Science**  
  - **Fall 2023**: TA for *DS 2000 Programming with Data*, assisting 700+ students with foundational programming concepts, debugging, and solving real-world data challenges using Python.  
  - **Fall 2024**: TA for *DS 3000 Advanced Programming with Data*, guiding students through advanced topics such as APIs, data visualization, and efficient data manipulation.  
  - Mentored students during office hours and project consultations, strengthening my ability to communicate complex concepts clearly.  
  - Collaborated with faculty on assignment design and grading, improving organizational and time management skills.  

  *Relevant Courses*: LLM Agents, Supervised & Unsupervised Machine Learning, Deep Learning, NLP, Database Systems, Data Processing & Visualization, Algorithms  

- **Vellore Institute of Technology**, Vellore, India  
  *Bachelor of Technology in Computer Science and Engineering* (June 2016 – June 2020)  
  *Relevant Courses*: Probability Theory, Linear Algebra, Statistics, Calculus, Differential Equations, AI, Data Mining  

---

## Work Experience

### **Apple** *(Austin, TX)*  
**Machine Learning Engineer – AI/ML (AI & Data Platforms, Customer & Brand Engagement)** *(July 2025 – Present)*  
**Key Focus Areas**:  
*ML Infrastructure, Experimentation Platforms, PySpark Pipelines, Snowflake, Databricks*

- **ML Pipeline Builder**: Engineered an internal ML pipeline builder enabling teams to compose end-to-end workflows over billions of Apple.com & survey events, from Snowflake extraction to model selection, inference, and evaluation.
- **Workflow Orchestration**: Designed backend orchestration in Python + PySpark to parameterize time windows, run performant Snowflake queries, and persist pipeline configs/results for reproducible, auditable workflows.
- **Experimentation Platform**: Co-developed an internal experimentation platform that standardizes A/B test creation across channels and enables teams to define primary/secondary KPIs and consistent analysis.
- **Statistics Framework**: Implemented a reusable Python statistics package to compute bias scores, p-values, confidence intervals, and lift across large-scale event streams using Databricks + Snowflake pipelines.
- **Cross-functional Execution**: Partnered with data engineering, product, and analytics teams to translate ambiguous optimization goals into concrete experiment designs and ML workflows tied to business impact.

---

### **Bose Corporation**  *(Boston, MA)* 
**Data Scientist NLP Intern** *(January 2024 – August 2024)*  
**Key Focus Areas**:  
*LLM Optimization (GPT-4, Llama 3.1), RAG Systems (AWS Kendra), NLP Pipelines (BERTopic, RoBERTa), Streamlit Development*

- **End-to-End ML Pipeline**: Implemented unsupervised topic clustering to identify 120 key return drivers from customer feedback. Trained & deployed a RoBERTa model on AWS for multi-label classification (F1 0.92), integrating Spark for preprocessing, inference, and result cleaning. 
- **AI Interview Automation**: Engineered OpenAI-powered assistant with Streamlit-Snowflake backend automating **200+ daily interviews**, reducing candidate dropout by **30%** while saving **50+ weekly hours**.
- **Enterprise Chatbot**: Deployed AWS Kendra RAG system handling **2K+ daily interactions** at **99.8% uptime**, validated through red team testing and guardrail implementation.
- **Cost-Optimized LLM Ops**: Transitioned sentiment analysis from GPT-4 → Llama 3.1 via A/B testing, achieving **97% cost reduction** while maintaining performance on **2M+ records**.
- **GenAI Analytics**: Automated product review analysis using Claude Sonnet/AWS Bedrock, enabling **65% faster insights** via Streamlit dashboard with **98% accuracy**.

---

### **West Pharmaceutical Services** *(Bangalore, IN)*  
**Data Scientist** *(November 2020 – December 2022)*  
**Key Focus Areas**:  
*Computer Vision (XceptionNet), Cloud Deployment (Azure), Production ML, Data Visualization*

- **Defect Detection**: Architected XceptionNet model identifying **15 defect classes** (**92% accuracy**, **37% improvement** vs manual), deployed via Docker/Azure.
- **Production Analytics**: Built Power BI dashboards enabling **43% faster** issue identification through visual trend analysis.
- **Document Intelligence**: Implemented BERT/ALBERT/RoBERTa pipelines improving document-keyword mapping by **23%**.

**Associate Data Scientist** *(January 2020 – November 2020)*  
**Key Focus Areas**:  
*ETL Pipelines (Azure Data Factory), NLP (BERT/ALBERT), Data Storytelling*

- **Enterprise Data Integration**: Designed Azure Data Factory pipelines ingesting/transforming documents from **10+ sources**, reducing data prep time by **35%**.
- **Document Intelligence**: Implemented transformer-based NLP workflows improving document-keyword mapping by **23%**, presenting insights through weekly stakeholder dashboards.
- **Process Optimization**: Migrated legacy manual workflows to automated ETL/NLP pipelines, collaborating with **5+ factory teams** to ensure operational alignment.

---

### **Info Origin** *(Bangalore, IN)*  
**Data Scientist Intern** *(May 2018 – August 2018)*  
**Key Focus Areas**:  
*Time Series Forecasting, ETL Development, Data Visualization*

- **Workplace Analytics**: Built ETL pipeline for 10K+ employee conference room data, enabling ARIMA forecasts (*R²: 0.90*) with Tableau dashboards tracking utilization trends.
- **Stakeholder Communication**: Presented forecasting insights through weekly visual reports, helping facilities team optimize room allocation and reduce scheduling conflicts by **28%**.
- **Process Documentation**: Created technical manuals for ARIMA model deployment, enabling knowledge transfer to the operations team.

---

## Projects

### Visual Mood-Based Music Recommendation (In progress)
- Leveraged LLaVA for vision-language understanding, retrieved mood-aligned songs via RAG with contrastive learning on audio embeddings, and integrated personalized Spotify playlist filtering.  
- Tools: LLaVA, RAG, Contrastive Learning, Spotify API, Streamlit  

### Automating Job Applications (October 2024) [Live App](https://promatchanalytics.streamlit.app)
- Built an LLM agent to scrape job descriptions, match resume embeddings, and generate tailored resumes/cover letters.  
- Tools: OpenAI Embedding API, Groq Llama 3.1 API, Streamlit  

### This Week in Football (September 2024)
- Developed a local LLM-powered agent to summarize and classify Reddit football data into short audio/text insights.  
- Tools: Reddit API, LangChain, Qwen 2.5, Llama 3.1, PostgreSQL  

### ArguSense: Argument Essay Evaluation (September 2023)
- Developed an NLP pipeline using Longformers and BERT to classify argument structures in essays. Integrated MLflow in AWS for model tracking, versioning, and deployment with containerization.  
- Tools: Streamlit, HuggingFace, Named Entity Recognition, Longformers, BERT, MLflow, AWS, Git LFS  

### Football Match Analysis and Predictions (June 2023) [Live App](https://barca-ds.streamlit.app)
- Deployed a Streamlit app for interactive analysis and visualization of 500+ football matches, integrating an ensemble model with Markov Chains, XGBoost, and Logistic Regression to predict the "Expected Threat" metric.  
- Tools: Streamlit, Python, StatsBomb API, OpenAI API, PostgreSQL  

---

## Achievements
- **Most Impactful Business Project Award** - Bose Hackathon: Developed a semantic search retrieval system for **1M+ records**.

---

## Technical Skills
- **Programming**: Python, R, SQL, C#  
- **Data Science**: Machine Learning, NLP, Deep Learning, Feature Engineering  
- **Libraries**: NumPy, Pandas, Scikit-learn, TensorFlow, PyTorch, LangChain, HuggingFace  
- **Platforms**: AWS, Microsoft Azure, Snowflake, Databricks  
- **Other**: Docker, Kubernetes, LLMOps, Streamlit  

---

## Contact
- **GitHub**: [github.com/PratikHotchandani22](https://github.com/PratikHotchandani22)  
- **LinkedIn**: [linkedin.com/in/pratik-hotchandani](https://linkedin.com/in/pratik-hotchandani)  
- **Email**: pratikhotchandani22@gmail.com, hotchandani.p@northeastern.edu  
