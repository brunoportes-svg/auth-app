# Auth App

Um projeto Laravel simples para gerenciar posts e categorias, com interface básica para criar, editar e exibir conteúdo.

## O que foi implementado

- Modelo `Categoria` e modelo `Post` com relacionamento `belongsTo`.
- Tela de criação de post com seleção de categoria.
- Lista de posts exibindo título, conteúdo e a categoria selecionada.
- Atualização da tabela para mostrar corretamente o nome da categoria vinculada a cada post.
- Rotas e controlador gerenciando criação, edição e exclusão de posts.

## Como usar

1. Instale dependências PHP:

```bash
composer install
```

2. Configure o ambiente copiando `.env.example` para `.env` e ajustando o banco de dados.

3. Execute as migrações:

```bash
php artisan migrate
```

4. Instale dependências JavaScript:

```bash
npm install
```
```

5. Crie o build front-end:

```bash
npm run build
```

> Se você estiver no PowerShell e receber um erro de política de execução, use:
>
> ```powershell
> Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
> ```
>
> Isso libera a execução de scripts do usuário apenas no escopo atual.

## O que esperar

- Página de listagem de posts com a categoria exibida corretamente.
- Formulário de criação de post com dropdown de categoria.
- Botões de editar e excluir para cada post.

## Observações

Este README foi atualizado para refletir as mudanças feitas no projeto de forma clara e organizada. Se quiser, posso também atualizar o fluxo de edição de categoria ou melhorar o layout da tabela.
