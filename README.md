# Exno.7-Prompt-Engineering
```
NAME : HARISH RAGAV S
REG NO : 212222110013
```

# Aim: 
To Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Algorithm:
Develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

# Objective:
To illustrate the creation of a prompt-based assistant for handling daily tasks, planning, and productivity. This includes a step-by-step transition from basic commands to advanced, context-aware prompts that emulate intelligent assistant behaviors.

# Procedure :

## Step 1: Define the User Needs
Organizing daily tasks efficiently
Receiving reminders or suggestions
Categorizing tasks by priority, time, or type (e.g., personal, academic, work)

Define the purpose of the application. Possible use cases include:

Daily task planner
Meal or fitness scheduler
Study routine assistant
Mental wellness check-in bot
Writing or content creation helper

## User gives a basic input like:
```
 "Add the following tasks: Write report, Attend meeting, Buy groceries"
```
### Selected Use Case : Daily Task Organizer

## Step 2: Simple Prompt Processing and Design the Prompt Flow
Basic Prompt:
“Help me organize my tasks for today: buy groceries, complete homework, attend meeting at 3 PM.”

#### Expected Output:
A bulleted or ordered task list
Simple schedule layout based on given tasks

 ### Intermediate Prompt :
“Organize the following tasks into a to-do list categorized by urgency and time needed. Include time slots if possible.”

### Advanced Prompt:
“Act as my personal productivity assistant. Based on the following tasks and my preferences, create a schedule that includes breaks, priority levels, and suggests the best order to complete them. Tasks: [task list], Preferences: [focus time, morning person, etc.]”

## Step 3: Intermediate Prompt (Add Time Slots or Categories) :
Categorize the tasks into Work and Personal. Suggest an estimated time for each.
Tasks: Write report, Attend meeting, Buy groceries.

### Output :

Work:
1. Write report – 2 hours
2. Attend meeting – 1 hour

Personal:
3. Buy groceries – 1.5 hours

## Step 4: Add Smart Features via Prompt Expansion
Introduce adaptive behaviors such as suggestions, self-care, and motivational support.

#### Advanced Prompt:
“Based on my productivity preferences (creative tasks in the morning, physical errands in the afternoon), generate a smart day plan from 9 AM to 6 PM with short breaks every 90 minutes. Include motivational quotes before major tasks.
Tasks:

Finish presentation
Grocery shopping
Team meeting at 3 PM
30-minute walk”

#### Expected Output:
A motivational quote or message before big tasks
A well-paced, context-aware schedule
Breaks and self-care integrated into the plan

## Step 4: Advanced Prompting (Priority + Scheduling + Analysis) :
You are a productivity assistant. Take the following tasks, estimate duration, assign priorities (High, Medium, Low), and suggest a schedule between 9 AM – 6 PM.

Tasks: Write report, Attend meeting, Buy groceries, Call client, Read articles
### Output :
< Suggested Daily Schedule >

9:00 AM – 10:00 AM: Attend meeting (High)  
10:00 AM – 11:30 AM: Write report (High)  
11:30 AM – 12:00 PM: Call client (Medium)  
12:00 PM – 1:00 PM: Lunch  
1:00 PM – 2:00 PM: Buy groceries (Low)  
2:00 PM – 4:00 PM: Read articles (Low)

✅ Prioritized & Time-Bound Tasks

## Step 6: Add Personalization for Reuse
Encourage reusable and customizable prompt templates that simulate memory and routine.

#### Reusable Prompt Template:
“Based on my previous schedule template, generate a day plan including the following tasks: [tasks]. Use the usual format and include motivational tips.”

#### Benefits:

Acts as a pseudo-memory feature
Enables consistent and efficient daily use
Promotes user ownership of productivity style

### Implementation Ideas
You can implement this in:
Python script using OpenAI API
No-code tools like Bubble or Glide with GPT plugin
Web app with input textbox + GPT response display

### Final Notes
This type of project teaches:

Prompt engineering
Progressive design (from simple to complex logic)
AI-powered productivity tools
Modular thinking (adding features step by step)

# Conclusion :
This experiment demonstrates how large language models like ChatGPT can be leveraged to build prompt-powered applications tailored to individual needs. By iteratively refining prompts—from simple task lists to interactive and context-aware daily planning—users can simulate digital assistant behavior without needing to write code. This fosters creativity, critical thinking, and practical problem-solving skills.

# Result : 
The Prompt is executed successfully


