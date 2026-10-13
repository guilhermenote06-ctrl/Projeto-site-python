# Manutenção e atualização do projeto

## Como atualizar o conteúdo

Para alterar textos, basta editar os arquivos HTML correspondentes:

- `index.html` para a página inicial;
- `materia.html` para a matéria;
- `jogos.html` para os jogos;
- `votação.html` para a votação.

## Como adicionar imagens

1. Coloque os arquivos das imagens em `imagens/`.
2. Referencie o caminho corretamente na tag `img` do HTML.
3. Sempre prefira nomes claros e consistentes.

## Como atualizar o áudio

O áudio da página de jogos fica em `midia/melodia-original.wav`. Ao substituir o arquivo,
preserve esse caminho e o formato WAV, ou atualize também o caminho e o tipo indicados
no elemento `source` de `jogos.html`.

## Como criar uma nova página

1. Crie um novo arquivo `.html` na raiz do projeto.
2. Mantenha o menu de navegação consistente.
3. Siga a mesma estrutura básica do restante do site.
4. Atualize a documentação caso a nova página seja relevante.

## Boas práticas

- use títulos claros e organizados;
- mantenha a navegação igual em todas as páginas;
- evite conteúdo repetido;
- mantenha uma padronização visual;
- teste a visualização em navegador após cada alteração.

## Organização de documentação

A documentação deve ser mantida em arquivos separados na pasta `docs/`, para garantir:

- clareza;
- manutenção mais fácil;
- entendimento rápido para avaliação e acompanhamento do projeto.

## Recomendação final

O projeto deve continuar simples, acessível e organizado. O foco principal deve ser manter a estrutura clara para facilitar tanto a leitura do código quanto a manutenção futura.
