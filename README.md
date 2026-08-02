# Resume vs JD Match Engine (n8n + Gemini AI)

An AI-powered workflow built with **n8n** and **Google Gemini** that analyzes a candidate's resume against a job description and provides an intelligent compatibility report.

## Features

* 📄 Extracts text from PDF resumes
* 🤖 Uses Google Gemini AI for resume analysis
* 🎯 Calculates Resume–JD Match Score
* ✅ Identifies matched skills
* ❌ Highlights missing skills
* 💪 Lists candidate strengths
* 📈 Suggests areas for improvement
* ⚡ Fully automated n8n workflow

## Tech Stack

* n8n
* Google Gemini AI
* HTTP Request
* PDF Extraction
* AI Agent
* JSON Processing

## Workflow

1. Upload Resume (PDF)
2. Extract resume text
3. Input Job Description
4. Send data to Gemini AI
5. Analyze resume against the JD
6. Generate:

   * Match Score
   * Matched Skills
   * Missing Skills
   * Strengths
   * Improvement Suggestions

## Project Structure

```text
Resume-JD-Match-Engine-n8n/
│── resume-jd-match-workflow.json
│── README.md
│── .gitignore
```

## Use Cases

* Resume screening
* Recruitment automation
* HR workflow automation
* Career guidance
* AI-powered candidate evaluation

## How to Use

1. Import `resume-jd-match-workflow.json` into n8n.
2. Configure your Google Gemini API credentials.
3. Run the workflow.
4. Upload a resume and provide a job description.
5. Review the AI-generated match report.

## Future Improvements

* ATS score calculation
* Multi-resume comparison
* Skill gap visualization
* Export reports to PDF
* Email notification integration
* Database support

## Author

**Rajsu Pandey**

AI Engineer | Machine Learning | Generative AI | Workflow Automation

If you found this project useful, consider giving it a ⭐ on GitHub.
