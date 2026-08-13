---

# `docs/02-requisitos.md`

```markdown
# Requisitos do Projeto

## Introdução

Este documento apresenta os requisitos funcionais e não funcionais da landing page "Panorama do Mercado Tech".

Os requisitos descrevem o que a página deve apresentar, como deve se comportar e quais características técnicas devem ser respeitadas durante o desenvolvimento.

## Requisitos funcionais

Requisitos funcionais descrevem as funcionalidades ou informações que o sistema deve oferecer ao usuário.

| Código | Requisito funcional                     | Descrição                                                                                                               |
| ------ | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| RF01   | Exibir cabeçalho                        | A página deve apresentar um cabeçalho com a logo do projeto e menu de navegação.                                        |
| RF02   | Navegar pelas seções                    | O menu deve permitir acesso às principais seções da landing page por meio de links internos.                            |
| RF03   | Apresentar introdução                   | A página deve apresentar uma seção inicial com o tema e objetivo da atividade.                                          |
| RF04   | Apresentar dados da pesquisa            | A página deve informar que foram analisadas vagas locais e nacionais da área de tecnologia.                             |
| RF05   | Apresentar resumo quantitativo          | A página deve exibir um resumo com quantidade de vagas analisadas, vagas locais, vagas nacionais e tecnologias citadas. |
| RF06   | Listar vagas locais                     | A página deve apresentar pelo menos quatro vagas locais com cargo, empresa/fonte, tecnologias e observações.            |
| RF07   | Listar vagas nacionais                  | A página deve apresentar pelo menos quatro vagas nacionais com cargo, empresa/fonte, tecnologias e observações.         |
| RF08   | Listar tecnologias                      | A página deve apresentar tecnologias, linguagens, frameworks, ferramentas ou práticas observadas nas vagas.             |
| RF09   | Apresentar competências técnicas        | A página deve listar competências técnicas identificadas durante a análise das vagas.                                   |
| RF10   | Apresentar competências comportamentais | A página deve listar competências comportamentais valorizadas pelo mercado.                                             |
| RF11   | Apresentar análise final                | A página deve conter uma síntese respondendo o que o mercado está exigindo dos profissionais de tecnologia.             |
| RF12   | Exibir rodapé                           | A página deve apresentar rodapé com identificação da disciplina, acadêmico e ano/semestre.                              |

## Requisitos não funcionais

Requisitos não funcionais descrevem características de qualidade, organização, manutenção e comportamento técnico do projeto.

| Código | Requisito não funcional              | Descrição                                                                                                              |
| ------ | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| RNF01  | Utilizar HTML5                       | O projeto deve utilizar HTML5 para estruturar o conteúdo da página.                                                    |
| RNF02  | Utilizar CSS3                        | O projeto deve utilizar CSS3 para personalizações visuais complementares.                                              |
| RNF03  | Utilizar Bootstrap                   | O projeto deve utilizar Bootstrap para facilitar grid, responsividade, cards, navbar e botões.                         |
| RNF04  | Ser responsivo                       | A página deve se adaptar a diferentes tamanhos de tela, incluindo desktop e dispositivos móveis.                       |
| RNF05  | Ter organização de arquivos          | O projeto deve manter arquivos organizados em pastas como `assets`, `css` e `docs`.                                    |
| RNF06  | Usar caminhos relativos              | Imagens, ícones e arquivos CSS devem ser referenciados com caminhos relativos.                                         |
| RNF07  | Possuir README                       | O projeto deve conter um arquivo `README.md` explicando objetivo, tecnologias, execução e estrutura.                   |
| RNF08  | Possuir documentação técnica         | O projeto deve conter documentação complementar na pasta `docs`.                                                       |
| RNF09  | Ser versionado com Git               | O projeto deve utilizar Git para controle de versão.                                                                   |
| RNF10  | Estar publicado no GitHub            | O projeto deve ser disponibilizado em um repositório remoto no GitHub.                                                 |
| RNF11  | Ter código legível                   | O HTML e o CSS devem utilizar organização, indentação e comentários adequados.                                         |
| RNF12  | Usar HTML semântico                  | A página deve utilizar tags como `header`, `main`, `section`, `nav` e `footer`.                                        |
| RNF13  | Ter metadados básicos                | O documento deve conter `charset`, `viewport`, `title`, `description`, favicon e demais metadados definidos no `head`. |
| RNF14  | Permitir publicação com GitHub Pages | O projeto deve estar estruturado de forma que o `index.html` possa ser publicado diretamente pela branch principal.    |

## Regras de conteúdo

| Código | Regra                            | Descrição                                                                             |
| ------ | -------------------------------- | ------------------------------------------------------------------------------------- |
| RC01   | Coerência com o tema             | As informações apresentadas devem estar relacionadas ao mercado de tecnologia.        |
| RC02   | Dados mínimos de vaga            | Cada vaga deve apresentar cargo, empresa/fonte, tecnologias e observação relevante.   |
| RC03   | Separação entre local e nacional | As vagas devem estar divididas entre mercado local e mercado nacional.                |
| RC04   | Clareza textual                  | Os textos devem ser objetivos, compreensíveis e adequados ao contexto acadêmico.      |
| RC05   | Autoria                          | O acadêmico deve substituir os dados genéricos pelos dados reais da própria pesquisa. |

## Critérios de aceite

A entrega será considerada adequada quando:

- o arquivo `index.html` abrir corretamente no navegador;
- a logo for exibida no cabeçalho;
- o favicon aparecer na aba do navegador;
- o menu permitir navegação entre as seções;
- a página apresentar todas as seções obrigatórias;
- o layout funcionar em desktop e mobile;
- os arquivos estiverem organizados nas pastas corretas;
- o README estiver preenchido;
- os documentos da pasta `docs` estiverem preenchidos;
- o projeto estiver versionado em um repositório GitHub.

## Observações

Este projeto ainda não possui integração com back-end. Os dados exibidos estão fixos no HTML.

Em uma etapa futura, as vagas poderão ser carregadas dinamicamente a partir de uma API REST desenvolvida com Java e Spring Boot.
```
