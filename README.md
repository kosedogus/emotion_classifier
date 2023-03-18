This model is a fine-tuned version of roberta-base on the emotion dataset. It achieves the following results on the evaluation set:

Loss: 0.1669

Accuracy: 0.94

F1: 0.9404


Training procedure
The model has trained twice. In the first run with 3 epochs, in the second run with 5.

Training hyperparameters
The following hyperparameters were used during training:

learning_rate: 2e-05

train_batch_size: 64

eval_batch_size: 64

seed: 42

optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08

lr_scheduler_type: linear

num_epochs: 8



Framework versions

Transformers 4.13.0

Pytorch 1.13.1+cu116

Datasets 2.8.0

Tokenizers 0.10.3
