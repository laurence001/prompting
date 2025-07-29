# Evaluating prompting techniques in AI-assisted fact-checking

_Laurence Dierickx & Carl-Gustav Lindén, University of Bergen_

Supporting materials for the paper "Strategic simplicity gets the most: Evaluating prompting techniques in AI-assisted fact-checking" This repository includes prompt templates, task definitions, and prompt formulations used in a comparative evaluation of large language models (LLMs) for three fact-checking tasks such as summarisation, verdict formulation, and headline generation. These datasets support reproducibility and further research in prompting.
## Tasks:
- **Condensation**: Summarising fact-checks into concise leads.
- **Evaluation**: Providing verdicts based on evidence.
- **Generation**: Creating headlines reflecting the claim and verdict.

### Abstract
Despite the challenges of bias, inaccuracy and hallucinations, large language models (LLMs) are increasingly being used in journalism and fact-checking. However, the potential of prompting strategies to help non-expert users in computer science address the issues related to their flaws and limitations has largely been overlooked. This study systematically evaluates seven prompting techniques in three core fact-checking tasks: headline generation, content summarisation, and verdict formulation. The prompts were tested on four popular and publicly accessible LLMs to generate a manually curated dataset of 2,520 outputs simulating real-world practices. The evaluation method consists of a mixed framework that combines human judgements with automated metrics to measure task completion, semantic accuracy, and factual consistency. The results highlight that effective prompting does not depend on complexity, but rather on a strategic wording and precise task definition. By providing robust empirical evidence in a relatively under-documented field, this study positions prompting as a core mechanism for trustworthy human-AI collaboration. Rather than viewing prompt design as a purely technical optimisation task, as in traditional prompt engineering, this paper presents prompting as a form of linguistic engineering wherein the semantic structure of language connects human intent with machine interpretation. This approach is particularly pertinent in high-stakes, information-sensitive domains, offering broader applicability in contexts where non-experts must reliably engage with AI systems.


_This work was supported by the European Union under Action 101158604 — NORDIS, funded through the DIGITAL-2023-DEPLOY-04-EDMO-HUBS call by the European Health and Digital Executive Agency._
