# AI-Powered Job Application Assistant

An n8n-based automation project that uses large language models to analyze job descriptions, compare resume content with job requirements, identify skill gaps, and support interview preparation.

## Features

- Accepts job descriptions through Telegram messages or URLs.
- Extracts job titles, skills, tools, and relevant keywords using an LLM.
- Compares resume content with job requirements and produces match scores.
- Identifies matched and missing keywords.
- Generates evidence-based resume improvement suggestions from a defined project inventory.
- Supports approval, rejection, and feedback-based revisions through Telegram.
- Logs analysis results and application status to Google Sheets.
- Generates technical and HR interview questions with suggested answers.

## Workflow Overview

1. Receive a job description.
2. Extract structured job requirements using an LLM.
3. Compare the requirements with the candidate's resume.
4. Identify matching skills and gaps.
5. Generate resume improvement suggestions.
6. Collect approval or revision feedback through Telegram.
7. Log results and prepare interview questions.

## Technology Stack

- **Automation:** n8n
- **LLM integration:** Groq API, Llama 3.3 70B
- **Scripting:** JavaScript
- **Messaging:** Telegram Bot API
- **Logging:** Google Sheets

## Setup

1. Download the sanitized workflow JSON from this repository.
2. Import the JSON into an n8n instance.
3. Configure your own Telegram, Groq, and Google Sheets credentials.
4. Replace placeholder IDs and destination values with your own configuration.
5. Test the workflow with a fictional resume and sample job description before activating it.

## Security

This repository should contain only sanitized workflow exports, documentation, and sample data. Never commit API keys, bot tokens, private webhook URLs, personal resumes, or private applicant information.

## Limitations

The workflow export is provided as a project template. Import it, configure the required integrations, and test each branch before using it operationally. Automatic discovery of LinkedIn job openings is not claimed by this version.

## Author

Sneha Porwal

[GitHub](https://github.com/Sneha-162)
