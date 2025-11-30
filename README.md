
# This is the project name. It matches the repository name and gives a clear identity.

This tool will analyze posts of a LinkedIn influencer and help them create new posts based on the writing style in their old posts.
# This short intro explains the purpose of the project in one line.

<img src="resources/tool.jpg"/> **# This is the tool's screenshot. Visuals help users understand the UI quickly.**

Let’s say Mohan is a LinkedIn influencer…
**# This example explains the use case in a real-world scenario.

It helps users understand why and how this tool is useful.**
Technical Architecture

**# This section explains how the system works internally.

It is important for technical users and for platforms like Kaggle.**
<img src="resources/architecture.jpg"/> **# This image shows the pipeline of the application. Visual architecture always improves clarity.**

Stage 1: Collect LinkedIn posts and extract Topic, Language, Length, etc.
# Stage 1 describes data extraction and analysis steps.

Stage 2: Generate new posts using topic/language/length + few-shot examples.
# Stage 2 explains how the LLM creates new content using old posts for style matching.

Set-up

**# This section explains how to run the project.

Very important for anyone who wants to replicate your results or run the app.**

Get your Groq API key from: https://console.groq.com/keys

Update .env with:

GROQ_API_KEY=your_api_key_here


# LLM will not work without this API key.

Install the dependencies:

pip install -r requirements.txt


# Installs all required Python libraries.

Run the Streamlit app:

streamlit run main.py


# This command starts the web application.
