<style>
/* Responsive container */
.doc-container {
  max-width: 900px;
  margin: auto;
  padding: 2rem;
  border-radius: 12px;
  font-family: 'Segoe UI', Roboto, sans-serif;
  line-height: 1.65;
}

/* Blockquote styles (applies to both themes) */
.doc-container blockquote {
  margin: 1.5rem 0;
  padding: 1rem 1.25rem;
  border-left: 4px solid;
  border-radius: 8px;
  font-style: normal;
}

/* Light theme */
@media (prefers-color-scheme: light) {
  .doc-container {
    background-color: #f5f5f5; /* neutral light gray */
    color: #1e293b; /* dark slate */
  }
  .doc-container h1, .doc-container h2, .doc-container h3 {
    color: #0f172a;
  }
  .doc-container a {
    color: #2563eb;
  }
  .doc-container blockquote {
    background-color: #e0f2fe; /* light blue tint */
    border-color: #3b82f6; /* accent blue */
    color: #1e3a8a; /* dark blue text */
  }
}

/* Dark theme */
@media (prefers-color-scheme: dark) {
  .doc-container {
    background-color: #0f172a; /* deep slate blue-black */
    color: #e2e8f0; /* light slate */
  }
  .doc-container h1, .doc-container h2, .doc-container h3 {
    color: #f1f5f9;
  }
  .doc-container a {
    color: #60a5fa;
  }
  .doc-container blockquote {
    background-color: #1e293b; /* subtle dark slate */
    border-color: #60a5fa; /* accent blue */
    color: #e2e8f0; /* readable light slate */
  }
}
</style>

<div class="doc-container">

<div align="center" style="margin-bottom: 2rem;">
  <h1>✨ Welcome to Agent Vector ✨</h1>
  <p><strong>The visual platform for building powerful AI agents and automations</strong></p>
</div>

Welcome! You're about to discover a new way to automate your work and bring your ideas to life.  
**Agent Vector** is a visual workflow platform that lets you connect apps, data, and AI models to handle complex tasks — without writing a single line of code.

Whether you want to summarize reports, manage customer inquiries, or build a fully autonomous AI agent that can use tools, you've come to the right place.

---

## 🌟 What is Agent Vector?

**Agent Vector** is a platform where you build automations by visually connecting blocks on a canvas. Each block, or **node**, is a specific action. You connect them to create a "flow" of work that runs automatically.

It's designed from the ground up for the new era of AI. Instead of just simple, one-step automations, you can build sophisticated **AI Agents** that can reason, make decisions, and use tools to interact with other software — just like a human assistant.

> ### 🎨 Visual First  
> No code required. If you can draw a flowchart, you can build an automation.  
> Our intuitive drag-and-drop canvas is your command center.  

> ### 🤖 Agent-Based AI  
> Go beyond simple prompts. Build intelligent agents that can use tools, process documents, and complete multi-step tasks autonomously.  

> ### 🔌 Connect Anything  
> With a growing library of tools and connectors, you can integrate with your favorite apps, databases, and services to create end-to-end automations.  

---

## 🚀 Your First Project: 5-Minute Quickstart

The best way to learn is by doing. Our step-by-step guide will walk you through building your first automation:  
**an AI agent that can read a document and answer your questions about it.**

👉 **[Start the Tutorial: Build a Document Q&A Agent →](use_cases/rag_use_case.md)**

---

## 🧰 Explore the Building Blocks

Agent Vector provides three types of nodes to build your workflows.  
Get familiar with your toolkit by exploring the documentation for each component.

### 🚦 Utils  
*Control the logic and flow of your workflow.*

- [AiAgent](utils/ai_agent.md)  
- [LLM](utils/llm.md)  
- [Start](utils/start.md)  
- [Schedule Trigger](utils/schedule_trigger.md)  
- [Condition](utils/condition.md)  
- [Output](utils/output.md)  

### ⚙️ Tools  
*Perform actions like reading files, accessing data, and processing information.*

- [Upload Tool](tools/upload_tool.md)  
- [Web Tool](tools/web_tool.md)  
- [PDF Tool](tools/pdf_tool.md)  
- [Text Tool](tools/text_tool.md)  
- [Markdown Tool](tools/markdown_tool.md)  
- [File Read Tool](tools/file_read_tool.md)  
- [Code Tool](tools/code_tool.md)  
- [Image Tool](tools/image_tool.md)  
- [Scheduling Tool](tools/scheduling_tool.md)  
- [Factory Scheduling Tool](tools/factory_scheduling_tool.md)  
- [Postgres Database Tool](tools/postgres_database_tool.md)  
- [Mongo Database Tool](tools/mongo_database_tool.md)  
- [SQLite Database Tool](tools/sqlite_database_tool.md)  
- [Aurora Database Tool](tools/aurora_database_tool.md)  

### 🔌 Connectors  
*Connect your workflow to external apps and services.*

- [Microsoft Teams](connectors/microsoft_teams.md)  
- [Outlook](connectors/outlook.md)  
- [SharePoint](connectors/sharepoint.md)  

---

## 📖 Foundational Concepts  

To get the most out of Agent Vector, a quick read through our terminology guide is highly recommended.  
It explains the core concepts in **simple, non-technical language**.  

👉 **[Read the Guide: Understanding Key Terminologies →](terminologies.md)**  

---

</div>
