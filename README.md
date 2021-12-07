# Recomendação de documentos no domínio jurídico para o projeto Querido Diário

This work proposes a recommendation system for official diaries content available in [“Querido Diário”](https://queridodiario.ok.org.br). 

For tokenization of the input data, we use the tokenizer of the trained agent in [BERTimbau](https://github.com/neuralmind-ai/portuguese-bert) ([BERT](https://github.com/google-research/bert) agent trained in Portuguese).

We use BERTimbau's embeddings to feed a KNN classifier, which is used in the semantic content recommendation task.
