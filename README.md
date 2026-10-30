# Telegram AI Customer Support Agent

I built and tested this workflow from start to finish.

An AI customer support assistant built with n8n and Telegram. It responds to customer messages, keeps track of the conversation, and alerts the support team when a request needs human attention.

<img width="537" height="217" alt="Telegram Customer Support demo" src="https://github.com/user-attachments/assets/88493c94-dc71-45ba-bc76-83ae16e63d54" />

## How it works

1. A customer sends a message to the Telegram bot.
2. The AI agent prepares a response using the conversation context.
3. The workflow checks whether the request needs escalation.
4. The bot replies to the customer or sends an alert to the support team.

## Main features

- AI-powered customer replies.
- Conversation memory.
- Human escalation path.
- Telegram notifications for the support team.

## Technologies

n8n, Google Gemini, Telegram, AI Agent, and Conversation Memory.

## Setup

Import [workflow.json](./workflow.json) into n8n and configure your Telegram and Google Gemini credentials. Set the support team's Telegram chat details before testing.
