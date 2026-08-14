# 04. Registro de Testes do Sistema

## 1. Visão Geral
Este documento registra a bateria de testes manuais e automatizados executados na landing page **Conecta Respeito**, validando sua responsividade, navegabilidade, acessibilidade e conformidade técnica antes da entrega final.

---

## 2. Testes Automatizados via Google Lighthouse
A avaliação automatizada foi realizada através da ferramenta nativa **Google Lighthouse** (DevTools), simulando os ambientes Mobile e Desktop.

### Resultados Obtidos:
| Dispositivo / Ambiente | Desempenho (Performance) | Acessibilidade | Melhores Práticas | SEO |
| :--- | :---: | :---: | :---: | :---: |
| **Mobile** | 63 | 90 | 100 | 100 |
| **Desktop** | 75 | 90 | 100 | 100 |

### Evidências Visuais dos Testes:

#### Evidência de Teste - Mobile
![Relatório de Teste Lighthouse Mobile](image.png)

#### Evidência de Teste - Desktop
![Relatório de Teste Lighthouse Desktop](image-1.png)

### Análise dos Indicadores:
- **SEO (100/100):** Metadados descritivos, hierarquia estruturada de cabeçalhos (`h1`, `h2`, `h3`) e tags semânticas devidamente validadas.
- **Melhores Práticas (100/100):** Uso correto de doctype HTML5, codificação UTF-8 e carregamento seguro de recursos externos.
- **Acessibilidade (90/100):** Textos alternativos (`alt`) presentes nas imagens e contraste de leitura aprovado.
- **Desempenho (63 Mobile / 75 Desktop):** Pontuação influenciada pelo carregamento em resolução nativa das imagens fotográficas no ambiente local.

---

## 3. Testes Manuais de Responsividade
Validação da adaptação visual em diferentes viewports através da emulação de dispositivos móveis do navegador:

| Cenário de Teste | Resolução / Dispositivo | Comportamento Esperado | Resultado |
| :--- | :---: | :--- | :---: |
| **Desktop Amplo** | 1920x1080 / 1366x768 | Menu horizontal expandido, grid em colunas lado a lado e imagens bem dimensionadas. | **Aprovado** |
| **Tablet** | 768px (iPad) | Reorganização do grid para 2 colunas e ajuste suave dos espaçamentos. | **Aprovado** |
| **Mobile** | 375px a 414px (Smartphones) | Menu hambúrguer retrátil funcional, cards empilhados em 1 coluna e sem barra de rolagem lateral. | **Aprovado** |

---

## 4. Testes Funcionais e de Navegação
Verificação dos elementos interativos da interface:

| Elemento Testado | Ação Realizada | Resultado Esperado | Status |
| :--- | :--- | :--- | :---: |
| **Links da Barra de Navegação** | Clique nos itens do menu superior | Rolagem suave (`smooth scroll`) até a âncora correspondente (`#inicio`, `#oquee`, `#tipos`, `#sinais`, `#apoio`). | **Aprovado** |
| **Botão CTA (Hero Section)** | Clique no botão "Saiba Mais" | Redirecionamento direto para a seção explicativa inicial. | **Aprovado** |
| **Menu Hambúrguer (Mobile)** | Clique no botão sanfona | Abertura e fechamento corretos da lista de navegação via Bootstrap JS. | **Aprovado** |

---

## 5. Testes de Acessibilidade e Inclusão
- **Leitores de Tela:** Todas as imagens (`friendship_illustration.jpg`, `cyberbullying_illustration.jpg`, `sad_student_sitting_alone.jpg`, `counseling_illustration.jpg`) e o logotipo possuem o atributo `alt` com descrições objetivas e contextuais.
- **Navegação por Teclado:** Utilização da tecla `Tab` confirmou foco visível e sequencial em todos os links e botões navegáveis.
- **Contraste de Cores:** Combinações de texto e fundo auditadas para garantir legibilidade adequada.

---

## 6. Conclusão dos Testes
A interface atende satisfatoriamente aos requisitos funcionais e não funcionais estabelecidos, apresentando estabilidade estrutural, facilidade de navegação e notas sólidas de conformidade técnica.