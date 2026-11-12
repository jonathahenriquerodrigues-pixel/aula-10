# Sistema de Gerenciamento Acadêmico — Aula 10

Projeto da disciplina Desenvolvimento Web 1. Usa HTML, CSS e JavaScript para exibir indicadores e gerar listagens a partir de dados de exemplo.

## Como abrir

Abra [index.html](index.html) no navegador. O projeto roda sem instalar dependências.

## O que experimentar

1. No painel inicial, confira os totais de alunos, cursos, matrículas e usuários.
2. Em **Alunos**, filtre por nome ou situação, abra os detalhes de um aluno e experimente a remoção.
3. Em **Novo aluno**, preencha o formulário e veja o novo registro na prévia da mesma página.
4. Visite as listagens de cursos, matrículas e usuários. Os formulários dessas três áreas são demonstrativos.

As alterações nos alunos ficam na memória da página e voltam ao estado inicial ao recarregar ou navegar. Essa etapa da disciplina trabalha a manipulação do DOM e eventos. A persistência ficou para a Aula 11.

## Estrutura

- `index.html` e demais páginas HTML contêm o painel, as listagens e os formulários.
- `css/style.css` contém os estilos responsivos.
- `js/dados.js` contém os dados fictícios.
- `js/app.js` renderiza os dados e configura os eventos.
