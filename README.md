Workflow 1:
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
------------------------------------------------------------------------------------------------------------------------------------------
Workflow 2:
AI LinkedIn Content Strategist (n8n Workflow)
This repository contains an automated n8n workflow designed to research topics and generate high-quality, professional LinkedIn posts using AI. It transforms raw web research into engaging thought-leadership content.  

🚀 Features
Automated Research: Uses the Tavily API to search the web for specific topics fetched from a Google Sheet.  

AI-Powered Synthesis: Leverages an OpenAI-driven agent (GPT-5 Mini) to analyze four different articles and synthesize them into a single, cohesive narrative.  

Professional Output: Follows a strict system prompt to ensure the content sounds human, includes a strong hook, provides value insights, and ends with an engagement call-to-action.  

Google Sheets Integration: Automatically pulls "To Do" topics from your sheet and updates the same row with the generated content and a "Created" status.  

🛠️ How it Works
Trigger: The workflow runs on a daily schedule (7:00 AM) or can be triggered manually.  

Fetch: It identifies rows in a Google Sheet labeled with the status "To Do".  

Search: It performs a web search for the topic using the Tavily API.  

Generate: The AI Agent processes the search results to write a LinkedIn post (~120–220 words).  

Update: The final post is written back to the Google Sheet.  

📋 Prerequisites
n8n (Self-hosted or Cloud)

OpenAI API Key

Tavily API Key (for web search)  

Google Cloud Console credentials (for Google Sheets access)  

🔧 Setup
Import the provided .json file into your n8n instance.  

Configure your credentials for Google Sheets, OpenAI, and the HTTP Request (Tavily) node.  

Update the documentId in the Google Sheets nodes to match your specific spreadsheet.  

Set the workflow to Active.
------------------------------------------------------------------------------------------------------------------------------------------

📣 Connect

If you found this useful, feel free to connect with me on LinkedIn and check out more projects!
