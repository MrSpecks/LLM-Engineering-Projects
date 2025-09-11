# AI Q&A Bot

The **AI Q&A Bot** is a Jupyter Notebook project that allows you to interactively ask technical or general questions and receive AI-generated answers in real-time. It leverages OpenAI's GPT models with **streaming output**, making responses feel conversational and dynamic inside Jupyter.

---

## ✨ Features

- **Interactive Q&A**: Ask questions directly in the notebook and receive clear, step-by-step answers.
- **Streaming Responses**: Displays answers as they are generated, similar to live chat.
- **Customizable System Prompt**: Tailor the assistant's personality (e.g., technical helper, explainer).
- **Markdown Rendering**: Outputs answers in nicely formatted Markdown for readability.
- **Secure API Integration**: Loads API keys via `.env` to avoid hardcoding sensitive info.

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebooks**
- **Libraries**:
  - `openai` – for GPT model interaction
  - `dotenv` – load API keys securely
  - `requests`, `json`, `typing` – utility modules
  - `IPython.display` – for streaming and Markdown rendering

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd AI-Q&A-Bot
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Set up your API key
Create a `.env` file with your OpenAI key:
```
OPENAI_API_KEY=your_api_key_here
```

### 4. Run the notebook
```bash
jupyter notebook "AI-Q&A-Bot.ipynb"
```

---

## 📖 Usage

1. Edit the `question` variable in the notebook to whatever you'd like to ask.
2. Run the cell to send the question to the model.
3. Watch as the model streams back its response in Markdown.
4. Refine or ask new questions iteratively.

---

## 📂 Project Structure

```
AI-Q&A-Bot.ipynb          # Main notebook with Q&A logic
requirements.txt          # Dependencies (to be created)
README.md                 # Documentation (this file)
.env                      # API key storage (not tracked in git)
```

---

## ⚡ Example Workflow

- Input: *"Please explain what this code does and why: yield from {book.get('author') for book in books if book.get('author')}"*
- Output: *Explanation of Python generator expression and yield mechanics.*

---

## 🔮 Future Improvements

- Add support for context-based Q&A (conversation memory).
- Integrate multiple model options (OpenAI, local LLMs).
- Build a lightweight web interface for real-time use.
- Export Q&A sessions as Markdown or PDF for documentation.

---

## 📜 License

This project is provided under the MIT License.

