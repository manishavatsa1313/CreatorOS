# 🚀 CreatorOS — AI Social Media Growth Operating System

An autonomous AI-powered content strategist that helps creators grow on Instagram, TikTok, and YouTube Shorts using Claude agents, MCP, and skills.

CreatorOS analyzes your past content, identifies what works, researches viral trends in your niche, and generates daily, weekly, and monthly growth strategies — along with SEO-optimized captions for every platform.

---

## ✨ Features

### 📊 Smart Content Audit
*   Analyze past posts (CSV, captions, metadata)
*   Identify:
    *   High-performing hooks
    *   Best posting times
    *   Engagement patterns
*   Generate actionable insights

### 🧠 AI Agent System
Built using Claude’s agent ecosystem:
*   **Strategist Agent** → Defines growth direction  
*   **Analytics Agent** → Audits performance  
*   **Trend Research Agent** → Finds viral patterns  
*   **SEO Writer Agent** → Generates captions & hooks  
*   **Planner Agent** → Creates content calendars  

### 🔥 Viral Content Engine
*   Breaks down viral videos in your niche
*   Extracts:
    *   Hook structures
    *   Storytelling formats
    *   Emotional triggers
*   Converts insights into repeatable content ideas

### ✍️ SEO-Optimized Captions (2026-ready)
Generates platform-specific content for:
*   Instagram
*   TikTok
*   YouTube Shorts

Includes:
*   Captions  
*   Hooks  
*   Hashtags  
*   Keyword tags  
*   CTAs  

### 📅 Growth Planning
*   Daily content ideas  
*   Weekly posting plan  
*   Monthly growth roadmap  

### 🔁 Continuous Learning
*   Stores creator profile in memory  
*   Adapts based on:
    *   Past performance  
    *   Audience behavior  
    *   Trend evolution  

---

## 🧩 Claude Features Used

| Feature | Usage |
| :--- | :--- |
| **MCP (Model Context Protocol)** | Connect YouTube, Reddit, Notion, Google Sheets |
| **Subagents** | Modular agents for each responsibility |
| **Skills** | Reusable workflows (captions, hooks, analysis) |
| **Memory** | Persistent creator profile |
| **Hooks** | Automated workflows |
| **Parallel Agents** | Run tasks simultaneously |
| **CLAUDE.md** | System orchestration |

---

## 📂 Project Structure

```text
.claude/
├── agents/
│   ├── strategist.md
│   ├── seo-writer.md
│   ├── analytics-auditor.md
│   ├── viral-researcher.md
│   └── planner.md
│
├── skills/
│   ├── generate-caption/
│   │   └── SKILL.md
│   ├── analyze-virality/
│   │   └── SKILL.md
│   └── optimize-hooks/
│       └── SKILL.md
│
├── hooks/
│   ├── after-upload.sh
│   └── daily-digest.sh
│
├── memory/
│   └── creator-profile.json
│
├── CLAUDE.md
└── .mcp.json
```
⚙️ Setup
1. Clone the repo
Bash
git clone https://github.com/your-username/creator-os.git
cd creator-os
2. Install dependencies
Bash
npm install
3. Configure MCP servers
Edit .mcp.json:

JSON
{
  "servers": [
    { "name": "youtube", "type": "api" },
    { "name": "reddit", "type": "api" },
    { "name": "notion", "type": "api" },
    { "name": "google-sheets", "type": "api" }
  ]
}
4. Run the app
Bash
npm run dev
📥 Input Examples
You can provide:

TikTok / Instagram analytics CSV

YouTube Shorts metadata

Past captions

Niche description (e.g., "travel + wellness")

📤 Example Output
🔍 Insights
Your storytelling videos outperform aesthetic edits by 42% in watch time.

📅 Weekly Plan
Mon: Emotional travel story

Tue: Routine / lifestyle POV

Wed: Day-in-the-life storytelling

Thu: Educational tip

Fri: Relatable humor

Sat: Aesthetic montage

Sun: Reflection / storytelling

✍️ TikTok Caption
Plaintext
training like a korean ajumma so i don’t travel like a tourist 😭
Hashtags: #travelroutine #koreatravel #realtravel #slowtravel #travelvlog

🎯 Viral Idea
POV: You stopped rushing and started actually experiencing your travels.

🔮 Roadmap
[ ] Thumbnail analyzer

[ ] Retention prediction

[ ] Auto-posting integrations

[ ] Creator niche clustering

[ ] Real-time trend alerts

🤝 Contributing
PRs are welcome! Feel free to improve:

Agent workflows

Caption quality

Integrations

UI/UX

📄 License
This project is licensed under the MIT License.

💡 Final Note
This is not just another AI wrapper. CreatorOS is an agent-driven system that learns, adapts, and evolves with your content — like a real growth team.
