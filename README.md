# PDF-Reader-Using-Gemini

### In this project we are going to build a GENAI project where we use gemini pro and faiss vectore store to store vectors and GoogleGenerativeAIEmbeddings and streamlit to easy user interface.

# Steps:
1. Get the pdf docs from ui and append it into one variable text and return text
2. After that we will split it into chunks using recursivecharactersplitter and return chunks.
3. After that we will convert it into vectors by using vector embeddings we used 
   GoogleGenerativeAIEmbeddings and store it into faiss vector store from texts and get the indexes and store it in local 
4. Next we need to get the conversational chain by using ChatGoogleGenerativeAI and giving prompt as     needed and load_qa_chain by giving model and prompt and return chain 
5. The above all steps are like preprocessing steps of model and , now we take user input and load index which are stored local and do similarity search on user question and get the chain of respone which we get from conversational chain.

# Get API key from Aistudio
```
GOOGLE_API_KEY ="need to get from https://aistudio.google.com/app/apikey"
```
# Conda virtual environment creation 
```
conda create -p venv python==3.10 -y
conda activate venv
```
basic git commands
```
git init 
git add .
git commit -m "message"
git push -u origin main
```



