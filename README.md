# Automation

## Overview
This repository hosts my automation projects built with [n8n](https://n8n.io/). Currently, it includes two workflows: "ATS Score Prediction" and "Integrate Gemini to Predict Score." Each project is designed to showcase automation techniques using Google services and AI.

---

## Projects

### 1. ATS Score Prediction
#### Overview
This workflow automates the evaluation of resumes to predict ATS (Applicant Tracking System) compatibility scores (0-100) for recruiters and HR professionals.

#### Features
- Extracts candidate data (names and resume links) from a Google Sheet.
- Converts Google Drive viewing links to downloadable URLs.
- Processes PDF resumes and analyzes content using Gemini AI.
- Updates the Google Sheet with ATS scores for easy tracking.

#### Getting Started
##### Prerequisites
- [n8n](https://n8n.io/) installed.
- Google Sheets API access with OAuth credentials.
- Google Drive API access.
- Google Gemini API key.

##### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Umar-MUF/Automation.git

Contributing:
Contributions are welcome! If you'd like to improve any project, please follow these steps:

1.Fork the repository.
2.Create a new branch for your feature or fix: git checkout -b feature-name.
3.Commit your changes: git commit -m "Add feature/fix description".
4.Push to your branch: git push origin feature-name.
5.Submit a pull request with a clear description of your changes.
6.Feel free to open an issue for bugs, suggestions, or questions!

Contact:
For questions, collaboration, or feedback, reach out to me at:

Email: muf.muhammadumarfarooq@gmail.com
LinkedIn: https://tinyurl.com/2wbwtctf
