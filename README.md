# 🤖 CEH-Assistant

An AI-powered assistant designed to help learners in the **Certified Ethical Hacker (CEH)** course by providing instant support for lab issues, troubleshooting guidance, and step-by-step help.

---

## 🎯 Project Purpose

CEH-Assistant reduces user support ticket load by acting as a virtual agent trained on internal CEH documentation. It:
- Identifies the issue based on module/lab/step
- Provides smart suggestions and solutions
- Integrates AI (LLMs) to enhance troubleshooting accuracy

---

## 🧠 Features

- 🧾 Understands module, lab, and step context
- 💬 AI-powered support responses using structured prompts
- 🧰 Can be trained on CEH PDFs and lab guides
- ⚙️ Built to integrate with platforms like Chipp.ai

---

## 🚀 How It Works

1. User selects **Module → Lab → Step** where they are facing an issue
2. CEH-Assistant asks diagnostic questions (if needed)
3. It uses a custom prompt to respond with suggestions, explanations, and fixes
4. Future versions include automatic ticket tagging & LLM finetuning

---

## 🛠️ Tech Stack

- 🧠 **OpenAI / Chipp.ai**
- 📄 Markdown / Prompt Engineering
- 🧪 Cyber Lab Documentation
- 🖥️ Integration-ready for CEH Lab Platforms

---

## 📸 Demo Walkthrough – Screenshots

Below are a few screenshots demonstrating the **CEH-Assistant Demo** in action. These showcase how the assistant interacts with users to troubleshoot issues based on module, lab, and step information.

🧪 Since this is a **demo version**, it includes only **5 sample modules** from the CEH curriculum. These modules are chosen purely for demonstrating functionality and do **not** contain any internal or confidential EC-Council content.

> 🔐 This version is built solely for portfolio and proof-of-concept purposes.

>
> ![image](https://github.com/user-attachments/assets/b8adc200-3aa7-4934-b2ac-59cbaa43ecc9)
>
>![image](https://github.com/user-attachments/assets/7dd6cf52-b0ba-4343-93df-4a0cf3e55be9)
>
> ![image](https://github.com/user-attachments/assets/87c6a787-6a43-4b4a-8d8a-4ca26e054766)
>
> ![image](https://github.com/user-attachments/assets/05e0052e-7f8e-42e9-857b-24d85fc78e92)





---

## 🧩 Folder Structure

```bash
ceh-assistant/
│
├── prompts/                 # All prompt variations
├── reference_docs/          # CEH lab PDFs, guides (non-confidential)
├── README.md                # This file
└── ai_agent_config/         # Agent configuration (Chipp.ai or custom)
