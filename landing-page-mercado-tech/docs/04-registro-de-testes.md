# 04 - Registro de Testes

Este documento registra os testes manuais executados, os resultados de auditoria de qualidade e os problemas resolvidos durante a construção da landing page, garantindo o funcionamento esperado do projeto.

## 1. Auditoria de Qualidade (Google Lighthouse)
A página foi submetida à auditoria do Lighthouse para validar a otimização técnica da estrutura desenvolvida.

| Dispositivo / Ambiente | Desempenho | Acessibilidade | Práticas Recomendadas | SEO | Status Geral |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Computador (Desktop)** | 94 | 95 | 100 | 100 | Aprovado |
| **Dispositivo Móvel (Mobile)** | 88 | 95 | 100 | 100 | Aprovado |

## 2. Testes de Responsividade e Interface
Testes manuais para validar o comportamento do layout perante as variações de tela.

| Cenário de Teste | Resolução / Ambiente | Comportamento Esperado | Resultado Obtido |
| :--- | :--- | :--- | :--- |
| **Visualização Mobile** | `< 768px` | Empilhamento dos cards em coluna única (`col-12`), adequação do *padding* e menu recolhido em hambúrguer. | Aprovado. Layout exibido com rolagem fluida e sem estourar limites horizontais. |
| **Visualização Desktop** | `≥ 992px` | Menu expandido horizontalmente e exibição comparativa das vagas em duas colunas paralelas (`col-lg-6`). | Aprovado. O grid distribuiu o conteúdo de forma centralizada. |

## 3. Testes Funcionais e de Navegação
Testes focados na interação da pessoa usuária com os componentes da interface.

| Funcionalidade Avaliada | Ação Executada | Resultado Obtido |
| :--- | :--- | :--- |
| **Navegação por Âncoras** | Clique nos links do menu superior (`#inicio`, `#pesquisa`, `#vagas`, etc.). | Rolagem suave da tela em direção à seção correspondente. Aprovado. |
| **Botão de Ação (CTA)** | Clique no botão verde "Ver vagas analisadas" na seção principal. | Redirecionamento instantâneo para a seção `#vagas`. Aprovado. |
| **Menu Fixo (`fixed-top`)** | Rolagem vertical da página de ponta a ponta. | A barra superior acompanhou a leitura sem encobrir o topo da seção. Aprovado. |
| **Assets e Recursos** | Carregamento da URL para visualização geral do projeto. | Logotipo, ícones e folha de estilos renderizados apropriadamente. Aprovado. |

## 4. Problemas Encontrados e Resolvidos
O registro de problemas garante a transparência da evolução do código durante a atividade.

* **Problema Identificado:** Durante as primeiras tentativas de carregamento da página e publicação via GitHub Pages, a logomarca e as regras de estilo (CSS) não foram carregadas, quebrando o visual da aplicação (Erros 404 de console).
* **Causa Raiz:** Inconsistência de caminhos relativos. O arquivo `index.html` estava alocado na raiz do repositório, porém os diretórios `assets/`, `css/` e `docs/` haviam sido colocados dentro de uma subpasta intermediária, impedindo a localização dos arquivos pelo navegador.
* **Ação Corretiva:** As pastas foram recortadas e realocadas no mesmo nível do arquivo `index.html`, eliminando a subpasta intermediária. Os caminhos foram mantidos simples (`css/style.css` e `assets/images/logo.png`) garantindo o funcionamento integral tanto no ambiente local quanto na URL pública final.