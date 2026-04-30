📧 AI-Powered Gmail Automation with n8n

This project showcases an intelligent email automation workflow built using n8n. It uses AI to classify incoming emails, retrieve relevant knowledge, and automatically respond—reducing manual effort and improving response time.

🚀 Features
📥 Automatic Email Trigger
Monitors incoming emails using Gmail Trigger.
🧠 AI-Based Classification
Classifies emails (e.g., customer support, general queries) using an OpenAI model.
🤖 AI Agent Processing
Routes emails through an AI Agent for intelligent decision-making.
🔍 Knowledge Retrieval
Uses Pinecone Vector Store to fetch relevant context.
🏷️ Auto Labeling
Adds labels to emails based on classification.
✉️ Automated Replies
Sends AI-generated responses using Gmail.
🏗️ Workflow Overview
Gmail Trigger → Detects new incoming emails
Text Classifier → Categorizes email content
AI Agent → Processes and decides next action
Pinecone Vector Store → Retrieves contextual data
Gmail Actions → Labels and replies to emails
🛠️ Tech Stack
n8n
OpenAI (Chat Model + Embeddings)
Pinecone (Vector Database)
Gmail (Email automation)
📦 Setup Instructions
1. Import Workflow
Download the .json file
Import it into n8n
2. Configure Credentials
Gmail OAuth credentials
OpenAI API key
Pinecone API key & index
3. Update Nodes
Set your Pinecone index (ensure correct vector dimension)
Adjust email labels and response templates
⚠️ Notes
Ensure embedding dimensions match your Pinecone index
Clear cookies if OAuth errors occur during setup
Test with sample emails before deploying
💡 Use Cases
Customer support automation
Email triaging system
AI-powered helpdesk
Smart inbox assistant

📣 Connect

If you found this useful, feel free to connect with me on LinkedIn and check out more projects!
