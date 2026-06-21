# AI Email & Document Automation Suite

AI-powered email and document automation workflows built using n8n, Gmail API, Google Drive API, OAuth 2.0, and MCP (Model Context Protocol).

## Overview

This repository contains a collection of workflow automations designed to streamline email communication and document delivery processes.

The workflows integrate Gmail and Google Drive services to automatically retrieve documents, generate email content, and send or reply to emails with dynamic attachments. MCP-compatible tools are also included to enable AI assistants to trigger these workflows.

---

## Features

- AI-assisted email generation
- Gmail email sending and reply automation
- Single-document retrieval and delivery
- Multi-document retrieval and delivery
- Automated Google Drive document search
- Dynamic attachment handling
- HTML email signature generation
- MCP-compatible workflow tools
- Modular workflow architecture

---

## Tech Stack

- n8n
- Gmail API
- Google Drive API
- OAuth 2.0
- MCP (Model Context Protocol)
- JavaScript

---

## Repository Structure

```text
ai-email-document-automation-suite/
│
├── workflows/
│   ├── AI Email Assistant.json
│   ├── Single Document Email Automation.json
│   ├── Single Document Email MCP Tool.json
│   ├── Document Retrieval & Multi-Attachment Email System.json
│   └── Multi-Document Email MCP Tool.json
│
├── screenshots/
│   └── workflow screenshots
│
└── README.md
```

---

## Workflows

### 1. AI Email Assistant

An MCP-enabled workflow that allows AI assistants to:

- Send Gmail messages
- Reply to Gmail threads
- Generate formatted email content
- Add standardized email signatures

---

### 2. Single Document Email Automation

Automates:

- Searching a document in Google Drive
- Downloading the requested file
- Appending an email signature
- Sending the document as an email attachment

---

### 3. Single Document Email MCP Tool

Exposes the Single Document Email Automation workflow as an MCP-compatible tool that can be invoked by AI assistants.

---

### 4. Document Retrieval & Multi-Attachment Email System

Automates:

- Retrieval of multiple documents from Google Drive
- Attachment aggregation
- Email preparation
- Sending multiple attachments in a single email reply

---

### 5. Multi-Document Email MCP Tool

Provides AI assistants with access to the multi-document retrieval workflow through MCP.

---

## Workflow Architecture

```text
AI Assistant / MCP Client
            │
            ▼
      MCP Tool Layer
            │
            ▼
            n8n
        ┌────┴────┐
        ▼         ▼
     Gmail   Google Drive
```

---

## Use Cases

- Automated customer communication
- Technical document delivery
- Product brochure distribution
- Workflow automation
- AI-assisted business operations
- Email response automation

---

## Screenshots

Workflow screenshots can be found in the `screenshots/` directory.

---

## Setup

1. Import the workflows into n8n.
2. Create your own Gmail OAuth credentials.
3. Create your own Google Drive OAuth credentials.
4. Update workflow credentials.
5. Execute the workflows.

---

## Security

No credentials, API keys, OAuth tokens, or sensitive business information are included in this repository.

Users must configure their own Gmail and Google Drive integrations before execution.

---

## Future Improvements

- Claude Desktop integration
- Public MCP deployment
- Enhanced document search capabilities
- CRM integration
- Advanced email templating
- Workflow monitoring and analytics

---

## Author
Riddhi Basu

Digital Process Coordinator | AI & Workflow Automation Enthusiast

Built as part of an automation and AI workflow engineering portfolio focused on business process automation, document management, and AI-assisted operations.
