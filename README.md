# Transformer from scratch using PyTorch
![pytorch](https://github.com/Kirouane-Ayoub/transformer_from_scratch-PyTorch/assets/99510125/ea0f83f2-10eb-4323-a104-0ff1c0412eb4)<svg height="310" preserveAspectRatio="xMidYMid" viewBox="0 0 256 310" width="256" xmlns="http://www.w3.org/2000/svg"><path d="m218.281037 90.106412c50.291951 50.291951 50.291951 130.968622 0 181.609823-49.244202 50.291951-130.2701229 50.291951-180.5620738 0s-50.2919509-131.317872 0-181.609823l90.1064118-90.106412v45.053206l-8.381992 8.3819918-59.7216913 59.7216912c-37.7189632 37.020464-37.7189632 97.789905 0 135.508868 37.0204638 37.718963 97.7899043 37.718963 135.5088673 0 37.718964-37.020464 37.718964-97.789904 0-135.508868zm-45.053206-5.5879945c-9.258493 0-16.763984-7.5054912-16.763984-16.7639837s7.505491-16.7639836 16.763984-16.7639836c9.258492 0 16.763983 7.5054911 16.763983 16.7639836s-7.505491 16.7639837-16.763983 16.7639837z" fill="#ee4c2c"/></svg>

![eAKQu](https://github.com/Kirouane-Ayoub/transformer_from_scratch/assets/99510125/4d676a46-4f31-4cea-91e0-00825aa5730a)


A transformer is a neural network architecture that relies on the parallel multi-head attention mechanism. It was first introduced in the paper "Attention Is All You Need" by Ashish Vaswani et al. in 2017.

Transformers have become the dominant approach for natural language processing (NLP) tasks, such as machine translation, text summarization, and question answering. They have also been used for other tasks, such as image captioning and speech recognition.

The key difference between transformers and other neural network architectures is the use of attention. Attention allows transformers to learn long-range dependencies between different parts of the input sequence. This is important for NLP tasks, where the meaning of a word can depend on the words that come before and after it.

Transformers are also more efficient than other neural network architectures. They can be trained on large datasets using parallel processing, which makes them faster to train.

Here are some of the key components of a transformer:

## Self-attention: 
Self-attention is a mechanism that allows a transformer to learn the relationship between different parts of the input sequence. It does this by computing a weighted sum of the representations of all the other words in the sequence.

## Multihead attention: 
Multihead attention is a generalization of self-attention that allows a transformer to learn multiple relationships between different parts of the input sequence. This is done by computing a weighted sum of the representations of the input sequence, each weighted by a different attention vector.

## Positional embeddings: 
Positional embeddings are used to encode the order of the words in the input sequence. This is important for NLP tasks, where the meaning of a word can depend on its position in the sentence.

## Feedforward neural networks: 
Feedforward neural networks are used to map the output of the attention layers to a final representation of the input sequence.
