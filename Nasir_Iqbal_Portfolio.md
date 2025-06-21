# 📂 Portfolio Highlights – Nasir Iqbal
**Python Backend Developer**  
_Flask • FastAPI • MongoDB • MySQL • Kafka/NATS • RabbitMQ • Redis • Celery • Playwright • Docker • CI/CD • AWS (EC2 • S3 • Lambda • RDS • SQS) • GCP BigQuery_

📞 +971 56 301 3462  
📧 nasir.iqbal.dev@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/nasir-iqbal5/) | [GitHub](https://github.com/itx-nasir) | [Portfolio Website](https://itx-nasir.github.io/)

---

## 🚀 Personal & Freelance Projects

### 🧠 ResuMatch – AI Resume Matching
**Links**: [GitHub](https://github.com/itx-nasir/ResuMatch) | [Live Demo](https://resumatch-qd38.onrender.com)  
**Stack**: FastAPI, React, MongoDB, **Gemini API**, Docker  
- Built an **AI-powered resume analyzer** that parses resumes and job descriptions (PDF, DOCX, TXT).  
- Calculates match percentage and highlights missing skills using **Gemini LLM**.  
- Developed clean **REST APIs** with FastAPI and integrated file parsing, OpenAI API, and **async processing**.  
- Deployed using **Docker** and Render with persistent file support and robust error handling.  
- Achieved significant improvement in candidate-job alignment and automated screening process.

---

### 🛡️ PhishGuard – Advanced Email Security Analysis System
**Links**: [GitHub](https://github.com/NasirIqbalDev/phishing-analyzer) | [Live Demo](https://phishing-analyzer.onrender.com)  
**Stack**: Flask, Celery, Redis, Docker, **ML-Ready Architecture**  
- Engineered a comprehensive email security analysis system with **real-time processing** capabilities.
- Parses email headers and HTML content to detect common **phishing patterns**.
- Extracts **SPF**, **DKIM**, suspicious URL presence, link mismatches, and encoding tricks.
- Developed **multi-layered detection** system analyzing headers, content, links, and attachments simultaneously.
- Implemented **async processing** architecture using Celery workers and Redis for handling large-scale analysis.
- Built **ML-ready API** architecture designed for seamless integration with machine learning models for enhanced detection.
- Implemented robust security features including:
  - **Containerized** file processing for isolation
  - Automated temporary file cleanup
  - **Rate limiting** and CORS protection
  - Comprehensive input validation
  - Secure file handling protocols
- Designed clean **RESTful API** endpoints with detailed documentation for easy third-party integration.
- Utilized Redis for efficient **message brokering** and result storage in distributed setup.
- Outputs structured JSON reports usable in email gateways and security systems.
- Implemented comprehensive error handling and logging system for production reliability.
- Architected the system for **horizontal scaling** with containerized components using Docker.

---

### 🎓 Student Management System
**Links**: [GitHub](https://github.com/itx-nasir/Student-Management-System) | [Live Demo](https://student-management-system-gfln.onrender.com/)  
**Stack**: Django, PostgreSQL, Celery, Docker  
- Built a school admin system to manage students, grades, staff, and attendance.  
- Developed staff dashboards and Celery-based report generation pipelines.  
- Used Docker for containerization and PostgreSQL for relational data storage.  
- Created scalable system capable of handling 1000+ academic institution records efficiently.

---

### 🛡️ NEBULA – Distributed Browser Automation & Fingerprint Manager
**Links**: [GitHub](https://github.com/itx-nasir/nebula-bot-manager)  
**Stack**: Playwright, Redis, Python, CLI, MongoDB  
- Built a **production-ready headless automation system** for parallel browser task management.
- Implemented sophisticated session management with **unique persistent fingerprints** per bot instance.
- Each bot maintains **isolated state** with dedicated login sessions and **sticky proxy** connections.
- Leveraged MongoDB for storing and managing unique **browser fingerprints**, cookies, and session data.
- Implemented **sharding** for bot session data across MongoDB collections for improved performance.
- CLI app enables **dynamic scaling** of concurrent bot instances with real-time monitoring.
- Integrated Redis for **distributed task queueing** and synchronized session state management.
- Built robust data persistence layer with MongoDB for storing proxy configurations, bot metrics, and execution logs.
- Bypasses modern **anti-bot systems** (FingerprintJS, Cloudflare) using advanced browser fingerprint spoofing.
- Features include proxy rotation, time-based execution patterns, and automated session recovery.
- Developed scalable and detection-resistant browser automation system with persistent bot identities.

---

### ✈️ Real-Time Flight Scraper
**Links**: [GitHub](https://github.com/NasirIqbalDev/flight-scraper) | [Live Demo](https://flight-scraper.onrender.com)  
**Stack**: Playwright, Flask, Docker, Gunicorn, Uvicorn, NGINX, DigitalOcean, Redis Queue  
- Engineered a sophisticated flight data scraping system replacing Odynn API (**$0.02/request**), achieving **100% cost reduction**.
- Implemented advanced **anti-bot bypass** techniques using Stealth.js, browser fingerprint spoofing, and intelligent session management.
- Built resilient architecture handling **4 requests/second** with Redis Queue for request processing and failure handling.
- Optimized performance achieving **20-second round-trip** searches compared to Odynn's **40-second one-way** searches.
- Developed smart proxy management system with **hybrid sticky/rotational strategy** to prevent IP blocking.
- Utilized **async programming** with 4 Gunicorn workers and Uvicorn for enhanced concurrency and throughput.
- Built Playwright workers with sophisticated retry logic, delay simulation, and JavaScript rendering handling.
- Implemented advanced session persistence and cookie management to maintain stable connections.
- Engineered custom solutions to bypass complex anti-bot systems including browser behavior analysis and fingerprint detection.
- Backend Flask API exposes endpoints with comprehensive error handling and request validation.
- Production deployment on **DigitalOcean Droplet** using **Docker**, **Gunicorn**, **Uvicorn**, and **NGINX**.
- Maintains 99% uptime and reliable anti-bot protection for continuous flight data collection.

---

### ⚙️ NasirPy – Minimal Async Web Framework
**Links**: [GitHub](https://github.com/itx-nasir/nasirpy) | [Documentation](https://itx-nasir.github.io/nasirpy/)  
**Stack**: Python, Asyncio, HTTPParser, PyTest, FastAPI/Flask  
- Developed a **FastAPI-like web framework** from scratch to understand internals of async routing, DI, and middleware.  
- Features routing, request/response handling, **middlewares**, **dependency injection**, and custom exceptions.  
- Published and documented for educational purposes.  
- Successfully demonstrated deep understanding of Python **async web server** architecture and implementation.

---

### 📊 Workflow & Process Management System
**Links**: [GitHub](https://github.com/itx-nasir/workflow-creator)  
**Stack**: Django, PostgreSQL, Celery, Redis, Docker  
- Built a complete BPM engine to create workflows and approval pipelines via drag-and-drop UI.  
- Included role-based access control, audit trails, approval delays, document management.  
- Backend written in Django with Celery for background task handling and secure document uploads.  
- Implemented comprehensive internal approval processes with robust security and traceability features.

---

### 🌍 WiseTranslator – English–Urdu Neural Translator
**Links**: [GitHub](https://github.com/itx-nasir/FYP-WiseTranslator)  
**Stack**: PyTorch, Transformers, Flask, HTML/CSS  
- Trained a bilingual transformer model to perform English↔Urdu translations using parallel corpora.  
- Added beam search decoding and fallback logic with Urdu WordNet for better semantic output.  
- Built a simple UI using Flask and HTML for real-time translation interface.  
- Enabled efficient translation support for native language content and educational purposes.

---

## 🏢 Impactful Company Projects

### 💼 Creed & Bear – Dubai, UAE  
*Python Backend Developer (Jul 2023 – Present)*

#### 🚀 Amaia Crypto Platform  
**Stack**: Django, MongoDB, NATS JetStream, Celery, Docker  
- Built microservices using event-driven architecture to manage crypto portfolio operations.  
- Developed APIs for KYC, wallet sync, balance management, and user dashboards.  
- Integrated Celery workers for background polling, webhook handlers, and investment logic.  
- Achieved real-time trading capabilities and maintained data accuracy under high-volume loads.

#### 🧪 Hercules Testing Suite  
**Stack**: FastAPI, PostgreSQL, Pytest, GitHub Actions  
- Built centralized async test framework for all backend services.  
- Included CI pipelines with automated coverage reports and test isolation.  
- Achieved 70% reduction in release cycles and QA bottlenecks through automated testing.

---

### 💼 PackageX – Islamabad, Pakistan  
*Python Developer (Jan 2022 – Jul 2023)*

#### 📬 Mailroom OCR Engine  
**Stack**: Flask, PyTorch, PostgreSQL, Docker  
- Built backend API for scanned document parsing using OCR and ML models.  
- Integrated PyTorch models with preprocessing (binarization, deskewing, resizing) to improve accuracy.  
- Achieved 80% reduction in human data entry through automated document processing.

#### 🔄 ETL Pipelines for Reporting  
**Stack**: Cron, AWS S3, GCP BigQuery, Pandas  
- Created ETL jobs for syncing ops/finance data into structured formats.  
- Wrote resilient data pipelines with alerting and schema validation.  
- Implemented near real-time dashboard updates and comprehensive internal reporting system.

---

## 🏆 Key Achievements
- ✨ Engineered **event-driven crypto trading platform** using NATS JetStream, reducing transaction latency by **60%**
- ✨ Achieved **88% OCR accuracy** in production for diverse document formats using hybrid ML techniques
- ✨ Reduced QA bottlenecks by **70%** through centralized async test framework implementation
- ✨ Built real-time flight data scraper achieving **4 requests/second**, replacing paid API ($0.02/request)
- ✨ Developed **distributed browser automation** system bypassing enterprise-grade anti-bot protection
- ✨ Created **ML-ready email security** system with multi-layered phishing detection
- ✨ Built lightweight **async web framework** demonstrating deep understanding of Python web internals

> **Note**: Some demo applications may experience slower response times as they are deployed on Render's free tier, which has limited resources and cold starts. For the best experience, please allow a few moments for the applications to wake up from their idle state.