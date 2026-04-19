# Evelyn-AI Bot
Self hosted AI trading assistant with dashboard, portfolio reports, and automation


# Evelyn AI Bot

Self hosted AI powered trading assistant with dashboard, portfolio analysis, and automation

---

## Overview

Evelyn is a self hosted AI driven trading assistant designed to help you analyze stocks, monitor portfolios, and generate intelligent reports without relying on external trading platforms.

It runs locally on your machine or server, giving you full control, privacy, and flexibility.

---

## Key Features

AI Powered Stock Analysis  
Evaluate stocks using trend signals, momentum, and AI driven insights

Portfolio Report System  
Monitor the stocks you own and generate structured reports with clear verdicts and risk signals

Automated Email Reports  
Receive scheduled summaries directly to your inbox

Web Dashboard  
Clean UI for managing stocks and viewing reports

Continuous Operation  
Runs 24 7 using Docker with automatic restart

AI Picker  
Identify potential opportunities from selected stocks

Logging and Monitoring  
Track activity and system behavior over time

Local First Architecture  
Runs entirely on your system

---

## Quick Start

### Requirements

Docker  
Docker Compose  

---

### Installation

git clone https://github.com/YOUR_USERNAME/evelyn-ai-bot.git  
cd evelyn-ai-bot  
cp .env.example .env  
docker compose up -d --build  

---

### Access the Dashboard

http://localhost:5000

---

## Usage

Add the stocks you want to track  
Use the AI Picker for insights  
Enable portfolio report mode  
Configure email alerts  
Let Evelyn run and monitor results  

---

## Portfolio Reporting

Evelyn generates reports including:

Current price  
Daily movement  
Short term trend  
AI verdict buy hold sell  
Risk indicators  
Strongest stock  
Weakest stock  
Portfolio summary  

---

## Project Structure

server.py  
app_config.py  
docker-compose.yml  
Dockerfile  
templates/  
static/  
.env.example  
.gitignore  

---

## Security

Designed for local use  
Do not expose to the public internet  
Never commit real credentials  
Use environment variables for sensitive data  

---

## Disclaimer

This project is for educational and research purposes only  

It is not financial advice  

---

## License

MIT License

---

## Author

Evelyn AI Bot Project
