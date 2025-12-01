# 🎓 EduBank.AI

**EduBank.AI** is an **AI-powered educational platform** that transforms the way students and educators interact with lecture materials. Upload PDFs, videos, images, and more, and let AI help generate **questions, practice problems, summaries, and explanations**, all grounded in your own course content.  

---

## 🚀 Features

- 📂 **Multi-format Uploads**: Supports PDFs, images, video lectures, and scanned notes  
- 📝 **AI-Powered Question Generation**: Automatically generates quizzes and practice problems  
- 🔄 **Example Variations**: Creates alternative versions of problems for deeper understanding  
- 📚 **Content Summarization**: Summarizes lectures and notes for quick revision  
- 💡 **Concept Clarification**: Provides step-by-step explanations for complex topics  
- 🔒 **Content-Grounded AI**: Ensures outputs are accurate and based solely on uploaded materials  

---

## 🛠️ Tech Stack

- **Backend**: Go (REST API for uploads, processing, and AI integration)  
- **Frontend**: React.js (interactive and responsive UI)  
- **Database**: PostgreSQL (for storing uploads and metadata)  
- **AI Integration**: Cloud or local models for question generation and content analysis  

---

## ⚡ Getting Started

### Prerequisites

- Go >= 1.20  
- Node.js >= 18  
- PostgreSQL (or any supported relational database)  
- AI API credentials (if using cloud models)  

### Installation

1. Clone the repository:

```bash
git clone https://github.com/EduBank-AI/edubank-backend.git
git clone https://github.com/EduBank-AI/edubank-frontend.git
```

2. Start the backend server:

```bash
cd edubank-backend
go mod tidy
go run main.go
```

3. Start frontend server

```bash
cd edubank-frontend
npm install
npm start
```

4. Open your browser at: http://localhost:3000

## 🎯 Usage
1. Upload lecture materials in supported formats
2.  Select the AI features you want:
  - Question generation
  - Summaries
  - Step-by-step explanations
  - Example variations
3. Interact with AI-generated content or download it for offline study

## 🤝 Contributing
We welcome contributions!
1. Fork the repository
2. Create a branch: ```git checkout -b feature/YourFeature```
3. Commit your changes: ```git commit -m 'Add new feature'```
4. Push to the branch: ```git push origin feature/YourFeature```
5. Open a Pull Request

## 📄 License
This project is licensed under the **MIT License**. See the LICENSE file for details.
