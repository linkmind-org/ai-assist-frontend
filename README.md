# 🧠 Personal AI Assistant – Frontend

This is the **frontend** application for a personal AI assistant designed to help individuals manage notes, tasks, documents, and more—much like GCP's NotebookLM, but tailored for personal use.

Whether you're tracking work tasks, family plans, life goals, or spontaneous ideas, this assistant gives you a unified interface to interact with your thoughts and create actionable outcomes from them.

## 🚀 Project Vision

This project aims to become a highly personalized, intelligent interface that helps you:

- Take structured or free-form notes
- Ask questions based on your notes
- Generate documents, lists, and schedules
- Build an evolving knowledge base of your life
- Eventually function like a personal assistant with deep context

While the overall project will include multiple components (API, on-prem LLM hosting, internet search integration), this repository is **only for the frontend application**.

## 🖥️ Tech Stack

- **React** – UI framework
- **Vite** – Build tool (or Webpack, if you prefer)
- **TypeScript** – Optional, but recommended for maintainability
- **TailwindCSS** – (optional) for styling
- **React Query or SWR** – For API data management
- **Custom Backend API** – Connected through a separate repository

## 📁 Project Structure

```
frontend/
├── public/
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/           # Main screens (notes, chat, documents, etc.)
│   ├── hooks/           # Custom React hooks
│   ├── services/        # API interaction logic
│   └── App.tsx
├── package.json
└── vite.config.ts
```

## 🧑‍💻 Getting Started

1. **Clone the repo:**

```bash
git clone https://github.com/your-username/personal-ai-assistant-frontend.git
cd personal-ai-assistant-frontend
```

2. **Install dependencies:**

```bash
npm install
# or
yarn install
```

3. **Run the development server:**

```bash
npm run dev
# or
yarn dev
```

4. **Configure API base URL:**

Set your API endpoint (hosted separately) in a `.env` file:

```
VITE_API_BASE_URL=http://localhost:5000/api
```

## 🔌 Integrations

The frontend connects to a backend API that handles:

- Note storage and retrieval
- LLM interactions
- Context-aware responses

Eventually, the full system will include:

- On-premise hosting of language models
- Private internet search and summarization layer
- Document ingestion from multiple sources

> 🔒 **Privacy-first by design.** This is intended to run on your own hardware or trusted environments.

## 🛠️ Development Status

This is an early-stage project, primarily for personal use. Contributions, feedback, and ideas are welcome if you find value in it.

- [x] Notes UI
- [x] Ask questions based on notes
- [ ] Document builder
- [ ] Schedule generator
- [ ] Voice interface
- [ ] Mobile optimization

## 📅 Roadmap

- **v1**: Local note-taking and AI Q&A
- **v2**: Contextual document generation
- **v3**: Scheduling and time management features
- **v4**: Pluggable modules for data ingestion and knowledge graphs

## 📜 License

This project is licensed under the [MIT License](LICENSE). Use it freely, privately or publicly.

## 🤝 Acknowledgments

Inspired by tools like:
- [NotebookLM (Google)](https://notebooklm.google/)
- Obsidian, Notion, Logseq
- OpenAI ChatGPT / Assistants API

---

> 🧪 Built as a personal experiment to explore the boundaries of productivity, autonomy, and contextual computing. If it helps others too—great.
