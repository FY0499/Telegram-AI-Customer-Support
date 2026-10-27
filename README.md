# Telegram AI Customer Support Agent

An AI-powered Telegram support assistant intended to answer common customer questions, retain conversation context, and route cases for human follow-up.

## Setup
1. Import the n8n workflow JSON once added to this repository.
2. Configure Telegram and AI credentials in n8n.
3. Define escalation rules and verify memory/session behavior.
4. Test normal, unclear, and escalation cases before production use.

## Security
Keep bot tokens, chat IDs, customer messages, and credentials private. End-to-end testing is not confirmed.

## Project status
This README documents the project scope and setup expectations. The workflow export must be present in the repository before it can be imported; validate the finished workflow in your own n8n instance before relying on it.
