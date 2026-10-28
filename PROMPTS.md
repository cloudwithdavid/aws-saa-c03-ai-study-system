# SAA-C03 activity prompts

First follow the [setup in the README](README.md#set-up-your-project) and save [PROJECT-INSTRUCTIONS.md](PROJECT-INSTRUCTIONS.md) in your Project instructions. These prompts start activities; you can ask follow-up questions naturally.

Replace bracketed fields with what you know. Leave unavailable details as unknown. You do not need to fill every field before getting started.

## 1. Start your preparation

Use in a new chat inside your study Project. If you already have a tracker, make its latest version available first.

```text
I am preparing for AWS SAA-C03.

My AWS background: [experience and certifications]
My course and practice resources: [resources]
Available study time: [hours per day or week]
Target exam date: [date or undecided]
Current stage: [course / practice testing]
Latest assessment: [result or none]

Read the current progress tracker if one is available and follow the Project
instructions. My priority is to pass efficiently and preserve time for building
practical engineering skills. Recommend my next useful activity and explain why.
Ask only for missing information that would change that recommendation.
```

## 2. Understand a course topic

Use when you can recognize terms but cannot yet explain the system. Dictating your current understanding can be useful.

```text
I'm studying [topic]. Here is my current understanding and what confuses me:
[my explanation or question]

Explain the missing pieces simply, with a practical scenario and an analogy
if helpful. Connect the components, data flow, permissions, and relevant
trade-offs. Compare only the closest plausible alternative.

End with: "What do I need to remember from this for SAA-C03?"
Keep the main explanation within exam scope. No quiz unless I request one.
```

## 3. Analyze a completed practice test

Use after **each practice test**, including short diagnostics and targeted assessments. Identify a results tab only if your environment can inspect it; otherwise supply results and question reviews. If using batches, state the ranges and identify the final batch.

```text
Review this completed practice assessment using the Project instructions.

Assessment and provider: [name]
Date and mode: [details]
Official score and question count: [details or supplied results]
First attempt or repeat: [answer or unknown]
Question reuse I noticed: [details or unknown]
Correct answers I guessed or was unsure about: [references or unknown]
Results and question reviews: [accessible tab / attached or pasted material]
Batch coverage, if applicable: [range; final batch or more to come]

Read the latest tracker. Inspect every available question review, including
correct answers. Report questions reviewed out of total and missing evidence.
Analyze supplied material if browser tools are unavailable.

Group mistakes by concept, distinguish confirmed gaps from provisional
diagnoses, and use counts as well as percentages. Ask about my reasoning
only where it could materially change the diagnosis.

Give me:
1. A concise assessment of what the evidence shows.
2. An ordered review plan with question references and the smallest useful
   activity for each priority.
3. The next suitable targeted assessment or fresh full timed test.
4. The complete updated SAA-Progress.md, even if some diagnosis is pending.

Keep this to analysis and planning. Wait for me to begin the review or request
a drill. Remind me to add or replace the tracker in Project sources.
```

## 4. Review a question and its decisive requirements

Use for a missed question, a correct guess, or uncertainty between plausible answers. Supply your original reasoning when possible.

```text
Review this practice question:
[question and answer choices]

My selected answer and reasoning: [explanation]
My confidence: [confident / unsure / guessed]
Provider's answer and explanation: [if available]

Diagnose the issue using the Project instructions. Explain why the best
architecture satisfies all requirements and why the nearest alternative
falls short. Label an uncertain diagnosis as provisional.

Extract the minimum decisive words or combination of requirements and explain
their significance. If no strong clue exists, say so. Show which requirements
would need to change for the alternative to become preferable, while keeping
the remaining constraints clear.

End with what I need to remember for SAA-C03. No automatic quiz. When this
focused review session is complete, provide the full updated tracker.
```

## 5. Compress an explanation

Use whenever you want a compact recall summary.

```text
What do I need to remember from this for SAA-C03?

Topic or explanation: [topic / text / preceding discussion]

Give me the essential concept, when to choose it, and the distinction most
likely to decide between plausible alternatives. Include decisive clues only
when they help. Keep newer product developments and nonessential implementation
detail outside the main explanation.
```

## 6. Test understanding on unfamiliar scenarios

Use when drilling would resolve uncertainty or check a reviewed weakness. Returning to this after a delay gives better evidence of retention.

```text
Read my tracker and test my understanding of [concept or weakness] with
3 original SAA-level questions. Present one at a time and wait for my answer
and reasoning before revealing the solution.

Substantially change the workloads, constraints, wording, and competing
solutions from the reviewed questions. Include a case where a changed
requirement makes another solution preferable. Use plausible distractors.

After the set, distinguish reinforcement from transfer, explain any weakness
status change, and recommend whether to move on or revisit it. Finish this
focused review session with the complete updated SAA-Progress.md and remind
me to replace the Project source.
```

## 7. Finish a focused review session

The Project instructions require this update automatically after each completed focused review session. Use this prompt when you decide to stop, when the session is interrupted, or when the LLM has not recognized completion.

```text
This focused review session is finished. Read the latest tracker and
incorporate the evidence from this session.

Record the concepts reviewed, misconceptions clarified, drill results and
reasoning, remaining uncertainty, and next activity. Explain status changes
without treating an explanation or familiar answer alone as mastery. Include
any concepts that need delayed recall or unfamiliar-scenario checks.

Provide the complete updated SAA-Progress.md in one copyable Markdown block,
preserving assessment history and prior supported evidence. Remind me to
add or replace it in Project sources and keep one current version.
```

## 8. Research exam relevance

Use selectively when uncertainty about a topic's scope would change how much time you spend on it. This requires web access; without it, supply the official guide or other sources for analysis.

```text
For SAA-C03 topic [topic], check the official exam guide and search recent
firsthand exam/preparation experiences discussing broad topic coverage.

Separate official scope, recurring anecdotal reports, and uncertain inference.
Give source links and dates. Exclude dumps and actual exam questions.

Recommend what I should understand, the justified depth, and what I can
deprioritize. Do not infer precise frequency or guaranteed coverage. Keep newer
product changes separate unless needed to correct a material error. State
which sources you could actually check.
```

## 9. Resume and choose the next activity

Use when returning to the Project or opening a new chat. Replace the tracker source with the latest generated version before starting.

```text
Read SAA-Progress.md from my Project sources and follow the Project instructions.

Time available today: [duration]
Changes since the tracker was updated: [details or none]

Recommend the next highest-value activity based on the evidence. Consider
unresolved gaps and any retention checks that are due. Explain why it comes
next, then begin it if the required material is available. Ask only for missing
information that changes the decision. Update the tracker when the practice
test or focused review session finishes.
```
