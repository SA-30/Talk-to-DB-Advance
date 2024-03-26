# Talk to Database

This web app lets you communicate with the database directly without requiring knowledge of query languages like SQL.

## Watch it live 🟢
🤗 [Live_app](https://huggingface.co/spaces/Asstrofic/Talk-to-DB)
- You can talk to default database

<img src="/ss/db1.PNG" alt="UI" width="700">

- Obtained answers

<img src="/ss/d1.PNG" alt="UI" width="700">
<img src="/ss/d2.PNG" alt="UI" width="700">

🅰 [Live_app_Advance](https://huggingface.co/spaces/Asstrofic/Talk-to-DB-Advance)
- You can create your own database and talk to it

<img src="/ss/db3.PNG" alt="UI" width="700">

## How to Clone It
- Dm for private repo & follow below

1) **Create a virtual environment:**
```bash
conda create -p venv python=3.9 -y
```

2) **Install the requirements libraries**
- Run below command to install all required libraries
```bash
pip install -r requirements.txt
```

```bash
streamlit
google-generativeai
python-dotenv
langchain
PyPDF2
chromadb
faiss-cpu
pdf2image
```

5) **Edit `.env.example`**
- Rename `.env.example` to `.env` and put your google api key

5) **Run**
- Run the sql file
```bash 
python sql.py
```

6) **Run**
```bash 
streamlit run app.py
```
