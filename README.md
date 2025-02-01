Welcome To Our Database Project
Instruções (PT/BR)
Faça um Fork deste repositório;
Clone localmente: git clone https://github.com/SEUUSERNAME/database-project.git;
Adicione o remote upstream para manter seu repositório local atualizado: git remote add upstream https://github.com/fabiomrtins/database-project;
Utilize o comando git pull upstream main para baixar e mesclar as alterações no seu repositório local com base na branch main deste repositório original de onde você fez o fork, ou git fetch upstream main para baixar sem mesclar.

Crie uma nova branch e nomeie como feat/authors/seunomedeusuario: git checkout -b feat/authors/seunomedeusuario;
Exemplo: git checkout -b feat/authors/fabiomrtins

Dentro da pasta [authors], crie uma nova pasta com seu nome de usuario ex: fabiomrtins.
Escolha uma ou mais atividades abaixo na seção [Exercícios], crie um arquivo dentro da sua pasta com o número do exercício vinculado e a extensão .sql. Ex: fabiomrtins/01.sql, lá dentro coloque a resposta.
Adicione suas alterações à "staging area" com o comando git add authors/seunomedeusuario.md;
Crie um commit e adicione a mensagem indicando a adição do seu perfil git commit -m"feat: add seunomedeusuario profile";
Envie as alterações para o seu repositório remoto git push origin feat/authors/seunomedeusuario;
Crie um Pull Request.
Exercícios:

Liste os produtos. (products)
Liste os produtos e o nome de seus fornecedores. (products / suppliers)
Recupere os pedidos com os nomes dos clientes e dos funcionários responsáveis. (orders / customers / employees)
Liste os produtos, suas categorias e o nome dos fornecedores. (products / categories / suppliers)
Quantos pedidos cada cliente já fez? (orders / employees)
Valor total vendido por cada funcionário (considerando os pedidos já enviados). (orders / employees)
Média de preços dos produtos por categoria. (products / categories)
Quais os clientes que nunca fizeram pedidos? (customers / orders)
Authors
Jhonatas Rodrigues
Fabio Martins
Filipe Izidorio
Bruno Rodrigo
Ian Vinícius
