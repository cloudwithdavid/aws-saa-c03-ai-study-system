# AWS SAA-C03 — Activity Prompts

These prompts accompany the [AWS SAA-C03 AI Study System](README.md).

First, configure your AI workspace using [PROJECT-INSTRUCTIONS.md](PROJECT-INSTRUCTIONS.md). The instructions handle teaching, assessment analysis, guided review, drilling, and progress tracking.

**These prompts simply start activities.** Use them as written, customize them, or ask questions naturally. Replace bracketed text with your information when relevant.

## 🚀 Core Prompts

### 1. Prepare Before a Course Video

**When:** Before watching a lesson about a new AWS topic.

```text
I'm about to study [topic]. What do I most need to know about it for SAA-C03?
```

The AI should surface decisive keywords, mental models, and connections to previously learned services so important concepts stand out during the lesson.

### 2. Analyze a Completed Practice Test

**When:** After finishing any practice assessment.

```text
I've completed [assessment name]. Analyze the complete results and question reviews using my workspace instructions.

Results: [open browser tab / attached screenshots / pasted results]

Unsure answers: [question numbers]
Guessed answers: [question numbers]

Prioritize my weaknesses, recommend what to review, and provide my updated SAA-Progress.md. Wait for me to begin the guided review.
```

Include the score, test mode, and attempt history if they aren't already available from the results. Unmarked answers are treated as confident.

If your AI can read your open browser tabs, use that to reduce manual copying. Otherwise, supply the results through screenshots, text, or exports.

### 3. Begin Guided Review

**When:** After the AI has analyzed your assessment and created a prioritized review plan.

```text
Begin reviewing my prioritized weaknesses. Start with the highest-priority item and guide me through the diagnostic review.
```

The AI should ask targeted questions to uncover your reasoning, explain the precise gap, and help you resolve it.

Simply say **"Next"** when you're satisfied with an item and want to continue.

### 4. Test Your Understanding

**When:** You want to reinforce a weakness or verify that you can apply a concept in unfamiliar situations.

```text
Test my understanding of [topic or weakness] using unfamiliar SAA-C03 scenarios. Adapt the questions to my previous mistakes and use interactive visuals when helpful.
```

You can also ask the AI to select the most valuable weakness from your tracker.

### 5. Finish a Review Session

**When:** You've finished reviewing one or more weaknesses.

```text
This focused review session is complete. Record what we established, update my weaknesses and next activities, and provide the complete updated SAA-Progress.md.
```

Add or replace the updated tracker in your workspace's reference files so future sessions can use your latest progress.

---

## 🛠️ Additional Prompts

### Start Your Preparation

**When:** First setting up the study system.

```text
I'm preparing for AWS SAA-C03.

My background: [AWS experience and certifications]
Resources: [course and practice exams]
Current stage: [studying / practice testing]
Available study time: [time]
Target exam date: [date or undecided]

Help me determine the most useful next activity based on my goals and experience.
```
### Research a Topic's Exam Relevance

**When:** You're unsure how much study time a topic deserves.

```text
How important is [topic] for SAA-C03? Check the official exam scope and relevant firsthand exam experiences. Tell me what I should understand and what I can deprioritize.
```

### Resume Preparation

**When:** Returning to your AI workspace for another session.

```text
Read my latest SAA-Progress.md. Based on my progress and remaining weaknesses, what's the highest-value activity I should work on next? Help me begin.
```

---

**You don't need to use a template for every interaction.** The system is designed for natural conversation. Ask follow-up questions, challenge explanations, request comparisons, or simply say **"What do I need to remember from this?"** whenever you need a more concentrated explanation.
