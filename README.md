# 🐦 Tweet Agent

This project contains a Jupyter Notebook that performs automated Twitter analysis using OpenAI’s GPT models. The notebook, `Tweet_Agent.ipynb`, allows users to extract tweets from a Twitter profile and generate summaries, engagement tips, and content ideas using AI.

---

## 🚀 Features

- Extracts latest tweets from any public Twitter handle
- Uses OpenAI GPT to:
  - Summarize tweet content
  - Suggest engagement strategies
  - Provide content ideas
- Easy to customize and extend

---

## 📂 Files

| File                  | Description                                      |
|-----------------------|--------------------------------------------------|
| `Tweet_Agent.ipynb`   | Main notebook with full code and documentation   |
| `requirements.txt`    | List of required Python libraries (see below)    |
| `.gitignore`          | Files ignored by Git (checkpoints, cache, etc.)  |

---

## 📦 Installation

### ✅ 1. Clone the Repository

```bash
git clone https://github.com/Pujitha-user/Tweet_Agent_Project.git
cd Tweet_Agent_Project
```

### ✅ 2. Install Dependencies

You can install the required Python packages with:

```bash
pip install -r requirements.txt
```

---

## 💡 How to Use

1. Launch Jupyter:

```bash
jupyter notebook
```

2. Open `Tweet_Agent.ipynb`
3. Replace the placeholder `TWITTER_HANDLE` and `OPENAI_API_KEY`
4. Run all cells to:
   - Fetch tweets
   - Process them with GPT
   - View the AI-generated output (summaries, tips, etc.)

---

## 🧠 Technologies Used

- **Python**
- **OpenAI GPT (via `openai` API)**
- **Tweepy** for accessing Twitter data
- **Pandas** for data processing

---

## ⚠️ Disclaimer

- This tool uses OpenAI's API and will incur costs based on usage.
- You must have access to an OpenAI API key and Twitter developer credentials to use this notebook fully.

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.

---

## 🙌 Acknowledgments

Thanks to OpenAI and the Python open-source community for the amazing tools that make this project possible.
