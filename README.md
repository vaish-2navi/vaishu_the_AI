## 📂 Project Structure


vaishu_the_AI/
│
├── frontend/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── app.js
│   │   ├── voice.js
│   │   └── chat.js
│   └── assets/
│
├── backend/
│   ├── manage.py
│   ├── config/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── asgi.py
│   │   └── wsgi.py
│   │
│   ├── assistant/
│   │   ├── views.py
│   │   ├── urls.py
│   │   ├── models.py
│   │   ├── serializers.py
│   │   └── services/
│   │       ├── llm.py
│   │       ├── rag.py
│   │       └── voice.py
│   │
│   └── requirements.txt
│
├── knowledge_base/
│   └── documents/
│
├── tests/
│   └── __init__.py
│
├── docs/
│   └── architecture.md
│
├── .env.example
├── .gitignore
└── README.md


### 📌 Folder Description

- **frontend/** — Modern mobile-first UI using HTML, CSS and JavaScript.
- **backend/config/** — Django project configuration and URL routing.
- **backend/assistant/** — AI assistant API, database models and serializers.
- **backend/assistant/services/llm.py** — LLM integration for Llama 3.2, GPT and Claude.
- **backend/assistant/services/rag.py** — Document retrieval and RAG pipeline.
- **backend/assistant/services/voice.py** — Voice processing integration.
- **knowledge_base/documents/** — Documents used for RAG-based question answering.
- **tests/** — Automated tests for the application.
- **docs/** — System architecture and technical documentation.
- **.env.example** — Example environment variable names without real secrets.
- **.gitignore** — Files and folders excluded from Git.
- **README.md** — Project overview, architecture, setup instructions and roadmap.

### 🛠️ Development Workflow

The project will be developed using the terminal, Python virtual environment, Django, PostgreSQL, Git and GitHub. The frontend and backend will communicate through API endpoints.

**Database:** PostgreSQL with Django ORM. Vector search can be added through `pgvector` for RAG.

**Mobile application:** The frontend will be designed as a responsive Progressive Web App (PWA), allowing users to install it on compatible mobile devices.

**AI capabilities:** Text chat, Voice-to-Text, Text-to-Voice and document-based question answering.



