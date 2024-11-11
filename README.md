# dio_db_oficina
Construindo um Esquema Conceitual para Banco De dados

Descrição do Projeto Conceitual
===============================
Escopo: Ordens de serviço em uma oficina

Narrativa:
* Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.
* Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas.
* Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra.
* O valor de cada peça também irá compro a OS.
* O cliente autoriza a execução dos serviços.
* A mesma equipe avalia e executa os serviços.
* Os mecânicos possuem código, nome, endereco e especialidade.
* Cada OS possui número, data de emissão, valor, status e uma data para conclusão dos trabalhos.
* Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS.
* Uma OS pode ter vários tipos de peças e uma peça pode estar presente em mais de uma OS.
