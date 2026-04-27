# 2026-DWII — Murilo Néfi de Faria

Repositório das atividades da disciplina **Desenvolvimento Web II** ministrada pelo
Prof. Berssa no IFPR — Campus Ponta Grossa.

## Estudante

- **Nome:** Murilo Néfi de Faria
- **Curso:** Técnico em Informática (Integrado ao Ensino Médio)
- **Instituição:** IFPR — Ponta Grossa
- **Ano letivo:** 2026

## Estrutura do Repositório

| Pasta | Conteúdo |
|-------|----------|
| `00_apresentacao/` | Página estática em HTML/CSS com apresentação pessoal e foto. |
| `01_php-intro/` | Portfólio dinâmico em PHP (variáveis, includes e menu). |
| `02_formularios/` | Formulário de contato com validação e padrão Post/Redirect/Get. |
| `03_pdo/` | Catálogo de tecnologias persistido em MariaDB via PDO. |
| `04_sessoes/` | Área restrita com login, sessões e bloqueio por tentativas. |
| `05_crud/` | CRUD completo de projetos (criar, listar, editar, excluir). |
| `includes/` | Cabeçalho, rodapé, navegação e folha de estilos compartilhados. |
| `.devcontainer/` | Configuração do ambiente de desenvolvimento (Docker). |

## Páginas Principais

- `index.php` na raiz — vitrine das aulas, com cards apontando para cada exercício.
- `01_php-intro/index.php` — página inicial do portfólio (Início, Sobre, Projetos).
- `02_formularios/contato.php` — formulário com validação no servidor.
- `03_pdo/index.php` — listagem e busca de tecnologias cadastradas.
- `04_sessoes/login.php` — autenticação para acessar o painel restrito.
- `05_crud/index.php` — gestão de projetos pessoais (CRUD completo).

## Como executar

O projeto é pensado para rodar dentro do *devcontainer* incluído na pasta
`.devcontainer/`, com PHP 8 e MariaDB já configurados. Os scripts SQL de
inicialização ficam em `.devcontainer/db-init/` e em cada pasta de aula que
utiliza banco de dados (`03_pdo/sql/` e `05_crud/sql/`).

## Autor

**Murilo Néfi de Faria** — IFPR Ponta Grossa — 2026
