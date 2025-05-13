# 🤖 Building AI Browser Agents

Welcome to the **AI Browser Agents** project! This repository contains Jupyter notebooks, code implementations, and notes inspired by the [Building AI Browser Agents](https://learn.deeplearning.ai/courses/building-ai-browser-agents/lesson/ee5yw/introduction) course by **DeepLearning.AI**, created in collaboration with **AGI Inc.** and taught by **Div Garg** and **Naman Garg**.

This course and project explore how to create **autonomous agents** capable of interacting with websites — from navigating the DOM to filling forms and summarizing content — using powerful decision-making frameworks like **Monte Carlo Tree Search (MCTS)** and **AgentQ**.

---

## 📚 What You’ll Learn

- **Understand Web Agents:** Learn the fundamentals of browser-based AI agents, including what they are, how they work, and their architectural components.
- **Build Smart Agents:** Create agents that can navigate, extract data, fill forms, and interact with real websites.
- **Explore AgentQ:** Learn how to build self-correcting agents using:
  - **Monte Carlo Tree Search (MCTS)**
  - **Self-critique mechanism**
  - **Direct Preference Optimization (DPO)**
- **Develop End-to-End Solutions:** Build agents that handle tasks such as:
  - Finding and summarizing webpages
  - Scraping course data from sites like DeepLearning.AI
  - Automating form-filling and sign-up processes
- **Understand Real-World Constraints:** Dive into the challenges and future of AI agents, including action explosion, error handling, and long-term memory planning.

---

## 🧠 Project Content

| File | Description |
|------|-------------|
| `📘 Building_AI_Browser_Agents_Notes.docx` | Full theory notes covering agent design, planning, rewards, DOM exploration, and the AgentQ framework |
| `📓 MCTS_and_AgentQ.ipynb` | Implementation of browser agents using MCTS and AgentQ; includes DOM tree traversal and simulated environments |
| `📓 Building_a_Simple_Web_Agent.ipynb` | A beginner-friendly notebook to build an agent that interacts with a real webpage (e.g., scraping or form filling) |

---

## 🛠 Technologies Used

- **Python** (Jupyter Notebooks)
- **Playwright / Puppeteer** – for browser automation
- **BeautifulSoup4** – for parsing HTML/DOM
- **NetworkX** – for tree/graph structures in MCTS
- **LangChain (optional)** – for LLM-style reasoning
- **AgentQ Framework** – combining MCTS + DPO + Self-critique

---

## 🚀 Getting Started

### Clone this repository:
```bash
git clone https://github.com/your-username/ai-browser-agents.git
cd ai-browser-agents
```
## Install dependencies:

### Make sure you have Python 3.8+ installed.
```bash
pip install -r requirements.txt
```
### Launch the notebooks:
```bash
jupyter notebook
```

## 🎯 Sample Use-Cases
1) 🔍 Scraping Course Info: Scrape and structure course recommendations from DeepLearning.AI
2) 📝 Form Submission: Automate newsletter sign-ups or contact forms
3) 🧠 Autonomous Browsing: Use MCTS to explore websites intelligently and take goal-directed actions

---


## 🔍 AgentQ in Action
AgentQ is a modular framework enabling AI agents to self-correct and learn preferences using:

🧭 MCTS (Monte Carlo Tree Search): Simulate and explore possible future actions
🪞 Self-Critique: Reflect on previous mistakes and improve behavior
🎯 DPO (Direct Preference Optimization): Optimize outcomes using feedback-based learning
➡️ The MCTS + DPO combo helps agents intelligently choose the best action among thousands of dynamic web elements.

---

## 📈 Project Vision
This project represents an early step toward building AI that can navigate the web like humans.
Future directions:

🧠 Integrate with LLMs for better natural language reasoning
🧾 Add memory modules for multi-session task handling
👥 Train using RLHF (Reinforcement Learning with Human Feedback)

---

## 🤝 Credits
DeepLearning.AI – Building AI Browser Agents
Div Garg and Naman Garg – Co-founders of AGI Inc.
The AGI Inc. team – For pioneering work in browser automation and intelligent web agents

---

## 📬 License
This project is for educational and research purposes only.
For commercial use, please refer to the licensing terms of DeepLearning.AI and AGI Inc.

---

## 💬 Contact
For discussions, feedback, or collaboration:
- Open an issue on this repo
- Or connect via LinkedIn- https://www.linkedin.com/in/sagar-shahari-703b84257/

---

## ⭐ If you found this project useful...
Give it a star ⭐ and share it with others interested in the future of autonomous web agents!


