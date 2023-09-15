# Text Similarity Techniques Exploration

In this Jupyter notebook, I've explored several text similarity techniques to measure the likeness between sentences or documents. These techniques are crucial in various Natural Language Processing (NLP) applications, and I've conducted experiments to better understand their strengths and weaknesses.

## Techniques Explored

1. **TF-IDF (Term Frequency-Inverse Document Frequency):** TF-IDF is a classic method for quantifying the importance of words in a document relative to a collection of documents. It can be used to compute the similarity between documents based on their word frequencies.

2. **BLEU (Bilingual Evaluation Understudy):** BLEU is primarily used for machine translation evaluation but can also be adapted to measure the similarity between two sentences. It evaluates the overlap of n-grams between reference and generated sentences.

3. **Word2Vec:** Word2Vec is a popular word embedding technique that can be used to represent words as dense vectors. Sentence similarity can be calculated using the vectors of their constituent words.

4. **Doc2Vec:** Doc2Vec extends Word2Vec to document-level embeddings, allowing you to calculate similarity between entire documents.

5. **LDA (Latent Dirichlet Allocation):** LDA is a topic modeling technique that can be applied to discover topics in a collection of documents. You can measure document similarity based on their topic distributions.

6. **BERT Classifier:** BERT (Bidirectional Encoder Representations from Transformers) is a pre-trained transformer-based model. Fine-tuning a BERT model as a classifier can be used to measure sentence similarity.

7. **Sentence Transformers:** Sentence Transformers are pre-trained models designed specifically for encoding and measuring sentence similarity.

Throughout the notebook, I've provided code examples and explanations for each of these techniques, allowing you to gain insights into their applications and performance in various text similarity tasks.

Feel free to explore the notebook and use these techniques in your own NLP projects. Each section provides code and explanations to help you get started.
