# RAG-based Document Retrieval System

![image](https://github.com/Ohmdatazwld5/RAG-for-Document-Retrieval-System/assets/130119515/797e7a7a-a5b2-4192-9615-852e9e2f6279)

![image](https://github.com/Ohmdatazwld5/RAG-for-Document-Retrieval-System/assets/130119515/6d16d9f7-6fdd-42c8-8654-bd0c209992e3)

Install Requirements
For Windows - pip3 install -U torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

-Why RAG?
LLMs, although capable of generating text that is both meaningful and grammatically correct, these LLMs suffer from a problem called 'hallucination'. Hallucination in LLMs is the concept where the LLMs confidently generate wrong answers, that is they make up the wrong answers in a way that makes us believe that is true. This has been a major problem since the introduction of the LLMs. These hallucinations lead to incorrect and factually wrong answers.

*Key Terms*

-Token: A sub-word piece of text. A token can be a whole word, part of a word or group of punctuation characters
        Before the API processes the request, the input is broken down into tokens. 
        1 token ~= 4 chars in English
        1 token ~= 3/4 words
        100 tokens ~= 75 words
        
-Chunking:
Chunking is the process in which we break down a bigger document into smaller pices. There are many chunking stategies there.The simple one is fixed-size chunks. Chosing a chunking strategy has a direct impact on the performance of your system and quality of answers you get.

- Embeddings:
  Embeddings are learned numerical representation of a piece of data. Embeddings are a way to convert text into a long list of numbers. These numbers are special because they dont only capture words but also meanings and relationships between words. Embeddings also referred as vectors.

- Embedding model: A embedding model is accept input data and output a numerical representations. A text embedding model may take in 384 tokens
                   of text and turn into a vector of size 768.

  - Vector/Similarity Search: This aims to 2 vectors which are close together in high-dimensional space. If 2 pieces of similar text passed through
                              an embedding model should have a high similarity score, where as 2 pices of text about different topics will have a
                              similarity score.

  RAG Use Cases:
  - TextBook Question and Answers: RAG helps to improve the answers and references to learn more about that topic

                        
