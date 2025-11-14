# AI-chatbot-NexusBot

## 📱 NexusTech Support Expert System (Python + PyDatalog)

A rule-based AI customer support chatbot built using PyDatalog, designed to diagnose and troubleshoot common smartphone issues such as battery problems, display issues, connectivity failures, audio faults, and more.
The bot intelligently detects categories, sub-issues, and provides solutions based on a knowledge-base of device faults.

## 🚀 Features
🔹 Intelligent Issue Detection

Detects smartphone problems from user text (keywords & rule-based logic)

Supports multiple categories:
Battery
Display
Connectivity
Performance
Camera
Audio
Software/OS

🔹 Guided Troubleshooting

If user mentions a category (e.g., battery), bot shows all related sub-issues.

User selects a sub-issue → bot provides exact troubleshooting steps.

Automatically extracts known issue keywords from natural language.

🔹 Rule-Based AI (PyDatalog)

Uses logical relations like:

has_issue(issue, category)

solution_for(issue, solution)

Easy to expand knowledge base by adding more facts.

🔹 Friendly Conversational Experience

Built-in greeting system:

Responds to “hi”, “hello”, “good morning”

Welcomes users at startup

Clean, user-friendly text flow and emoji-enhanced responses.

🧠 How It Works

User enters a problem (e.g., “my phone is not charging”)

Chatbot detects keywords and maps them to known issues

If a category is detected, bot asks for specific sub-issue

🛠 Technologies Used

Python 3

PyDatalog (logic programming)

Rule-based inference engine

Console-based chat interface

🤝 Contributing

Pull requests are welcome!
You can add:

More device models

More issue categories

GUI using Tkinter / PyQt

Voice input using Azure Speech SDK

PyDatalog retrieves the correct solution from the knowledge base

Bot displays recommended troubleshooting steps
