# Transition-based  Universal Dependency Parser for Korean: in progress

## Pipeline
1. preprocessing stage
	1. morphological analysis, lemmatize
	1. tokenizer: which tokenizer?
2. word embedding vector: which embedding?
3. transition classifier - a seq2seq model or a transformer


## Oracle for generating training examples

## Evaluation Metrics
- UAS (Unlabeled Attachment Score): measure if the tree has a correct head/arc structure, percentage of *words* that have been assigned the correct head,arc
- LAS (Labeled): also measures the accuracy of arc labels

