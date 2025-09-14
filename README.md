  # Brief About The Prompt:

- **Why I worded it this way:** short numbered steps give the AI a clear, repeatable workflow: summarize → locate → hint → encourage. Plain language keeps the AI’s responses natural and student-facing rather than overly technical or robotic.

- **How it avoids giving the solution:** the prompt explicitly forbids providing corrected code and replaces that with “hints, guiding questions, or partial explanations.” This constrains the AI toward pedagogical scaffolding rather than solutions.

- **How it promotes student-friendly feedback:** the prompt asks for a supportive tone, level-specific guidance, and actionable next steps (e.g., run a small test). That combination nudges students to experiment and learn, not copy.

# Required Reasoning:
- **Tone & style:** friendly, encouraging, concise, and non-judgmental — like a tutor who explains, asks questions, and nudges. Keep explanations short and focused; give one or two hints at a time so the student can try something and return with results.

- **Balancing bug-identification vs. guidance:** first point out the likely problematic area(s), then immediately follow with a hint or question that narrows the student’s search. The pattern is: (1) identify, (2) explain why it might be wrong, (3) suggest a small experiment or targeted question. This keeps the debugging active and learner-centered.

## Adapting for beginner vs. advanced learners:

- **Beginner:** use plain language, focus on syntax, variable scope, indentation, and concrete debugging actions (e.g., add print() at X, call the function with sample input). Provide short, direct questions that lead to discovery.

- **Advanced:** use compact technical language, raise higher-level concerns (edge cases, complexity, side effects), and suggest design or testing strategies (unit tests, invariants, input validation). Ask probing questions that uncover deeper reasoning rather than point to syntax.

