vaishu_the_AI/
│
├── frontend/                      # Modern AI Assistant UI
│   ├── index.html                 # Main chat interface
│   ├── pages/
│   │   ├── login.html
│   │   ├── chat.html
│   │   └── settings.html
│   ├── css/
│   │   ├── style.css
│   │   ├── chat.css
│   │   └── responsive.css
│   ├── js/
│   │   ├── app.js
│   │   ├── chat.js
│   │   ├── voice-input.js
│   │   └── voice-output.js
│   └── assets/
│       ├── images/
│       └── icons/
│
├── backend/                       # Python + Django
│   ├── manage.py
│   ├── config/                    # Django project configuration
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── asgi.py
│   │   └── wsgi.py
│   │
│   ├── apps/
│   │   ├── accounts/              # User authentication
│   │   ├── assistant/             # AI chat APIs
│   │   ├── conversations/         # Chat history
│   │   ├── documents/             # Document upload
│   │   └── voice/                 # Voice processing APIs
│   │
│   ├── ai_engine/
│   │   ├── llm_service.py         # Llama 3.2 integration
│   │   ├── rag_pipeline.py        # RAG workflow
│   │   ├── embeddings.py           # Text embeddings
│   │   ├── retriever.py            # Relevant document retrieval
│   │   ├── speech_to_text.py       # STT service
│   │   └── text_to_speech.py       # TTS service
│   │
│   ├── requirements.txt
│   └── tests/
│
├── database/
│   ├── README.md                  # Database setup instructions
│   └── schema.md                  # Database design
│
├── media/                         # Uploaded documents (local development)
├── docs/
│   ├── architecture.md
│   ├── api-documentation.md
│   └── screenshots/
│
├── scripts/                       # Setup and utility scripts
├── tests/                         # Integration tests
│
├── .env.example                   # Environment variable template
├── .gitignore
├── README.md
└── LICENSE



