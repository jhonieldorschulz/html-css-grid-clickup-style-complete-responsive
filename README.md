# html-css-grid-clickup-style-complete-responsive
Template responsivo baseado nos quadros Kanban do Clickup com HTML, CSS usando grid layout

### Explicação Detalhada

#### HTML
1. **<!DOCTYPE html>**: Define o tipo de documento como HTML5.
2. **<html lang="pt-BR">**: Inicia o documento HTML e define o idioma como português do Brasil.
3. **<head>**: Contém metadados, como a codificação de caracteres e o título da página.
4. **<meta charset="UTF-8">**: Define a codificação de caracteres.
5. **<meta name="viewport" content="width=device-width, initial-scale=1.0">**: Define a viewport para tornar a página responsiva.
6. **<title>Kanban ClickUp</title>**: Define o título da página.
7. **<link rel="stylesheet" href="styles.css">**: Linka o arquivo CSS externo.
8. **<header>**: Contém o cabeçalho da página.
9. **<h1>Kanban ClickUp</h1>**: Título principal da página.
10. **<main>**: Contém o conteúdo principal da página.
11. **<section class="kanban-board">**: Seção principal que representa o quadro Kanban.
12. **<article class="column todo">**: Coluna "To Do" do Kanban.
13. **<h2>To Do</h2>**: Título da coluna "To Do".
14. **<div class="card">**: Cada tarefa representada como um cartão.
15. **<p>Tarefa 1</p>**: Texto dentro do cartão.
16. **Outras colunas e cartões seguem o mesmo padrão.**

#### CSS
1. **body**: Define estilos gerais para o corpo da página, como fonte, margens e fundo.
2. **header**: Estiliza o cabeçalho com fundo branco, padding e sombra.
3. **h1**: Define o estilo do título principal.
4. **main**: Aplica padding ao conteúdo principal.
5. **.kanban-board**: Usa CSS Grid para criar um layout com três colunas.
6. **.column**: Estiliza as colunas do Kanban, adicionando fundo branco, bordas arredondadas e sombra.
7. **.column h2**: Estiliza os títulos das colunas, adicionando margem, borda inferior e padding.
8. **.card**: Estiliza os cartões com fundo cinza claro, margens, padding, bordas arredondadas e sombra.
9. **.todo, .in-progress, .done**: Adiciona uma borda superior colorida para diferenciar as colunas, usando as cores do ClickUp (rosa, azul e verde, respectivamente).

Esse código cria uma estrutura básica para um quadro Kanban com estilo inspirado no ClickUp, utilizando HTML semântico e CSS Grid Layout para um layout responsivo e organizado.