# Arquitetura do projeto

## Visão geral

Este projeto é um site estático simples, organizado em páginas HTML independentes. A navegação entre as páginas é feita por links no menu principal e cada arquivo representa uma seção do conteúdo.

## Estrutura principal

- `index.html`: página inicial e apresentação principal do tema.
- `materia.html`: conteúdo editorial ou artigo.
- `jogos.html`: seção dedicada aos jogos.
- `votação.html`: seção de votação ou enquete.
- `imagens/`: arquivos visuais usados nas páginas.

## Organização por responsabilidade

### Página inicial
A página inicial deve funcionar como apresentação geral do projeto. Ela deve conter:

- título principal;
- apresentação do tema;
- destaque de conteúdo relevante;
- navegação para outras páginas.

### Página de matéria
A página de matéria deve ser usada para apresentar um texto ou artigo principal, com:

- título da matéria;
- data de publicação;
- texto principal;
- elementos visuais quando necessário.

### Página de jogos
A página de jogos deve listar e destacar elementos ligados ao tema do projeto, como:

- imagens;
- descrições curtas;
- títulos de jogos ou itens relacionados;
- listas, tabela de dados e áudio local.

### Página de votação
A página de votação deve ser reservada para:

- enquete;
- campos de formulário acessíveis com validação nativa;
- processamento futuro das respostas por um serviço apropriado.

## Boas práticas de organização

- manter cada página com responsabilidade única;
- usar semântica adequada em HTML;
- conservar a navegação consistente em todas as páginas;
- manter a estrutura de arquivos organizada e previsível.

## Objetivo da arquitetura

A arquitetura escolhida é simples e adequada para projetos estáticos, pois facilita:

- entendimento visual;
- manutenção do conteúdo;
- inclusão de novas páginas;
- apresentação em ambiente acadêmico ou profissional.
