# AI Scrum Retrospective Assistant

An AI-powered workflow built with **n8n** that helps analyze Scrum Sprint Retrospective feedback and convert it into structured, actionable insights.

The automation uses AI to identify important themes, categorize feedback, assign priorities, generate summaries, and suggest practical action items. The results are automatically stored in Google Sheets for easy tracking and review.

---

## 🚀 Features

- Analyzes Sprint Retrospective feedback using AI
- Categorizes feedback into:
  - What Went Well
  - What Didn't Go Well
  - Blocker
  - Suggestion
- Identifies the main theme
- Assigns a priority:
  - High
  - Medium
  - Low
- Generates a clear summary
- Suggests a practical action item
- Uses structured JSON output
- Automatically stores results in Google Sheets

---

## 🛠️ Technologies Used

- **n8n** – Workflow automation
- **OpenRouter** – AI model integration
- **AI Agent** – Feedback analysis
- **Structured Output Parser** – Ensures consistent output format
- **Google Sheets** – Stores retrospective insights
- **JSON** – Structured AI output

---

# ⚙️ How the Workflow Works

The workflow follows these steps:

1. Sprint Retrospective feedback is provided as input.
2. The AI Agent analyzes the feedback.
3. The Structured Output Parser formats the AI response.
4. The workflow identifies:
   - Category
   - Theme
   - Priority
   - Summary
   - Action Item
5. The structured results are automatically sent to Google Sheets.

---

# 📊 Example Input

```text
The team experienced delays during the Sprint because some requirements were unclear. The Daily Scrums were helpful, but we discovered blockers too late. We should improve backlog refinement before the next Sprint.


🤖 Example AI Output
{
  "category": "suggestion",
  "theme": "Backlog Refinement and Early Blocker Identification",
  "priority": "high",
  "summary": "The team experienced delays due to unclear requirements and late identification of blockers. Daily Scrums were helpful, and the team suggested improving backlog refinement.",
  "action_item": "Improve backlog refinement before the next Sprint and discuss potential blockers earlier."
}
📸 Project Screenshots
n8n Workflow

AI Analysis Output

Google Sheets Results

🎯 Scrum Value

This project demonstrates how AI automation can support a Scrum Team by helping organize and analyze retrospective feedback.

It can help a Scrum Master identify recurring themes, surface important blockers, and turn retrospective discussions into actionable improvement ideas.

The automation is designed to support the Scrum Team's inspection and adaptation process by making retrospective insights easier to capture and review.

👨‍💻 Author

Ebube Allen Nwachukwu

Professional Scrum Master I (PSM I)
Front-End Developer
AI Automation Enthusiast

GitHub: https://github.com/EBUBENWACHUKWU
