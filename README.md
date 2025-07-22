# MySQL-Workbench - Consultando Dados da Insight Places

Este projeto demonstra como realizar consultas **SQL** essenciais no **MySQL Workbench** para extrair informações valiosas de um banco de dados fictício da **Insight Places**. Relembramos diversas consultas que abordam desde a **filtragem de dados** até **cálculos de agregação complexos**, fornecendo *insights* importantes para o negócio.

## Comandos Demonstração

Explore os seguintes comandos e conceitos SQL, essenciais para a análise de dados:

* **Filtragem de Dados:**
    * `WHERE` com operadores de comparação (`>=`) e lógicos (`AND`).

* **Agregação e Agrupamento:**
    * Funções de agregação: `AVG`, `COUNT`.
    * `GROUP BY` para agrupar resultados.
    * `ORDER BY` para ordenar os resultados.
    * `LIMIT` para restringir o número de resultados.

* **Manipulação de Datas:**
    * `DATEDIFF` para calcular a diferença entre datas.
    * `YEAR` e `MONTH` para extrair componentes de datas.

* **Combinação de Tabelas:**
    * `JOIN` para combinar dados de múltiplas tabelas.

## Visualização dos Comandos

Você pode replicar e executar essas consultas no **MySQL Workbench** ou em qualquer ambiente de MySQL.

<img width="1280" height="985" alt="image" src="https://github.com/user-attachments/assets/424a0707-9b52-44d7-9bca-e5c1a4d48718" />
*Filtramos as hospedagens mais bem avaliadas, ou seja, que tiveram como nota 4 ou 5.


<img width="1280" height="984" alt="image" src="https://github.com/user-attachments/assets/55a013fd-3219-434b-9d1b-1b40950f6b78" />
*Filtramos todas as hospedagens disponíveis que fossem do tipo hotel e estivessem ativas na plataforma.


<img width="1280" height="985" alt="image" src="https://github.com/user-attachments/assets/955ff3c4-7a4b-4226-87b6-9f92d6af848c" />
*Calculamos o gasto médio de cada cliente dentro da plataforma.


<img width="1278" height="985" alt="image" src="https://github.com/user-attachments/assets/0460b816-7593-4d76-a255-c6c0d65aa682" />
*Média de dias de estadia de cada cliente.


<img width="1280" height="983" alt="image" src="https://github.com/user-attachments/assets/522e36e2-503a-420a-a57d-2ad745cf6071" />
*Top 10 proprietários com mais hospedagens ativas na plataforma.


<img width="1280" height="983" alt="image" src="https://github.com/user-attachments/assets/82678ee8-a8e2-4a8e-aef9-620abc10bab9" />
*Número de hospedagens inativas por proprietário.


<img width="1278" height="984" alt="image" src="https://github.com/user-attachments/assets/cc97caad-4c9f-49dd-bc8c-939992e8349a" />
*Identificando os períodos de maior e menor demanda de aluguel na plataforma.
