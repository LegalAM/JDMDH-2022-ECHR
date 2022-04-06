# JDMDH-2022-ECHR

This repository includes the evaluation results in "Enhancing Legal Argument Mining with Domain Pre-training and Neural Networks".

Six embedding models are used as basic modules for different combinations: ELMo, GloVe, Legal-BERT-base, Legal-BERT-echr, Legal-BERT-harv, Legal-BERT-harv (custom).
The six folders each contains different model combinations with classic neural networks: embedding, embedding+cnn, embedding+bilstm, embedding+resnet.

Each .XLSX file includes four tables: *task1*, *task1-law*, *task2*, *task3-c*, *task3-p*, which respectively include evaluation results for the three argument mining tasks (as well as sub-tasks). Specifically, task1 for argument clause recognition (document level), task1-law for argument clause recognition (section level), task2 for argument relation mining,task3-c for conclusion classification sub-task in argument component classification, and task3-p for premise classification sub-task in argument component classification.