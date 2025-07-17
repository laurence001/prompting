# Second iteration of prompts for fact-checkings tasks

| **Type of Prompt**   | **Task**       | **Prompt** |
|----------------------|----------------|------------|
| Vanilla              | Condensation   | Please summarise the fact-check including these three components: 1) The main claim (assertion), 2) The key evidence, 3) The verdict (conclusion). You may present this summary as a lead, a sentence, or bullet points. |
| Vanilla              | Evaluation     | Please provide the verdict for the fact-check. Is the claim true, false, mixed, or another suitable category? Explain your reasoning based on the evidence. |
| Vanilla              | Generation     | Please generate one headline for the fact-check that clearly reflects both the main claim and the final verdict. |
| Ask-me-anything      | Condensation   | Please summarise the fact-check, ensuring it contains: 1) The claim being verified, 2) The key evidence, and 3) The verdict and justification. Present as a sentence, bullet points, or structured pair (e.g., assertion/conclusion). |
| Ask-me-anything      | Evaluation     | Determine the verdict of the fact-check by answering: 1) What is the claim? 2) What is the verdict (True/False/Mixed)? 3) What evidence supports it? |
| Ask-me-anything      | Generation     | Generate one headline for the fact-check including: 1) The main claim, 2) The final verdict, 3) A concise combination of both. |
| Chain-of-Thought     | Condensation   | To summarise the fact-check, include: 1) The claim (assertion), 2) The evidence, and 3) The conclusion (verdict). You may write this as three bullet points or as a brief summary. |
| Chain-of-Thought     | Evaluation     | Provide the verdict for the claim by following: 1) Identify the claim, 2) Examine the evidence, 3) Conclude with a justified verdict (True/False/Mixed). |
| Chain-of-Thought     | Generation     | Create a headline summarising: 1) The core claim, 2) The verdict, 3) A clear and concise formulation that combines both. |
| Contextual           | Condensation   | Read the fact-check and produce a summary including: 1) The claim (assertion), 2) The key evidence, 3) The conclusion (verdict). Format can vary (sentence, bullet points, etc.) but all three elements must be covered. |
| Contextual           | Evaluation     | Provide a verdict by answering: 1) What is the claim? 2) What is the verdict? 3) What reasoning supports this decision? |
| Contextual           | Generation     | Write a headline for the fact-check that clearly conveys both the main claim and the final verdict. |
| Least-to-Most        | Condensation   | Please summarise the fact-check by including: 1) The verdict, 2) The key evidence, and 3) The claim. Reorder into a coherent summary that includes all three core components. |
| Least-to-Most        | Evaluation     | Determine the verdict by explaining: 1) What is the claim? 2) What is the final verdict? 3) What evidence supports the verdict? |
| Least-to-Most        | Generation     | Generate a headline by clearly reflecting: 1) The claim, 2) The verdict, and 3) A concise combination in headline format. |
| Role-based           | Condensation   | As a fact-checker, summarise the fact-check using: 1) The claim (assertion), 2) The key evidence, 3) The final verdict (conclusion). The summary format can vary (e.g., sentence, bullet points, structured pair). |
| Role-based           | Evaluation     | As a fact-checker, provide the verdict with: 1) The claim, 2) The final verdict, 3) The evidence supporting it. |
| Role-based           | Generation     | Write a headline for the fact-check that accurately captures both the claim and the verdict. |
| Zero-shot            | Condensation   | Summarise the fact-check with these three elements: 1) The main claim, 2) The key evidence, 3) The final verdict. Use any clear and concise format. |
| Zero-shot            | Evaluation     | Provide the verdict: 1) What is the claim? 2) What is the verdict? 3) What supports this verdict? |
| Zero-shot            | Generation     | Generate a headline that summarises both the claim and the verdict clearly and concisely. |
