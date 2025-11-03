# 🧠 Code Review Assistant

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://codereviewassistant.streamlit.app/)

[**Code Review Assistant**](https://codereviewassistant.streamlit.app/) is an AI-powered app that helps software developers improve their code quality by leveraging OpenAI’s large language models.  
It analyzes code directly from GitHub repositories and provides intelligent, human-like feedback to enhance readability, performance, and maintainability.

---

## 🚀 Features

- 🔍 **Automated Code Analysis** — Quickly reviews code from any public GitHub repository.  
- 💡 **Smart AI Recommendations** — Get improvement suggestions powered by OpenAI’s LLMs.  
- 🌳 **Interactive File Tree** — Select which files to analyze before review.  
- 🔒 **Secure API Integration** — Uses your own OpenAI API key safely within the app.  
- ⚙️ **Custom File Extension Support** — Analyze `.py`, `.js`, `.ts`, `.java`, etc.  
- 🧠 **Token Management** — Optimized with `tiktoken` for better model input handling.  
- 🪶 **Streamlit UI** — Clean, lightweight, and interactive interface.

---

## 🧭 How to Use (Live App)

1. **Open the App**  
   👉 Visit [https://codereviewassistant.streamlit.app/](https://codereviewassistant.streamlit.app/)

2. **Enter Repository URL**  
   Paste the GitHub repository link you want to analyze.

3. **Add Your OpenAI API Key**  
   You can get one from your [OpenAI Dashboard](https://platform.openai.com/account/api-keys).

4. **Choose File Extensions**  
   Select which file types to include (e.g., `.py`, `.js`, `.ts`) or add custom ones.

5. **Clone the Repository**  
   Click **“Clone Repository”** — the app will fetch files and display them in a tree view.

6. **Pick Files to Analyze**  
   Select the files you want to analyze, then click **“Analyze Files”**.

7. **Review AI Recommendations**  
   The app displays structured insights, explanations, and suggested improvements.

🧩 Tech Stack

| Component                   | Technology Used                                                          |
| --------------------------- | ------------------------------------------------------------------------ |
| **Language**                | Python 3.11                                                              |
| **Framework**               | [Streamlit](https://streamlit.io/)                                       |
| **Dependency Manager**      | [Poetry](https://python-poetry.org/)                                     |
| **AI Integration**          | [OpenAI API](https://platform.openai.com/)                               |
| **Git Repository Handling** | [GitPython](https://github.com/gitpython-developers/GitPython)           |
| **Token Handling**          | [tiktoken](https://github.com/openai/tiktoken)                           |
| **Code Formatting (Dev)**   | Black, isort, flake8                                                     |
| **Tree File Selector**      | [streamlit-tree-select](https://pypi.org/project/streamlit-tree-select/) |
| **Numerical Support**       | numpy                                                                    |
| **Frontend**                | Streamlit Components (custom UI widgets)                                 |



---

