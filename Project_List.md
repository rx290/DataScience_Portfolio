# Project List

1. Custom AI Agent with Memory
    Voice and text assistant with long-term memory
    Stack: Python (LangChain), OpenAI, Whisper, Redis/ChromaDB, Streamlit/Next.js
2. AI Code Review Bot
    Github bot that auto-reviews PRs using GPT
    Stack: Python, Fast API, GPT-4/Claude, Github API + Actions and Gitbhu Actions
3. AI Document Search (RAG Chatbot)
    Chat with PDFs using LLMs + semantic Search
    Tailwing, Python, FastAPI, OpenAI, Langchain, Pinecone/FAISS vercel+Docker
4. Holiday Shopping Budget Planner
    Stack: Python, Dash or Streamlit, SQL, Sklearn forecasting
    Dataset: Personal expenses CSV uploaded by user + industry seasonal spend data
5. Eid Recipe Recommendation Engine
    Python, NLP(SpaCy/BERT), collaborative filtering, Streamlit
    Source: Food.com Recipes Datasets/Kaggle + User ingredient input
    Suggest Recipes based on dietary needs & ingredients on hand.
6. Fall Travel Demand Forecaster
    Stack: Python, Scikit-learn, prophet, streamlit, Mapbox
    Source: Google Trends, Skyscanner API, weather data, tourism stats
    Predict Popular Fall destinations + budget forecast for flights/hotels
7. Winter Flue & Vitamin D Trend Predictor
    Stack: Python, Prophet, CDC/ECDC data, weather API
    Source: Flu vaccination stats, Google trends("flu symptoms"), sunlight Hours
8. Multi Agent Workflow Automator
    Use a framework like CrewAI or LangGraph to build a team of specialized AI agents that collaborate to complete a complex task, for example a Marketing Campaign creator team consisting of:
    1. A Research Agent that analyzes current trends.
    2. A copywriter Agent that drafts ad copy
    3. An Art Director Agent that generates image prompts for Dall E or stable Diffusion
    4. A manager Agent that Assembles the final Brief.

9. The Self-correcting RAG Pipeline
    Build Retrieval-Augmented Generation(RAG) system that doesn't just retrieve and answer. It first retrieves documents, has a second LLM (A Guardrail Agent) review the retrieved context for relevance, and then has a third LLM generate the answer. Finally it uses a fourth LLM (an Evaluator Agent) to score the final answer against the source context for factual conistency.
10. The LLM as Judge Evaluation Framework
    Build a custom evaluation framework for a subjective task that is hard to measure (e.g. creativity in story writing, brand tone adherence in marketing copy, or code readability). Use a powerful LLM like GPT-4o as a judge and build a Streamlit app that allows a user to compare outputs from two different models/prompts and see the judge's score and reasoning.
11. The Niche Fine-Tuned Open Source Model
    Identify, a highly specific, non commercial domain (e.g. academic biochemistry research papers, 18th century legal texts, or a specific open-source library's documentation)
    Curate a high-qualtiy dataset of a few thousand examples and fine-tune a small, open-source model (like Llama 3 8B or Phi-3) to be an expert in that niche.
12. Seasonal Depression (SAD) Early Warning Model
    Model Correlation Between Daylight drop, mood and routines.
    Stack: Python, LightGBM, wearable data, Google Trends
    Source: Sleep logs, step count, sunlight hours, mental health trends
13. Fall Drink Sentiment Analyzer
    Analyze Online sentiment around fall falvors(Pumpkin spice, chai, apple cider)
    Stack: Twitter API, Hugging Face, Streamlit
    Source: Tweets, TIktok captions, Stabucks and similar resturants Menu Prices
14. Autum Air Quality & Health Analysis
    Analyze Lead-burning, Humidity, air quality + symptons reports
    Stack: Python, Air Quality APIs, Regression
    Source: Get data from Air Pollution datasets, or weather APIs
15. Netflix Show Clustering
    Group similar shows using K-means based on genre, rating and duration.
    Stack: Python, Pandas, Scikit-learn, Seaborn
16. Spotify Audio Feature Analyzer
    Analyze Songs by tempo, energy and dancebility using spotify API.
    Stac: Python, Spotipy, Matplotlib, Plotly
17. Youtube Trending Video Analyzer
    Discover what makes a video go viral.
    Stack: Python, Pandas, BeautifulSoup, Seaborn
18. Resume Scanner Using NLP
    Predict BTC/ETH prices using historical data.
    Stack: Python, LSTM(keras), Pandas, Matplotlib
19. Crypto Price Predictor
    Sugget hashtags based on image captions or niche
    Stack: Python, NLP, TF-IDF, Cosine Similarity
20. Instagram Hashtag Recommender
    Analyze community sentiment on hot topics using Reddit API.
    Stack: Python, PRAW, VADER, Plotly
21. Reddit Sentiment Tracker
22. AI Job Posting Dashboard
    Scrape and visualize job trends by tech stack and location
    Stack: Python, Selenium/BeautifulSoup, Streamlit
23. Airbnb Price Estimator
    Predict Listing Prices based on location and amenities
    Stack: Python, Scikit0learn, Pandas, XGBoost
24. Food Calories Image Classifier
    Estimate calories from food images using CNNs.
    Stack: Python TensorFlow/Keras, OpenCV
25. Removing Music From Songs or Videos
26. Youtube app that allows you to disable shorts and block channels
27. Amusement Chatbot that uses Hollywood and bollywood dataset to return quotes or teach you quotes
28. AI Chatbot that visualize mindmap and build diffrent diagrams
29. Algo From Scratch
    1. Linear Regression
    2. Logistic Regression
    3. Naive Bayes
    4. Decision Tree
    5. Random Forrest
    6. Gradient Boosted Trees
    7. Principal Component
    8. K-nearest Neighbour
    9. Dense Neural Network
    10. K-mean Clusttering
    11. SVM
    12. Dimensionality Reduction
    13. Time Series
    14. Anomaly Detection
    15. Search
    16. Recommenders
    17. Buy Recommendations
    18. Classification
    19. Regression
30. Papers to Read
    1. Attention is all you need (2017)
    2. BERT (2018)
    3. GPT-3: Few-shot learners
    4. T5 (2020)
    5. Scaling Laws
    6. RAG
    7. LoRA(2021)
    8. Chain of Thought Prompting (2022)
    9. Self-consistency
    10. In-context learning & Induction Heads
    11. instruction Tunning
    12. Toolformer
    13. ColBertv2
    14. LLMs as a Judge 2023
    15. Deepseek-R1 2025

## Other Projects

   Basic Automation & System Scripts

        1 | File Organizer | Organizes files based on type/date | #Python #Automation | 1 day | Shows file ops, scripting
        2 | PDF Data Extractor | Extracts tables, text from PDFs | #Python #Automation #NLP | 1 day | Real use-case in doc parsing
        3 | CLI Weather App | API-based weather CLI | #API #Scripting | 1 day | Lightweight API integration
        4 | Alarm Clock with Audio | Plays sound at given time | #Scripting #Async | 1 day | Time/event handling
        5 | CSV Data Cleaner | Cleans noisy datasets | #Python #ETL #DataPrep | 1–2 days | Practical data engineering starter
        6 | Screenshot Auto Logger | Takes screenshots periodically | #Automation #Threading | 1–2 days | Automation + timer threading
        7 | Automated Backup Script | Zips and backs up folders | #Python #Automation | 1–2 days | Basic archiving and scheduling

    Intermediate Projects – API, Concurrency, Local AI

        8 | Multithreaded File Downloader | Download multiple files | #Threading #I/O #Python | 2–3 days | Thread-safe design
        9 | Image Resizer API | Resize, convert image formats | #FastAPI #Pillow | 2 days | Practical API service
        10 | Markdown → HTML Site Generator | Build static site generator | #Jinja2 #Templating #CLI | 2 days | Shows templating + CLI
        11 | Resume Parser API | Parses PDF resumes | #FastAPI #PyMuPDF #NLP | 3 days | Real-world NLP use
        12 | Email Auto Responder | Parses + replies based on rules | #Email #RuleEngine | 3 days | Inbox automation + regex logic
        13 | URL Monitor + Alert | Checks uptime, notifies on failure | #FastAPI #Scheduler #DB | 3 days | Monitoring + alert logic
        14 | Job Scheduler with SQLite | Task table + cron-style logic | #SQLite #Threading #Scheduler | 3–4 days | Basic job management

        AI & ML-Infused Projects

        15 | Document Summarizer API | Local summarizer (DistilBART) | #ML #API #HuggingFace | 4 days | Shows LLM-lite use
        16 | Intent Classifier (with fallback) | Classifies phrases + rule fallback | #NLP #Fallback | 4–5 days | Realistic hybrid design
        17 | PDF → Keyword + QnA Extractor | Chunk text, extract Q&A | #NLP #LangChain #Embeddings | 5–7 days | Use of context-aware RAG
        18 | AI Chat Logger + Visualizer | Chatbot + SQLite + charts | #NLP #DB #Analytics | 4–5 days | ML + backend + analytics
        19 | CLI Research Assistant | Query over local files (RAG) | #Embeddings #NLP | 5 days | Smart document search
        20 | Audio Keyword Spotter | Classifies audio keywords | #TinyML #Audio #TFLite | 1 week | Embedded ML use-case

        Backends, APIs, and Infra Projects

        21 | Rate Limiter with Redis | API rate control by user/IP | #FastAPI #Redis #Security | 2 days | Security + infra insight
        22 | Secure Auth System (JWT) | Login, refresh, RBAC | #FastAPI #JWT #Security | 3–4 days | Must-have auth skills
        23 | Modular Microservice Boilerplate | N microservices + broker | #FastAPI #Kafka #Docker | 5–7 days | Scalable architecture
        24 | Real-time WebSocket Chat | Socket + user sessions | #WebSockets #Auth | 3 days | Async + real-time comms
        25 | Image Upload + Scan API | Image upload, scan, classify | #API #ML #Security | 4 days | Storage, ML + threat scanning
        26 | Dockerized ML Inference Server | Serve a model in container | #Docker #ML | 2–3 days | MLOps intro

        Job Management + Scheduling

        27 | Python Celery-Lite | Build basic Celery clone | #Multiprocessing #Broker | 5 days | Shows how queues work
        28 | AI Job Queue Manager | ML tasks queued + status | #AI #JobQueue #Redis | 5–6 days | AI + job control
        29 | CLI Job Runner with Retry | Failsafe script with retry logic | #Retry #CLI #Logs | 2–3 days | Command-level robustness
        30 | SQLite-Backed Queue API | API to enqueue + view jobs | #FastAPI #SQLite #Threading | 4 days | Backend + concurrency

        Advanced AI + Backend Projects

        31 | Secure AI Inference API | Role-based access + quotas | #FastAPI #AI #Security | 1 week | Shows real-world ML SaaS
        32 | ML Model Deployment Manager | Upload, deploy, run models | #ML #Deployment | 1 week | Model lifecycle engineering
        33 | Log Parser + Threat Detector | Regex + ML alerts | #Security #NLP #Streaming | 1 week | Realistic SIEM mini-system
        34 | Automated Code Reviewer | LLM + GitHub API | #AI #Code #LangChain | 1 week | Apply AI to DevOps
        35 | Model Benchmark Dashboard | Compare latency/accuracy | #ML #FastAPI #Dash | 1 week | Useful for MLOps interviews
        36 | Docker Sandbox Code Runner | Run user code securely | #Security #Sandboxing | 1 week | Critical skill for SaaS
        37 | Video Processor API | Upload, compress, store | #FFmpeg #FastAPI #Storage | 1 week | Shows backend + video + optimization

        Full Stack + Deployment Projects

        38 | Portfolio Deployment System | Script to deploy on Fly.io | #CI/CD #Bash #Fly.io | 2–3 days | DevOps automation
        39 | Blog Deployment via GitHub API | Script → Blog via GitHub | #GitHubAPI #CI | 2–3 days | Creative automation
        40 | Low-Code AI Dashboard | Configure pipelines via GUI | #Streamlit #ML #Jobs | 1 week | GUI + backend + dynamic logic
        41 | GraphQL API + DB | Structured backend alternative | #GraphQL #PostgreSQL | 3–4 days | Showcases modern API stack
        42 | Dynamic Config Engine | JSON/YAML-driven rules | #Python #RulesEngine | 4 days | Template automation tool

        Workflow, Rule Systems, Monitoring

        43 | Rule-Based Task Engine | DSL or JSON rules trigger tasks | #RulesEngine #Automation #Python | 1 week | Useful for IFTTT/automation systems
        44 | Smart Log Analyzer | Regex + ML to classify logs | #Security #LogAnalysis | 1 week | Core for monitoring and ops
        45 | Configurable Alert System | JSON rules + triggers | #Automation #Alerting | 3–4 days | Integrates well with APIs and ops
        46 | Event-Driven Notifier | Accepts webhook & routes events | #Webhooks #PubSub | 3–5 days | Core microservice pattern
        47 | Resume Ranker + ML | Score resumes based on job post | #ML #TextSimilarity #Automation | 1 week | AI + rule integration
        48 | Markdown Wiki System | CLI wiki builder from .md files | #StaticSite #Python #CLI | 2–3 days | Templating + parsing + docs
        49 | Folder-Based CI Runner | Runs scripts based on folder rules | #CI #Bash #JobRunner | 3 days | DIY DevOps job manager
        50 | Dynamic Document Generator | PDF / DOCX report engine | #ReportGen #Templates | 3–4 days | Useful for forms, HR, etc.

        Lightweight NLP + AI UX

        51 | Sentence Rewriter API | Rewrite in friendly/formal tone | #NLP #API | 4–5 days | Showcases practical NLP
        52 | Local LLM for Search Suggestions | Typing suggestion engine | #Embeddings #LLM | 1 week | Search system backbone
        53 | NER Extractor + Exporter | Named entities from text corpus | #NLP #spacy | 3–4 days | Foundation of info extraction
        54 | Doc Tagger + Classifier | Auto-label PDFs / articles | #NLP #Classifier | 1 week | Embedding or keyword-based
        55 | Text Intent Mapping Tool | Rule + model intent assigner | #IntentMapping #CommandParser | 5–7 days | Useful for AI/IoT bridge

        Stream Processing + Async Systems

        56 | Real-Time Log Stream Analyzer | Stream logs, detect anomalies | #Kafka #Streaming #ML | 1 week | Intro to async pipelines
        57 | Tweet Stream Tracker | Async collector + parser + store | #Streaming #AsyncIO | 3–4 days | Shows data ingestion
        58 | File Ingest Pipeline | Async file watcher → parser | #Async #Pipeline #Concurrency | 4 days | Core ETL pattern
        59 | Simple Alert Aggregator | Ingests alerts → deduplicates | #FastAPI #Concurrency #Security | 3–5 days | Security ops + job mgmt
        60 | ML-Based Rate Anomaly Detector | Finds request spikes in API logs | #ML #Security #Streaming | 1 week | Security + infra AI use

        MLOps and Model Lifecycle

        61 | Lightweight Model Registry | Register/upload ML models | #MLOps #Backend | 1 week | Core to production AI
        62 | AI Task Version Manager | Assign model versions per job | #MLInfra #APIs | 1 week | Shows thought on versioning
        63 | ML Explainer API | SHAP or LIME on inference calls | #Explainability #ML | 1 week | High-value for enterprise ML
        64 | Model Drift Tracker | Monitor prediction drift over time | #MLOps #DataDrift | 1 week | Essential for real-world ML
        65 | Custom Feature Store | Build + query features for models | #MLInfra #Backend | 1–2 weeks | Advanced infra design

        DevOps, Tooling, Security, and Monitoring

        66 | JWT Manager CLI | Encode, decode, validate JWTs | #Security #CLI #JWT | 2–3 days | Developer-focused tool
        67 | File Integrity Watcher | Track file changes over time | #Security #Monitoring | 3 days | Useful for security/ops
        68 | Dependency Scanner | Scan Python project for risks | #Security #Pip #CLI | 3 days | Good for security knowledge
        69 | Simple Secrets Vault | CLI tool to encrypt/decrypt files | #Encryption #SecretsMgmt | 4–5 days | Applied crypto + CLI
        70 | Secure Command Executor | Run shell commands with validation | #Security #Subprocess | 4 days | Sandbox-lite + DevOps

        Projects with NLP + Automation + Voice

        71 | CLI Voice Assistant | Offline command recognizer | #Voice #Automation #NLP | 1 week | Voice + NLP + shell ops
        72 | CLI Translator with History | Translate + store + export | #NLP #Translation #Logs | 3–4 days | Language + workflow
        73 | Text Macro Expander | Expand template-based text | #Rules #CLI | 3 days | String engine + productivity
        74 | Custom Rule DSL Parser | Parse and execute custom rules | #Interpreter #Parser #Security | 1 week | Shows compiler theory + backend logic
        75 | Tiny Voice Command Engine | Keyword → command router | #Voice #Intent #RuleBased | 4 days | Useful for IoT / edge control

        Full Stack + Flutter-Enabled AI Projects

        76 | Flutter + AI Summarizer | Upload text, get summary | #Flutter #PythonAPI #LLM | 1 week | Clean frontend for LLM
        77 | Flutter + Scan & Classify | Upload image, classify result | #Flutter #TFLite | 5 days | Mobile ML integration
        78 | Flutter + Chat with Local API | Chat UI + LangChain backend | #Flutter #Chatbot #API | 1 week | Cross-stack AI
        79 | Flutter + Real-time Weather + AI Commentary | Weather + auto-suggestions | #Flutter #API #AI | 1 week | Combines multiple systems
        80 | Flutter + Notification Engine | Receive alerts from job system | #Flutter #API #DevOps | 1 week | Mobile ops integration

        Advanced Infra + System Design Projects

        81 | Remote Shell Executor (Secure) | Run commands via REST safely | #Security #Subprocess | 1 week | Sandbox + permissions
        82 | Data Lake Builder (Mini Version) | Ingest, store, query datasets | #ETL #DuckDB #API | 2 weeks | Shows real data infra
        83 | Mini Git Client | Clone, commit, push | #CLI #GitInternals | 2 weeks | Shows deep system-level understanding
        84 | Real-Time Dashboard for Jobs | Live chart of system metrics | #WebSockets #Monitoring | 1 week | Async + UI + infra
        85 | AI Content Filter | Scan inputs for risky content | #NLP #Security | 5–7 days | Practical in chat tools

        Research-Focused or Experimental

        86 | Gesture-to-Intent Mapper | Radar + Rule system | #TinyML #Radar #NLP | 1–2 weeks | Your thesis toolchain
        87 | Document Triplet Extractor | Extract subject–verb–object | #NLP #Embeddings | 1 week | Info extraction research
        88 | AI PDF Reviewer | Reviews academic PDFs | #NLP #ScholarAI | 1 week | Research NLP pipeline
        89 | Codebase Tagger + Summarizer | Extracts topics from repo | #AI #Code #AST | 1–2 weeks | Advanced static + semantic analysis
        90 | Sensor Fusion API | Combine multiple sensor readings | #IoT #APIs #AI | 1 week | Useful in robotics/edge AI

        Platform Engineering / DevTool Projects

        91 | Model Comparison Framework | Load, test, compare results | #MLInfra #Benchmarks | 1–2 weeks | Evaluation engine
        92 | AI Test Generator | Given code → test cases | #AI #PromptGen | 1 week | LLM in DevOps
        93 | API Mock Server | Simulate any API from schema | #FastAPI #Testing | 3–5 days | Great for integration testing
        94 | Rule-Based Config Validator | JSON/YAML policy enforcer | #Rules #Validation | 4–5 days | Used in DevOps & infra
        95 | Interactive Log Explorer | GUI + filters + context | #Logs #Dashboard | 1 week | Useful for observability

        Final 5 – Creative, Hybrid, or Stretch Projects

        96 | Human-in-the-loop Decision API | ML + manual approval paths | #ML #Workflow #Moderation | 1–2 weeks | Shows pipeline design
        97 | Secure Script Runner for Teams | Shared task runner with auth | #Security #TaskRunner | 1 week | DevOps/infra for teams
        98 | CLI Model Playground | Load/compare models from CLI | #LLM #CLI #Tooling | 5–6 days | Great for AI devs
        99 | AI-Powered Incident Responder | Ingest logs → suggest actions | #Security #AI | 2 weeks | Smart incident assistant
        100 | Modular ML API Marketplace | Upload model, assign routes | #MLInfra #Docker #API | 2–3 weeks | Full backend platform
