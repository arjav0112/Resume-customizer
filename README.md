# Resume Customizer in n8n  

An **AI-powered Resume Customizer and Screener** built using **n8n**.  
This workflow helps candidates automatically tailor their resumes to specific job descriptions, while also acting as a screening tool to evaluate whether the candidate is a good fit for the role.  

---

## 🚀 Features  

- 📄 **Resume Customization** – Takes your current resume and a job description as inputs, then generates a tailored resume that matches the requirements.  
- ✅ **Resume Screening** – Analyzes your resume against the job description and provides a "Fit/Not Fit" evaluation with reasoning.  
- 🔄 **Automated Workflow** – Entire process is automated in n8n, reducing manual editing and guesswork.  
- ⚡ **Reusable** – Can be extended to multiple job applications with minimal changes.  

---

## 🛠️ How It Works  

1. **Input**: Upload your current resume and the target job description.  
2. **Processing**:  
   - Extracts key skills and requirements from the job description.  
   - Maps your existing experience and skills to match the requirements.  
   - Generates a customized version of your resume.  
   - Screens your resume to determine job fit.  
3. **Output**:  
   - A tailored resume ready for submission.  
   - A screening report stating if you are a fit for the job.  

---

## 📂 Project Structure  

- **Workflow JSON** – Importable n8n workflow file.  
- **Custom Resume Generator** – AI node for resume customization.  
- **Resume Screener** – AI node for fit analysis.  
- **Merge & Output** – Final customized resume + screening result.  

---

## ▶️ Demo  

🎥 ( https://drive.google.com/file/d/1qRtSd3k-DcaU-qb6Glb-oIOyrNie--fg/view ) 

---

## 📦 Installation  

1. Clone this repository.  
2. Import the provided workflow JSON into your **n8n instance**.  
3. Configure your **Google Gemini API credentials** in n8n.  
4. Run the workflow and provide the required inputs.  

---

## ✅ Example Use Case  

- A candidate applies to multiple companies. Instead of rewriting their resume each time, they run the workflow with the target job description.  
- The workflow produces a customized resume and instantly tells whether the candidate’s background fits the job role.  

---

## 🔮 Future Enhancements  

- Integration with **LinkedIn Job Posts** for automatic JD parsing.  
- One-click export to **PDF/Word formats**.  
- Automated job tracking dashboard inside n8n.  

---

## 📧 Contact  

For questions or contributions, feel free to open an issue or connect with me on LinkedIn.  
