# My_Blog

Este é um blog inspirado no site "[tabnews.com.br](https://www.tabnews.com.br/)" desenvolvido usando o framework CodeIgniter, JavaScript e Bootstrap. O blog possui as seguintes funcionalidades:

- Autenticação de usuário: permite que os usuários façam login, registrem-se e redefinam suas senhas.
- Gerenciamento de posts: os usuários podem criar, editar e excluir posts.
- Dashboard: oferece recursos como upload de foto de perfil, alteração de senha e logout.

## Configuração

Para executar o blog, siga as etapas abaixo:

1. Configure o banco de dados: Abra o arquivo `.env` e defina as configurações do banco de dados de acordo com o seu ambiente. Certifique-se de ter um banco de dados configurado e as credenciais corretas.

2. Execute as migrações do banco de dados: Abra um terminal na pasta raiz do projeto e execute o seguinte comando para criar as tabelas necessárias no banco de dados:

```php
php spark migrate

```

1. Remova o `index.php` da URL: Abra o arquivo `app/Config/App.php` e localize a linha que define a variável `$indexPage`. Altere-a para o seguinte:

```php
public string $indexPage = '';

```

1. Inicie o servidor: Você pode usar um servidor local para executar o blog. Por exemplo, usando o servidor embutido do PHP, execute o seguinte comando no terminal dentro da pasta raiz do projeto:

```php
php -S localhost:8000 -t public

```

Acesse o blog: Abra um navegador da web e acesse [http://localhost:8000](http://localhost:8000) para visualizar o blog.

## Funcionalidades

O blog possui as seguintes funcionalidades:

- Login: os usuários podem fazer login usando suas credenciais.
- Registro: os usuários podem se registrar para criar uma nova conta.
- Redefinição de senha: os usuários podem solicitar a redefinição de sua senha caso a esqueçam.
- Criação de posts: os usuários podem criar novos posts para compartilhar conteúdo.
- Edição de posts: os usuários podem editar os posts existentes.
- Exclusão de posts: os usuários podem excluir os posts que não desejam mais.
- Dashboard: os usuários têm acesso a um painel de controle com recursos adicionais, como upload de foto de perfil, alteração de senha e logout.

## Capturas de Tela

Aqui estão algumas capturas de tela do blog:

Tela de login:
![Tela de login](https://github.com/tarcisiodev1/Blog-Dashboard-Ci4/assets/111070575/532ab174-b634-465c-8343-d33bcab56c40)

Tela de registro:
![Tela de registro](https://github.com/tarcisiodev1/Blog-Dashboard-Ci4/assets/111070575/6cb035d4-1702-4bff-823b-0c54a0297038)

Tela de post:
![Tela de edição de post](https://github.com/tarcisiodev1/Blog-Dashboard-Ci4/assets/111070575/7f879d74-358b-4d5f-b741-afe48fc80b48)

Tela home Posts:
![Tela de edição de post](https://github.com/tarcisiodev1/Blog-Dashboard-Ci4/assets/111070575/12a5e240-ce13-4857-a7c6-6cdabf54aa7d)

Tela de criação de post:
![Tela de criação de post](https://github.com/tarcisiodev1/Blog-Dashboard-Ci4/assets/111070575/62224d9c-b3f1-42b3-a627-0c9eda365b56)

Tela de edição de post:
![Tela de edição de post](https://github.com/tarcisiodev1/Blog-Dashboard-Ci4/assets/111070575/db3712c1-8bdd-4a18-b6eb-e61e584b9283)

Tela de perfil do usuário:
![Tela de perfil do usuário](https://github.com/tarcisiodev1/Blog-Dashboard-Ci4/assets/111070575/52f6e736-f39c-4d9c-bcfe-9284c417f04d)

Sinta-se à vontade para personalizar e expandir o blog de acordo com suas necessidades. Divirta-se blogando!
