# 🚀 JobLens AI

### AI-Powered Resume & Job Description Analyzer

JobLens AI helps job seekers understand how well their resume matches a job description using advanced AI, NLP, OCR, and data visualization techniques. Upload resumes, analyze job requirements, identify skill gaps, and receive actionable recommendations to improve your chances of landing interviews.

---

## ✨ Features

### 🤖 AI-Powered Resume Analysis

* Analyze resumes against job descriptions
* Generate match scores and compatibility insights
* AI-generated recommendations for resume improvement
* Identify missing skills and keywords

### 📄 Resume Parsing

* Extract text from PDF resumes
* OCR support for scanned resumes and image-based documents
* Structured data extraction from uploaded files

### 🎯 Skill Gap Detection

* Compare candidate skills against job requirements
* Highlight missing competencies
* Prioritize high-impact skills for improvement

### 📊 Interactive Analytics Dashboard

* Resume-job match visualization
* Skill distribution charts
* Keyword coverage analysis
* Performance metrics and scoring breakdowns

### 🧠 Natural Language Processing

* Advanced text processing using NLP libraries
* Keyword extraction and matching
* Semantic analysis of resumes and job descriptions

### ☁️ Cloud Backend

* User authentication and profile management
* Secure cloud database using Supabase
* Persistent analysis history

### 📑 Report Generation

* Download analysis reports as PDF
* Export insights for future reference
* Professional report formatting

---

## 🛠 Tech Stack

### Frontend

* React 18
* TypeScript
* Vite
* Tailwind CSS
* Framer Motion

### AI & NLP

* Google Gemini AI
* OpenAI API
* Natural Language Toolkit (Natural)
* Wink NLP

### Data Visualization

* Chart.js
* D3.js
* Plotly

### Document Processing

* PDF Parse
* Tesseract OCR
* jsPDF

### Backend & Database

* Supabase
* PostgreSQL
* Redis

### Development Tools

* ESLint
* TypeScript
* GitHub

---

## 🏗 Architecture

```text
User Uploads Resume
          │
          ▼
   PDF/OCR Processing
          │
          ▼
    Text Extraction
          │
          ▼
      NLP Engine
          │
          ▼
 Job Description Analysis
          │
          ▼
    AI Evaluation Layer
          │
          ▼
 Match Score & Insights
          │
          ▼
 Interactive Dashboard
```

---

## ⚡ Quick Start

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/JobLens-AI.git
cd JobLens-AI
```

### Install Dependencies

```bash
npm install
```

### Environment Variables

Create a `.env` file:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

VITE_GEMINI_API_KEY=your_gemini_api_key

VITE_OPENAI_API_KEY=your_openai_api_key
```

### Run Development Server

```bash
npm run dev
```

Application runs at:

```text
http://localhost:5173
```

---

## 📊 Core Analysis Features

| Feature          | Description                             |
| ---------------- | --------------------------------------- |
| Resume Parsing   | Extract content from uploaded resumes   |
| OCR Processing   | Read scanned resumes and images         |
| Skill Matching   | Compare resume against job requirements |
| AI Insights      | Personalized improvement suggestions    |
| Keyword Analysis | ATS keyword optimization                |
| Visual Analytics | Interactive charts and dashboards       |
| PDF Reports      | Export detailed analysis reports        |

---

## 📁 Project Structure

```text
src/
├── components/
├── pages/
├── services/
├── hooks/
├── utils/
├── assets/
└── styles/

supabase/
└── migrations/
```

---

## 🎯 Use Cases

### For Students

* Prepare for internships
* Improve ATS compatibility
* Identify missing technical skills

### For Job Seekers

* Optimize resumes for specific roles
* Increase interview chances
* Receive AI-powered feedback

### For Career Coaches

* Analyze candidate readiness
* Generate professional reports
* Track improvement over time

---

## 🔒 Security

* Secure authentication with Supabase
* Protected user data
* Encrypted API communication
* Role-based access control

---

## 🚀 Future Roadmap

* Multi-resume comparison
* Cover letter generation
* LinkedIn profile analysis
* Interview preparation assistant
* AI career path recommendations
* Real-time job market insights
* Resume version tracking

---

## 📈 Why JobLens AI?

Most resume checkers simply count keywords.

**JobLens AI goes further by combining AI, NLP, OCR, and data visualization to provide intelligent, actionable career insights rather than basic keyword matching.**

---

## 👩‍💻 Author

**Deepti Jain**

Computer Science Engineering Student • AI Enthusiast • Full Stack Developer

