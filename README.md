# Virtual Teaching Assistant (Virtual TA)

A Virtual Teaching Assistant (Virtual TA) project designed to assist students with programming-related questions, focusing on guiding them toward solutions rather than providing direct answers.

---

## 🚀 Project Phases

### ✅ Phase 1: Input Relatedness Detection (Completed)
- Developed a system to determine whether the **user's question is related to the given code or error message**.
- Used machine learning techniques to **classify input pairs** (code + error + question) as *related* or *not related*.
- Fine-tuned the model using a **custom dataset** sourced from Stack Overflow, Kaggle, and other error logs.
- Integrated the model into a **FastAPI backend**, exposing an API for relatedness prediction.

### 🛠️ Phase 2: Optimized Prompt Generation (In Progress)
- Designing logic to **generate optimized prompts** only when the input is marked as *related*.
- Ensuring that the prompts guide the LLM to give a **method/approach**, not the direct answer or complete code.
- Experimenting with **few-shot learning** and **prompt engineering** techniques to improve response quality.

### 🔜 Phase 3: LLM Integration for Guided Help (Planned)
- Connect to an LLM (e.g., GPT-4, Claude, or open-source models) via API.
- Use optimized prompts to extract **step-by-step guidance or hints** rather than full answers.
- Build a feedback system to **refine LLM outputs** over time based on user satisfaction.

### 📈 Future Enhancements
- Develop a **dashboard** for students and tutors to track learning progress and common issues.
- Extend support to **multiple domains and languages**, not just Python or programming.
- Incorporate **reinforcement from user feedback** to enhance relatedness classification and prompt effectiveness.

---

## 🖼️ Virtual TA - User Interface Preview

![Virtual TA UI](https://github.com/Virenbhalgamiya/Virtual-Teaching-Assistant/blob/main/virtual-ta-ui.png)

---

