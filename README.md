# Sistema de login 

## Descrição

Este projeto é um sistema de login simples usando PHP e MySQL. Ele não possui criptografia de senha e é destinado apenas para fins educacionais.

## Arquivos

- `conexao.php`: arquivo responsável por estabelecer a conexão com o banco de dados MySQL.

- `index.php`: arquivo responsável pela página de login do sistema. Ele recebe os dados do usuário, realiza a verificação no banco de dados e, em caso de sucesso, inicia a sessão do usuário e redireciona para a página de painel.

- `logout.php`: arquivo responsável por destruir a sessão do usuário e redirecionar para a página de login.

- `painel.php`: arquivo responsável pela página de painel do sistema. Ele verifica se o usuário está logado e, em caso afirmativo, exibe as informações do usuário e um botão para fazer logout.

- `protect.php`: arquivo responsável por verificar se o usuário está logado. Caso não esteja, ele redireciona para a página de login.

## Instalação

Para utilizar este sistema, é necessário importar o arquivo `login.sql` para um banco de dados MySQL. Depois, basta configurar a conexão no arquivo `conexao.php`, inserindo o nome de usuário, senha, nome do banco de dados e host.

## Observações

Este sistema é apenas um exemplo simples e não deve ser utilizado em produção, uma vez que não utiliza criptografia na senha do usuário. Recomenda-se sempre utilizar métodos seguros de autenticação e armazenamento de senhas. 


## Contribuição

Sinta-se livre para contribuir com este projeto criando pull requests ou reportando problemas na seção de issues.



