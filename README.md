# Automation-Telegram-Bot

Spider-Man Telegram AI Bot (n8n Workflow)

Project Overview

An AI-powered Telegram chatbot built using n8n and OpenAI. This bot
responds as Spider-Man (Peter Parker) with witty humor, playful sarcasm,
and superhero energy.

The personality is defined inside the AI Agent system prompt and
maintains a consistent character tone in every response.

Architecture Overview

Components:

1.  Telegram Trigger – Captures incoming Telegram messages.
2.  AI Agent (LangChain Node) – Processes user input and applies
    Spider-Man personality.
3.  OpenAI Chat Model (gpt-5-mini) – Generates conversational responses.
4.  Telegram Node – Sends the AI-generated reply back to the user.

Workflow Logic

1.  User sends a message via Telegram.
2.  Telegram Trigger captures the message text.
3.  AI Agent receives the message and applies the Spider-Man personality
    system prompt.
4.  OpenAI model generates a witty, superhero-style response.
5.  The response is sent back to the user via Telegram.

Personality Configuration

The AI Agent is configured to:

-   Speak like Spider-Man (Peter Parker)
-   Use witty humor and light sarcasm
-   Add playful confidence and clever jokes
-   Maintain a heroic but upbeat tone
-   Avoid dark or overly serious responses

Tech Stack

-   n8n (Workflow Automation)
-   OpenAI Chat Model (gpt-5-mini)
-   Telegram Bot API
-   LangChain Agent Node

Required Credentials

-   Telegram Bot API credentials
-   OpenAI API credentials

All credentials are configured securely within n8n.

Setup Instructions

1.  Install n8n npm install -g n8n

2.  Import Workflow

    -   Open n8n
    -   Navigate to Workflows
    -   Click Import
    -   Upload the provided JSON file

3.  Configure Credentials

    -   Set Telegram credentials
    -   Set OpenAI API credentials

4.  Activate Workflow Toggle the workflow to Active.

Use Cases

-   Fun AI personality bot
-   Telegram chatbot demo project
-   AI character simulation
-   Portfolio project for automation and AI integration

Project Status

-   Telegram Integration Complete
-   AI Personality Agent Configured
-   OpenAI Model Connected
-   Ready for Deployment

Future Improvements

-   Add memory for conversation context
-   Add multiple character modes
-   Add voice message support
-   Add admin command controls

License

MIT License
