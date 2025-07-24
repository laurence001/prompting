# Evaluating prompting strategies for fact-checking

_Laurence Dierickx & Carl-Gustav Lindén, University of Bergen_

Supporting materials for the paper "No Technique Is the Technique: Evaluating Prompting Strategies for Non-Expert Users in Fact-Checking" This repository includes prompt templates, task definitions, and prompt formulations used in a comparative evaluation of large language models (LLMs) for three fact-checking tasks such as summarisation, verdict formulation, and headline generation. These datasets support reproducibility and further research in prompting.
## Tasks:
- **Condensation**: Summarising fact-checks into concise leads.
- **Evaluation**: Providing verdicts based on evidence.
- **Generation**: Creating headlines reflecting the claim and verdict.

### Abstract
Despite persistent challenges such as bias and hallucinations, large language models (LLMs) are being increasingly integrated into journalistic and fact-checking routines and workflows. However, the potential of prompting strategies to help non-expert users mitigate these issues has largely been overlooked. This study systematically evaluates seven prompting techniques across three core fact-checking tasks: headline generation, content summarisation and verdict formulation. These techniques were manually tested on four publicly accessible LLMs (ChatGPT, Llama, Gemini and Grok) using a curated dataset of 15 fact-checks reflecting real-world practices. The models' outputs were evaluated using a combination of automated metrics and expert human judgements, focusing on task completion and factual accuracy. The results highlight that effective prompting depends more on clear task focus and precise wording to minimise ambiguity and enhance clarity than on complex or elaborate methods.
