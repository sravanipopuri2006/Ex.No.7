## Ex. No. 7 – Develop a Prompt-Based Application using ChatGPT
Date:01.11.25
Register No.:2122223240117


## Aim:

To develop a prompt-based application using ChatGPT, demonstrating how to design and refine prompts that organize daily tasks and enhance productivity — progressing from simple to advanced prompt designs and analyzing their corresponding outputs.

## AI Tools Required:

ChatGPT (GPT-5 or equivalent LLM)

Python (optional, for simulation or CLI interface)

Text Editor / IDE (VS Code, Jupyter Notebook)

## Explanation:

The goal of this experiment is to create a personal productivity assistant using prompt-based interaction with a large language model (LLM).
The assistant should be able to:

Manage daily tasks

Schedule reminders

Suggest wellness tips

Answer general queries

Adapt to user preferences over time through conversational feedback

## Prompt:

"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."

## Procedure:

Define Core Requirements

Understand natural language input.

Add, update, and delete daily tasks.

Schedule reminders and detect overlapping events.

Suggest wellness activities like breaks, hydration, or mindfulness.

Adapt to user preferences over time (using basic memory).

Identify and Construct Prompts for Each Feature

## Example:

“Remind me to complete my project report at 5 PM.”

“Suggest a wellness tip for focus.”

“What are my pending tasks today?”

The assistant interprets user intent, stores data, and responds contextually.

Simulate Natural User Interaction

Implement a command-line or chat-style interface.

## Example interaction:

User: Add "finish assignment" to my to-do list.  
Assistant: Got it! Task added to your list.  
User: Set a reminder for 6 PM.  
Assistant: Reminder set for 6 PM today.  
User: I’m feeling tired.  
Assistant: Try a 5-minute breathing exercise or a short walk.


## Collect Feedback and Adapt Responses

Capture user feedback like “That’s helpful” or “Don’t repeat this.”

Store preferences in memory (e.g., preferred reminder times, liked tips).

Integrate Basic Memory (Optional)

Use a small JSON/dictionary structure to remember preferences:

```
memory = {
    "tasks": ["Finish assignment"],
    "preferences": {"reminder_time": "8 AM"},
    "feedback": {"wellness_tips": "liked"}
}
```

## Expected Output:

Personal Productivity Assistant Features:

Daily Task Manager:

Accepts tasks via natural language (e.g., “Remind me to call mom at 6 PM.”)

Organizes tasks by priority and deadline.

Provides daily summaries and lists pending items.

Smart Scheduler:

Sets and manages reminders contextually.

Warns about overlapping events or available time slots.

Wellness Tips Generator:

Offers daily wellness advice like exercise, hydration, and screen breaks.

Adapts suggestions based on user feedback or mood indicators.

Preference Learning (Adaptive Memory):

Remembers preferred times for reminders or updates.

Adjusts tone, frequency, and type of responses based on user interaction.

Example Output:

Assistant: Good morning! You have 2 tasks for today:
1. Complete project report by 5 PM.
2. Team call at 6 PM.

Tip for today: Stay hydrated — drink at least 8 glasses of water.
Would you like me to set tomorrow’s reminder for 8 AM as usual?

## Result:

The experiment successfully produced a conceptual personal productivity assistant using large language model capabilities.

