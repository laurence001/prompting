# Evaluating prompting strategies for fact-checking
Supporting materials for the paper "No Technique Is the Technique: Evaluating Prompting Strategies for Non-Expert Users in Fact-Checking" This repository includes prompt templates, task definitions, and prompt formulations used in a comparative evaluation of large language models (LLMs) for three fact-checking tasks such as summarisation, verdict formulation, and headline generation. These datasets support reproducibility and further research in prompting.
## Tasks:
- **Condensation**: Summarising fact-checks into concise leads.
- **Evaluation**: Providing verdicts based on evidence.
- **Generation**: Creating headlines reflecting the claim and verdict.

### Abstract
Despite ongoing challenges such as bias, inaccuracies and hallucinations, large language models (LLMs) are being increasingly integrated into journalistic and fact-checking workflows. However, research into optimising prompting strategies for fact-checking, particularly for non-expert users, remains limited. This study evaluates seven prompting techniques across three tasks: headline generation, summarisation, and verdict formulation. A manually curated dataset of fifteen Nordic fact-checks was used to test the techniques in four widely accessible LLMs—ChatGPT, Llama, Gemini and Grok—under controlled conditions designed to reflect real-world fact-checking scenarios. Outcomes were evaluated using automated metrics and human assessments of accuracy, clarity, and factual alignment. The findings demonstrate that short, clear prompts are more effective than complex ones and that well-structured task definitions are essential for achieving reliable outcomes.


