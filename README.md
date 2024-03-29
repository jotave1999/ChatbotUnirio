# ChatbotUnirio

Este repositório guarda o código fonte dos experimentos realizados na pesquisa de ICC `APLICAÇÕES DE TÉCNICAS DE PROCESSAMENTO DE LINGUAGEM NATURAL A UM CHATBOT ACADÊMICO` realizada pelo aluno da Universidade Federal do Estado do Rio de Janeiro, João Victor Antunes Figueira.

## Organização das Pastas

Cada pasta deste repositório guarda os notebooks de cada experimento realizado até o momento na pesquisa.

As pastas `Primeiros Testes` e `Segundos Testes` guardam o código das redes neurais artificais LSTM que foram utilizadas até o momento

A pasta `CNN` guarda o código das redes neurais artificiais convolucionais que foram utilizadas até o momento.

A pasta `CNN+LSTM` guarda o código das redes neurais artificiais que utilizam tanto um modelo `CNN` quanto um modelo `LSTM` que foram utilizadas até o momento.

## Word Embeddings

Nesta pesquisa foram utilizados os Word Embeddings da USP que podem ser encontrados no site [Repositório de Word Embeddings do NILC](http://www.nilc.icmc.usp.br/embeddings).

Todos os Word Embeddings são do Modelo Word2Vec que variam entre `SKIP-GRAM` e `CBOW` de dimenções de 50 camadas a 1000 camadas.

## Como rodar os experimentos

Para rodar os notebooks com os experimentos é recomendado o uso do `ANACONDA3` ou algum gerenciador de ambientes em Python.

Tendo criado o ambiente basta baixar os Word Embeddings do site referenciado acima, inseri-los no diretório raiz do projeto, e rodar as células do notebook.
