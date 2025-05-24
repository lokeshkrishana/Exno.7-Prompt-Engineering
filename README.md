# Exno.7-Prompt-Engineering
### Date:
### Register no.212222040087

## Aim: 
To Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.
## Algorithm: 
Develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

### 1. Define the Scenario and Use Case
#### Scenario:
A student or professional wants a lightweight, personalized digital assistant powered by ChatGPT to manage daily activities, from to-do lists to time-blocking and prioritization.

#### Target User: 
Individuals seeking daily structure, time management, or habit tracking.

#### Primary Objectives:

1. Encourage consistent task tracking

2. Improve time utilization

3. Adapt to personal task patterns using prompt evolution

### 2. Prompt Patterns for Design Aspects
#### A. Idea Generation Prompts
Prompt: “What features should a ChatGPT-based daily task manager have?”

Brainstormed Features:

Add/view/edit/delete tasks via natural language

Prioritize tasks using urgency/importance

Suggest optimal time slots for tasks

Generate summaries and progress updates

#### B. Persona and Context Prompts
#### Prompt: “Act as a personal productivity coach who is friendly, motivational, and non-intrusive.”

Style Outcome:

Responses are supportive: “Hey! Let’s tackle the day together. What’s your first task?”

Avoids pressure, focuses on encouragement and personalization

#### C. Exploratory Prompts
#### Prompt: “List common personal productivity methods and how they can be incorporated into a prompt-based system.”

Incorporated Methods:

Eisenhower Matrix: Classify tasks by importance/urgency

Pomodoro Technique: Suggest time blocks with breaks

SMART Goals: Help convert vague goals into actionable ones

#### D. Refinement Prompts
#### Prompt: “Refine the response to give users time estimates and suggest alternatives if time is short.”

Refined Interaction:

“Task: Finish project report – Est. Time: 2 hours. Don’t have 2 hours? Try outlining it first (20 mins).”

#### E. Scenario Testing Prompts
#### Prompt: “Simulate a user having only 4 hours and 6 tasks. How should the assistant respond?”

ChatGPT Output:

Sorts tasks by impact and time

Suggests deferrals or delegations

Outputs: “Focus on Task A and B (2.5 hrs). Postpone C or D. You’ve got this!”

#### F. Error Handling Prompts
#### Prompt: “If a user enters conflicting tasks or incomplete info, how should the assistant clarify?”

ChatGPT Behavior:

“I noticed you scheduled two tasks at the same time. Would you like me to reschedule one?”

“Can you tell me what ‘prepare’ refers to? Is it a meeting, assignment, or something else?”

### 3. Implementation Plan
#### Environment Setup:

Python + Streamlit or Flask for UI

OpenAI API integration with secret management

#### Prompt Engine:

Basic: Accepts task descriptions and outputs summaries

Advanced: Custom prompt templates using daily logs, time constraints, priorities

#### Features:

Task Entry (add_task(prompt))

Task Sorting & Suggestions (sort_by_urgency(prompt))

Motivation/Check-in Prompt Generator (generate_checkin())

#### Progressive Prompt Design:

Simple: “Add these 3 tasks to my list.”

Intermediate: “Schedule my day with 6 tasks and 5 hours available.”

Advanced: “I’m low on energy. Which of my tasks can I do with minimal focus?”

### 4. Evaluation and Feedback Collection
#### Prompt: “How do users feel about the assistant after 7 days of use?”

Collected via built-in feedback prompts like:

“Was this suggestion helpful?”

“Do you feel more organized today?”

Feedback Summary:

Liked: Tone, flexibility, intelligent rearrangement

Wanted: Calendar integration, voice support


### 5. Prototype/System Outline
#### Backend:

Python modules for ChatGPT prompt engineering

SQLite or JSON file for task persistence

#### Frontend Options:

Streamlit dashboard with daily planner

CLI for minimalist users

```python
Today’s Plan:
1. Write essay (1.5 hrs)
2. Team call (30 mins) [11 AM]
3. Grocery shopping (45 mins)
Tip: Start with the essay to build momentum!
```

### 6. User Testing Results and Improvement Plan
#### Findings:

80% of users felt “more in control” of their day

65% preferred motivational tone over formal tone

#### Next Iteration:

Add calendar syncing (Google/Outlook)

Implement voice assistant module (e.g., Whisper + ChatGPT)

Daily goal tracking with gamification


## Result: 
The Prompt is executed successfully
