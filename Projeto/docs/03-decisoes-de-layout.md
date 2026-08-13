# Decisões de Layout

## Introdução

Este documento registra as principais decisões de layout adotadas no desenvolvimento da landing page "Panorama do Mercado Tech".

O objetivo é justificar escolhas visuais, estruturais e técnicas aplicadas na interface.

## Organização visual

A página foi organizada no formato de landing page, com seções verticais e navegação por âncoras.

Essa escolha facilita a leitura sequencial do conteúdo e permite que o usuário compreenda rapidamente:

- o objetivo da pesquisa;
- os dados analisados;
- as vagas locais e nacionais;
- as tecnologias observadas;
- as competências valorizadas;
- a análise final.

## Uso de Bootstrap

O Bootstrap foi utilizado para acelerar a construção da interface e garantir uma base responsiva.

Foram utilizados recursos como:

- `container`;
- `row`;
- `col`;
- `navbar`;
- `card`;
- `badge`;
- `button`;
- `progress`;
- classes de espaçamento;
- classes de alinhamento;
- classes de responsividade.

A escolha pelo Bootstrap permite concentrar a atividade em estruturação, organização e documentação, reduzindo o tempo necessário para criação manual de todos os estilos CSS.

## Estrutura por seções

O conteúdo foi dividido em seções com a tag `section`.

Cada seção possui uma responsabilidade específica:

| Seção        | Finalidade                                         |
| ------------ | -------------------------------------------------- |
| Header       | Exibir logo e menu de navegação                    |
| Hero         | Apresentar o tema principal da página              |
| Pesquisa     | Explicar o levantamento realizado                  |
| Vagas        | Apresentar vagas locais e nacionais                |
| Tecnologias  | Exibir tecnologias mais citadas                    |
| Competências | Apresentar competências técnicas e comportamentais |
| Análise      | Sintetizar as exigências do mercado                |
| Footer       | Exibir informações finais da atividade             |

Essa divisão melhora a organização do código e facilita futuras manutenções.

## Cabeçalho

O cabeçalho utiliza uma `navbar` fixa no topo da página.

A decisão de usar menu fixo foi adotada para facilitar a navegação entre as seções, especialmente em páginas mais longas.

A logo do projeto foi carregada a partir do caminho:

```text
assets/images/logo.png
```
