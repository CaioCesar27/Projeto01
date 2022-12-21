# Análise de Dados - Base dados Amazon Prime


## Introdução
O Objetivo desta análise é colocar em prática meus conhecimentos e levantar insights relevantes para tomadas de decisões, simulando um projeto em um ambiente organizacional. Apesar de ser uma análise básica é bastante eficaz num contexto organizacional para insigths imediatos.

## Desenvolvimento 
#### Análise Exploratória
-  A primeira parte é a mais importante, onde buscamos enteder os dados e o modelo de negócio em questão. É possível notar que o conjunto de dados da Amazon Prime traz dados faltante em relação país, diretor, elenco, data_add (quando o filme foi adicionado na plataforma) e classificação, sendo assim já compromete parte da nossa análise.

    Em relação o tamanho do dataset, possui 9668 linhas e 12 colunas dentre elas:
        'id', 'tipo', 'titulo', 'diretor', 'elenco', 'pais', 'date_add', 'data_lancamento', 'classificacao', 'duracao', 'categoria', 'descricao'. A coluna país e data_add tinham 90% dos dados faltantes.
    
#### Tratamento dos Dados
- Nesta etapa comecei a tratar o dataset principalmente na alteração dos nomes das colunas para que nenhum espaço ou acento venha atrapalhar na manipulação dos dados; alterei o type das colunas para datetime64, pois estavam como object e realizei outras alterações no dataset.

#### Insigths
* De acordo com a base de dados analisada é possível notar que a plataforma tem mais filmes do que séries sendo 7814 filmes e 1854 séries onde a maioria é do gênero drama.
* Maioria dos filmes foram produzidos nos EUA, em segundo lugar India, porém a base de dados na coluna país tem 90% dos dados nulos.
* Referente a classficação dos filmes e séries de acordo com EUA, tem mais filmes e séries para os adultos sendo 1310 e 1217 para crianças e adolescentes.
* O diretor com mais filmes lançados na plataforma é o Mark Knigth.
* Ao analisar os dados no gráfico boxplot é possível verificar que 50% dos dados em relação a duração dos filmes está em 91 minutos, neste gráfico apresenta alguns outliers, porém realmente esses dados são verídicos onde o filme com maior duração tem 601 minutos.

#### Conclusão
* Apesar de se tratar de uma análise rápida foi possível extrair vários insigths na qual a empresa poderia trabalhar e aprofundar e expandir ainda mais o catálogo de filmes e séries. Seria interessante explorar qual filme ou série teve mais acesso, qual faixa etária acessa quais tipos de filmes e dentre outras análises.