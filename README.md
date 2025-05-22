# Past2Prep 🎓📄

**Past2Prep** is an open-source platform that leverages AI to analyze previously written documents and generate custom question-and-answer sets or insights that mimic the style, structure, and intent of the original content. It uses document parsing, NLP, and large language models (LLMs) to extract meaning, detect patterns, and generate intelligent outputs.

---

## 🔍 Use Cases

While the initial focus of Past2Prep is **exam preparation**, the core technology can be applied to many other domains where understanding and mimicking prior content is valuable:

### 🎓 Education (Initial Target)
- Analyze past exam questions set by lecturers.
- Generate customized practice questions in similar formats.
- Help students revise with content that reflects actual exam patterns.

### 🧑‍🏫 Corporate Training
- Analyze previous internal training materials and assessments.
- Auto-generate employee quizzes aligned with company-specific terminology and knowledge.

### 📜 Legal & Compliance
- Review and extract entities and relationships from contracts or legal memos.
- Create Q&A pairs or summaries based on past case studies or agreements.

### 📝 Policy & Research
- Process prior research or policy documents to suggest new questions or topics for exploration.
- Build knowledge graphs of related policy subjects or historical narratives.

---

## 🧠 Core Features

- Upload documents (PDFs, scanned files).
- Extract structured questions and patterns using NLP.
- Generate new Q&A based on past content using LLMs.
- Visualize semantic relationships (basic knowledge graphs).
- Conduct similarity comparison between documents.

---

## ⚙️ Tech Stack

- PDF Parsing & OCR: `pdfplumber`, `PyMuPDF`, `Tesseract`
- NLP & LLMs: `spaCy`, `LangChain`, `Hugging Face Transformers`
- Knowledge Graphs: `NetworkX`, `Neo4j`
- Web Interface: `Flask` (or FastAPI)
- Containerization: `Docker`, `docker-compose`

---

## 🚀 Getting Started

A full Docker-based setup will be included soon for local or cloud deployment.

---

## 🤝 Contributing

We're building an open-source ecosystem around document understanding, question generation, and semantic analysis. See [CONTRIBUTING.md](CONTRIBUTING.md) to get started.

---

## 📜 License

MIT License — free to use and modify. Build with us!
