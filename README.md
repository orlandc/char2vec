# Char2vec Ancora Corpus CESS_CAST v3.0

## English

This code implements the skip-gram algorithm to find vector representations for the letters of the alphabet. It does this by taking a body of text (stored in /raw) and training a shallow neural network to predict characters c_(n-1) and c_(n+1) given c_n. In this implementation, the word2vec model of the library is used, which has as input vector character representations

The result this algorithm has is that characters which appear in similar contexts will have similar encodings. For example, vowels often appear in similar contexts, so we would expect them to have similar encodings.

## Spanish

Este código implementa el algoritmo skip-gram para encontrar representaciones vectoriales para las letras del alfabeto. Lo hace tomando un cuerpo de texto (almacenado en la carpeta /raw) y entrenando una red neuronal poco profunda para predecir los caracteres c_(n-1) y c_(n + 1) dado c_n. En esta implementación, se usa el modelo word2vec de la librería gensim, el cual tiene como entrada representaciones vectoriales de caracteres.

El resultado que tiene este algoritmo es que los caracteres que aparecen en contextos similares tendrán codificaciones similares. Por ejemplo, las vocales a menudo aparecen en contextos similares, por lo que esperaríamos que tuvieran codificaciones similares.

### Resultados

| Implementación a nivel de palabras | Implementación a nivel de Oraciones |
| :----:                             | :----:                              |
| [ref]:(/img/emb1.png)              | [ref]:(/img/emb2.png)               |
| [ref]:(/img/emb1-multi.png)        | [ref]:(/img/emb2-multi.png)         |
