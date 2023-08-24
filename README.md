# Text Summarization with Transformers

## Project Overview:

This project is an exploration into the world of text summarization using the Transformer architecture, specifically focusing on the decoder aspect. The goal is to build a model capable of effectively summarizing large bodies of text, harnessing the power of attention mechanisms to capture contextual information across sequences.

## Course Details:

This work was done as a part of the **Coursera's NLP with Attention Models** course, exploring the intricate details of attention mechanisms and their implementation in modern NLP tasks.

## Key Features:

1. **Transformer Decoder**: Developed a Transformer decoder from scratch using the Trax deep learning framework. 
2. **Dataset**: Imported and preprocessed the CNN/DailyMail dataset, ensuring data is appropriately structured for training the summarization model.
3. **Tokenization**: Designed custom tokenize and detokenize functions for seamless conversion between text and its tokenized representation.
4. **Attention Mechanisms**:
   - Implemented **scaled dot-product attention** for capturing relationships across different words in a sequence.
   - Incorporated **causal attention mechanisms** to ensure predictions for a particular word only depend on previous words, preserving the sequential nature of text.
   - Utilized **multi-head attention** to capture information from various representation subspaces at different sequence positions.
5. **Optimization Techniques**: Employed the bucketing technique to batch sequences of similar lengths, ensuring efficient and optimized training by reducing the need for excessive padding.

## Notebooks:

1. [Attention Mechanisms](./C4_W2_Ungraded_Lab_1_Attention.ipynb): Dive deep into the three ways of attention - encoder-decoder attention, causal attention, and bi-directional self-attention, and understand how to implement them with dot product attention.
2. [Transformer Decoder](./C4_W2_Ungraded_Lab_2_Transformer_Decoder.ipynb): Understand the intricacies of the Transformer decoder and its various components.
3. [Assignment - Summarization Task](./C4_W2_Assignment.ipynb): Implementation of the text summarization task using the concepts learned, culminating in a model capable of summarizing articles.

## Future Scope:

While the current implementation provides robust summarization capabilities, there's always room for improvement. Future work can explore:
- Inclusion of the encoder component for a complete Transformer architecture.
- Integration with state-of-the-art tokenization methods like BPE or SentencePiece.
- Expansion to other NLP tasks like translation or question-answering using similar architectures.

