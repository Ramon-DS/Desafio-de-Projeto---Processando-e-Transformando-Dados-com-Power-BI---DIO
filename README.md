# Desafio-de-Projeto---Processando-e-Transformando-Dados-com-Power-BI---DIO
Desafio de Projeto - Processando e Transformando Dados com Power BI - DIO

Processamento de Dados Simplificado com Power BI

1. Criação de uma instância na Azure para MySQL

2. Criar o Banco de dados com base disponível no github

3. Integração do Power BI com MySQL no Azure

4. Verificar problemas na base a fim de realizar a transformação dos dados


Diretrizes para transformação dos dados realizadas:

1. Verificação dos cabeçalhos e tipos de dados

2. Modifiquei os valores monetários para o tipo double preciso

3. Verifiquei a existência dos nulos e analise a remoção

4. Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente

5. Verifiquei se há algum departamento sem gerente

6. Ajustando os departamento sem gerente

7. Verifiquei o número de horas dos projetos

8. Separei colunas complexas

9. Mesclei consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção

10. Neste processo elimine as colunas desnecessárias.

11. Realizei a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.

12. Mesclei as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores

13. Mesclei os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.

14. Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.

    
Nesse desafio criamos um BD MySql, manipulamos pelo Workbanch.
Foi necessário criar um banco de dados na Azure para acesso na cloud, onde inserimos todas as informações do BD para acesso em tempo real.

Após carregar o BD no Power BI, foi feito um processo de ETL.

Servidor: desafio-projeto-dio-company.mysql.database.azure.com
