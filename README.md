# Medical-Chatbot

# How to run?
### STEPS:

Clone the repository

'''bash
https://github.com/Dikendra-123/Chatbot.git
'''

###Step-1- Create conda environment after opening repo

'''bash
conda create -n Chatbot python=3.10 -y
'''

'''bash
conda activate Chatbot
'''

###Step 2- install the requirements

'''bash
pip install -r requirements.txt
'''

### Create a `.env` file in the root directory and add your Pinecone & OpenAI credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_BASE= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python index_store.py
```

```bash
# Finally, run the following command
python app.py
```

Now,
```bash
Open up localhost:
```

### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone
