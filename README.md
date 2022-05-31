# Sys_Store
Projeto de um sistema de loja, criado durante curso de Python Full


O armazenamento de dados é feito usando arquivo de texto e tem algumas limitações.
Por exemplo: durante o cadastro de mercadorias, pessoas, fornecedores entre outros, o campo "nome" só deve ter uma palavra, ou então caso deseje alterar alguma informação futuramente, dará erro.

Maneira correta de preencher: João, José.
Maneira incorreta: João Dantas, José Silva.

Caso deseje cadastrar um nome com mais de uma palavra preferencialmente utilizar o underline entre elas.
Por exemplo: Jailton_Araújo, José_Oliveira.

O sistema faz distinção entre caracteres maiúsculos e minúsculos, tenha em mente caso deseje alterar alguma informação.

Para visualizar as informações cadastradas, pode usar a opção "Relatórios".

O sistema não utiliza nenhuma biblioteca exterior do python, necessitando apenas da importação das mesmas.
Para executar, abra o arquivo "view.py"

Futuramente o armazenamento de dados será migrado para SQL e adicionado o front end utilizando o django.
