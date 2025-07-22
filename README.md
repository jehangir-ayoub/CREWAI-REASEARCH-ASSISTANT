# CREWAI-REASEARCH-ASSISTANT
🔍 CrewAI Research Assistant A powerful research assistant built with CrewAI, Exa, and Streamlit that helps you research any topic using AI Agents.
🌟 Features
🤖 Multiple LLM Support
🔍 Advanced answering capabilities using Exa
📊 Real-time research process visualization
📝 Structured research reports
🎯 Topic-focused research and analysis
🔒 Secure API key management
📱 Responsive and modern UI
📚 Code Organization
# Main Application (streamlit_app.py):

Configures the Streamlit interface
Manages the research workflow
Handles result display
Research Component (researcher.py):

Configures LLM providers (OpenAI, GROQ, Ollama)
Creates research agents with appropriate tools
Defines research task structure
Manages the research execution process
Sidebar Component (sidebar.py):

Handles model selection UI
Manages API key input
Integrates with local Ollama instance
Provides configuration options
Output Handler (output_handler.py):

Captures and formats research process output
Manages real-time display updates
# 🛠️ Project Structure

├── streamlit_app.py # Main Streamlit application entry point
├── requirements.txt # Project dependencies
└── src/
├── components/
│ ├── researcher.py # Research agent and task implementation
│ │  - LLM configuration
│ │  - Research task creation
│ │  - Exa search integration
│ └── sidebar.py # Sidebar UI and configuration
│ - Model selection
│ - API key management
│ - Ollama integration
└── utils/
└── output_handler.py # Process output management



   # - Real-time output capture
   # - Output formatting
# 📋 Requirements
Python >=3.10 and <3.13
OpenAI API key or GROQ API key
Exa API key
Streamlit
# 🚀 Getting Started
Clone the repository:
git clone https://github.com/tonykipkemboi/crewai-streamlit-demo.git
cd crewai-streamlit-demo
Create and activate a virtual environment:
python -m venv .venv
source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
Install dependencies:
pip install -r requirements.txt
Run the application:
streamlit run streamlit_app.py
# 🔑 API Keys Setup
The application requires the following API keys:

OpenAI API Key or GROQ API Key

For OpenAI: Get it from OpenAI Platform
For GROQ: Get it from GROQ Console
Exa API Key

Get it from Exa
Enter these keys in the sidebar of the application when prompted.

# 🎯 Usage
Open the application in your web browser
Select your preferred LLM provider (OpenAI or GROQ)
Enter your API keys in the sidebar
Type your research query in the text area
Click "Start Research" to begin the research process
View the real-time research process and final results
# 💡 Features in Detail
Research Agent
The research agent (src/components/researcher.py) is powered by CrewAI and configured to:

Conduct thorough research on given topics
Analyze and summarize information
Provide structured reports with key findings
Process Output
The output handler (src/utils/output_handler.py) provides:

Real-time process visualization
Clean, formatted output
Progress tracking
User Interface
The application features a modern, responsive UI with:

Intuitive sidebar configuration
Clear process visualization
Organized research results
Professional styling
🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

# 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

# 🙏 Acknowledgments
CrewAI for the AI agent framework
Exa for advanced search capabilities
Streamlit for the web interface
Made with ❤️ using CrewAI, Exa, and Streamlit
