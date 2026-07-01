# Karthik Potti
**Full Stack Developer | AI Engineer | Software Engineer**

* **Phone:** +91 9515759632
* **Email:** [karthikpotti842@gmail.com](mailto:karthikpotti842@gmail.com)
* **Location:** Hyderabad, India
* **GitHub:** [github.com/KarthikP-Mac](https://github.com/KarthikP-Mac)
* **Hugging Face:** [huggingface.co/KarthikP-Mac/spaces](https://huggingface.co/KarthikP-Mac/spaces)
* **Portfolio:** [karthikp-mac-portfolio.vercel.app](https://karthikp-mac-portfolio.vercel.app/)
* **Google Developer Profile:** [g.dev/karthikPMac](https://g.dev/karthikPMac)
* **LinkedIn:** [linkedin.com/in/karthik-potti842](http://www.linkedin.com/in/karthik-potti842)

---

## Professional Summary

Results-driven Full Stack Developer and AI Engineer with 4+ years of professional experience at Tata Consultancy Services (TCS), specializing in enterprise-scale web applications, distributed system design, and Generative AI solutions for the BFSI sector. Expert in architecting microservices and single-page applications using Java, Spring Boot, React, Angular, and Node.js. Proven track record of designing high-performance Retrieval-Augmented Generation (RAG/CRAG) pipelines using LangChain, LangGraph, and FAISS Vector databases, automating business workflows via AutoGen Multi-Agent frameworks, and deploying containerized services on Azure Kubernetes Service (AKS). Accomplished in remediating 100+ security vulnerabilities, reducing CI/CD deployment time by 70%, and decreasing system Mean Time to Resolution (MTTR) by 45% while achieving 100% security audit compliance.

---

## Technical Skills

* **Programming Languages:** Java, Python, JavaScript, TypeScript, C, HTML5, CSS3
* **Frontend:** React, Angular, Angular Material, Vite, Bootstrap, Materialize CSS, jQuery, CSS3, PWA, Font Awesome
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
*May 2022 – Present* | *Hyderabad, India*

#### Project 1: GenAI — Upsell, Cross-Sell & Operational Call Intelligence
*Role: AI Developer & Automation Engineer*

* Architected and deployed end-to-end **Generative AI pipelines** using **Python**, **LangChain**, and **RAG** to extract and analyze **7,000–9,000 daily call recording transcripts** from **Genesys PureCloud** into SQL, surfacing upsell/cross-sell client insights at scale and improving data processing throughput by 40%.
* Automated multi-step report generation and stakeholder distribution using **AutoGen** multi-agent workflows and **Microsoft Logic Apps**, saving 15+ manual hours per week.
* Designed and implemented a **Python-based OCR automation service** (Azure OCR) that parsed and processed user-uploaded PDFs, reducing document processing time by 80% and increasing data extraction accuracy to 99%.
* Engineered a responsive **React** frontend and **Flask** REST API backend, integrating embedded **Power BI** dashboards to deliver real-time operational insights, enhancing decision-making efficiency by 30%.
* Collaborated with cross-functional product teams to integrate AI pipelines into enterprise BFSI core services, boosting client engagement by 15% and ensuring seamless cross-system compatibility.

#### Project 2: Java Full Stack — Latte Rewrite & ACH Integration
*Role: Full Stack Developer*

* Developed high-throughput financial backend services using **Java Spring Boot** and dynamic UIs in **Angular** (**Angular Material** / **TypeScript**) within a **monolithic application** architecture for ACH payment integrations with Bank of America, securely processing $10M+ in quarterly transactions.
* Engineered a custom multi-window modal manager in **Angular** mimicking Windows Explorer desktop OS behavior — dynamically orchestrating z-index depth to bring active popups to foreground and stack inactive ones, improving UX for complex financial workflows.
* Orchestrated vulnerability remediations across 100+ critical financial REST APIs, centralizing security patches into a reusable **Maven JAR** artifact — achieving consistent compliance across 10+ microservices and reducing duplicate remediation effort by ~60%.
* Managed background automation batch jobs in a **Linux** environment, utilizing shell scripting and **WinSCP** for secure file transfers, achieving 99.9% pipeline reliability.

#### Cross-Project Contributions

* Developed and maintained **Angular** (**Angular Material** / **TypeScript**) and **React** component libraries alongside RESTful APIs using **Spring Boot** and **Flask**, reducing UI development cycles by 35% and enabling seamless UI–backend integration across multiple enterprise applications.
* Resolved 100+ application security vulnerabilities as part of Equitable's Vulnerability Remediation Team, achieving full compliance in **Veracode** security scans and internal audits.
* Designed secure REST APIs and UI flows using **JWT-based authentication** and **role-based authorization (RBAC)**, achieving 100% pass rate in all internal security compliance audits.
* Optimized **CI/CD pipelines** in **Azure DevOps**, slashing manual deployment overhead by **70%** and increasing release frequency by 3x.
* Implemented centralized logging and observability using **Azure Kubernetes Service (AKS)** monitoring and loggers, reducing Mean Time to Resolution (MTTR) by 45% across distributed **microservices**.
* Owned end-to-end **system design** across multiple enterprise applications — architecting UI/UX layouts, REST API contracts, database schemas, GitHub Actions workflows, Azure Kubernetes clusters, and AI pipeline service integrations from requirements to production deployment.

---

## Projects & Portfolio

### GenAI & RAG Applications

#### BFSI-Insurance-Ai-Agent (Banking AI Copilot) — *[Live Demo](https://karthikp-mac-banking-ai-copilot.hf.space/)*
*Tech: Python, LangChain, CRAG, FAISS Vector DB, Streamlit, Multi-LLM Orchestration (Groq, Llama-4 Scout 17B), Hugging Face*

* Developed a domain-specific financial AI assistant that answers complex BFSI queries using a robust **Corrective RAG (CRAG)** pipeline, **FAISS vector database**, and a **Multi-Model LLM Orchestration** architecture — configured with **Llama-4 Scout 17B** (meta-llama/llama-4-scout-17b-16e-instruct) as the active primary reasoning engine, with dynamic hot-swapping fallback routing across Llama-3.3-70b, Llama-3.1-8b, and Qwen-3 to manage token limits and optimize cost per query.
* Designed modular **LangChain** retrieval chains with pluggable model-routing middleware and provider-agnostic interfaces, ensuring zero-downtime hot-swapping of LLM backends without pipeline refactoring.

#### Jarvis AI Assistant (Real-Time Voice Assistant) — *[Live Demo](https://karthikp-mac-jarvis-ai-assistant.hf.space/)*
*Tech: Vite + React, FastAPI, Python, WebSockets, Groq (Whisper + Llama-4 Scout), ONNX Runtime (Kokoro-ONNX), ElevenLabs, Docker, Hugging Face Spaces*

* Engineered a real-time, **Multimodal Voice-to-Voice AI Assistant** featuring a cyberpunk React UI and a **FastAPI ASGI** server handling duplex **WebSocket** streaming of raw audio packets.
* Implemented a dual-engine speech synthesis pipeline (cloud-based **ElevenLabs** for premium voice streaming and local **Kokoro-ONNX** / ONNX Runtime for zero-latency offline English voice generation).
* Integrated a **Multi-Model LLM Routing Layer** powered by **Groq API**, utilizing **Llama-4 Scout 17B** as the active primary model (best quality/throughput ratio at 500K TPD) with alternative fallbacks to Llama-3.3-70b-versatile (complex reasoning) and Llama-3.1-8b-instant (low-latency responses), protected by a double-layered regex safety guardrail.

---

### Real-Time Web Applications

#### Web-RTC (Live Random Video Calls) — *[Live Demo](https://web-rtc-lq00.onrender.com/)*
*Tech: React, WebRTC APIs, Spring Boot, Java Virtual Threads (Project Loom), WebSocket (Signaling), Render*

* Developed a peer-to-peer video conferencing application supporting live video/audio streams, screen sharing, and adaptive signaling. Backend built with **Java Virtual Threads** (Project Loom) for high-concurrency, low-latency signaling coordination, deployed as a **monolithic Docker** container on Render.

#### Web-Sockets (Live Chat Application) — *[Live Demo](https://web-sockets-ju5x.onrender.com/)*
*Tech: Angular, Spring Boot, WebSocket (STOMP), Docker, Render*

* Built a real-time instant messaging service with persistent connection tracking and **STOMP**-based WebSocket messaging, deployed as a **monolithic Docker** container on Render — ensuring reliable end-to-end delivery of chat messages at scale.

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

* Designed a standalone desktop ERP and ledger system using **Python (Tkinter)** and **SQLite3**, featuring local data caching, asynchronous background auto-saves, and Matplotlib-based analytics dashboards.
* Implemented an automated stock advisory module providing real-time stock alert thresholds (yellow/red warnings) and predictive profit forecasting.
* Integrated secure PDF document compilation for automated generation of invoices, purchase orders, and monthly ledger sheets.

#### PDF Batch Processor
*Tech: Python, Tkinter, PyPDF, Pillow, OS APIs, File Automation*

* Engineered a desktop utility using **Python (Tkinter)** to batch convert entire folders of images into high-quality, compressed PDFs with a live progress renderer.
* Supports custom page and image ordering with a **live sequence preview** (allowing interactive drag-and-drop or button-based reordering) before exporting the final PDF.
* Implemented selective page extraction (e.g., picking 2 of 10 pages) and image-only extraction from existing PDF documents.

#### System Power Scheduler
*Tech: Python, Tkinter, Windows OS APIs, JSON, Task Scheduling*

* Developed a desktop power automation tool in **Python (Tkinter)** that schedules system events (shutdown, sleep, lock) via countdown timers and persistent daily schedules saved in JSON.
* Implemented a system-overlay countdown notification in the final 5 minutes of a scheduled event, with password-protected controls to cancel timers, edit tasks, or exit.

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
