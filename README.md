# AI-soc investigation
AI-assisted SOC investigation and security alert automation using n8n and OpenAI
# AI-SOC-Investigation

## Project Overview

AI-SOC-Investigation is a cybersecurity automation project designed to help security analysts investigate security alerts using n8n and AI.

The workflow connects automated steps to process security-related information and generate investigation results.

## Objectives

* Automate parts of the security investigation process.
* Analyze security alerts using AI.
* Reduce repetitive manual investigation tasks.
* Present investigation results in a structured format.

## Technologies Used

* n8n — Workflow automation
* AI integration — Security alert analysis
* GitHub — Version control and project documentation

## Workflow

1. Receive or trigger an investigation request.
2. Process the available security information.
3. Send relevant information to the configured AI service.
4. Generate an investigation result.
5. Review the result for further security investigation.

*Note: The steps above describe the intended workflow. Actual functionality depends on the nodes configured in the exported workflow.*

## How to Use

1. Download the exported n8n workflow JSON file from this repository.
2. Open your n8n instance.
3. Import the workflow JSON file.
4. Configure the required credentials.
5. Review the nodes and connections.
6. Execute the workflow using its configured trigger.
7. Review the investigation output.

## Security Notice

Do not upload API keys, passwords, access tokens, private security logs, or other sensitive information to GitHub.

## Project Status

Prototype — further testing and improvements may be added.
