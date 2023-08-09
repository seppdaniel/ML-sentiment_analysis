## Sistema de Análise de Sentimentos

- Um sistema de análise de sentimentos é uma aplicação de processamento de linguagem natural (NLP) que tem como objetivo identificar e classificar as emoções e sentimentos expressos em textos. Ele utiliza algoritmos e técnicas de Machine Learning para atribuir rótulos de polaridade, como positivo, neutro ou negativo, a um determinado texto, com base na tonalidade emocional das palavras e frases presentes. Ele permite que máquinas entendam a essência emocional das palavras, proporcionando insights valiosos sobre como as pessoas se sentem em relação a diferentes tópicos.
### Neste projeto, explorei a magia da programação e do Machine Learning para criar um sistema que pode discernir sentimentos com base nas palavras utilizadas.

## Exemplos de Aplicações:

- Monitoramento de Mídias Sociais:
Empresas utilizam sistemas de análise de sentimentos para acompanhar a opinião pública sobre seus produtos, marcas ou serviços. Por exemplo, podem avaliar como as pessoas estão reagindo a um novo lançamento e identificar rapidamente problemas ou elogios.

- Avaliação de Avaliações de Produtos:
Plataformas de comércio eletrônico podem empregar essa tecnologia para analisar avaliações e comentários de clientes sobre produtos. Isso ajuda a entender se os consumidores estão satisfeitos ou insatisfeitos com um produto específico.

- Feedback de Atendimento ao Cliente:
Empresas de serviços ao cliente podem utilizar análise de sentimentos para analisar as interações com os clientes. Isso ajuda a identificar a satisfação do cliente e a detectar problemas potenciais em tempo real.

🛠️ Como o Sistema Funciona: Passo a Passo

- Importando Bibliotecas: Começamos importando as bibliotecas essenciais para processar e analisar textos, como NLTK e Numpy.
- Pré-processamento de Tweets: Criei uma função para processar os tweets, eliminando links, símbolos e transformando palavras em suas formas radicais.
- Construindo Frequências: Uma etapa crucial! Construí um dicionário de frequências associando palavras aos seus sentimentos (positivos ou negativos) para treinar o modelo.
- Selecionando Dados de Treino e Teste: Utilizei conjuntos de tweets positivos e negativos do Twitter para treinar e testar o modelo.
- Extração de Recursos: Desenvolvi uma função para extrair recursos de um tweet e transformá-los em um vetor numérico.
- Treinando o Modelo: Construí um modelo de Regressão Logística a partir do zero! Utilizei a descida de gradiente para ajustar os pesos do modelo.
- Testando a Precisão: Avaliei a precisão do modelo usando tweets de teste e medindo a quantidade de previsões corretas.
- Fazendo Previsões: Criei uma função para prever sentimentos em um tweet personalizado.

💬 Vejam só um exemplo:

Você pode digitar qualquer frase e meu sistema dirá qual é o sentimento expresso. Por exemplo, se você digitar "I am really happy whit this project!", meu sistema classificará como "Sentimento: Positivo". E se escrever "I am a little bit frustrated with this.", ele dirá: "Sentimento: Negativo".


#IA #NLP #machinelearning #sentimentanalysis

