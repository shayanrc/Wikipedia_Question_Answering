# Wikipedia Question Answering

## Goal
Create NLP pipeline(s) which perform well on Wikipedia based question datasets.


## Datasets


### HOTPOTQA
HOTPOTQA is a dataset which contains 113k Wikipedia-based question-answer pairs with four key features. These are questions that require finding and reasoning over multiple supporting documents to answer, the questions are diverse and not constrained to any pre-existing knowledge bases or knowledge schemas, sentence-level supporting facts required for reasoning, allowing QA systems to reason with strong supervision and explain predictions and a new type of factoid comparison questions to test QA systems’ ability to extract relevant facts and perform necessary comparison.

**Size**: 113000

### SQuAD
Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset which includes questions posed by crowd-workers on a set of Wikipedia articles and the answer to every question is a segment of text, or span, from the corresponding reading passage, or the question might be unanswerable. The dataset was presented by researchers at Stanford University and SQuAD 2.0 contains more than 100,000 questions.

**Size**: 100000

### Natural Questions (NQ)
Natural Questions (NQ) is a new, large-scale corpus for training and evaluating open-domain question answering systems. Presented by Google, this dataset is the first to replicate the end-to-end process in which people find answers to questions. It contains 300,000 naturally occurring questions, along with human-annotated answers from Wikipedia pages, to be used in training QA systems. Furthermore, researchers added 16,000 examples where answers (to the same questions) are provided by 5 different annotators which will be useful for evaluating the performance of the learned QA systems.

**Size**: 16000

### Question Answering in Context (QuAC)
Question Answering in Context (QuAC) is a dataset for modeling, understanding, and participating in information seeking dialog. In this dataset, instances consist of an interactive dialogue between two crowd workers which is a student who poses a sequence of freeform questions to learn as much as possible about a hidden Wikipedia text, and a teacher who answers the questions by providing short excerpts (spans) from the text. It contains 14K information-seeking QA dialogs which include 100K QA pairs in total.

**Size**: 14000
