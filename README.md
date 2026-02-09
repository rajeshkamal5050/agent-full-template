# AI Foundry Agent Template

A starter template for deploying AI agents to Azure using Azure Developer CLI (azd).

## Prerequisites

- [Azure Developer CLI (azd)](https://learn.microsoft.com/azure/developer/azure-developer-cli/install-azd)
- Azure subscription

## Quick Start

Initialize and deploy using this template:

```bash
azd init -t rajeshkamal5050/agent-full-template
```

Then run:

```bash
azd up
```

This will:
1. Initialize the AI agent from the Foundry samples
2. Provision Azure infrastructure (AI Foundry, Container Registry, Storage, etc.)
3. Deploy the System Utility Agent

## What's Included

- **Infrastructure**: Bicep templates for Azure AI Foundry, Container Registry, Application Insights, Log Analytics, and Storage
- **Agent**: System Utility Agent configured with GPT-5 model deployment

## License

MIT
