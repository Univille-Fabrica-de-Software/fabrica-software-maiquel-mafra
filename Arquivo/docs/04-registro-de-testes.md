---

# `docs/04-registro-de-testes.md`

````markdown
# Registro de Testes

## Introdução

Este documento registra os testes manuais realizados na landing page "Panorama do Mercado Tech".

O objetivo é verificar se a página abre corretamente, se os recursos visuais são carregados, se a navegação funciona e se o layout responde adequadamente em diferentes tamanhos de tela.

## Ambiente de teste

Preencha as informações abaixo conforme o ambiente utilizado.

| Item                   | Informação                                        |
| ---------------------- | ------------------------------------------------- |
| Sistema operacional    | macOS / Windows / Linux                           |
| Navegador utilizado    | Google Chrome / Microsoft Edge / Firefox / Safari |
| Editor de código       | VS Code                                           |
| Forma de execução      | Arquivo local / Live Server / GitHub Pages        |
| Data do teste          | Informar data                                     |
| Responsável pelo teste | Nome do acadêmico                                 |

## Teste 1 - Abertura da página

| Verificação                   | Resultado esperado                                      | Status   |
| ----------------------------- | ------------------------------------------------------- | -------- |
| Abrir o arquivo `index.html`  | A página deve abrir no navegador sem erro               | Pendente |
| Carregar o título da aba      | A aba deve exibir "Panorama do Mercado Tech"            | Pendente |
| Carregar o conteúdo principal | O título e a descrição inicial devem aparecer           | Pendente |
| Carregar o Bootstrap          | Layout deve aparecer organizado em grid, cards e navbar | Pendente |
| Carregar o CSS próprio        | Ajustes de espaçamento, logo e efeitos devem funcionar  | Pendente |

## Teste 2 - Logo e favicon

| Verificação                         | Resultado esperado                                        | Status   |
| ----------------------------------- | --------------------------------------------------------- | -------- |
| Exibir a logo no cabeçalho          | A imagem `logo.png` deve aparecer na navbar               | Pendente |
| Verificar texto alternativo da logo | A imagem deve possuir atributo `alt`                      | Pendente |
| Exibir favicon na aba               | O ícone deve aparecer na aba do navegador                 | Pendente |
| Conferir caminhos dos ícones        | Os caminhos devem apontar para `assets/icons/favicon_io/` | Pendente |

## Teste 3 - Navegação interna

| Link do menu | Destino esperado                                      | Status   |
| ------------ | ----------------------------------------------------- | -------- |
| Início       | Deve navegar para a seção inicial                     | Pendente |
| Pesquisa     | Deve navegar para a seção de apresentação da pesquisa | Pendente |
| Vagas        | Deve navegar para a seção de vagas analisadas         | Pendente |
| Tecnologias  | Deve navegar para a seção de tecnologias mais citadas | Pendente |
| Competências | Deve navegar para a seção de competências observadas  | Pendente |
| Análise      | Deve navegar para a seção de análise final            | Pendente |

## Teste 4 - Conteúdo obrigatório

| Conteúdo                 | Resultado esperado                                      | Status   |
| ------------------------ | ------------------------------------------------------- | -------- |
| Cabeçalho                | Deve conter logo e menu                                 | Pendente |
| Apresentação inicial     | Deve conter título, descrição e botão                   | Pendente |
| Apresentação da pesquisa | Deve explicar o levantamento realizado                  | Pendente |
| Vagas locais             | Deve apresentar 4 vagas locais                          | Pendente |
| Vagas nacionais          | Deve apresentar 4 vagas nacionais                       | Pendente |
| Tecnologias              | Deve listar tecnologias citadas nas vagas               | Pendente |
| Competências             | Deve apresentar competências técnicas e comportamentais | Pendente |
| Análise final            | Deve responder o que o mercado exige                    | Pendente |
| Rodapé                   | Deve apresentar disciplina, acadêmico e ano             | Pendente |

## Teste 5 - Responsividade

| Dispositivo/tamanho | Resultado esperado                                       | Status   |
| ------------------- | -------------------------------------------------------- | -------- |
| Desktop             | Layout deve aparecer em colunas quando aplicável         | Pendente |
| Notebook            | Conteúdo deve permanecer legível e organizado            | Pendente |
| Tablet              | Cards e colunas devem se adaptar ao tamanho da tela      | Pendente |
| Celular             | Conteúdo deve aparecer em coluna única quando necessário | Pendente |
| Menu mobile         | Navbar deve exibir botão de menu recolhido               | Pendente |

## Teste 6 - Acessibilidade básica

| Verificação           | Resultado esperado                                      | Status   |
| --------------------- | ------------------------------------------------------- | -------- |
| Idioma da página      | A tag `html` deve conter `lang="pt-BR"`                 | Pendente |
| Hierarquia de títulos | Deve existir um `h1` principal e subtítulos organizados | Pendente |
| Texto alternativo     | Imagens devem possuir atributo `alt`                    | Pendente |
| Links compreensíveis  | Links devem indicar claramente seu destino              | Pendente |
| Navegação por teclado | Menu e links devem ser acessíveis com teclado           | Pendente |
| Contraste visual      | Textos devem ser legíveis sobre o fundo                 | Pendente |

## Teste 7 - Publicação no GitHub Pages

| Verificação                        | Resultado esperado                                      | Status   |
| ---------------------------------- | ------------------------------------------------------- | -------- |
| Repositório criado                 | Projeto deve estar disponível no GitHub                 | Pendente |
| GitHub Pages configurado           | Página deve estar publicada pela branch principal       | Pendente |
| Página publicada abre corretamente | URL pública deve abrir a landing page                   | Pendente |
| Arquivos estáticos carregam        | CSS, logo e favicon devem funcionar na versão publicada | Pendente |
| Links internos funcionam           | Menu deve navegar corretamente na versão publicada      | Pendente |

## Problemas encontrados

Registre abaixo os problemas identificados durante os testes.

```text
Exemplo:
O favicon não apareceu na aba do navegador.
Causa provável: caminho incorreto no atributo href.
Correção: ajuste do caminho para assets/icons/favicon_io/favicon-32x32.png.
```
````
