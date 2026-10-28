# AWS SAA-C03 — AI Study System

**Use GenAI to understand AWS concepts, diagnose practice exam mistakes, and focus your preparation on what needs work.**

By [David Rodriguez · CloudWithDavid](https://cloudwithdavid.com)

I passed AWS Certified Solutions Architect – Associate with a score of **788**, after **20 calendar days of preparation**. My objective was to earn the certification efficiently so I could dedicate more time to building practical engineering skills.

This resource gives you the study system behind that approach: Project instructions, reusable prompts, and a workflow for turning assessment results into your next useful study activity. It consolidates instructions I used throughout preparation, with refinements to make the setup easier for other people to use.

**The loop:** learn → clarify → assess → diagnose → review and drill → reassess.

## What you get

| File | How to use it |
| --- | --- |
| [PROJECT-INSTRUCTIONS.md](PROJECT-INSTRUCTIONS.md) | Copy the entire file into your ChatGPT Project instructions. It establishes ongoing teaching, diagnosis, practice, and tracking behavior. |
| [PROMPTS.md](PROMPTS.md) | Copy a prompt when you want to start a particular activity. |
| This README | Follow the setup, study workflow, and worked example. |

There is no blank tracker to download. The LLM creates `SAA-Progress.md` from your preparation and supplies a complete replacement **after each practice test and after each completed focused review session**. You add or replace that file in your Project sources.

## Who this is for

Use this if you want to prepare for **SAA-C03 efficiently**, with a structured course and reputable practice assessments as your foundation. The instructions help you use an LLM deliberately: explain what you do not understand, analyze your mistakes, and decide what to do next.

My preparation built on Cloud Practitioner knowledge, AWS re/Start, and independent hands-on work. Your starting point determines your pace. A beginner can use the same loop with more foundational study and selected labs; someone already familiar with AWS can move quickly through familiar material.

This release is focused on **SAA-C03**. Its broader applicability has not been validated across other certifications. ChatGPT is the documented setup; another LLM may work if you adapt its instruction, context, and file features.

## Set up your Project

1. Create a ChatGPT Project named **AWS SAA-C03**.
2. Open [PROJECT-INSTRUCTIONS.md](PROJECT-INSTRUCTIONS.md). Use GitHub's **Raw** view if helpful, then copy the entire file into the Project's instructions field. Save it there; uploading it only as a source does not complete this setup.
3. Add the [official SAA-C03 exam guide](https://docs.aws.amazon.com/pdfs/aws-certification/latest/solutions-architect-associate-03/solutions-architect-associate-03.pdf) and any assessment results you already have as Project sources. Check the guide's revision information when you begin preparation.
4. Start a chat **inside that Project** and use the [opening prompt](PROMPTS.md#1-start-your-preparation). Supply your background, resources, available study time, and target date if you have one.
5. Follow the recommended activity. The first completed practice test or focused review session should produce your tracker. If you already have one, supply it and continue from it.

Project instructions and sources provide shared context across the Project's chats. See [OpenAI's Projects documentation](https://learn.chatgpt.com/docs/projects) for current product guidance. The setup uses Project instructions, supplied learning material, and chat; browser control is optional.

### What you need

- A structured SAA-C03 course or an equivalent foundation. I used **Stéphane Maarek's course**.
- Reputable practice exams. I used **[Tutorials Dojo](https://tutorialsdojo.com/)**; the instructions also accept results from other providers and official AWS practice material.
- An LLM that can work with your instructions and supplied results. Web search is useful for technical verification and selective research into exam relevance.

Use your course and practice platform as the main learning and assessment resources. The LLM helps you extract more value from them; its generated drills are supplemental practice.

### Supplying assessment results

If your environment provides browser tools that can inspect your signed-in results page, identify the completed assessment and ask for a review of **all available question reviews**, including correct answers. The LLM should state how much it actually inspected.

Otherwise, provide copied review text, an export if your provider offers one, or screenshots in numbered batches. Include the assessment name, official score, question numbers, your selected answers, correct answers, and explanations where available. Mark questions you guessed or answered uncertainly if you remember them. The results page alone cannot reveal your confidence.

For batches, label the question range and say when the final batch is supplied. The LLM can record the assessment immediately, then refine its diagnosis as the remaining reviews arrive. Missing information should stay visible in the tracker.

Public web search cannot read your private test results. Copying these instructions does not grant browser access or enable direct editing of your Project sources.

## Use the system during preparation

### 1. Learn actively alongside your course

When a topic is unclear, explain your current understanding in your own words and use the [topic prompt](PROMPTS.md#2-understand-a-course-topic). Ask follow-up questions until you can explain the capability, the problem it solves, and when it fits.

Voice dictation made this easy for me. I could question an explanation and work through analogies without interrupting the course to write extensive notes. I repeatedly asked, **“What do I need to remember from this?”**

I watched nearly all course videos at least at 1.5× speed, many at 2×, and very few at normal speed. I skipped almost all hands-on demonstrations because I was already getting practical experience elsewhere. Choose a pace that preserves understanding, and use a focused lab when you need to see how something behaves. Notes and flashcards are optional; use them when they solve a specific learning problem.

Keep the main explanation focused on SAA-C03. If newer AWS behavior conflicts with a course or practice answer, ask for the discrepancy to be flagged briefly and kept separate. The official exam guide establishes scope; an older course statement alone does not establish what the exam currently expects.

### 2. Establish a baseline

Use available official AWS practice questions and a short diagnostic if you have them. These help reveal gaps, but a small sample gives limited evidence about readiness.

After completing the course, take a fresh full timed assessment for a broader baseline. Record guesses and uncertainty when practical. You can get an answer right while still needing to review the concept.

### 3. Analyze the whole assessment

Use the [assessment prompt](PROMPTS.md#3-analyze-a-completed-practice-test). The LLM should group related mistakes and prioritize concepts using the question evidence, recurrence, exam relevance, and effort needed to improve.

Distinguish missing knowledge, confused services, misunderstood requirements, incorrect assumptions, careless mistakes, and timing problems. Include both question counts and percentages where available. The domain with the lowest percentage is not necessarily responsible for the most mistakes.

The output should give you an ordered review plan and a complete tracker. Save that tracker before moving to another chat.

### 4. Complete a focused review session

Work through one weakness or a small group of related weaknesses. Use the [question review prompt](PROMPTS.md#4-review-a-question-and-its-decisive-requirements) to understand why the solution meets the requirements, which clues distinguish it from plausible alternatives, and what would need to change for another solution to become preferable.

When additional practice would help, request a short set of [unfamiliar scenarios](PROMPTS.md#6-test-understanding-on-unfamiliar-scenarios). Different workloads and constraints help reveal whether you can apply the concept beyond the question you just reviewed.

A focused review session ends when its agreed learning goal is reached or you decide to stop. The LLM should then provide a complete updated tracker, including the evidence from the session. Use the [close-session prompt](PROMPTS.md#7-finish-a-focused-review-session) if needed.

### 5. Reassess and adapt

Use Tutorials Dojo **Topic-Based** practice for narrow weaknesses, **Section-Based** practice for broader domain weaknesses, and a fresh **Timed** assessment for another overall check, when those modes are available. Use the closest equivalent if you study with another provider.

Revisit earlier weaknesses after a delay. Understanding an explanation or immediately answering a similar question shows progress; unfamiliar scenarios and later recall give stronger evidence of retention.

## Keep one current progress tracker

**After each practice test and after each completed focused review session, the LLM should provide the complete updated `SAA-Progress.md`. Each event independently triggers an update.**

The instructions specify its contents: learner context, assessment history, domain results, weaknesses, review evidence, next activity, and later retention checks. The LLM should generate the structure and fill it from the evidence you supply.

When you receive an update:

1. Check the assessment identity, official score, and any changes to weakness status.
2. Copy the complete Markdown block into a file named `SAA-Progress.md`, or use the generated file if the LLM supplies one.
3. Add it to Project sources the first time. On later updates, replace the previous source. If your interface has no replacement action, remove the older source and add the new file.
4. Keep one current version available to the Project. Start later sessions by asking the LLM to read it before choosing your next activity.

The default workflow requires this manual source update. A message saying the tracker was generated does not mean your Project source changed. If a session is interrupted, ask the LLM to close the review with the evidence collected so far and provide the updated tracker.

## Worked example: from results to the next activity

**This is a fictional illustration, not my assessment history or a reproduced practice-provider question.** The short assessment demonstrates the workflow rather than a full exam or readiness threshold.

### Assessment and diagnosis

Suppose you supply a first-attempt 20-question practice set with **13/20 correct (65%)**, all 20 question reviews, and a note that Q6 was a correct guess.

| Domain | Correct / total | Percentage | Incorrect question references |
| --- | --- | --- | --- |
| Security | 7/8 | 87.5% | Q2 |
| Resilience | 3/4 | 75% | Q10 |
| Performance | 2/5 | 40% | Q13, Q14, Q16 |
| Cost Optimization | 1/3 | 33.33% | Q18, Q19 |

Cost has the lowest percentage, while performance contributes the most incorrect answers. Neither fact alone determines the plan. Suppose the reviews show Q13 and Q14 involve load balancer selection, and your reasoning confirms the same misconception in both.

An ordered plan might start with that recurring gap, then address the separate issues in Q16, Q18, and Q19. Q2, Q6, and Q10 also need inspection; Q6's correct result should not hide your uncertainty. The tracker records the official result and the initial diagnoses, including any provisional ones.

### Explanation, decisive clues, and a changed requirement

Consider this original learning scenario:

> An HTTP application needs `/orders/*` requests sent to one target group and `/images/*` requests sent to another. Which load balancer fits that routing requirement?

An **Application Load Balancer** supports path-based listener rules. The decisive combination is **HTTP requests + routing by URL path to different target groups**. High traffic alone would not distinguish ALB from NLB.

Now replace the requirements: the workload uses **TCP**, and partners need **fixed public IP addresses to allowlist**. It no longer needs URL-path routing. A **Network Load Balancer** fits those requirements. Both the protocol/routing need and the addressing requirement changed; simply adding fixed addresses to the original HTTP requirement would require further design reasoning.

See AWS's [Application Load Balancer documentation](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html) and [Network Load Balancer documentation](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/introduction.html) for the capabilities behind this example.

### Practice and tracker update

Ask for three original scenarios with changed workloads and plausible alternatives. In this fictional session, suppose you reason correctly through two but still miss one involving a different protocol constraint.

The LLM should mark the gap **Improving**, record the remaining issue, recommend the smallest useful follow-up, and provide the complete updated tracker because the review session has finished. You replace the Project source with that version.

Later, successful reasoning on unfamiliar scenarios can support **Demonstrated** status, with the evidence retained. A new failure should reopen the gap. Once targeted review has addressed the relevant weaknesses, a fresh full timed assessment helps determine the next preparation step.

## Decide when to take the exam

My three full timed Tutorials Dojo scores were **66.15% → 66.15% → 76.92%**. I passed SAA-C03 without reaching 80% on a full timed practice test. My final attempt included questions I had already encountered, so those scores need that context.

Evaluate your fresh-question performance, reasoning, timing, remaining gaps, and tolerance for retake risk together. Improving scores on repeated questions can partly reflect recognition. Consistently strong performance on fresh material gives stronger confidence; one percentage cannot guarantee a pass.

AWS reports a scaled score, so my **788/1000 is not an exact percentage correct** and should not be directly compared with a practice-test percentage. Use AI-generated drills to investigate understanding and reputable provider assessments as the main readiness evidence.

Once the evidence supports taking the exam, put the time you save toward practical work. Certification preparation and independent engineering can support each other without requiring every course activity to serve both purposes.

## Sources and credits

- [Official SAA-C03 exam guide](https://docs.aws.amazon.com/aws-certification/latest/solutions-architect-associate-03/solutions-architect-associate-03.html) — scope, tasks, and scoring information. Check its current revision when preparing.
- [Official SAA-C03 PDF](https://docs.aws.amazon.com/pdfs/aws-certification/latest/solutions-architect-associate-03/solutions-architect-associate-03.pdf) — useful as a Project source.
- [OpenAI: Projects and chats](https://learn.chatgpt.com/docs/projects) — current guidance on shared Project context.
- [RonitSachdev's SAA-C03 guides](https://github.com/RonitSachdev/aws-saa-c03-guides) — a community teaching reference used in my original instructions. Credit belongs to RonitSachdev; this repository links to those guides rather than reproducing them.
- [Tutorials Dojo](https://tutorialsdojo.com/) — the practice platform used in my preparation.

Prepared by David Rodriguez. Last reviewed: **October 27, 2026**. This is an independent study resource. Product features, practice modes, and exam guides may change; the linked official sources are the reference for current behavior.
