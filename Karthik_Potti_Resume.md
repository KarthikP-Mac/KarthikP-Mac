# Karthik Potti
**Full Stack Developer | AI Engineer | Software Engineer**

* **Phone:** +91 9515759632
* **Email:** [karthikpotti842@gmail.com](mailto:karthikpotti842@gmail.com)
* **Location:** Hyderabad, India
* **GitHub:** [github.com/KarthikP-Mac](https://github.com/KarthikP-Mac)
* **Portfolio:** [karthikp-mac-portfolio.vercel.app](https://karthikp-mac-portfolio.vercel.app/)
* **Google Developer Profile:** [g.dev/karthikPMac](https://g.dev/karthikPMac)
* **LinkedIn:** [linkedin.com/in/karthik-potti842](http://www.linkedin.com/in/karthik-potti842)

---

## Professional Summary

Results-driven Full Stack Developer and AI Engineer with 4+ years of experience at Tata Consultancy Services (TCS), delivering enterprise-grade web applications and Generative AI solutions in the BFSI sector. Demonstrated expertise building full stack systems with React, Angular, and Java Spring Boot, designing RAG/CRAG pipelines with LangChain and FAISS, and automating complex business workflows using AutoGen AI and Azure services. Proven track record in resolving 100+ security vulnerabilities, streamlining CI/CD pipelines to reduce deployment effort by 70%, and integrating multi-LLM systems (Groq, Gemini, OpenAI, Claude) into production. Skilled in REST API design, JWT/RBAC security, Docker containerization, and Linux automation.

---

## Technical Skills

* **Programming Languages:** Java, Python, JavaScript, TypeScript, C, HTML5, CSS3
* **Frontend:** React, Angular, Vite, Bootstrap, Materialize CSS, jQuery, CSS3, PWA
* **Backend:** Java Spring Boot, Node.js, Express.js, Flask, FastAPI, REST APIs, WebSocket, Microservices
* **Desktop & UI:** Tkinter (Python GUI)
* **AI / ML / GenAI:** LangChain, LangGraph, AutoGen AI, AI Agents, RAG, CRAG, Prompt Engineering, FAISS Vector DB, Azure RAG Index, Groq API, OpenAI API, Gemini API, Claude API, ElevenLabs, ONNX Runtime (Kokoro), Streamlit, Azure OCR, Microsoft Logic Apps
* **Databases:** Oracle SQL, MySQL, MongoDB, Firebase Firestore
* **Cloud & DevOps:** Azure DevOps (CI/CD), Docker, Azure Kubernetes, GitHub Actions, Vercel, Render, Hugging Face Spaces
* **Security & Tools:** JWT Authentication, RBAC (Role-Based Authorization), OAuth2 (Google Sign-In / Firebase Auth), Veracode, Maven, Postman, WinSCP, Linux, Git, GitHub, Power BI

---

## Professional Experience

### Tata Consultancy Services (TCS)
**IT Systems Engineer** | *Client: Equitable Financial Life Insurance (BFSI)*
*Apr 2022 – Present* | *Hyderabad, India*

#### Project 1: GenAI — Upsell, Cross-Sell & Operational Call Intelligence
*Role: AI Developer & Automation Engineer*

* Architected and deployed end-to-end **Generative AI pipelines** using **Python**, **LangChain**, and **RAG** to analyze insurance call recordings, extracting upsell/cross-sell client insights at scale.
* Automated multi-step report compilation and scheduled stakeholder email distribution using **AutoGen AI** and **Microsoft Logic Apps**, eliminating 100% manual effort for recurring reporting cycles.
* Designed and implemented a **Python-based OCR automation service** (Azure OCR) that parsed and processed user-uploaded PDFs for automated transaction data extraction, reducing processing time significantly.
* Built the GenAI full stack application using **Flask** (REST API backend) and **React** (frontend), and integrated **Power BI** dashboards to visualize statistical workflow details and operational KPIs for business stakeholders.
* Collaborated with cross-functional teams of engineers, analysts, and product owners to integrate AI models into existing enterprise BFSI systems, improving client engagement metrics.

#### Project 2: Java Full Stack — Latte Rewrite & ACH Integration
*Role: Full Stack Developer*

* Developed highly responsive, enterprise-grade frontend layouts in **Angular** and implemented backend services using **Java Spring Boot** for ACH payment integrations with Bank of America, processing financial transactions reliably.
* Engineered a custom multi-window modal manager in **Angular** mimicking Windows Explorer desktop OS behavior — dynamically orchestrating z-index depth to bring active popups to foreground and stack inactive ones, improving UX for complex financial workflows.
* Orchestrated vulnerability remediations across 100+ critical financial REST APIs, centralizing security patches into a reusable **Maven JAR** artifact — achieving consistent compliance across 10+ microservices and reducing duplicate remediation effort by ~60%.
* Managed and monitored background automation batch processes in a **Linux** environment, utilizing **WinSCP** for secure file transmittal and log analysis, ensuring 99%+ batch job reliability.

#### Cross-Project Contributions

* Developed and maintained **Angular** and **React** component libraries alongside RESTful APIs using **Spring Boot** and **Flask**, enabling seamless UI–backend integration across multiple enterprise applications.
* Resolved 100+ application security vulnerabilities as part of Equitable's Vulnerability Remediation Team, achieving full compliance in **Veracode** security scans and internal audits.
* Designed secure REST APIs and UI flows using **JWT-based authentication** and **role-based authorization (RBAC)**, achieving 100% pass rate in all internal security compliance audits.
* Streamlined **CI/CD pipelines** using **Azure DevOps** and **GitHub**, reducing manual deployment effort by **70%** and enabling faster, more reliable release cycles.
* Implemented centralized logging and exception handling with **Azure Kubernetes** loggers, improving error traceability and reducing MTTR for production incidents across **microservices** architecture.

---

## Projects & Portfolio

### GenAI & RAG Applications

#### BFSI-Insurance-Ai-Agent (Banking AI Copilot) — *[Live Demo](https://karthikp-mac-banking-ai-copilot.hf.space/)*
*Tech: Python, LangChain, CRAG, FAISS Vector DB, Streamlit, Hugging Face Embeddings, Groq / Gemini / OpenAI / Claude*

* Developed a domain-specific financial AI assistant that answers complex BFSI queries using a robust **Corrective RAG (CRAG)** pipeline with custom recursive text splitters, **FAISS vector database**, and multi-LLM support (Groq, Gemini, OpenAI, Claude).
* Designed modular LangChain retrieval chains supporting dynamic LLM switching and configurable context windows, improving answer accuracy for domain-specific financial queries.

#### Jarvis AI Assistant (Real-Time Voice Assistant) — *[Live Demo](https://karthikp-mac-jarvis-ai-assistant.hf.space/)*
*Tech: Vite + React, FastAPI, Python, WebSockets, Groq (Whisper + Llama), ONNX Runtime (Kokoro-ONNX), ElevenLabs, Docker, Hugging Face Spaces*

* Engineered a real-time, voice-activated AI assistant with a cyberpunk React UI and a **FastAPI ASGI** server handling bidirectional **WebSocket** streaming of raw audio packets.
* Implemented dual-engine TTS pipeline: cloud-based **ElevenLabs** for premium voice and local **Kokoro-ONNX** for offline English synthesis — with Web Speech API as fallback for multi-lingual support (Hindi, Telugu).
* Integrated **Groq API** (Whisper-large-v3-turbo for STT, Llama-3.3-70b for reasoning), a double-layered regex safety guardrail filter, and deployed as a monolithic **Docker** container on Hugging Face Spaces.

---

### Real-Time Web Applications

#### Web-RTC (Live Random Video Calls) — *[Live Demo](https://web-rtc-lq00.onrender.com/)*
*Tech: React, WebRTC APIs, Spring Boot, Java Virtual Threads (Project Loom), WebSocket (Signaling), Render*

* Developed a peer-to-peer video conferencing application supporting live video/audio streams, screen sharing, and adaptive signaling. Backend built with **Java Virtual Threads** (Project Loom) for high-concurrency, low-latency signaling coordination.

#### Web-Sockets (Live Chat Application) — *[Live Demo](https://web-sockets-ju5x.onrender.com/)*
*Tech: Angular, Spring Boot, WebSocket (STOMP), Docker, Render*

* Built a real-time instant messaging service with persistent connection tracking, ensuring reliable end-to-end delivery of chat messages at scale.

#### Sticky-Notes (Progressive Web App) — *[Live Demo](https://stickynotes-pk-mac.vercel.app/)*
*Tech: React 19, Vite, PWA, Firebase Firestore, Firebase Auth (Google OAuth2), LocalStorage, CSS3, Vercel*

* Engineered a **Progressive Web App (PWA)** digital corkboard and kanban board with Google **OAuth2 sign-in** via Firebase Auth, custom drag-and-drop mechanics, coordinate persistence, tag categorization, and a multi-tab Firebase Firestore offline sync manager.

---

### Institutional & Full Stack Web Portals

#### Adarsh Computers Portal (Full Stack) — *[Live Website](https://adarsh-computers.vercel.app/)*
*Tech: React, Node.js, Express.js, Bootstrap, SMTP, Vercel, Render*

* Contributed to full stack development of an educational institution portal — built responsive React frontend and robust Express/Node.js backend to manage courses, student registrations, announcements, and online quizzes.

#### Institution Landing Page Portal
*Tech: HTML5, CSS3, JavaScript, jQuery, Bootstrap*

* Built a responsive frontend portal with dynamic landing pages, mobile-first layouts, and interactive UI components for a computer education institution.

---

### Python Desktop Applications

#### Smart Stocker — Inventory & Ledger App
*Tech: Python, Tkinter, SQLite3, Excel (openpyxl), SMTP, Matplotlib, AI Bot, JSON*

* Full-featured desktop inventory & ledger system with an **AI stock advisor bot** (low-stock / profit-loss alerts), interactive **bar/pie chart dashboard**, and automated email reports via SMTP.
* Generates customer bill, purchase order, and monthly profit report PDFs; includes undo/redo, forecast sale, reset/clear, and **password-protected access**.
* Auto-saves every 300s to JSON + SQLite3 backup; supports Excel import/export with automatic state restoration on relaunch. Color-coded stock alerts: yellow (≤50% items), red (≤25% items).

#### PDF Batch Processor
*Tech: Python, Tkinter, PyPDF, Pillow, OS APIs, File Automation*

* Batch converts entire image folders to high-quality, compressed PDFs with a live progress renderer (handles unlimited files in a single run).
* Select images, **custom-reorder pages interactively with live preview**, and generate the PDF in that exact sequence by buttons up/down for images selected or drag to reorder images; also supports selective page extraction (e.g. pick 2 of 10 pages) and image-only extraction from existing PDF files.

#### System Power Scheduler
*Tech: Python, Tkinter, Windows OS APIs, JSON, Task Scheduling*

* Automates shutdown, sleep, and lock via countdown timers or persistent **daily schedules** (saved in JSON, auto-triggered at a set HH:MM each day).
* Displays a system-overlay countdown notification in the final 5 minutes to alert the user; **password-protected** to cancel timers, delete tasks, or exit the application.

---

## Education

* **B.Tech. in Computer Science & Engineering** — NRI Institute of Technology (2021) | CGPA: **7.68 / 10**
* **Diploma in Science & Technology** — Amrita Sai Institution (2018) | **75.2%**
* **Secondary School (SSC)** — Ravindra Bharati Public School (2015) | **82.0%**

---

## Languages

* **English:** Professional Working Proficiency
* **Telugu:** Native / Bilingual Proficiency
* **Hindi:** Full Professional Proficiency
