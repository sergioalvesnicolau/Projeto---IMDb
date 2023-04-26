# Projeto - IMDb
 Projeto para o curso de Análise de Dados da Ironhack (ativo).

# Objetivo
 Analisar a lista do top 250 filmes do IMDb. A motivação inicial foi avaliar um viés de tempo para os filmes com maiores notas no site. Como comparação, usou-se a última lista do Sight & Sound e a lista análoga do Letterboxd.

# Métodos
 Webscraping, API, filtering, grouping, visualization, graphics.

# Tecnologias
 Foram usados: Python, Pandas, MySQL e Tableau.

# Descrição
 O projeto tinha a ideia de desenvolver e praticar a extração e visualização de dados. Partiu-se da hipótese de que a lista do IMDb tinha um viés com relação ao ano de lançamento do filme, ou seja, de que filmes avaliados de forma simultânea ao seu lançamento teriam uma nota inflada pelo momento e estariam mais presentes relativamente na lista que os com distanciamento histórico. Justamente por isso, a ideia de recorte inicial foi 1993, ano de lançamento do IMDb no site. A partir de webscraping extraiu-se as três listas com os títulos dos filmes (IMDb, Letterboxd, BFI Sight & Sound). Então, usando a API aberta do IMDb, foram construídos os dataframes completos de cada filme. Por fim, com a conexão com o MySQL e, sucessivamente, com o Tableau, foram desenhados gráficos para a análise sobre o viés na lista do IMDb usando das outras de comparação.

# Conclusão
 A conclusão foi de que foi sim observada uma diferença significativa da quantidades de filmes produzidos pós-1993 (ano em que o IMDb é lançado na internet), o que leva a creer que a avaliação dos usuários do site, quando feita de forma simultânea ao lançamento do filme, pode gerar uma inflação na nota. Além disso, demonstrou-se que, mais que as outras, a lista do IMDb têm indíces de popularidade envolvidos: os filmes tem, em média, maior número de avaliações e estão relativamente mais presentes gêneros mais populares como Ação, Aventura, Animação e Comédia. Por fim, também há de se ressaltar que a lista ainda apresenta uma prepondêrancia de filmes estado-unidenses muito maior que as outras, indicando um viés também de localidade.

# Contato
 https://github.com/sergioalvesnicolau
