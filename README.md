Comparative Study of Open-Source Large Language Models' Performance in Answering True/False Questions


This project explores the performance of three large language models (LLMs)—Llama2, Mistral 7B, and Zephyr—on a dataset of true/false questions using the Retrieval-Augmented Generation (RAG) technique. The results demonstrate the strengths and limitations of each model in terms of accuracy, precision, recall, and F1 score.


Author:
Deniz Kaya

Project Overview:

The goal of this study is to compare the performance of Llama2, Mistral 7B, and Zephyr models in answering 500 true/false questions. The evaluation metrics used include:

Accuracy
Precision
Recall
F1 score
The models were tested on a subset of the BoolQ dataset, a dataset of yes/no questions extracted from Wikipedia articles. The RAG technique was applied to enhance the performance by retrieving relevant passages before generating answers.

Dataset:

BoolQ Dataset: Comprising 15,942 questions with corresponding passages from Wikipedia.
The dataset was preprocessed before being fed into the models.
Models:
Llama2 (7B):

Showed superior performance across all metrics.
Achieved higher consistency and reliability in generating answers for complex and diverse questions.
Mistral 7B:

Delivered competitive performance, especially in certain test scenarios.
Slightly lagged behind Llama2 but was efficient in handling the tasks with the RAG system.
Zephyr 7B:

Although a capable model, it did not outperform Llama2 or Mistral 7B.
Performed reasonably well with the RAG integration.
Methodology:
Retrieval-Augmented Generation (RAG): This technique was used to retrieve relevant context from the dataset before generating an answer.
Evaluation Metrics: Each model’s performance was evaluated using accuracy, precision, recall, and F1 score.
ChromaDB: A vector database was used to store the preprocessed passages, enabling the models to retrieve and utilize relevant information.
Results:

Llama2 emerged as the best-performing model, with the highest scores in accuracy, precision, recall, and F1 score.
Mistral 7B also performed well, though it slightly lagged behind Llama2 in terms of consistency and precision.
Zephyr 7B, while robust, showed weaker performance compared to the other models but was still competitive in certain test cases.
Conclusion:
The study demonstrates that Llama2 outperforms other models in handling true/false questions, making it a reliable choice for applications requiring high accuracy and consistency. This study provides insights into the strengths and weaknesses of large language models in natural language processing tasks.

How to Run:

Clone the repository.
Install the required libraries from requirements.txt.
Run the provided Jupyter notebooks for each model.

References:
BoolQ Dataset: https://github.com/google-research-datasets/boolean-questions
Llama2: Meta AI
