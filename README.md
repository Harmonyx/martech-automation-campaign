# Campaign Workflow Templates

## Overview

This repository contains a collection of JSON workflow templates for an agentic marketing campaign system built on n8n. The system orchestrates specialized AI agents to create comprehensive marketing campaigns following a structured sequence with proper data validation.

## System Architecture

The campaign workflow system uses a multi-agent approach where specialized AI agents collaborate to create a complete marketing campaign. The main workflow coordinates these agents in a sequential process:

1. **Campaign Orchestrator Agent**: Coordinates the entire campaign creation process and handles language detection/translation
2. **Marketing Manager Agent**: Defines campaign objectives, target audience, and strategic goals
3. **Creative Director Agent**: Develops creative concepts, brand positioning, and visual identity
4. **Graphic Designer Agent**: Creates visual mockups, color palettes, typography, and layout guidelines
5. **Content Creator Agent**: Develops platform-specific content ideas, copy suggestions, and content calendars
6. **PR and Social Media Agent**: Handles media outreach, press releases, and social media strategy

## Template Files

The repository includes the following JSON template files:

- `Campaign_Agentic.json`: The main workflow that orchestrates all agents
- `Agent___Market_Manager.json`: Specialized agent for marketing strategy
- `Agent___Creative_Director.json`: Specialized agent for creative direction
- `Agent___Graphic_Designer.json`: Specialized agent for visual design
- `Agent___Content_Creator.json`: Specialized agent for content creation
- `Agent___PR_and_Social_Content.json`: Specialized agent for PR and social media

## Key Features

- **Multi-language Support**: Detects the language of user requests and responds in the same language
- **Comprehensive Campaign Planning**: Creates complete marketing campaigns with all necessary components
- **Specialized Agent Roles**: Each agent focuses on a specific aspect of the campaign
- **Structured Output**: All agents produce standardized JSON outputs for seamless integration
- **Visual Asset Creation**: Includes mockups and design specifications for various channels
- **Content Strategy**: Develops platform-specific content ideas and posting schedules
- **Project Timeline**: Creates detailed project timelines with task assignments

## Usage

These templates are designed to be imported into n8n, a workflow automation platform. To use them:

1. Import the template files into your n8n instance
2. Configure the OpenAI API credentials for the language models
3. Trigger the main workflow with a marketing campaign request
4. The system will process the request through all specialized agents
5. Review the comprehensive campaign output

## Example Input

The system accepts marketing campaign requests in any language. A typical request might include:

- Product name and description
- Target market and pricing
- Key product features and benefits
- Target audience demographics
- Marketing budget and timeline
- Desired marketing channels
- Campaign objectives

## Output

The system produces a comprehensive marketing campaign that includes:

1. **Executive Summary**: Overview of the entire campaign
2. **Campaign Strategy**: Product overview, target audience, key messaging
3. **Creative Direction**: Creative concepts, visual identity, design elements
4. **Content Strategy**: Content themes, platform-specific approaches, examples
5. **Channel Strategy**: Channel mix, platform-specific tactics, posting schedule
6. **PR Strategy**: Media outreach, event planning, press materials
7. **Budget Allocation**: Cost breakdown, ROI projections
8. **Implementation Roadmap**: Timeline, key milestones, team responsibilities
9. **Success Metrics**: KPIs, measurement methodology

## Requirements

- n8n workflow automation platform
- OpenAI API access (GPT-4o model)
- Google Drive integration (for document storage)

## License

This project is proprietary and confidential. Unauthorized copying, distribution, or use is strictly prohibited.
