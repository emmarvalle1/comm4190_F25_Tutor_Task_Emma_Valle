# Evaluation & Reflections

**Topic:** Running a multiple regression in R  
**Platform:** ChatGPT  
**Date:** October 2025  

---

## 1) Subjective Experience

### Session 1 — Vanilla (No Structured Prompt)
This session felt confusing and somewhat directionless. The model acted more like a general assistant than a tutor. It gave some explanations about regression, but the flow wasn’t organized and there were no checkpoints to make sure I was following. It felt like I had to drive the learning process myself by asking specific questions.

### Session 2 — Mollick Structured Prompt
This session was clearly more “tutor-like,” but it became too rigid and robotic. Instead of teaching, it repeatedly asked me about my level of knowledge or what I wanted to achieve. It never actually started explaining how to run a multiple regression or show examples. The prompt made it polite and formal, but it lost flexibility and didn’t adapt when I tried to move forward. It felt overly scripted and not very interactive.

### Session 3 — My Modified Prompt
This session was the best overall. It followed a clear, step-by-step structure but felt more natural and conversational. The tutor explained code, concepts, and outputs clearly while checking for understanding in shorter, easier-to-follow ways. It handled distractions well—acknowledging off-topic questions but quickly redirecting me back to the main lesson. This version felt more realistic and effective as a tutoring experience.

---

## 2) Communication Style — Quote Snippets

**Session 1**
> “Sure! You can use the `lm()` function in R.”  
> No structure or check for understanding — it just jumped into the answer.

**Session 2**
> “Before we begin, tell me your learning goals and what level you are at with R.”  
> It stayed stuck in this loop and never started teaching.

**Session 3**
> “Good question! Let’s finish the regression diagnostics, then I’ll answer that.”  
> This shows redirection and better control of the lesson flow.  

> “Did your code run without any errors?”  
> This check-in shows clear scaffolding and engagement.

---

## 3) Learning Effectiveness
I actually learned the process of running a multiple regression in R — including loading data, using `lm()`, reading coefficients, and interpreting p-values. The modified prompt helped me connect the steps better and understand why each part mattered. The quizzes and summaries made the learning feel more interactive, and I ended up with a clearer grasp of what each output in `summary(lm())` represents.

---

## 4) Comparison & Takeaways
| Session | Structure | Tone | Teaching Quality | Distraction Handling |
|----------|------------|------|------------------|----------------------|
| 1 | Minimal | Conversational | Incomplete explanations | Ignored distractions |
| 2 | Over-structured | Robotic | Poor (never started teaching) | Avoided but didn’t redirect |
| 3 | Balanced | Natural | Clear, step-by-step | Acknowledged + refocused |

Session 1 lacked structure. Session 2 had too much structure. Session 3 struck the right balance by being both organized and adaptable. The most important takeaway is that a good tutoring prompt needs **scaffolding and feedback loops**, but also **flexibility and responsiveness** to student behavior.

---

## 5) Did My Modifications Help?
Yes. The modified prompt combined structure with human-like communication. The shorter, numbered steps and explicit “check for understanding” lines made it easier to stay engaged. The distraction-handling rule (“acknowledge briefly, then refocus”) worked perfectly — the tutor never ignored me, but always guided me back. These changes made the experience feel realistic and effective for learning.

---

## 6) Future Work
If I repeated this task, I would add even more emphasis on mini-assessments or short coding challenges after each concept. I’d also test prompts that include visual or code examples automatically. Overall, I’d use the modified prompt as a baseline — it created the best mix of structure, friendliness, and adaptability.
