# WORKFLOW (Checklist)

1) Create folders (sessions, prompts, evaluation, guides) and files (done).
2) Fill prompts:
   - prompts/mollick_tutor_prompt.md → paste the official “Updated Tutoring Prompt”.
   - prompts/my_modified_prompt.md → paste the modified prompt text.
3) Run three sessions (details below), export each transcript, paste into:
   - sessions/session1_vanilla.md
   - sessions/session2_mollick.md
   - sessions/session3_my-mods.md
4) Write evaluation in evaluation/evaluation.md.
5) Git push (see guides/GIT-QUICKSTART.md).
6) Submit your GitHub URL on Canvas.

## Session 1 — Vanilla (no structured prompt)
- New chat.
- Send (in order):
  1) “I want you to be my tutor.”
  2) “I want to learn how to run a multiple regression in R. Start with loading a CSV and a tiny example using lm(y ~ x1 + x2, data=df), and how to read the output.”
  3) “Explain coefficients, standard errors, t-stats, p-values, and R-squared.”
  4) “Give me a tiny dataset and a short practice task.”
  5) “Show basic diagnostics and how to read them.”
  6) “Give me a 3-question quiz.”
- Distraction half:
  7) “What’s your favorite movie?”
  8) “Can we switch to juggling?”
  9) “I’m bored—why does regression matter?”
  10) “Help me find a good pizza place?”
  11) “Okay, refocus me—what’s the next step?”
- Export → paste into sessions/session1_vanilla.md under **Transcript**.

## Session 2 — Mollick structured prompt
- New chat.
- First message: paste the **official Updated Tutoring Prompt**.
- Second message: “Tutor me on running a multiple regression in R. Use small steps and check my understanding often.”
- Use the same focus/distraction flow as Session 1.
- Export → paste into sessions/session2_mollick.md.

## Session 3 — My modified prompt
- New chat.
- First message: paste **all** of prompts/my_modified_prompt.md.
- Second message: “Tutor me on running a multiple regression in R. Follow the rules.”
- Use the same focus/distraction flow as Session 1.
- Export → paste into sessions/session3_my-mods.md.
