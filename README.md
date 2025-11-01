# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:1.011.2025
# Register no.21223240117
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Title: Personal Productivity Assistant using LLM
Objective

To design an AI-powered personal productivity assistant that manages daily tasks, schedules reminders, provides wellness suggestions, and adapts to user preferences over time through natural language interaction.

## Procedure
Step 1: Define Core Requirements

The assistant must:

Understand and respond to natural language commands.

Add, modify, and delete daily tasks.

Set reminders and manage a simple schedule.

Offer wellness tips based on user behavior.

Learn user preferences over time (simulated memory).

Answer general queries conversationally.

Step 2: Identify and Construct Prompts for Each Task

Each module uses tailored prompts to interact with the user through an LLM (like ChatGPT):

Feature	Example User Input	LLM Prompt / Action
Task Manager	“Remind me to submit my report by 5 PM.”	Parse and store the task with time and priority. Generate confirmation message.
Scheduler	“Do I have any free time tomorrow afternoon?”	Analyze the schedule and list available slots.
Wellness Tips	“I feel tired today.”	Suggest rest breaks, hydration, or short workouts based on sentiment.
General Queries	“What’s the weather today?”	Retrieve or simulate an answer through an external API or LLM response.
Preference Learning	“I prefer getting reminders at 8 AM.”	Store this preference in memory for future suggestions.
Step 3: Simulate Natural User Interaction

Use a simple command-line interface (CLI) or chat-style console for interaction.

Example CLI Interaction:

User: Add "finish project report" to my to-do list.
Assistant: Got it! I’ve added "finish project report" to your list.
User: Remind me tomorrow at 8 AM.
Assistant: Reminder set for tomorrow at 8 AM.
User: I feel stressed.
Assistant: Try a short breathing exercise and stretch for 5 minutes.

Step 4: Collect Feedback and Adapt Responses

Capture user feedback (e.g., “That was helpful” or “Don’t show this again”).

Use a basic memory structure (like a dictionary or JSON file) to store:

Task history

Preferred reminder times

Response feedback

Modify future responses accordingly (e.g., avoid repeating unwanted suggestions).

Step 5 (Optional): Integrate Basic Memory

Implement a lightweight storage mechanism:

memory = {
    "preferences": {"reminder_time": "8 AM"},
    "tasks": [],
    "wellness_feedback": {"hydration_tips": "liked"}
}


When the user interacts again, responses adapt using stored preferences.

Expected Output

Personal Productivity Assistant – Example Response

Daily Task Manager

Accepts natural language input (e.g., “Remind me to call mom at 6 PM.”)

Organizes tasks by priority and deadline.

Provides daily summaries and lists pending items.

Smart Scheduler

Sets and manages reminders contextually.

Warns about overlapping events and suggests optimal time slots.

Wellness Tips Generator

Offers daily health and mindfulness tips.

Adapts suggestions based on past user feedback and activity patterns.

User Adaptation

Learns preferred notification times and wellness categories.

Improves response tone and timing based on user interaction.

Example Console Output

Assistant: Good morning, Sravani! You have 2 tasks today:
1. Submit project report by 5 PM.
2. Team call at 6 PM.

Tip for today: Drink at least 8 glasses of water and take short screen breaks.
Would you like me to schedule your next reminder at 8 AM as usual?



# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
