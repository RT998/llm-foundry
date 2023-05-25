# G-Eval

This is a starting point for implementing [G-Eval: NLG Evaluation using GPT-4 with Better Human Alignment](https://arxiv.org/abs/2303.16634), which is becoming a common evaluation technique in evaluating chat/instruction-tuned models.

In `open_evals` we collect some common open-ended questions which are commonly used as prompts to compare domain-general models.

The most repeatable way to run this is to run an open-ended eval through a model and store the prompt and responses in a JSONL file with the keys `prompt` and `response`. Then call this script with that file as the `model1` argument.