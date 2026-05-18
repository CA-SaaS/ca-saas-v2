🏦 CA SaaS V2
AI-Powered SaaS Platform for India's Chartered Accountants
     "Built for India's 400,000+ practicing Chartered Accountants"

🎯 Vision
CA SaaS V2 is India's most intelligent AI-powered accounting management platform — think Tally, but rebuilt from scratch with modern AI at its core. We're solving the real pain points that 400,000+ Indian CAs face every single day.

✨ Features 
   **  Feature**	     **  Description	Status**
   
🔐 Authentication              	CA Register & Login with JWT tokens	✅ V1 Done
👥 Client Management	          Add, view, update, delete clients with PAN details	✅ V1 Done
📄 Document Upload	            Upload ITR & notice PDFs with AI text extraction	✅ V1 Done
🤖 AI Assistant	                Summarize documents, draft ITD notice replies	✅ V1 Done
🔍 Anomaly Detection	          Scan all clients and flag suspicious patterns	✅ V1 Done
📋 Notice Tracker	              Track ITD notices with deadlines and status	✅ V1 Done
⚡ React Frontend	               Modern web interface for all features	✅ V1 Done
🧠 RAG System	                   Indian tax law knowledge base for accurate AI	🚧 V2
🎨 Dark UI                      Redesign	Professional dark theme with modern UX	🚧 V2
📱 Mobile App	                   iOS & Android app for CAs on the go	📅 Planned


🚀 Quick Start
Prerequisites

Python 3.12+
Node.js 18+
PostgreSQL 15+
Groq API 

📡 API Endpoints
🔐 Authentication
POST /auth/register    — Register a new CA
POST /auth/login       — Login and get JWT token


👥 Client Management
POST   /clients/         — Add new client
GET    /clients/         — List all clients
GET    /clients/{id}     — Get specific client
PUT    /clients/{id}     — Update client
DELETE /clients/{id}     — Delete client


📄 Documents
POST /documents/upload/{client_id}   — Upload PDF
GET  /documents/{client_id}          — List documents
GET  /documents/detail/{id}          — Get document details


🤖 AI Features
POST /ai/summarize/{document_id}     — Summarize document
POST /ai/draft-reply/{document_id}   — Draft ITD notice reply
POST /ai/ask/{document_id}           — Ask question about document

🔍 Anomaly Detection
GET /anomaly/scan    — Scan all clients for anomalies

📋 Notice Tracker
POST   /notices/           — Add notice
GET    /notices/           — List all notices
GET    /notices/overdue    — Get overdue notices
GET    /notices/due-soon   — Get notices due soon
PUT    /notices/{id}       — Update notice status
DELETE /notices/{id}       — Delete notice

V2 🚧 IN PROGRESS
├── 🔄 RAG System — Indian tax law knowledge base
├── 🔄 Dark UI redesign — professional theme
├── 🔄 Fix AI notice reply accuracy
├── 🔄 Production deployment
├── 📅 GST filing integration
├── 📅 WhatsApp notifications for deadlines
└── 📅 Mobile app (React Native)

👥 Team
We're a team of engineering students building in public 🚀

Allen Christian  github:- https://github.com/allen745 , Linkedin :- https://www.linkedin.com/in/allen-christian-708545409/
Vishvraj solanki github:- https://github.com/vishvrajsolanki-dev , Linkedin :- https://www.linkedin.com/in/vishvrajsinh-solanki-1396ab37a/

🎓 B.Tech AI & Data Science — A.D. Patel Institute of Technology, CVM University

📄 License
Distributed under the MIT License

Built with ❤️ in India 🇮🇳
⭐ Star this repo if you find it useful!
Follow our Building in Public journey on LinkedIn
