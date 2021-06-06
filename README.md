# Word_Embeddings_Comparison_for_Sarcasm_Detection
In this project, we propose a Deep Learning architecture for **Sarcasm Detection**, while utilizing pre-trained Word Embeddings from three well-known models: *Word2Vec*, *fastText* and *Glove*.

By taking inspiration from CADE, our intuition is to use a **non-trainable Embedding layer** representing the three models and a Bidirectional Long Term Short Memory (Bi-LTSM) layer.

This model will also be compared to current state-of-the-art approaches for Sarcasm Detection in order to check if we can reach comparable results.

We also try to understand why it works from a **semantic** point of view. Does the accuracy of sarcasm detection depend on the nature of word embeddings?
