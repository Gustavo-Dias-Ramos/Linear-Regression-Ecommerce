# Regressão Linear - Ecommerce

Este projeto apresenta a utilização de regressão linear para tomada de decisão de uma Ecommerce de venda de roupas online.

Regressão linear é uma técnica de análise de dados que utiliza uma equação linear para modelar matematicamente as variáveis, prevendo o valor de uma variável desconhecida (dependente) com base em outra variável conhecida (independente). (AWS Amazon) É uma técnica relativamente simples pois assume a existência de uma relação aproximadamente linear entre as variáveis (James et al., 2013)

Esta análise foi feita como parte do curso 'Python for Data Science and Machine Learning Bootcamp', criado por José Portilla na plataforma Udemy (https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/), e teve como objetivo apresentar os conhecimentos iniciais sobre análise de dados e machine learning.

- James et al., 2013 - An introduction to statistical learning: with application in R. Springer, New York (2013)
- AWS Amazon - O que é regressão linear?. Disponível em: https://aws.amazon.com/pt/what-is/linear-regression/#:~:text=A%20regress%C3%A3o%20linear%20%C3%A9%20uma,independente%20como%20uma%20equa%C3%A7%C3%A3o%20linear.

_________
## Sobre os dados
Neste projeto, vamos utilizar o cenário de uma loja de roupas online, que funciona via App e Website. 
A loja disponibiliza um serviço de aconselhamento in-loco. Os usuários vão até a loja, recebem dicas e conselhos de estilistas e profissionais da moda. Na sequência, podem realizar suas compras, em casa, através do app ou do website.

A loja busca decidir em qual dessas plataformas focar seus esforços de venda. Para isso, utilizaremos regressão linear.

Os dados utilizados são originários da plataforma Kaggle (https://www.kaggle.com/datasets/kolawale/focusing-on-mobile-app-or-website?resource=download) em formato .csv, e apresentam informações sobre usuários de uma Ecommerce de roupas.

Os campos de informação são:

- Email: o e-mail do usuário;
- Address: o endereço do usuário;
- Avatar: a cor do avatar do usuário;
- Avg. Session Length: a média de tempo gasto in-loco na sessão de aconselhamento (em min.);
- Time on App: a média de tempo gasto no App (em min.);
- Time on Website: a média de tempo gasto no Website (em min.);
- Length of Membership:  a quanto tempo o usuário utiliza a loja (em anos);
- Yearly Amount Spent: Quantia gasta anualmente.
