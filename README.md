# Medical-bot
An AI medical chatbot using LLMs, LangChain, and Pinecone, with a Flask backend deployed on AWS.

## Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone

## COMMITS

### 1. Creating conda environment
```bash
conda create -n medibot pyhton=3.10 -y
```

```bash
conda activate medibot
```

### 2. Install requirements
```bash
pip install -r requirements.txt
```

### 3. Create .env file
```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
python app.py
```

```bash
open up localhost:
```
##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

##  Author

**SHREEYA P S** - [shreeyashree-65](https://github.com/shreeyashree-65)
