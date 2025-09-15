# MR-Oficina
Essa atividade tinha como desafio criar um esquema conceitual para o contexto de oficina com base na narrativa fornecida. 
> O arquivo do modelo relacional está disponível na página main para download

Ferramentas utilizadas: 

[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://github.com/mysql)

# Narrativa:
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

# Modelo Conceitual:
![](https://github.com/mariaefoliveira/MR-Oficina/blob/main/Images/Modelo%20Conceitual.png?raw=true)

Para acrescentar foi feito um modelo relacional, não ficou tão diferente do previsto
# Modelo Relacional:
![](https://github.com/mariaefoliveira/MR-Oficina/blob/main/Images/Oficina.png?raw=true)
