# 02 - Requisitos do Projeto

## 1. Requisitos Funcionais (RF)
Os requisitos funcionais indicam exatamente o que a página deve apresentar ao visitante final.

* **RF01 - Exibir cabeçalho:** A página deve apresentar logo e menu de navegação.
* **RF02 - Apresentar introdução:** A página deve conter título, descrição e chamada principal na seção inicial (*Hero*).
* **RF03 - Apresentar pesquisa:** A página deve explicar o levantamento de vagas analisadas com métricas quantitativas.
* **RF04 - Listar vagas locais:** A página deve apresentar oportunidades do mercado local em formato de *cards*.
* **RF05 - Listar vagas nacionais:** A página deve apresentar oportunidades de mercado nacional (remoto) em formato de *cards* para comparativo.
* **RF06 - Listar tecnologias:** A página deve destacar tecnologias recorrentes mapeadas no mercado.
* **RF07 - Apresentar competências:** A página deve listar competências técnicas (*hard skills*) e comportamentais (*soft skills*).
* **RF08 - Apresentar análise final:** A página deve sintetizar em um bloco de conclusão o que o mercado exige atualmente.
* **RF09 - Exibir rodapé:** A página deve apresentar de forma clara a disciplina, o acadêmico responsável e o ano de vigência institucional.

## 2. Requisitos Não Funcionais (RNF)
Os requisitos não funcionais definem as restrições técnicas, qualidades de uso e critérios de organização estipulados para a implementação.

* **RNF01 - Responsividade:** O layout da página deve adaptar-se e funcionar perfeitamente em telas de desktop, tablets e celulares.
* **RNF02 - Organização de Pastas:** O projeto deve manter uma estrutura limpa, separando HTML na raiz e abrigando itens nos diretórios `assets` (para imagens e ícones), `css` e `docs`.
* **RNF03 - Versionamento:** Todo o projeto e suas atualizações devem ser versionados com a ferramenta Git e armazenados na plataforma GitHub.
* **RNF04 - Documentação:** O projeto deve possuir arquivo base `README.md` atualizado e toda a documentação técnica preenchida no diretório `docs`.
* **RNF05 - Semântica de Código:** O arquivo HTML obrigatoriamente deve utilizar as marcações estruturais apropriadas, como `header`, `main`, `section`, `nav` e `footer`.
* **RNF06 - Metadados:** A seção `<head>` deve possuir propriedades críticas declaradas, incluindo charset, viewport, título da página, descrição, ícone (favicon) e manifest.
* **RNF07 - Caminhos Relativos:** Todas as mídias e folhas de estilos internas devem ser importadas por rotas relativas sem barras de início para prevenir rotas quebradas no servidor de publicação.
* **RNF08 - Publicação:** A aplicação estática deve ser corretamente configurada e disponibilizada em domínio público via GitHub Pages.