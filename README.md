# 📚  Escolaridade x Produção Hospitalar 💊

Projeto Módulo 1 - BootCamp Data Science Aplicada da Alura
![image](https://user-images.githubusercontent.com/57717982/141686944-37855357-41e1-451a-a868-07d370f98504.png)

# O projeto
Olá! Este projeto tem o intuito de tentar entender se quanto maior o grau de escolaridade no estado menos gasto com hospitais.

# Pergunta 

Será que o Estado que possui maior escolaridade , gasta mais, por irem mais vezes aos hospitais por conta da informação ou gastam menos por saberem se prevenir de doenças, assim evitando a ida ao hospital ?

# Os dados
Os dados analisados foram retiados do tabnet, sistema do DATASUS que disponibiliza dados de saúde do Brasil. Comparei os gastos de produção hospitalares com o Censo 2010 sobre escolaridade.

Para a separação entre estes escopos, foi utilizado o filtro de Naturezas Jurídicas, no próprio tabnet. No escopo Público, foram selecionadas todas as entidades de admnistração pública. Já no Não Público, foram selecionadas todas as outras entidades, sendo elas empresariais, sem fim lucrativo, pessoas físicas e instituições extraterritoriais.

O filtro por ano/mes atendimento foi selecionado, para usarmos dados que correspondessem melhor a data em que os procedimentos foram realizados. Por isso, não incluí os dados de 2021, posto que, como ainda há atendimentos que não foram processados, eles não são tão confiáveis. Utilizei dados a partir de 2015, pois antes disso, havia dados faltando.

# Como foi feito
Após a importação e limpeza dos bancos de dados utilizados, foram feitos gráficos comparando os valores desejados.

# Conclusão

Minha Hipótese seria que o estado que possui maior grau de escolaridade gastaria menos que outro que possui menor.

Porém analisando o estados da Região do Nordeste que possui taxa populacional parecidas, não é possível obter essa conclusão.
