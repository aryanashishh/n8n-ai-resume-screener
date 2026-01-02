🤖 The AI Resume Screener

Stop manually reading every resume. This n8n workflow acts as your tireless recruiting assistant, using Google Gemini to grade incoming candidates against your Job Description instantly.

⚡What it does

Watches: You drop a PDF resume into a Google Drive folder.
Compares: The AI reads the resume and compares it against your specific Job Description.
Scores: It assigns a 0-100 Relevance Score (based on Skills, Exp, and Edu).
Logs: It saves the candidate's name, contact info, and "Why they fit" reasoning to Google Sheets.

🛠️ Setup in 3 Steps

Import: Load the workflow.json file into n8n.
Connect: Add your Google Drive and Google Gemini credentials.
Configure:
Trigger Node: Select your "Resumes" folder.
Download JD Node: Select your Job Description PDF file.
Sheets Node: Select your results spreadsheet.

📋The Google Sheet

Create a sheet with these exact headers in Row 1: candidate_name | email | mobile | relevance_score | reasoning
