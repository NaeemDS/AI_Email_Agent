# Setup Instructions - AI_Mail_Assistant

Follow these steps to get the AI_Mail_Assistant workflow running in n8n.

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/naeemurrehman/AI_Mail_Assistant.git
cd AI_Mail_Assistant
2️⃣ Import Workflow into n8n
Open n8n

Go to Workflows → Import

Import the workflow JSON from:

bash
Copy code
workflows/ai_mail_assistant.workflow.json
3️⃣ Configure Credentials in n8n
Create the following credentials inside n8n:

OpenAI API

Gmail OAuth

Google Contacts OAuth

All credentials are encrypted and never stored in workflow files.

4️⃣ Start Using the Agent
Example commands:

Send an email to Ali about the project update

Email all contacts about tomorrow’s meeting

Rewrite the email in a more professional tone



