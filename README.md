# Negotiation homeworks


| Notebook | Backend |
|----------|---------|
| `negotiation_exercises.ipynb` | OpenAI GPT 5-4 |
| `local_negotiation_exercises.ipynb` | Ollama `llama3.2` (local) |

---

## 1. Install Python packages
```powershell
cd "E:\MasterSem1\An2Sem1\MultiAgentic AI\homework1_negotiation"
python -m pip install -r requirements.txt
```

---

## 2. Homework 1 — GPT tokens

1. Setup .env file
   ```
   OPENAI_API_KEY=sk-... 
   ```
2. Open and run:
   ```
   python -m jupyter notebook negotiation_exercises.ipynb
   ```

   Get a key from [platform.openai.com/api-keys](https://platform.openai.com/api-keys) (needs API billing credits... :( )
---

## 3. Homework 2 — local Ollama

1. Install Ollama from [ollama.com](https://ollama.com) and start it.
2. Pull the model:
   ```powershell
   ollama pull llama3.2
   ```
3. Open and run:
   ```powershell
   python -m jupyter notebook local_negotiation_exercises.ipynb
   ```

No API key needed.

---
