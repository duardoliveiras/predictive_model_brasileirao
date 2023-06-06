# Predictive Model Brasileirão

Esse projeto foi desenvolvido como forma de avaliação para a disciplina de Inteligência Artificial da Universidade Federal de Mato Grosso 

## Começando

Para rodar o projeto, o caminho mais fácil é você acessar o colab.research.google.com e importar o arquivo `model_predictive_brasileirao_ipynb` 
Com ele importado será necessario extrair o .ZIP `IA_FUTEBOL_DADOS.ZIP` esse zip contém a pasta com as bases de dados necessários para rodar o projeto
Então você pode enviar essa pasta para o google drive na pasta raíz e rodar tranquilamente.

Você pode estar realizando a cópia do notebok a partir desse link público:
https://colab.research.google.com/drive/1D62UnVOGGD_yGNpGJZMrca2ELaRf-ORR?usp=sharing

### Pré-requisitos

Conta Google


## Executando os testes

Para executar o projeto, você pode apertar Ctrl + F9 que vai executar todas as célular notebooks. Ao final do projeto você irá ter acesso aos gráficos e tabelas comprovando o desempenho do modelo proposto. Caso queria testa-lo você mesmo, recomendo adicionar uma célula nova utilizando a função `  previsao_times(mandante, visitante) `.
Essa função retorna a probabilidade do time mandante ganhar, a probabilidade do time visitante ganhar e a probabilidade de resultar em empate.

### Analise os testes de ponta a ponta
Utilizei de uma amostra aleatória obtida do Brasileirão 2023 roda 6/38 e obtemos o seguinte resultado:
ML: Modelo preditivo elaborado
R: Resultado Real

* Bahia 2 x 3 Flamengo `ML: Flamengo R: Flamengo`
* Fluminense 2 x 0 Cuiaba `ML: Fluminense R: Fluminense`
* Palmeiras 1 x 1 Bragantino `ML: Palmeiras R: Empate`
* Atletico-MG 2 x 0 Internacional `ML: Atletico-MG R: Atletico-MG`
* Gremio 0 x 0 Fortaleza `ML: Gremio R: Empate`
* Vasco 0 x 1 Santos `ML: Santos R: Santos`
* Corinthians 1 x 1 Sao paulo `ML: Empate R: Empate` 
* Athletico-PR 3 x 2 Coritiba `ML: Coritiba R: Athletico-PR`
* Goias 2 x 1 Botafogo-RJ `ML: Goias R: Goias`
* America-MG 0 x 4 Cruzeiro `ML: Cruzeiro R: Cruzeiro`

## Construído com

* [numpy](https://pypi.org/project/numpy/) - Cálculos científicos
* [pandas](https://pypi.org/project/pandas/) - Manipulação de dados
* [seaborn](https://seaborn.pydata.org/) - Exibição de dados
* [matplotlib.pyplot](https://matplotlib.org/stable/tutorials/introductory/pyplot.html) - Plotagem de gráficos
* [warnings](https://docs.python.org/3/library/warnings.html) - Controle de alertas 
* [xgboost](https://xgboost.readthedocs.io/en/stable/) - Método de machine learning
* [sklearn](https://pypi.org/project/scikit-learn/) - Método de machine learning e análise de dados


## Autores

Mencione todos aqueles que ajudaram a levantar o projeto desde o seu início

* **Eduardo Oliveira** - [Eduardo Oliveira](https://github.com/duardoliveiras)
* **Matheo Bonucia** - [Matheo Bonucia](https://github.com/tanakagl)

Você também pode ver a lista de todos os [colaboradores](https://github.com/usuario/projeto/colaboradores) que participaram deste projeto.

## Expressões de gratidão

* Gostaria de agradecer ao professor Mestre [Frederico S. Oliveira](https://github.com/freds0) por sua orientação e apoio no ensino de machine learning, graças ao seu conhecimento compartilhado pudemos desenvolver esse projeto.
