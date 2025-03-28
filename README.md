# CrewAI Agents - AI-Powered Workflow Automation

This repository contains a Google Colab notebook implementing a CrewAI-powered team of four AI agents designed to assist with various career-related tasks, including web scraping, resume analysis, CV writing, and interview preparation.

## 🚀 Features
- **Web Scraper**: Collects relevant job postings and industry trends.
- **Resume Analyzer**: Reviews resumes and provides improvement suggestions.
- **CV Writer**: Generates professional CVs based on user input.
- **Interview Helper**: Prepares users for interviews with tailored questions and feedback.
- **CrewAI Framework**: Utilizes CrewAI for coordinated task execution.
- **OpenAI API Integration**: Uses `gpt-4o-mini` for natural language processing.
- **Task Automation**: Automates repetitive processes to save time.
- **Customizable Agents**: Modify agent behavior to fit specific use cases.

## 🛠 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/kabirkohli123/Resume_AI_Agent.git
cd Resume_AI_Agent
```

### 2️⃣ Install Dependencies
Ensure you have the required Python packages installed:
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook in Google Colab
Upload the `crewai_agents.ipynb` file to [Google Colab](https://colab.research.google.com/) and execute the cells.

### 4️⃣ Set Up Environment Variables
Ensure your OpenAI API key is correctly configured:
```python
import os
os.environ["OPENAI_API_KEY"] = "your-api-key-here"
os.environ["OPENAI_MODEL_NAME"] = "gpt-4o-mini"
```

## 💡 AI Agents & Their Roles
This CrewAI team consists of four specialized agents working together:

### 1️⃣ **Web Scraper**
- Gathers job postings from various sources.
- Analyzes industry trends to provide insights.

### 2️⃣ **Resume Analyzer**
- Reviews resumes for structure, keywords, and clarity.
- Suggests improvements based on job descriptions.

### 3️⃣ **CV Writer**
- Generates a professional CV tailored to different industries.
- Formats and structures CVs for readability and impact.

### 4️⃣ **Interview Helper**
- Prepares users for interviews with industry-specific questions.
- Provides feedback on answers and suggests improvements.

## 🔧 Usage
1. Open the Colab notebook.
2. Follow the instructions in the notebook to initialize and run the CrewAI agents.
3. Input your resume details or job preferences and let the agents assist you.


## 🤝 Contributing
We welcome contributions! Feel free to submit issues or pull requests to improve this project.

## 👤 Author
[Kabir Kohli](https://github.com/kabirkohli123)

