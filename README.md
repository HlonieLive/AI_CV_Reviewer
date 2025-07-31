# 🚀 Overview

**AI_CV_Reviewer** is an intelligent CV analysis and optimization system that evaluates resumes against a specific job description using advanced AI and computer vision (CV) techniques. It provides a detailed score, actionable feedback, and automatically tailors your CV to increase your chances of getting shortlisted.

Whether you're applying for a software engineering role, marketing position, or data science job, this tool helps you align your CV with the job requirements, highlights missing skills, and generates a professionally optimized version.

Built using **Jupyter Notebooks, Gemini AI, and Google Cloud Platform (GCP)**, this project combines natural language processing (NLP), document parsing, and generative AI to deliver a powerful, user-friendly CV enhancement experience.

# 🌟 Key Features
✅ **CV Scoring** – Get a percentage match score between your CV and the job description.
✅ **Skill Gap Analysis** – Identify missing or underrepresented skills.
✅ **Personalized Feedback** – Receive AI-generated suggestions for improvement.
✅ **CV Tailoring** – Automatically rewrite and restructure your CV to match the job.
✅ **Keyword Optimization** – Enhance ATS (Applicant Tracking System) compatibility.
✅ **Professional Formatting** – Generate a clean, modern, and tailored CV.
✅ **Multilingual Support** – Works with CVs and job descriptions in multiple languages.

# 🔧 Usage
    Step 1: Upload Documents
        User uploads their CV (PDF/DOCX) and the job description (text/PDF).
        
    Step 2: Select the Job Type
        User selects the job type on the dropdown menu (e.g., software engineer, marketing manager etc).

    Step 3: Parse & Extract Text
        Uses pdfplumber and python-docx to extract clean text from documents.

    Step 4: Analyze & Score
        Extracts key skills, experience, education, and keywords.
        Compares against job description using cosine similarity and BERT-based embeddings.
        Generates a match score (0–100%).

    Step 5: AI-Powered Feedback
        Uses Google Gemini via Vertex AI to:
        Highlight missing skills.
        Suggest improvements in structure and content.
        Recommend action verbs and industry-specific keywords.

    Step 6: Tailor the CV
        Rewrites sections (summary, experience, skills) to align with the job.
        Optimizes for ATS by including relevant keywords naturally.
        Preserves original formatting while enhancing clarity.

    Step 7: Export Final CV
        Outputs a clean, tailored CV in PDF and DOCX formats.
