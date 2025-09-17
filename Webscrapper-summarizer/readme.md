# Website Scraper & Summarizer

This project is a **Jupyter Notebook application** that allows you to scrape the contents of a website and automatically generate a concise summary using a Large Language Model (LLM). It combines web scraping techniques with natural language processing to produce easy-to-read summaries of online content.

---

## Impact:

- Saves time & effort: Automates the tedious process of reading and filtering through entire websites.
- Boosts decision-making: Provides executives, analysts, and researchers with quick, digestible takeaways.
- Privacy-first Al: Runs on local infrastructure (via Ollama), ensuring sensitive data never leaves the system.
- Reusable & scalable: Can be extended into applications like competitive intelligence, market research, and content monitoring dashboards.

---

## ✨ Features

- **Web Scraping**: Uses `requests` and `BeautifulSoup` to fetch and parse website content.
- **Custom Website Object**: Stores URL, title, and cleaned text.
- **AI-Powered Summarization**: Uses an LLM (via the OpenAI API / local Ollama endpoint) to summarize website contents.
- **Markdown Output**: Displays results in clean Markdown format directly in Jupyter.
- **Noise Filtering**: Ignores navigation or repetitive elements, focusing only on meaningful content.

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebooks**
- **Libraries**:
  - `requests` – for HTTP requests
  - `BeautifulSoup` – for HTML parsing
  - `openai` – for LLM integration (configurable for local Ollama)
  - `IPython.display` – for rendering Markdown summaries

---

## 🚀 Getting Started

### 1. Clone this repository
```bash
git clone <your-repo-url>
cd website-summarizer
```

### 2. Set up environment
```bash
pip install -r requirements.txt
```

### 3. Configure API
- If using **OpenAI**, add your API key to the notebook or as an environment variable.
- If using **Ollama**, ensure the service is running locally at `http://localhost:11434/v1` and update the `MODEL` variable as needed.

### 4. Run the notebook
Open the notebook in Jupyter and execute the cells step-by-step:
```bash
jupyter notebook "Website Summarizer.ipynb"
```

---

## 📖 Usage

1. Provide the target website URL.
2. The scraper fetches and cleans the page text.
3. The LLM generates a concise summary.
4. The result is displayed in Markdown inside the notebook.

---

## 📂 Project Structure

```
Website Summarizer.ipynb   # Main notebook with code and instructions
requirements.txt           # Python dependencies (to be created)
README.md                  # Project documentation (this file)
```

---

## ⚡ Example Workflow

- Input: `https://example.com/news`
- Scraped: Page title + body content
- Output: *"This news article announces..."* (clean summary in Markdown)

---

## 🔮 Future Improvements

- Add support for batch summarization of multiple URLs.
- Extend to PDFs or text documents.
- Export summaries to a database or CSV.
- Add a web UI for easier use outside Jupyter.

---

## 📜 License

This project is provided under the MIT License.

