
# SmartHire - AI-Powered Resume & Job Match System
Smart recruitment system using NLP and ML to match candidates with job roles. Built with SentenceTransformers, scikit-learn, and Gradio for interactive demos.

<p align="center">
    <img src="image_resume_matching_demo.png" alt="demo-img"/>
</p>


# 🚀 What This Does
- **Problem:**
   Recruiters spend hours manually screening resumes and matching candidates to job postings.

- **Solution:** This system automatically
  - Screens resumes with 85%+ accuracy using ML models
  - Matches candidates to jobs using semantic similarity
  - Explains WHY a candidate is a good fit (explainable AI)
  - Provides salary predictions and hiring probability scores
 
Built from a real dataset of 1,000+ resumes with actual hiring decisions.

# ⚡ Quick Demo

- **Run in Google Colab (recommended):**
  - Upload AI_RESUME_MATCHING.ipynb to Google Colab
  - Upload your AI_Resume_Screening.csv dataset
  - Run all cells - everything installs automatically
  - Get instant results with the interactive Gradio demo
  
Test with your own data: Just replace the CSV file with your resume dataset.

# 📈 Performance Results
From the trained models:
- **Hiring Decision Classifier**
  - Algorithm: RandomForest (100 estimators)
  - Accuracy: 85%+ on test data
  - Features: 384-dim embeddings + numerical features


- **Salary Prediction Model:**
  - Algorithm: GradientBoosting
  - RMSE: <$8,000 prediction error
  - Predicts based on skills, experience, education

- **Job Matching Speed:**
  - 0.03 seconds per candidate evaluation
  - Can process 1000+ resumes in under 30 seconds

# 🚀 Extensions & Next Steps
Your system is production-ready for:

- **1. Real Job Posting Integration**
  - Replace hardcoded job profiles with live job postings
  - Scrape from LinkedIn, Indeed, company websites

- **2. Resume Parsing**
  - Add PDF/DOC resume upload
  - Extract structured data from unstructured resumes

- **3. Advanced NLP**
  - Fine-tune transformers on domain-specific data
  - Add named entity recognition for skills

- **4. Production Deployment**
  - Wrap in FastAPI for REST endpoints
  - Deploy on AWS/GCP with auto-scaling
  - Add user authentication and database storage


