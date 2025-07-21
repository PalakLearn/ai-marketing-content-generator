# ai-marketing-content-generator
End-to-end marketing content generation workflow using OpenAI, Vertex AI, Power Automate, and Dynamics 365.
#  AI-Powered Marketing Content Generator

##  Objective
Automate the creation, approval, and distribution of marketing content (emails, blogs, social posts) using Generative AI + Microsoft stack.

## 🛠 Tools Used
- OpenAI GPT-4 API
- Vertex AI (PaLM 2)
- Microsoft Power Automate
- Dynamics 365 Marketing
- Microsoft outlook (Approval flow)
- Power BI (Email engagement tracking)

##  Workflow

1. Marketer submits a product brief via Power Apps
2. Power Automate triggers prompt → sends to OpenAI or Vertex AI
3. Generated content sent to Microsoft Teams for manager approval
4. Approved content is auto-sent via Dynamics 365 Marketing
5. Email engagement is tracked via Power BI dashboard

##  Outcomes
- Reduced manual writing time by 80%
- Improved content-to-launch time from 2 days → 15 minutes
- Reusable flows across multiple campaigns and formats

##  Files

- `prompt-templates/openai-prompt.txt`  
- `prompt-templates/vertex-prompt.txt`  
- `power-automate/flow-json-export.json`  
- `sample-output/ai-email-example.txt`  
- `flow-diagram.png`

## 📸 Screenshots

<img src="flow-diagram.png" alt="Power Automate Flow" width="600"/>

## ✍️ Author
Palak Chaturvedi  
[LinkedIn](https://www.linkedin.com/in/palak-chaturvedi-a25323211/) | [Portfolio](https://www.notion.so/AI-Marketing-Portfolio-Palak-Chaturvedi-237080ad24ae80159762e58865881432?p=237080ad24ae80f7bb59dd4d4a1601e2&showMoveTo=true)
