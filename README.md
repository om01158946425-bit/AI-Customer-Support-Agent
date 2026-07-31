# 🤖 AI Customer Support Agent (n8n + Google Gemini + Google Sheets)

An intelligent customer support chatbot built with n8n automation.

## 🚀 Features

- Answers FAQ questions from Google Sheets
- Uses Google Gemini AI when no FAQ answer exists
- Automatically saves new questions and AI responses
- Maintains a growing knowledge base
- Simple Memory for conversational context
- Built completely with n8n (low-code)

---

## 🛠 Tech Stack

- n8n
- Google Gemini API
- Google Sheets
- AI Agent
- Google Gemini Chat Model
- Filter Node
- Chat Trigger

---

## Workflow

1. User sends a message.
2. Search Google Sheets FAQ.
3. If found → return FAQ answer.
4. If not found → ask Gemini AI.
5. Save new Question & Answer into Google Sheets.
6. Return AI response.

---

## Project Structure

```
workflow/
screenshots/
README.md
```

---


## Author

Omar Mohamed Abdel Hamid

LinkedIn: https://www.linkedin.com/in/omar-mohamed- b17731343?utm_source=share_via&utm_content=profile&utm_medium=member_android

GitHub: https://github.com/om01158946425-bit
