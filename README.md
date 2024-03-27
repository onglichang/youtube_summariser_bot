# youtube_summariser_bot
A chatbot that helps you to summarise Youtube videos using LLMs

## Requirements
1. Python 3
2. Langchain library
3. OpenAI API Key

## How to use
1. Clone repo 
```
git clone https://github.com/onglichang/youtube_summariser_bot.git
```
2. Create a python virtual environment 
```
cd youtube_summariser_bot
python3 -m venv env
source env/bin/activate
```
3. Install all required dependencies
```
pip install -r requirements.txt
```
4. Create a .env file in root directory and add OpenAI API key
```
OPENAI_API_KEY="api_key"
```
5. Run youtube_chatbot.ipynb jupyter notebook, you will get a locally hosted app that you can interact with. Input is Youtube url, output is summary
