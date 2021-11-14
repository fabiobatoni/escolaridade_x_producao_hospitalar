# 📚  Escolaridade x Produção Hospitalar 💊

Projeto Módulo 1 - BootCamp Data Science Aplicada da Alura
![image](https://user-images.githubusercontent.com/57717982/141686944-37855357-41e1-451a-a868-07d370f98504.png)

# O projeto
Olá! Este projeto tem o intuito de comparar os dados de produção hospitalar e dados de escolaridade dos estados

# Pergunta 

Será que o estado que possui maior escolaridade, gasta mais pelo fato da população ir mais vezes aos hospitais, por terem mais informação, ou gasta menos por saberem se prevenir de doenças, assim evitando a ida ao hospital?

# Os dados
Os dados analisados foram retirados do tabnet, sistema do DATASUS que disponibiliza dados de saúde do Brasil. Comparei os gastos de produção hospitalar com o Censo 2010 sobre escolaridade.

Para a separação entre estes escopos foi utilizado o filtro de procedimento hospitalar do SUS, no próprio tabnet. Na linha Unidade de Federação, Coluna Ano/Mês de Atendimento e no Conteúdo Valor Total, na análise foi selecionado apenas o ano de 2010.

Foi utilizado o filtro de Escolaridade da população de 15 anos ou mais - Brasil, Período de 2010.

Para comparação foi utilizado 4 estados da região do Nordeste, que possuem o taxa populacional equivalentes.

# Como foi feito
Após a importação e limpeza dos bancos de dados utilizados, foram feitos gráficos comparando os valores desejados.

# Conclusão

Minha hipótese seria que o estado que possui maior grau de escolaridade gastaria menos que outro que possui menor.

Porém analisando os quatro estados da Região do Nordeste que possuem taxa populacional parecidas, não é possível obter essa conclusão.
