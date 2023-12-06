This project leverages the Hugging Face Transformers library to perform text summarization on a given file using the BART (Facebook's denoising autoencoder for sequence-to-sequence pre-training) model. 
The process involves:

Loading the Summarization Pipeline:
The project utilizes the Hugging Face Transformers library to load a pre-trained summarization pipeline specifically using the BART-large model.

Reading Text from File:
The content of a specified text file ('Ch1_cleaned.txt') is read.

Text Chunking:
The input text is split into smaller chunks, with the chunk size being adjustable.

Generating Summaries:
The summarizer processes each chunk, producing concise summaries.
Parameters such as max_length, min_length, length_penalty, num_beams, and early_stopping are
