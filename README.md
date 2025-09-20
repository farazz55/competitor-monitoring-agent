AI-Powered Competitor Monitoring Agent

🚀 Automating competitor discovery and intelligence extraction using n8n, OpenAI, and self-hosted workflows.

📋 Project Overview

Our project helps businesses discover competitors and monitor their signals automatically:

Onboarding Workflow – captures company info, finds competitors, and stores structured profiles.

Monitoring Workflow – runs on a schedule, fetches competitor pages, extracts pricing/positioning signals, and emails a structured daily report.

This makes it easy for companies to track industry moves without manual research.

✨ Features

Competitor discovery from company input

Automated scraping of competitor websites

Signal extraction (pricing, products, AI focus, etc.)

Structured HTML email reports with Observations + Action Plan

Self-hosted n8n workflows (Oracle Cloud VPS)

🛠️ Tech Stack

n8n (workflow automation, self-hosted at n8n.smartaichronicle.com)

OpenAI GPT-4o-mini (AI agent for competitor signals)

Google Sheets (data persistence)

Gmail API (report delivery)

Oracle Cloud VPS (hosting environment)

📂 Repository Contents

.env.example → Example config file (replace with your own keys)

AI-Powered Competitor Monitoring Agent.json → Export of the n8n workflows

Competitor Monitoring Agent.pdf → Slides for submission

workflows snapshot.png → Workflow canvas screenshot

final output snapshot.png → Example of final email report

LICENSE → MIT license

🚀 Demo

Live Demo (self-hosted n8n): https://n8n.smartaichronicle.com

Presentation Slides: See Competitor Monitoring Agent.pdf

Video Link: https://www.loom.com/share/0c0971e713c14eb5bf6dd0a10eb289b4?sid=fcb06242-8e5b-40b9-840e-070f1c3aa1d0

📖 How to Run Locally

Clone the repo:

git clone (https://github.com/farazz55/competitor-monitoring-agent)

cd competitor-monitoring-agent

Copy .env.example → .env and add your keys.

Import the JSON workflows into n8n.

Run n8n locally or on a VPS.

🏷️ Category & Tags

Track: Agent Builder – Internet of Agents

Categories: Business Intelligence, Automation, Competitive Analysis

Technologies: n8n, OpenAI GPT-4o-mini, Gmail API, Google Sheets

📜 License

This project is licensed under the MIT License.
