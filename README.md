# 🧠 AI Career Simulation & Recommendation System

## 🚀 Overview
This project presents an **AI-powered platform** that helps students and job seekers identify the best-suited career paths by simulating real-world tasks, conducting interview evaluations, and offering **personalized feedback** based on AI-generated insights.

## 🌟 Key Features
1. **Resume–Job Matching** 🔍  
   - Automatically detects the best-fit career roles by analyzing uploaded resumes using **Sentence-BERT**.

2. **Interview Simulation** 🎙  
   - Generates **20 domain-specific interview questions** using **LLaMA 3.2** via Ollama for selected roles.

3. **Answer Evaluation** 📑  
   - Evaluates user answers by comparing them with AI-generated ideal answers using **TF-IDF + Cosine Similarity**.

4. **Performance Scoring** 🎯  
   - Calculates a **Career Fit Score**, supported by **visual feedback**, and highlights strengths and areas to improve.

5. **Personalized Feedback** 💡  
   - Recommends **online courses and learning paths** tailored to the user's performance and career goal.

6. **AI Mentorship** 🧑‍🏫  
   - A built-in chatbot for **career Q&A, clarification, and real-time guidance**.

## 🔬 Methodology

1️⃣ **Resume Analysis & Role Matching**  
- Uses Sentence-BERT embeddings to find the best matching job description from the dataset.

2️⃣ **Interview Question Generation**  
- Role-specific questions generated using LLaMA 3.2.

3️⃣ **Answer Evaluation**  
- Answers are uploaded (PDF/DOCX), converted to vectors, and evaluated with TF-IDF and cosine similarity.

4️⃣ **Feedback Report Generation**  
- Generates a professional **PDF report** with career fit scores and improvement suggestions using FPDF.

5️⃣ **Visual Insight & Analysis**  
- Resume-category vs Role heatmap, score gauge chart, and distribution graphs created with Matplotlib and Seaborn.

## 📊 Results
- **Accuracy**: TF-IDF + Cosine Similarity provided a reliable match for text-based answer evaluations.
- **Best Experience**: LLaMA-based simulations enhanced user engagement with contextual, role-specific questions.
- **Outcome**: Users received clear next steps with targeted feedback and course suggestions.

## 🔧 Technologies Used
- **Python**
- **Libraries**: Transformers, Scikit-learn, PyPDF2, docx2txt, Matplotlib, Seaborn, FPDF, Tesseract, Sentence-BERT
- **Models**: Sentence-BERT (`all-MiniLM-L6-v2`), LLaMA 3.2 (via Ollama)
- **Similarity**: TF-IDF, Cosine Similarity

## ⚙️ Installation

1️⃣ Clone the repository:
```bash
git clone https://github.com/deepthee-03/ai-career-simulator.git
cd ai-career-simulator
