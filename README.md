AI Content Automation Pipeline (n8n + OpenAI)

🚀 Overview

This project is an AI-powered automation workflow built using n8n and OpenAI.

It takes a simple topic as input and automatically:

* Generates an SEO-friendly article
* Summarizes the content
* Extracts relevant keywords
* Returns structured JSON response

⚙️ How it works

1. Receives input via webhook (POST request)
2. Uses OpenAI to generate content
3. Processes and analyzes the content
4. Formats output using JavaScript
5. Returns a clean API response

📥 Input


curl -X POST http://localhost:5678/webhook-test/content-pipeline \
-H "Content-Type: application/json" \
-d '{"topic":"AI tools"}'


📤 Output


curl -X POST http://localhost:5678/webhook-test/content-pipeline \
-H "Content-Type: application/json" \
-d '{"topic":"AI tools"}'


🛠️ Tech Stack

* n8n (workflow automation)
* OpenAI API
* JavaScript (Code node)
* Webhooks

💡 Use Cases

* SEO content generation
* Marketing automation
* AI content pipelines
* Automation workflows

📸 Screenshot

(Add your workflow screenshot here)

📌 Notes

* Built as a production-style workflow
* Includes structured JSON output
* Designed for scalability and automation
    :::

  <img width="1582" height="703" alt="image" src="https://github.com/user-attachments/assets/575571a4-4f1e-4caf-b9be-1d44e90ea807" />
