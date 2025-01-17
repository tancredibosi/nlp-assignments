# NLP Assignments
Two assignments for the AI master degree course "Natural Language Processing". These projects aim to discriminate sexist and non-sexist tweets in different ways.
The two reports show briefly the ideas and the results.

### Assigment 1
This assignment tries to solve the classification of tweets task by training two bi-directional LSTM models from scratch and fine-tuning a pre-trained version of RoBERTa specifically designed for hate speech detection.
We compared these models on the same dataset and conducted analyses on the impact of out-of-vocabulary (OOV) tokens on the final results.
Additionally, we investigated how the embedding dimension affects accuracy and F1 score.

### Assignment 2
This assinment tries to solve the same task (different dataset) by making pre-trained LLMs (Mistral v3 and Llama v3.1) choose the label of the classification problem.
We compared these models on the same dataset using zero-shot prompting and few-shot prompting; then we conducted analyses on the generated responses and on the general behavior of the LLMs.
Additionally, we investigated how these models perform on the Assignment 1 dataset, comparing the results with the models used in the previous experiment.
