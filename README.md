# MentalHealthProject

DrPsychoAI is a Python-based voice assistant that utilizes spaCy for natural language processing. It can perform actions such as searching the web and fetching weather reports based on voice commands. Additionally, DrPsychoAI can help you understand your mental health by engaging in conversations about your mood and day.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/DrPsychoAI.git
    cd DrPsychoAI
    ```

2. Install required packages:
    ```bash
    pip install spacy SpeechRecognition
    python -m spacy download en_core_web_sm
    ```

## Usage

Run the script:
```bash
python main.py



Voice Commands

To search the web: Say "search for [query]".

Example: "search for Python programming tutorials".
DrPsychoAI will open your default web browser and perform a Google search for your query.
To get a weather report: Say "weather report".

DrPsychoAI will open your default web browser and navigate to Weather.com.
To stop the assistant: Say "stop listening".

DrPsychoAI will stop listening and terminate the session.
To talk about your day or mood: Simply mention how you are feeling.

Example: "I am feeling sad" or "I had a great day".
DrPsychoAI will respond to your statements and engage in a conversation to help you understand and reflect on your mental health. For example:
If you say "I am feeling sad", DrPsychoAI might respond with "I'm sorry to hear that you're feeling sad. How was your day?".
If you say "I had a great day", DrPsychoAI might respond with "That's great to hear! Could you tell me more about your day?".
Steps to Talk About Your Day or Mood
Start the assistant:

Run the script by typing python main.py in your terminal.
Wait for the prompt:

DrPsychoAI will indicate that it is listening.
Speak your mood or daily experience:

Mention your feelings or describe your day. For example, you can say "I am feeling happy" or "I had a stressful day".
Engage in conversation:

DrPsychoAI will respond to your statements and ask follow-up questions to help you reflect on your feelings.