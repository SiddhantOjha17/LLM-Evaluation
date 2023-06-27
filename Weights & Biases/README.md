# How to use W&B Prompts with OpenAI evals
W&B Prompts is a tool that makes it easy to run OpenAI evals. With just one click, you can run any evaluation from the OpenAI Evals repository.

To use W&B Prompts, you will need to:

1. Clone a preset or define your own config.
2. (Optional) Try some prompt engineering by changing the registry or model.override_prompt.
2. Select the W&B Global CPU queue and a destination project.
3. Click the Launch now button.
4. The generated report will include key performance and cost metrics, as well as a plot showing how performance has changed over every version of the evaluation. The report also includes data lineage and a preview of the registry where you can see the artifacts that are the input to and output of the job.

## Launch
Launch is a feature in Weights & Biases that allows you to scale your machine learning workflows to larger datasets and compute resources.

Launch works by creating a blueprint for your workflow, which includes the code, data, and infrastructure you need to run your experiments.

Launch then submits your workflow to a queue of workers, which will execute your code and collect the results.

Launch provides a dashboard where you can track the progress of your workflows and view the results.

## Here are some of the benefits of using Launch:

1. Efficiency: Launch can help you scale your machine learning workflows to larger datasets and compute resources, which can lead to faster training times and better results.
2. Reproducibility: Launch ensures that your workflows are reproducible, so you can easily share your results with others.
3. Cost savings: Launch can help you save money on compute costs by distributing your workflows across multiple workers.

Here are some additional resources:

* [W&B Prompts documentation](https://wandb.ai/site/prompts)
* [OpenAI Evals repository](https://github.com/openai/evals)
* [Example report](https://wandb.ai/wandb_fc/openai-evals/reports/OpenAI-Evals-Demo-Using-W-B-Prompts-to-Run-Evaluations)
* [Launch documentation](https://docs.wandb.ai/guides/launch)
