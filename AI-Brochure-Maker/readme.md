# AI Brochure Maker

The **AI Brochure Maker** is a Jupyter Notebook project that automates the creation of professional company brochures. It scrapes and analyzes website content, identifies the most relevant information (e.g., About, Company, Careers pages), and generates a polished brochure draft using a Large Language Model (LLM).

---

## Impact

This project demonstrates the power of combining web scraping, intelligent link filtering, and **Al-driven** content generation to deliver ready-to-use marketing assets. It shows how **businesses can reduce costs, speed up content creation, and maintain consistent messaging** with minimal human input.

---

## ✨ Features

- **Website Scraping**: Fetches company web pages with proper request headers.
- **Content Filtering**: Identifies relevant links such as *About*, *Company*, or *Careers*.
- **AI-Powered Summarization**: Uses an LLM (via OpenAI API) to condense content into brochure-ready text.
- **Structured Output**: Formats results as structured JSON and text for brochure sections.
- **Interactive Notebook**: Allows step-by-step brochure creation and refinement.

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebooks**
- **Libraries**:
  - `requests` – fetch web content
  - `dotenv` – manage API keys securely
  - `openai` – connect to LLM for summarization
  - `BeautifulSoup` – optional, for HTML parsing

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd AI-Brochure_Maker
```

### 2. Set up environment
```bash
pip install -r requirements.txt
```

### 3. Configure API Key
Create a `.env` file and add your OpenAI API key:
```
OPENAI_API_KEY=your_api_key_here
```

### 4. Run the notebook
```bash
jupyter notebook "AI-Brochure_Maker.ipynb"
```

---

## 📖 Usage

1. Input the company website URL.
2. The scraper extracts relevant pages and sections.
3. The AI model generates brochure text (About, Services, Careers, etc.).
4. Review and refine content interactively within the notebook.

---

## 📂 Project Structure

```
AI-Brochure_Maker.ipynb   # Main notebook with scraping and brochure generation logic
requirements.txt          # Dependencies (to be created)
README.md                 # Documentation (this file)
.env                      # API key storage (not tracked in git)
```

---

## ⚡ Example Workflow

- Input: `https://examplecompany.com`
- Extracted: About Us, Services, Careers pages
- Output: *A company brochure summarizing mission, values, offerings, and opportunities.*

---

## 🔮 Future Improvements

- Add image/logo scraping for branding.
- Export brochures as **PDF** or **Word documents**.
- Support multi-language brochure generation.
- Build a lightweight web UI for non-technical users.

---

## 📜 License

This project is provided under the MIT License.

