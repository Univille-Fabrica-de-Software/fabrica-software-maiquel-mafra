# 03 - Decisões de Layout

As escolhas visuais adotadas visam otimizar a clareza informacional, separar corretamente a estrutura da apresentação e demonstrar aplicação fundamentada das classes utilitárias do framework utilizado.

## 1. Estruturação e Navegação
* **Header Fixo (`fixed-top`):** A barra de navegação no topo foi fixada para que os atalhos de seções permaneçam constantemente acessíveis ao longo do fluxo de rolagem do usuário.
* **Espaçamento de Compensação:** Foi adicionada uma regra estrita de `padding-top: 72px` no escopo da tag `body` do CSS original do projeto. Isso impede que o conteúdo inicial da página inicie por trás da navbar fixa.
* **Scroll Suave:** Utilização de `scroll-behavior: smooth` diretamente na tag `html` para garantir transições animadas confortáveis quando o usuário clica nos links do menu.

## 2. Responsividade e Grid (Bootstrap 5)
* **Contêineres:** Uso generalizado da classe `.container` para assegurar que todo o conteúdo permaneça centralizado de forma alinhada em monitores maiores, evitando expansão ilimitada da tela.
* **Mapeamento de Colunas (Grid):**
  * Para o comparativo de vagas, usou-se a divisão `col-lg-6` permitindo dispor o mercado local e nacional lado a lado na visualização desktop.
  * Foi garantido o empilhamento em bloco único nativo para telas com menos de 768px de largura, adequando de imediato a legibilidade aos *smartphones*.
* **Ajustes de Padding Customizado:** Com uso de `@media max-width: 768px`, as regras `.section-padding` recebem decréscimo de preenchimento (`48px 0` no lugar de `72px 0`) no CSS interno para liberar mais espaço vertical nas telas restritas dos celulares.

## 3. Disposição dos Componentes Visuais
* **Utilização de Cards:** Tanto as vagas de emprego quanto os indicadores numéricos da pesquisa foram alocados em componentes `.card`. Esse componente foi eleito por enquadrar dados repetitivos de forma contida e facilitar imensamente a absorção rápida do número pelas pessoas.
* **Feedbacks de Hover via CSS:** Os cartões com a classe `.card` e botões da aplicação receberam transições declarativas suaves como `transform: translateY(-4px)` e `box-shadow` moderado no arquivo `style.css`. Esse efeito transmite a percepção de clique e interatividade tátil dispensando manipulação pesada por JavaScript.
* **Badges de Categoria:** O projeto adotou formatações modulares em estilo pílula (`.rounded-pill text-bg-light border`) para agrupar as tecnologias e modalidades das vagas. O objetivo disso foi viabilizar escaneabilidade — as "palavras-chave" são avistadas prontamente pela audiência.
* **Hierarquia de Cores:** Foi mantido o uso estratégico de contraste em tons neutros com alternância (`bg-light` contra branco puro) para segregar visualmente onde uma seção acaba e onde a próxima inicia, intercalado pela cor verde corporativa nas tipografias de atenção (`text-success`).