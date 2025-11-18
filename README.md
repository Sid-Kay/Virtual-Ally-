
**Virtual-Ally**

**Your friendly multi-agent companion that helps make everyday tasks a little easier, a little smarter, and a lot more fun.**



**Overview:**

Virtual-Ally is a small-but-mighty AI project I built as part of the Kaggle x Google Five-Day AI Agent Course.
I’m pretty new to coding, and this project was my way of learning how agents actually work — while also making something that feels personal and fun.

This agent helps with everyday tasks like planning, getting recommendations, answering questions, and managing small routines. It’s designed to feel like a helpful buddy rather than a stiff robotic assistant.

It combines different tools, agents, and memory features taught during the course, wrapped neatly into one mini multi-agent system.


---

**Problem Statement**:

Sometimes, daily tasks feel repetitive, boring, or overwhelming — especially when juggling studies, hobbies, and life in general. I wanted an assistant that could:

Think through tasks step by step

Fetch helpful info

Give suggestions

Remember small preferences

And still feel fun to use


So I decided to build a personal “virtual best friend” that can help with the small things in a smart, structured way.


**Solution Summary**:

Virtual-Ally uses a multi-agent architecture, combining:

A Coordinator Agent

A Planning Agent

A Research/Info Agent

A Creative Assistant Agent


Each agent has a clear job, and the main controller decides how to route tasks so everything stays organized and efficient.

The system includes:

Agent-to-agent communication

Sequential execution

Custom tools

Memory storage

Clean state management

A simple command-line interface to interact with the agent


The goal wasn’t perfection — the goal was learning, experimenting, and actually completing a working AI agent from scratch.


---

 **Project Structure:**

Virtual-Ally/
│
├── main.py            → Runs the entire agent system
├── agents.py          → Contains all agents (coordinator, planner, researcher, creative)
├── helpers.py         → Utility functions for prompts, routing, formatting, memory
├── tools.py           → Custom tools (search, mini database, notes)
├── config.py          → API key loader (kept empty by default for safety)
│
├── requirements.txt   → Python dependencies
├── .gitignore         → Prevents API keys or env files from uploading
├── LICENSE
└── README.md


---

**How It Works (Simple Explanation):**

1. You type something like:
“Help me plan a fun workout + movie night.”


2. The Coordinator Agent reads your request and decides which agent should handle it.


3. The Planner Agent breaks the task into steps.


4. If needed, the Research Agent fetches facts or suggestions.


5. The Creative Agent adds fun ideas (themes, styles, activities).


6. Everything is combined into one friendly final answer.



**How to Run It:**

1. Install Python (3.10+ recommended).


2. Open the folder in VS Code.


3. Create a virtual environment:

python -m venv venv


4. Activate it:

Windows:

venv\Scripts\activate

Mac/Linux:

source venv/bin/activate



5. Install dependencies:

pip install -r requirements.txt


6. Create a .env file and add your API key:

OPENAI_API_KEY=your_key_here


7. Run the agent:

python main.py



Your Virtual-Ally is now ready to chat!


**What I Learned:**

How multi-agent systems actually work behind the scenes

How to create custom tools

How to structure a Python project

How to work with environment variables safely

How to break down tasks logically instead of trying to do everything at once

How to think like an AI engineer (baby steps!)



**If I Had More Time...**

I’d love to add:

A web UI instead of a command line

A mood-based response system

More tools (calendar management, reminders, study helpers)

Image-generation support for creative tasks

A memory dashboard showing what the agent has learned


Maybe this becomes a bigger personal assistant someday — who knows?


---

**Credits:**

Built by me as part of the
Kaggle x Google Five-Day AI Agent Course (2025).
