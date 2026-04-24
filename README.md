# Aprendizagem Baseada em Projetos Integradores (API)
A aprendizagem baseada em projetos integradores (API) segue uma abordagem dinâmica e interativa, inspirada nas metodologias ágeis. Os alunos desenvolvem conhecimentos e habilidades ao longo de projetos práticos, divididos em ciclos de planejamento, execução e retrospectiva. A metodologia valoriza a interdisciplinaridade, promovendo a colaboração entre diferentes áreas para resolver desafios do mundo real, com entregas incrementais e adaptação contínua — alinhadas às práticas do mercado.

# :dart: Índice
* [Objetivo do Projeto](#Objetivo)
* [Equipe](#equipe)
* [Backlog do Produto](#Cronograma-das-Sprints)
* [Dashboard](#Dashboard)
* [Competências desenvolvidas](#competências-desenvolvidas)

# Projeto (API)
Este projeto tem como objetivo analisar o desempenho e a eficiência de terminais portuários, a partir de dados operacionais e logísticos, buscando gerar insights estratégicos para otimização das operações.

   # Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Team Member |  Joyce Barros       |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/joyce-moura-barros-ab0286284?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JoyceMBP)        |
| Scrum Master  | João P.|       [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-pedro-vargas-dos-santos-973b44329?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/joao-p-vargas) |
| Scrum Master   | Fernanda S             |        [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/emilly-ajala-15a34622a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Imyouremi)     |
|  Team Member  | Emilly Ajala                |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/alana-ro?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Alana-Rodrigues-01)        |
|  Product Owner  | Cauan C.                 |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://br.linkedin.com/in/cauan-cesar-214b77251) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/C4U4N) |

# Objetivo do Projeto

Este projeto tem como objetivo desenvolver uma API para análise de dados portuários, visando:

- A eficiência operacional, comparando a produtividade dos terminais com base na infraestrutura disponível e no volume de carga movimentada
- A avaliação dos tempos de operação, identificando portos mais ágeis e aqueles com maiores tempos de espera
- A análise das paradas portuárias, destacando os principais motivos (Top N) e possíveis padrões sazonais ao longo do ano
- O estudo da movimentação portuária, identificando os portos com maior volume de carga e a quantidade de operações realizadas mensalmente
- A análise dos tipos de carga, evidenciando quais são as mais movimentadas nos terminais

# Tecnologias Utilizadas
- Jira Software
- Power BI
- WhatsApp
- Python (Colab)
- Mysql
- Jira

# # Product Backlog
  
| Rank | Prioridade | User Story                                                                                                                                              | Estimativa | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
1 |Alta | Como analista, quero coletar dados da ANTAQ para ter uma base confiável para análise |5| 1 
2 |Alta|  Como analista, quero filtrar os dados para os anos de 2024 e 2025 para manter relevância temporal |3| 1 |
3 | Alta | Como analista, quero tratar e limpar os dados para evitar inconsistências |8 | 1 |
4 | Média |  Como analista, quero padronizar nomes de portos para garantir uniformidade|  5|  1 |
5 | Média | Como analista, quero classificar os motivos de parada para facilitar análise futura.| 5| 1 |
6 |Média | Como analista, quero estruturar os dados em gráficos e tabelas para uma melhor visualização.| 3 | 1 |
7|  Alta | Como usuário, quero acessar endpoint de paradas para visualizar motivos e tempos.|5 | 2 | 
8 | Alta | Como usuário, quero acessar endpoint de produtividade para analisar desempenho dos portos.| 5 | 2 |
9 | Média | Como analista, quero calcular tempo total de parada para entender gargalos| 3 | 2 |
10 | Média |  Como analista, quero calcular produtividade (volume por hora) para medir eficiência |5 | 2 |
11 | Média | Como analista, quero criar indicador de eficiência operacional para comparação entre portos. |5 |2 |
12 | Alta |  Como gestor, quero visualizar um ranking de eficiência dos portos para tomada de decisão. | 5| 3 | 
13| Alta | Como analista, quero comparar portos brasileiros com internacionais para avaliar competitividade| 8 | 3 |
14 | Alta | Como usuário, quero visualizar dashboards interativos para entender os dados facilmente.| 8 | 3 |
15 | Média |C Como gestor, quero identificar principais motivos de parada para reduzir ineficiências| 5 | 3 |
16 | Média |  Como analista, quero gerar gráficos de produtividade para análise visual rápida| 3 | 3 |
17 |  Média |Como stakeholder, quero uma visão consolidada dos dados para apoiar decisões estratégicas| 5 | 3 |


# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| 01                | 27/03/2026 | Concluida | [MVP](MVP/sp1.md)  |
| 02                | 24/04/2026 | Em progresso  | [MVP](MVP/sp2.md)  |
| 03                | 15/05/2026 | a fazer | [MVP](MVP/sp2.md)  |
| Feira de Soluções               | 18/06/2026 | a fazer | [MVP](MVP/sp3.md)  |



  

<p align="center">
  <img src="https://github.com/user-attachments/assets/b50cfb6f-79b2-490e-b4bb-d29228ccdbbe" alt="Imagem exemplo">
</p>
