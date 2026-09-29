# CysecPRO

Cybersecurity demo project exploring prompt injection, RAG poisoning, and MINJA-style memory poisoning with local LLMs.

## Project Contents

- `app.py` - Streamlit demo containing the prompt-injection, RAG, and MINJA experiment report modes.
- `MINJA/` - Adapted local MINJA memory-poisoning experiment using Qwen3 and Ollama.

## Run the Streamlit App

```powershell
streamlit run app.py
```

## Run the mode 8 demo            

- Run the Mode 8 MINJA Experiment with cosine similarity from the QA folder:
- cd MINJA\QA
- python main.py --data_path .\data\test\nutrition_test.csv --core_model qwen3:8b
                
The logs that we used for the report can be found in MINJA/QA/logs/