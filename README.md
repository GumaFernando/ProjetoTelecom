## Projeto Análise de Reclamações de operadoras de Telecomunicações
Criado um cenário fictício, baseado em cloud computing utilizando a plataforma Microsoft Azure. Onde teria um banco de dados contendo reclamações junto a Anatel referente a operadoras de telecomunicações, este banco de dados seria composto por mais de 5 milhões de observações, a partir disso ao realizar consultas de agregações mais complexas para gerar Dashboards estava com alta latência para processar os dados, e seria necessário fazer a inserção desses dados para um ambiente mais escalável, no caso foi utilizado o recurso de Big Data Hdinsight da Azure para trabalhar com o cluster Spark, e na sequência utilizar os resultados das operações para gerar Dashboards utilizando o Power Bi. 

##Atividades realizadas

- Modelagem de dados (dimensional) 
- Criação de um Banco de Dados
- Criação de um processo de ETL com o Data Factory
- Criação de um ambiente de Big Data Hdinisgh
- Utilização do sqoop para transferência dos dados 
- Utilização do Hive e Spark Sql para processamento 
- Utilização do Power Bi para criar visualizações
