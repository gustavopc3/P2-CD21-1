# P2-CD21-1
   No projeto 2 da disciplina Ciência dos Dados do segundo semestre de Engenharia do Insper, foi pedido que descrevêssemos o processo de análise de um dataset a fim de prever uma variável principal (TARGET) em função de demais outras variáveis que poderiam influenciar o seu comportamento (FEATURES). Dessa forma, seriamos capazes de prever rótulos ou informações numéricas para a variável target escolhida a partir de técnicas de classificação, como regressão linear, decision tree, random forest, entre outras.


   Para isso, decidimos avaliar o comportamento da população em relação a atividades físicas durante a pandemia do Coronavírus, visto que os órgãos reguladores tiveram que criar inúmeras restrições ao estilo de vida da população para conter a disseminação do vírus. Queriamos avaliar a frequência de exercícios semanais que as pessoas estavam realizando durante a pandemia, e por não existir um dataset que já nos fornecesse, decidimos realizar um Google Forms com diversas perguntas relacionadas ao tema e as informações de cada um dos participantes. Dessa forma, nos baseamos em recomendações de especialistas da área da saúde para definir a frequência semanal recomendada de atividades físicas que uma pessoa deve ter para ter uma melhor qualidade de vida e uma saúde melhor.
	
	
   Como estávamos um pouco apreensivos com a receptividade dos participantes ao nosso formulário, decidimos pegar apenas algumas informações pessoais básicas, mas que nos guiasse nas condições fisiológicas de cada participante. Além disso, fizemos várias perguntas sobre a frequência, forma e tempo de exercício estimado que elas realizam por semana. No final, ficamos surpresos com a participação de tantas pessoas, e conseguimos dados de 170 participantes.
	
	
   A partir da base de dados, a ideia é criar 2 modelos de predição para a frequência semanal de exercícios de uma pessoa dentro da população brasileira com base nas características fisiológicas e possíveis impedimentos que a pandemia possa ter causado em suas rotinas de atividades físicas. Portanto, a variável Target escolhida foi a frequência semanal de exercícios físicos, enquanto o restante das informações serão estudadas para que seja possível determinar se elas influenciam, ou não, a variável Target determinada.
   
   Como a nossa variável target é QUANTITATIVA, decidimos escolher as seguintes técnicas de classificação: 
    
   O repositório git do trabalho contém o arquivo do Jupyter Notebook denominado `Projeto2.ipynb`, no qual é feito a análise dos dados, os modelos de predição, as suas respectivas validações e a conclusão do trabalho. Além dele, consta também a base de dados `"Pesquisa.xlsx"`, que contém os dados que serão utilizados no notebook.

   Link da pesquisa: https://docs.google.com/forms/d/1ipv8PgUMkudfi-mbXNFdrKsHpOQUSKgA4RBEw2M3X5s/edit#responses

* Gustavo Pinheiro de Carvalho
* Maria Eduarda Mourão
* Gabriel Penna de Lima
* Celina Vieira de Melo
