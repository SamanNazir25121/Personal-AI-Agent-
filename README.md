# Personal-AI-Agent
# Personal AI Agent

> An intelligent AI assistant built with **n8n** and powered by the **Groq API**, capable of managing emails, calendars, weather updates, and automating everyday productivity tasks through natural language conversations.

---

# Overview

Personal AI Agent is an AI-powered automation assistant designed to simplify daily workflows by combining Large Language Models with real-world productivity tools.

Instead of acting as a traditional chatbot, the assistant can understand user intent, reason over requests, and interact with external services to perform real actions.

The project uses **n8n** as the workflow orchestration platform and **Groq's Llama models** for conversational reasoning, enabling intelligent, context-aware automation.

---

# Features

## Calendar Management

- View upcoming meetings
- Schedule new events
- Update existing events
- Find available time slots
- Check schedule conflicts

---

## Email Assistant

- Read emails
- Search emails
- Summarize conversations
- Organize inbox
- Label important emails

---

## Weather Intelligence

- Retrieve current weather conditions
- Access weather forecasts
- Check rain probability
- View temperature and humidity
- Monitor wind conditions

---

## AI Reasoning

Powered by Groq Llama models, the assistant can:

- Understand natural language
- Determine the appropriate tool automatically
- Execute workflows
- Generate conversational responses

---

# Technology Stack

- n8n
- Groq API
- Llama 3
- Gmail API
- Google Calendar API
- OpenWeatherMap API

---

# Workflow

![Workflow](screenshots/workflow.png)

The AI agent receives natural language requests, interprets user intent using Groq's LLM, selects the appropriate connected services, executes the required APIs, and returns a conversational response.

---

# Example Prompts

```
What's on my calendar today?

Schedule a meeting tomorrow at 2 PM.

Summarize my unread emails.

What's the weather like today?

Will it rain tomorrow?
```

# Future Improvements

- Voice assistant integration
- WhatsApp integration
- Slack integration
- Google Drive support
- Long-term memory
- Multi-agent collaboration
- Daily productivity briefings
- Task automation

---
