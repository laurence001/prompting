# Evaluating prompting techniques in AI-assisted fact-checking

_Laurence Dierickx & Carl-Gustav Lindén, University of Bergen_

Supporting materials for the paper "The less for the more: Evaluating prompting techniques in AI-assisted fact-checking" This repository includes prompt templates, task definitions, and prompt formulations used in a comparative evaluation of large language models (LLMs) for three fact-checking tasks such as summarisation, verdict formulation, and headline generation. These datasets support reproducibility and further research in prompting.
## Tasks:
- **Condensation**: Summarising fact-checks into concise leads.
- **Evaluation**: Providing verdicts based on evidence.
- **Generation**: Creating headlines reflecting the claim and verdict.

### Abstract
Despite the challenges of bias, inaccuracy and hallucinations, large language models (LLMs) are being used more and more in journalism and fact-checking. However, the potential of prompting strategies to help non-expert users address these issues has largely been overlooked. This study systematically evaluates seven promptings techniques across three core fact-checking tasks: headline generation, content summarisation, and verdict formulation. The prompts were manually tested on four popular and publicly accessible LLMs using a curated dataset of 2,520 outputs that simulated real-world practices. The evaluation method is a hybrid approach combining human expert judgements with automated metrics to measure task completion, semantic accuracy and factual consistency. The results show that simple techniques often outperform more sophisticated ones, although structured techniques are beneficial for complex tasks that require explainability. The results also emphasise the importance of designing clear prompts that relate to specific tasks, showing that effective prompting does not require complexity, but rather a strategic approach. Consequently, this study establishes prompting as a vital design mechanism for fostering reliable human-AI collaboration, especially in scenarios where information quality is particularly critical.
