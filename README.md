# projeto_dio_powerbi_2

Descrição do desafio módulo 3 – Processamento de Dados Simplificado com Power BI
1.	Criação de uma instância na Azure para MySQL
2.	Criar o Banco de dados com base disponível no GitHub: (https://github.com/julianazanelatto/power_bi_analyst/tree/main/M%C3%B3dulo%203/Desafio%20de%20Projeto)
3.	Integração do Power BI com MySQL no Azure 
4.	Verificar problemas na base a fim de realizar a transformação dos dados
Diretrizes para transformação dos dados
1.	Verifique os cabeçalhos e tipos de dados
2.	Modifique os valores monetários para o tipo double preciso
3.	Verifique a existência dos nulos e analise a remoção
4.	Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente
5.	Verifique se há algum departamento sem gerente
6.	Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas
7.	Verifique o número de horas dos projetos
8.	Separar colunas complexas
9.	Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção
10.	Neste processo elimine as colunas desnecessárias. 
11.	Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.
12.	Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores
13.	Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.
14.	Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.

Porque nesse caso é necessário fazer uma junção entre as duas tabelas usando a chave “departamento_id” e não apenas acrescentar as linhas de uma tabela na outra, que seria o caso se as tabelas possuíssem colunas iguais contendo o mesmo tipo de dados.

16.	Agrupe os dados a fim de saber quantos colaboradores existem por gerente
17.	Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela
