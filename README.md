# Large Language Models Evaluation

This repository aims to explore and showcase different ways to evaluate Language Models (LLMs). Language models have become increasingly powerful, and it is essential to have robust evaluation methods to assess their performance accurately. This README provides an overview of some evaluation methods covered in this repository.
## Evaluation Methods

### 1. [Big-Bench](https://arxiv.org/abs/2206.04615)
The Beyond the Imitation Game Benchmark (BIG-bench) is a collaborative benchmark intended to probe large language models and extrapolate their future capabilities. The more than 200 tasks included in BIG-bench are summarized by keyword, and by task name.

### 2. [TruthfulQA](https://arxiv.org/abs/2109.07958)
TruthfulQA is a benchmark to measure whether a language model is truthful in generating answers to questions. The benchmark comprises 817 questions that span 38 categories, including health, law, finance, and politics. The authors crafted questions that some humans would answer falsely due to a false belief or misconception.

### 3. [Weights & Biases](https://wandb.ai/wandb_fc/openai-evals/reports/OpenAI-Evals-Demo-Using-W-B-Prompts-to-Run-Evaluations--Vmlldzo0MTI4ODA3)
W&B Launch introduces a connective layer between machine learning practitioners and the high-scale, specialized hardware that powers modern machine learning workflows. Easily scale training runs from your desktop to your GPUs, quickly spin up intensive model evaluation suites, and prepare models for production inference, all without the friction of complex infrastructure.

### 4. Custom Prompts Evaluation using OpenAI
OpenAI provides an API that allows you to interact with their language models programmatically. You can use this evaluation method to generate custom prompts and evaluate the quality, coherence, and relevance of the model's responses. By experimenting with various prompts and evaluating the outputs, you can gain insights into the strengths and weaknesses of your LLM.

## Contributing
Contributions to this repository are welcome! If you have any ideas for additional evaluation methods or improvements to the existing ones, please submit a pull request. Be sure to follow the established guidelines and provide clear documentation for any changes made.

Please make sure to update tests as appropriate.
## Acknowledgments
We would like to express our gratitude to the authors of the TruthfulQA dataset and the BigBenchHard benchmark dataset for their valuable contributions to the field. Additionally, we appreciate the support and services provided by Weights & Biases and OpenAI in enabling the evaluation of language models.

