# shamsAIdin
A Ollama AI Chatbot

This chat bot requires the system to have Ollama installed and uses the Llama 3 model.

To download, use the following link https://ollama.com/download

Check if it's installed by using the following command in the terminal:
ollama


https://github.com/ollama/ollama?tab=readme-ov-file
The project uses the Llama 3 model, refer to the above link for details on system specs. Run the following to install llama 3:

ollama pull llama3


Once this is complete, use the following to set up a virtual environment.

python -m venv chatbot
.\chatbot\Scripts\activate

pip install langchain langchain-ollama ollama


### To run the chatbot type python .\shamsAIdin\main.py 

Type "exit" to quit the chat bot
