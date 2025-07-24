# Evaluating prompting strategies for fact-checking

_Laurence Dierickx & Carl-Gustav Lindén, University of Bergen_

Supporting materials for the paper "No Technique Is the Technique: Evaluating Prompting Strategies for Non-Expert Users in Fact-Checking" This repository includes prompt templates, task definitions, and prompt formulations used in a comparative evaluation of large language models (LLMs) for three fact-checking tasks such as summarisation, verdict formulation, and headline generation. These datasets support reproducibility and further research in prompting.
## Tasks:
- **Condensation**: Summarising fact-checks into concise leads.
- **Evaluation**: Providing verdicts based on evidence.
- **Generation**: Creating headlines reflecting the claim and verdict.

### Abstract
Despite ongoing challenges such as bias and hallucinations, large language models (LLMs) are being increasingly integrated into journalistic and fact-checking routines. However, the potential of prompting by non-experts to address these challenges has received little attention. This study systematically evaluates seven prompting techniques for three core fact-checking tasks: headline generation, content summarisation, and verdict formulation. These techniques were tested manually on four publicly and freely accessible LLMs (ChatGPT, Llama, Gemini and Grok) using a curated dataset of fifteen fact-checks, reflecting real-world professional practices. The LLMs' outcomes were assessed using a combination of automated metrics and expert human judgements. The focus was on the models' ability to perform the task and their factual accuracy. The results highlight the advantages of simplicity over complexity. Instead of relying on elaborate techniques, effective prompting depends on clear task focus and precise word choice to reduce ambiguity.


