# Autonomous Data Analyst AI — JavaScript Edition

A full-stack final-year AI/ML project implemented with JavaScript on both frontend and backend.

## Stack
- React + Vite
- Node.js + Express
- Multer for uploads
- CSV Parse + SheetJS for CSV/XLSX
- Recharts for visual analytics
- Lucide React for UI icons

## Features
- CSV/XLS/XLSX upload
- Automatic schema profiling
- Missing/duplicate detection
- Data-quality score
- Descriptive statistics
- Automatic visualizations
- Numeric anomaly screening
- Natural-language analyst interface
- Autonomous investigation trace
- Evidence-backed deterministic answers
- Executive HTML report generation

## Run
### Backend
```bash
cd backend
npm install
npm run dev
```
Runs at http://localhost:8000

### Frontend
Open another terminal:
```bash
cd frontend
npm install
npm run dev
```
Open the Vite URL shown in the terminal.

## Optional AI/LLM upgrade
The current build is fully functional without an API key and uses deterministic analysis for numerical correctness. For the next version, an LLM provider can be connected as a planner/explainer while Python/JS data tools remain the source of truth for calculations.
