# Microsoft Studio Agents — Stellar Recruitment

A collection of Copilot Studio AI Agents built for Stellar Recruitment.

## Agents

| Agent | Description |
|-------|-------------|
| [report-generator](./report-generator/) | Generates branded candidate reports for Stellar Recruitment |

## Structure

Each agent lives in its own subfolder and contains a self-contained Copilot Studio project:

```
agent-name/
├── agent.mcs.yml     ← Agent definition
├── topics/           ← Conversation topics
├── actions/          ← Connector actions
└── README.md         ← Agent-specific docs
```

## Getting Started

Each agent folder is an independent Copilot Studio project. Use the Copilot Studio VS Code extension to push/pull changes between local files and your Power Platform environment.
