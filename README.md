# ai-email-intelligence-n8n
AI-powered email intelligence automation built with n8n and Google Gemini to classify emails, determine priority, generate summaries, identify action items, and store insights in Google Sheets.

✨ Features
📩 Automatically detects incoming Gmail emails
🤖 Uses Google Gemini for AI-powered email analysis
🏷️ Classifies emails by category
🚨 Determines email priority
📝 Generates concise email summaries
✅ Identifies required action items
📊 Stores structured results in Google Sheets
⚡ Runs automatically through n8n
🔄 Produces consistent structured output using an Output Parser
🧠 AI Processing

For every incoming email, the AI analyzes information such as:

Email subject
Sender
Email content
Email category
Priority
Summary
Required action items

The AI converts the email into structured information that can be easily stored and analyzed.

Example

Incoming Email

Subject: Meeting scheduled for tomorrow
From: client@example.com

Please confirm your availability for tomorrow's client meeting at 10 AM.

AI Output

Category: CLIENT
Priority: HIGH

Summary:
Client has requested confirmation for tomorrow's meeting.

Action Item:
Confirm availability for the meeting.
🛠️ Technologies Used
Technology	Purpose
n8n	Workflow automation
Gmail	Email trigger and input
Google Gemini	AI email analysis
Structured Output Parser	Consistent AI output
Google Sheets	Store processed email data
🔄 Workflow Architecture

The automation consists of the following main components:

1. Gmail Trigger

The workflow starts when a new email is received.

Gmail Trigger
      ↓
Incoming Email
2. AI Email Analysis

The email information is passed to Google Gemini.

Gemini analyzes the email and determines:

Category
Priority
Summary
Action items
3. Structured Output Parser

The AI response is converted into a structured format.

This makes the output predictable and easier to use in the next step.

4. Google Sheets

The processed email information is stored in Google Sheets for tracking and further analysis.

📸 Workflow Screenshot

📊 Google Sheets Output

The processed email information is stored in Google Sheets.

📁 Project Structure
ai-email-intelligence-n8n
│
├── README.md
├── AI Email Intelligence Automation.json
│
└── screenshots
    ├── workflow.png
    └── google-sheets.png
⚙️ How to Use
1. Download the Workflow

Download:

AI Email Intelligence Automation.json

from this repository.

2. Open n8n

Open your n8n instance and import the JSON workflow.

3. Configure Credentials

Connect your own:

Gmail account
Google Gemini credentials
Google Sheets account

Credentials are not included in this repository.

4. Configure Google Sheets

Select the Google Spreadsheet and worksheet where the processed email information should be stored.

5. Test the Workflow

Send a test email to the connected Gmail account and execute the workflow.

The workflow should:

Receive Email
      ↓
Analyze with Gemini
      ↓
Generate Structured Result
      ↓
Save to Google Sheets
💼 Business Use Cases

This automation can be useful for:

Customer support teams
Sales teams
Freelancers
Small businesses
Operations teams
Email-heavy organizations
Lead management
Client communication

It can help reduce manual email processing and make important emails easier to identify and manage.

🔐 Security

This repository does not contain personal Gmail credentials, API keys, passwords, or Google Sheets credentials.

Users should configure their own credentials inside n8n.

🎯 Future Improvements

Possible future improvements include:

Automatic email replies
Slack/WhatsApp notifications for high-priority emails
Automatic task creation
CRM integration
Lead scoring
Sentiment analysis
Email routing
Daily email intelligence reports
Human approval before sending AI-generated replies
👨‍💻 Author

Mohammed Apsal

AI Automation | Generative AI | n8n | AI Agents

⭐ If you find this project useful, feel free to explore the workflow and adapt it for your own automation projects.


### What you should do now

On your GitHub page:

**1. Open `README.md`**

**2. Click the ✏️ pencil/edit icon**

**3. Delete the existing 2 lines**

**4. Paste the entire README above**

**5. Scroll down → click `Commit changes`**

### ⚠️ One important check

Your screenshot currently shows:

```text
screenshots
AI Email Intelligence Automation.json
README.md
