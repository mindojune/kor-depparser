# Transition-based Dependency Parser for Korean: in progress

## Pipeline
1. tokenizer
2. word embedding vector
3. transition classifier - a seq2seq model or a transformer


## Oracle for generating training examples

## Evaluation Metrics
- refer to: https://www.aclweb.org/anthology/W17-0411
- UAS (Unlabeled Attachment Score): measure if the tree has a correct head/arc structure
- LAS (Labeled): also measures the accuracy of arc labels

