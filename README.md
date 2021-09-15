# Dev Back-End PL - Desafio

### O candidato deverá desenvolver uma api rest para um Cadastro de Pets, de acordo com as regras abaixo:

## STACK
1. Deverá desenvolver a api usando TypeScript
2. Deverá realizar a persistência de dados usando o TypeORM
3. O código deverá ter injeção de dependência. Será considerado diferencial o uso de inversão de dependências com o inversify.
4. Deverá usar um banco de dados SQL..
5. Deverá ser usado como método de autenticação o JWT.

## REGAS DE NEGÓCIO
Você irá criar um cadastro de Pais e Filhos. Todos os filhos precisam estar relacionados a um Pai. Com isso definido:

1. Deverá existir um relacionamento entre Pais e Filhos. (1:N)
2. Deverá existir validação das informações antes da gravação.
3. A api deverá permitir:
    3.1. Cadastro de Pais
    3.2. Cadastro de Filhos
    3.3. Ver todos os Pais e filhos
    3.4. Ver todos os filhos de um determinado pai
    3.5. Editar os dados de um pai
    3.6. Editar os dados de um filho
    3.7. Excluir um Pai e seus filhos (cascata)
    3.8. As rotas de cadastro de pais deverão ser uma rota pública.
    3.9. As rotas de edição e exclusão deverão ser rotas restritas protegidas por autenticação via JWT
    3.10. A rota de cadastro de filhos deverá ser uma rota protegida por JWT


### Para envio do teste:

1. Deverá ser criado um repositório no git ou bitbucket com o nome de Test-Dev-Back-PL. Esse repositório deverá conter todo o código desenvolvido.
2. Enviar o link do repositório para os emails de Paulo Tozzi (paulo.tozzi@diwe.com.br), Vinicius Silva (vinicius.silva@diwe.com.br) e Maicon Passos (maicon.passos@diwe.com.br)
