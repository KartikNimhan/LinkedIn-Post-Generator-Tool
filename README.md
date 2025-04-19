# LinkedIn-Post-Generator-Tool


# 🧠 LinkedIn Post Generator Tool

A Generative AI-powered tool designed to create high-quality LinkedIn posts using a few simple inputs. It leverages LLMs via Groq's API and LangChain to generate professional content for job seekers, creators, and tech professionals.

---

## 🚀 Features

- ✨ Generate LinkedIn posts from minimal input
- 🧩 Few-shot prompting for high-context output
- ⚡ Fast, efficient inference using **Groq LLM API**
- 🛠 Modular codebase using LangChain and prompt engineering

---

## Below is the video for the implementation
https://github.com/user-attachments/assets/909e92d2-f01f-4b4b-bb1a-514ed01f4742

## 🛠 Tech Stack

- Python
- [LangChain](https://www.langchain.com/)
- [Groq API](https://console.groq.com) (for accessing LLMs)
- dotenv (for secure API key management)

---

## 🧪 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/KartikNimhan/LinkedIn-Post-Generator-Tool.git
   cd LinkedIn-Post-Generator-Tool
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Create a `.env` file** and add your API key:
   ```
   GROQ_API_KEY=your_groq_api_key_here
   ```

4. **Run the tool**
   ```bash
   python main.py
   ```

---

## 📂 File Structure

```
.
├── main.py               # Entry point
├── llm_helper.py         # Groq LLM setup
├── post_generator.py     # Prompt formatting & response
├── few_shot.py           # Sample prompts for better output
├── preprocess.py         # Input cleanup
├── .env                  # API keys (excluded via .gitignore)
```

---

## 🙏 Credits

This project was inspired by and built with help from the amazing [Codebasics](https://github.com/codebasics).  
**All rights reserved by the original authors.**

---

## 📄 License

MIT License – feel free to use, fork, or contribute!
```

---

