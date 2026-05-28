# REQUISITOS:

## Requisitos Funcionais (RF)
1. Aba de Login, com Email, Senha e Botão de cadastro de usuário.
2. Cadastrar o Produto: ID, Nome, Marca e o Estoque disponível.
3. Movimentação no almoxarifado (Controle de estoque): Quantidade (Quanto foi tirado), Tipo (De produto disponível), Produto, ForeignId (Do produto).

## Requisitos Não-Funcionais (RNF)
1. Tempo de resposta: o site responderá a uma solicitação do usuário em 2 milisegundos.
2. Escalabilidade do site, para ter a capacidade de lidar com o aumento gradativo de usuários, produtos cadastrados e da demanda sem se comprometer.
3. O sistema protegerá os dados dos usuários, poderá ter criptografia e controle de ataques.
4. Compatibilidade e responsividade para funcionar em diferentes plataformas e tipos de aparelhos.

## Regras de Negócio (RN)
1. Controle de dados, logo nenhum produto será cadastrado sem que o usuário faça o Login utilizando Email e Senha.
2. Estoque para estabelecer regras qu evitem excesso de produtos ou a falta total deles.
3. Regras operacionais e estratégicas para controlar as retiradas e evitar que uma única pessoa retire muito do mesmo produto por dia.