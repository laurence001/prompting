
# First iteration of prompts for fact-checkings tasks

| **Type of Prompt** | **Task**       | **Prompt** |
|--------------------|----------------|------------|
| **Vanilla**         | Condensation   | Please summarise the fact-check [in three bullet points / as a lead], including the claim, the key evidence, and the verdict. |
|                    | Evaluation     | Please provide the verdict for the fact-check. Is the claim true, false, mixed, or another suitable verdict category? Explain your reasoning. |
|                    | Generation     | Please generate one headline for the fact-check that clearly reflects the main claim and final verdict. |
| **Ask-me-anything**| Condensation   | Please summarise the fact-check [in three bullet points / as a lead] by answering: 1) What is the claim being verified? 2) What is the main evidence used? 3) What is the verdict and why? |
|                    | Evaluation     | Please determine the verdict of the fact-check by answering: 1) What is the claim? 2) What is the final verdict (True/False/Mixed)? 3) What evidence supports this verdict? |
|                    | Generation     | Please generate one headline for the fact-check by answering: 1) What is the claim? 2) What is the verdict? 3) How can this be summarised in a headline? |
| **Chain-of-Thought**| Condensation  | To summarise the fact-check [in three bullet points / as a lead], follow these steps: 1) Identify and explain the claim. 2) Summarise the key evidence. 3) Present the verdict with justification. |
|                    | Evaluation     | To determine the verdict, follow these steps: 1) Identify the claim. 2) Review the evidence. 3) Decide on the verdict and justify your answer. |
|                    | Generation     | To generate a headline, follow these steps: 1) Identify the claim. 2) Identify the verdict. 3) Combine both in a concise, informative headline. |
| **Contextual**      | Condensation   | Please summarise the fact-check [in three bullet points / as a lead], ensuring you cover: 1) The claim being assessed, 2) The main evidence, and 3) The verdict and rationale. Use a neutral tone. |
|                    | Evaluation     | Please provide the verdict based on the fact-check: 1) What is the claim? 2) What is the verdict? 3) What reasoning supports this decision? |
|                    | Generation     | Please generate one informative headline that captures the claim and verdict of the fact-check. |
| **Least-to-Most**   | Condensation   | Please summarise the fact-check [in three bullet points / as a lead] by answering in order: 1) Verdict, 2) Evidence, 3) Claim. Then combine into a cohesive summary. |
|                    | Evaluation     | Please determine the verdict by answering: 1) What is the claim? 2) What is the verdict? 3) What supports the decision? Then provide the final verdict. |
|                    | Generation     | Generate a headline by answering: 1) What is the claim? 2) What is the verdict? 3) How to express both clearly in a concise headline? |
| **Role-based**      | Condensation   | You are a professional fact-checker. Summarise the fact-check [in three bullet points / as a lead], covering: 1) The claim, 2) The evidence, 3) The verdict with reasoning. |
|                    | Evaluation     | As a professional fact-checker, provide the verdict: 1) What is the claim? 2) What is the verdict? 3) How does the evidence support it? |
|                    | Generation     | As a professional fact-checker, generate one headline reflecting the main claim and final verdict. |
| **Zero-shot**       | Condensation   | Summarise the fact-check [in three bullet points / as a lead]: Identify the claim, outline the key evidence, and state the verdict. Be concise and clear without relying on prior task-specific context. |
|                    | Evaluation     | Provide the verdict for the fact-check: 1) What is the claim? 2) What is the verdict? 3) Explain briefly using the evidence. |
|                    | Generation     | Generate one concise headline that summarises the claim and the verdict of the fact-check. |
