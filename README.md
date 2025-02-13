# Esquema Conceitual Oficina DIO Heineken


 Projeto Oficina para o Bootcamp Heineken - DIO

# Objetivo
Criar um esquema conceitual com um contexto para uma oficina mecânica

Projeto foi feito no Draw.io

## Narrativa

1. Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.
2. Clientes levam veículos a oficina mecânica para serem consertados ou para passarem por revisões periódicas.
3. Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
4. A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra.
5. O valor de cada peça também irá compor a OS.
6. O cliente autoriza a execução dos serviços.
7. A mesma equipe avalia e executa os serviços.
8. Os mecânicos possuem código, nome, endereço e especialidade.
9. Cada OS possui: ID, data de emissão, um valor, status, e uma data para conclusão dos trabalhos.
10. Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS.
11. Uma OS pode ter vários tipos de peça e uma peça pode estar presente em mais de uma OS.