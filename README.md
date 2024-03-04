# PredArg-Template_Extraction

This repository contains the resources for a work in progress about extracting predicate-argument templates that correspond to DBpedia triples to be used as input for the rule-based generator FORGe. The project is currently on pause and may be continued in 2025.

For the moment, we only released the code for assessing the similarity between a triple and a candidate text. The Colab notebook allows for reproducing the experiments described in our [Depling'23 paper](https://aclanthology.org/2023.depling-1.9/). Unfortunately we lost the seeds of the original experiment, so the exact numbers reported in the paper may not be reproduced.

Sentence_similarity_WebNLG-fineTune-evaluate.ipynb contains:
- A part for creating data for fine-tuning a Transformers model on the triple/sentence task.
- A part for creating a fine-tuned model.
- A part for evaluating the fine-tuned model and the corresponding off-the-shelf model. 



