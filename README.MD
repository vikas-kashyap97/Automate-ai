# AI Agents Project

The AI Agents Project is a comprehensive suite of intelligent agents designed to automate and enhance various tasks including research, newsletter generation, social media management, and cognitive thinking. Built using the CrewAI framework, this project leverages cutting-edge AI technologies to provide efficient and intelligent solutions.

## Features

- **Research Agent**: Automates web research and information gathering
- **Newsletter Agent**: Generates professional newsletters based on specified topics
- **Social Media Agent**: Manages and optimizes social media content
- **Thinking Agent**: Provides cognitive analysis and decision-making capabilities
- **Document Processing**: Includes utilities for DOCX file handling
- **Teleprompter**: Modern teleprompter application for content presentation


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vikas-kashyap97/Automate-ai.git
   cd ai-agents
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   Create a `.env` file and add your API keys:
   ```
   OPENAI_API_KEY=your_openai_key
   SERPER_API_KEY=your_serper_key
   ```

## Usage

### Running Agents

To run a specific agent, use the corresponding Python script:

```bash
# Run Research Agent
python research.py

# Run Newsletter Agent
python newsletter.py

# Run Social Media Agent
python agents/social_media/main.py

# Run Thinking Agent
python agents/thinking/streamlit-based.py
```

### Using the Teleprompter

```bash
python teleprompter.py
```


## Project Structure

```
ai-agents/
├── agents/               # Contains all agent implementations
│   ├── newsletter/       # Newsletter generation agent
│   ├── research/         # Research agent
│   ├── social_media/     # Social media management agent
│   └── thinking/         # Cognitive thinking agents
├── db/                   # Database files
├── requirements.txt     # Python dependencies
├── README.md             # Project documentation
└── ...                   # Other project files
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Contact

Project Maintainer - [Vikas Kashyap]  
Email - vikaskashyaprock@gmail.com  
Project Link: [link](https://github.com/vikas-kashyap97/Automate-ai.git)
