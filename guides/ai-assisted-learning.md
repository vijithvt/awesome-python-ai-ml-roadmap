# AI-Assisted Learning Protocol

AI tools can accelerate feedback while also hiding knowledge gaps. Use this protocol
to keep ownership of the work.

## Before asking AI

1. Write the desired behavior and one example.
2. Attempt a solution for 20–30 minutes.
3. Reduce the failure to the smallest reproducible case.
4. Read the error and relevant official documentation.
5. Record your hypothesis.

## Good requests

- “Ask me questions that help me find the bug; do not give the solution.”
- “Review this split for leakage and explain each risk.”
- “Generate edge cases for this function without implementing it.”
- “Compare these two approaches against my stated constraints.”
- “Quiz me and wait for each answer.”
- “Review my explanation for conceptual errors.”

## Poor requests

- “Build my complete capstone.”
- “Give a perfect model with 99% accuracy.”
- “Fix everything” with no reproduction or reasoning.
- requesting solutions during a closed checkpoint.

## Verification loop

For AI-produced suggestions:

1. inspect every line/change;
2. verify APIs against official documentation;
3. run tests and add a test that would fail for a plausible wrong answer;
4. check data, licensing, privacy, and security assumptions;
5. explain the solution without the conversation;
6. record material AI assistance in the project notes.

Never paste secrets, private company code/data, personal information, or material you
are not authorized to share.
