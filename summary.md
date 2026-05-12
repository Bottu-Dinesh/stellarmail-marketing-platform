# 📋 Executive Summary | StellarMail Platform

## 1. Project Overview
StellarMail is a high-performance, self-hosted email marketing and telemetry platform designed to provide organizations with complete sovereignty over their outbound communication data. Unlike traditional SaaS solutions that obscure technical delivery mechanics, StellarMail provides a transparent, zero-dependency engine for campaign orchestration and engagement tracking.

## 2. Engineering Problem Statement
Modern digital marketing infrastructure often operates as a "black box," making it difficult for developers to troubleshoot delivery failures or verify analytics integrity. The core objective of this project was to engineer a proprietary tracking system capable of monitoring user behavior (Opens and Clicks) in real-time, while managing a robust background delivery schedule via SMTP.

## 3. Core Capabilities
* **The Telemetry Engine:** Utilizes a custom-built tracking system involving 1x1 transparent GIF injection for "Open" rate monitoring and URL redirection wrappers for "Click-Through Rate" (CTR) capture.
* **Asynchronous Orchestration:** A background task engine that continuously polls the database to deploy scheduled campaigns at precise millisecond timestamps.
* **Data Integrity & Management:** Integrated `Pandas` processing for CSV contact ingestion, featuring automated deduplication and suppression list cross-referencing.
* **Clustered UI Design:** A modular Single Page Application (SPA) frontend that consolidates disparate tools into 6 unified operational hubs (Data, Workflow, Analytics, Studio, Specialty, and System).

## 4. Technical Stack
* **Backend:** Python, Flask, SQLAlchemy, smtplib
* **Frontend:** HTML5, CSS3, Vanilla JavaScript, Chart.js
* **Data Processing:** Pandas
* **Database:** SQLite

## 5. Architectural Impact
StellarMail successfully demonstrates the convergence of RESTful API design, complex relational database mapping, and network request interception. It serves as a scalable foundation for enterprise-grade communication tools, proving that sophisticated marketing telemetry can be achieved through custom-engineered local infrastructure.

---
**Lead Developer:** Dinesh Kumar
**Project Category:** Full-Stack Engineering / Software Development
