# Como instalar e executar o projeto
É preciso abrir o arquivo "Desafio.ipynb" no Jupyter Notebook e baixar a base de dados "desafio_indicium_imdb.csv"<br/> 
Pacotes utilizados e suas versões:

pandas 2.2.1<br/> 
numpy 1.26.4<br/> 
matplotlib.pyplot 1.16.0<br/> 
seaborn 0.13.2<br/> 
plotly.express 5.22.0

(Lista completa no arquivo requirements.txt)

# Desafio
Você foi alocado em um time da Indicium contratado por um estúdio de
Hollywood chamado PProductions, e agora deve fazer uma análise em cima de um
banco de dados cinematográfico para orientar qual tipo de filme deve ser o próximo
a ser desenvolvido. Lembre-se que há muito dinheiro envolvido, então a análise deve
ser muito detalhada e levar em consideração o máximo de fatores possíveis.

# Entregas
1. Faça uma análise exploratória dos dados (EDA), demonstrando as principais
características entre as variáveis e apresentando algumas hipóteses
relacionadas. Seja criativo!
2. Responda também às seguintes perguntas:
a. Qual filme você recomendaria para uma pessoa que você não
conhece?
b. Quais são os principais fatores que estão relacionados com alta
expectativa de faturamento de um filme?
c. Quais insights podem ser tirados com a coluna Overview? É possível
inferir o gênero do filme a partir dessa coluna?
3. Explique como você faria a previsão da nota do imdb a partir dos dados.
Quais variáveis e/ou suas transformações você utilizou e por quê? Qual tipo
de problema estamos resolvendo (regressão, classificação)? Qual modelo
melhor se aproxima dos dados e quais seus prós e contras? Qual medida de
performance do modelo foi escolhida e por quê?
4. Supondo um filme com as seguintes características:

        {'Series_Title': 'The Shawshank Redemption',
        'Released_Year': '1994',
        'Certificate': 'A',
        'Runtime': '142 min',
        'Genre': 'Drama',
        'Overview': 'Two imprisoned men bond over a number of years,
        finding solace and eventual redemption through acts of common
        decency.',
        'Meta_score': 80.0,
        'Director': 'Frank Darabont',
        'Star1': 'Tim Robbins',
        'Star2': 'Morgan Freeman',
        'Star3': 'Bob Gunton',
        'Star4': 'William Sadler',
        'No_of_Votes': 2343110,
        'Gross': '28,341,469'}
   
Qual seria a nota do IMDB?
