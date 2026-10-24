# Negotiation homeworks

Two notebooks, same idea (Buyer / Seller / Mediator + exercises):

| Notebook | Backend |
|----------|---------|
| `negotiation_exercises.ipynb` | OpenAI GPT (cloud) |
| `local_negotiation_exercises.ipynb` | Ollama `llama3.2` (local) |

---

## 1. Install Python packages (once)

```powershell
cd "E:\MasterSem1\An2Sem1\MultiAgentic AI\homework1_negotiation"
python -m pip install -r requirements.txt
```

---

## 2. Homework 1 — GPT

1. Copy `.env.example` to `.env` and put your key in it:
   ```
   OPENAI_API_KEY=sk-...
   ```
2. Open and run:
   ```powershell
   python -m jupyter notebook negotiation_exercises.ipynb
   ```

Get a key at [platform.openai.com/api-keys](https://platform.openai.com/api-keys) (needs API billing credits).

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

## Tip

In Cursor you can also open either `.ipynb` and run cells with **Shift+Enter** (pick a Python kernel first).
