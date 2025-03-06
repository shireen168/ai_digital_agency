# 🚀 AI Digital Agency

A streamlined AI-powered digital agency platform that leverages specialized AI agents to analyze and plan projects effectively.

## Features

### Specialized AI Agents

#### 1. Project Director (CEO) Agent 👔

- Strategic project analysis
- Requirement evaluation
- Budget feasibility assessment
- Project complexity assessment
- Timeline estimation

#### 2. Technical Architect (CTO) Agent 🔧

- Technical architecture design
- Technology stack recommendations
- Scalability assessment
- Infrastructure planning
- Technical specifications

#### 3. Product Manager Agent 📊

- Project scope management
- Timeline roadmap planning
- Product requirements definition
- Feature prioritization
- Startup product planning

#### 4. Lead Developer Agent 💻

- Technical implementation planning
- Effort estimation
- Technical feasibility review
- Full-stack expertise
- Development best practices

#### 5. Client Success Manager Agent 🤝

- Client satisfaction management
- Expectation management
- Feedback handling
- Project delivery oversight
- Communication management

### Custom Tools 🛠️

- **Project Assessment**: Analyze project requirements and generate feasibility reports
- **Technical Specification**: Create detailed technical architecture and implementation plans

### 🔄 Agent Communication

The agency operates through coordinated communication between agents:

1. Project Director analyzes project requirements and feasibility
2. Technical Architect creates detailed technical specifications based on the analysis
3. Product Manager defines product roadmap and features
4. Lead Developer plans technical implementation
5. Client Success Manager ensures project alignment with goals

## Setup

1. Clone the repository:

```bash
git clone https://github.com/shireen168/ai_servicing_agent.git
cd ai_servicing_agent
```

2. Install dependencies using Poetry:

```bash
poetry install
```

3. Set up your OpenAI API key:

- You'll be prompted to enter your API key in the application
- Get your API key from [OpenAI Platform](https://platform.openai.com/api-keys)

4. Run the application:

```bash
poetry run streamlit run agency.py
```

## Usage

1. Project Initiation:

   - Enter your OpenAI API key
   - Submit project details including:
     - Project name and description
     - Project type
     - Budget range
     - Timeline expectations
     - Technical requirements
     - Special considerations

2. Agent Analysis:

   - Project Director evaluates project feasibility
   - Technical Architect creates technical specifications
   - Product Manager develops product roadmap
   - Lead Developer assesses implementation approach
   - Client Success Manager reviews project alignment
   - Receive comprehensive analysis and recommendations

3. Deliverables:
   - Project feasibility analysis
   - Technical architecture specifications
   - Product roadmap and features
   - Implementation plan
   - Client success strategy

## Project Structure

```
ai_servicing_agent/
├── agency.py             # Main Streamlit application with agent implementations
├── pyproject.toml        # Poetry project configuration
├── poetry.lock          # Poetry dependency lock file
└── settings.json        # Agent configuration settings
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

MIT License
