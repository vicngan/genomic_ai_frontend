# Genomic Foundation Model (GFM) Platform — Frontend

Welcome to the GFM Platform frontend, a modern React application for AI-powered genomic research workflows. This repository contains the user interface only and is designed to connect to a separately maintained backend service.

## ✨ Features

- **Dashboard Overview**: View research activity, recent results, and active jobs.
- **New Analysis Runs**: Submit DNA sequences, FASTA files, or genomic regions for predictions.
- **Detailed Results**: Explore scores, confidence assessments, and evidence panels with external links (e.g., UCSC, Ensembl).
- **Research Notebook**: Rich-text notes with result snapshots and version tracking.
- **AI Assistant UI**: Integrated chat interface with queued prompts and training prompt shortcuts.

## 🛠️ Tech Stack

- **Framework**: [React](https://reactjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **UI Components**: Custom components (shadcn/ui-style patterns)
- **Routing**: [React Router](https://reactrouter.com/)
- **Build Tooling**: [Vite](https://vitejs.dev/)

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or newer recommended)
- npm, yarn, or pnpm

### Installation & Setup

1. **Clone the repository:**
   ```sh
   git clone <your-repository-url>
   cd genomic_model_ai
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Configure environment variables:**

   Create a `.env` file in the project root:
   ```env
   VITE_API_BASE_URL=http://localhost:8000
   ```
   Point this to the backend service URL provided by your collaboration partner.

### Running the App

```sh
npm run dev
```
The frontend will be available at `http://localhost:5173`.

## 📁 Project Structure

```
genomic_model_ai/
├── src/                          # Frontend React application
│   ├── components/               # Reusable React components
│   │   └── layout/
│   │       └── AIChatPanel.tsx   # AI chat interface
│   └── ...
├── public/                        # Static assets
├── .env.example                   # Environment variable template
├── index.html
└── README.md
```

## 📚 Documentation

Any backend integration docs and API references live in the backend repository managed by your collaboration partner.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## 📄 License

This project is proprietary. All rights reserved. (Or specify an open-source license like MIT if applicable).
