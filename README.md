# 🚘 AUTO-GUIA GG: Plataforma de Venda e Avaliação de Veículos

## 1. Informações do Projeto

| Tópico | Detalhes |
| :--- | :--- |
| **Nome do Projeto** | AUTO-GUIA GG |
| **Tema** | Classificados e Guia de Preços (Automotivo) |
| **Integrantes e Papéis** | **Gabriel Saldanha Cavalcanti:** Desenvolvedor (HTML/CSS/JS) |
| | **Gabriel Michael Magalhães Lima:** Designer UX/UI e Desenvolvedor (Figma/HTML/CSS) |

## 2. Visão Geral do Negócio

### Objetivo
Criar uma plataforma digital intuitiva e segura para a compra e venda de veículos seminovos e usados, com foco em oferecer transparência através da integração direta com a Tabela FIPE e fornecer ferramentas de busca eficientes.

### Público-Alvo
1.  **Compradores:** Pessoas físicas que buscam veículos usados ou seminovos, valorizando a transparência de preços (FIPE) e a credibilidade das informações.
2.  **Vendedores:** Pessoas físicas ou pequenas revendas que desejam anunciar seus veículos em uma plataforma com alta visibilidade e recursos de avaliação de mercado.

### Justificativa
O mercado de veículos usados no Brasil é vasto e, muitas vezes, carece de transparência e padronização. A **AUTO-GUIA GG** se justifica pela necessidade de:
* **Credibilidade:** Reduzir a incerteza na negociação ao integrar informações oficiais de preço.
* **Usabilidade:** Oferecer uma experiência de usuário limpa e otimizada (como refletido no Figma), fugindo do excesso de informação de concorrentes.
* **Foco Mobile:** Garantir que a busca de veículos, que geralmente ocorre em momentos de deslocamento, seja perfeita em dispositivos móveis.

## 3. Protótipo e Design

### Link para o Protótipo no Figma
https://www.figma.com/design/tpRCTctWhvw6IU8X5CSQjI/Auto-GG?node-id=0-1&t=zGF2zJK9lMABnbBA-1

### Justificativas Detalhadas de Design

| Elemento | Detalhes e Aplicação | Motivação |
| :--- | :--- | :--- |
| **Cores Primárias** | **Escuro (`#353b42`):** Fundo de menus e rodapé. | Transmite sofisticação, solidez e modernidade, sendo a base neutra. |
| | **Azul Link/Destaque (`#007bff`):** Preços, botões ativos, barra do rodapé. | Usado para chamar a atenção para ações cruciais (CTA) e valores (Preço), simbolizando confiança. |
| | **Cinza Claro (`#b1b5bd`):** Fundo da página principal. | Garante contraste ideal com o texto escuro do cabeçalho e destaca os cards de veículos. |
| **Cores Secundárias** | **Fundo Card (`#3e444b`):** Fundo dos cards de veículos e box "Sobre Nós". | Uma variação escura para dar profundidade e fazer o texto claro (`#FFFFFF`) se destacar, reforçando a elegância. |
| **Tipografia (Fontes)** | **Arial, sans-serif** (em todo o projeto). | Escolhida pela sua alta legibilidade em todas as resoluções e dispositivos, ideal para um site focado em informações e listagens. |
| **Layout (Design System)** | **Grid e Flexbox:** Utilização intensa de `display: flex` e `display: grid`. | Garante que o layout seja nativamente responsivo, adaptando a lista de carros de um `row` (desktop) para duas colunas (`grid` em tablet) ou uma coluna (`grid` em mobile). O cabeçalho mantém a estrutura de duas barras em todas as telas. |
| **Ícones** | **`☰ MENU` (Ícone Simples):** Usado para navegação. | Simplicidade e universalidade. O design mantém o foco na busca e nas listagens, não sobrecarregando o usuário com ícones complexos. |

## 4. Estrutura de Pastas e Arquivos

O projeto segue uma estrutura básica e organizada para desenvolvimento web:
├── css/
│   └── style.css  // Arquivo CSS ÚNICO e completo
├── img/           // Pasta para todas as imagens (carros, logos, ícones)
├── index.html     // (ou carros.html) Página de listagem de carros (página inicial)
└── sobre-nos.html // Página institucional "Sobre Nós"
└── README.md      // Este arquivo

## 5. Etapas Realizadas (9 a 14 de Outubro)

| Data | Responsável | Etapa Realizada |
| :--- | :--- | :--- |
| 09/10 (Qui) | Gabriel Michael (Figma) | Recebimento da Tarefa, Pesquisa Inicial e Definição do Escopo. |
| 10/10 (Sex) | Gabriel Michael (Figma) | Criação do Protótipo de Alta Fidelidade (Definição de Cores, Fontes e Layout). |
| 11/10 (Sáb) | Gabriel Saldanha (HTML/CSS) | Estrutura HTML das páginas (`index.html` e `sobre-nos.html`). |
| 12/10 (Dom) | Gabriel Saldanha (HTML/CSS) | Estilização CSS Base e Layout Inicial dos Cards (Desktop View). |
| 13/10 (Seg) | Gabriel Saldanha (HTML/CSS) | Implementação Completa da Responsividade (Media Queries) e Layout Mobile. |
| 14/10 (Ter) | Ambos | Refinamento final, Correções de Consistência do Cabeçalho e Rodapé, e Preparação do Repositório (README). |
| 10/11 (Seg) | Ambos | adicionaram a localização e meios de contao ao site. |
| 12/11 (qua) | Gabriel Saldanha JavaScript colocando o header e o footer. |



## 6. Acesse o site aqui
https://saldanhagdev.github.io/Auto-Guia-GG

<img width="1858" height="918" alt="image" src="https://github.com/user-attachments/assets/c65297a4-805b-417b-83da-bd11cb62a42f" />

| Data         | Descrição                  |
|--------------|---------------------------|
| 13/11 (Qui) | Dia da publicação do site.|



##7. Navegadores testados
| Navegador      | Avaliação| O layout está correto? | Todas as páginas carregam? |  Imagens aparecem? | CSS está aplicado corretamente? | JavaScript funciona | Formulários estão funcionais? | Menu e navegação funcionam? |
|--------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|---------------------------|
| Opera GX     | funcionou bem| Sim | Sim | Sim | Sim | Sim | Sim | Sim |  
| Chrome       | funcionou bem|
| Firefox      | funcionou bem|
| Edge         | funcionou bem|


##8. Teste em dispositivos reais
| Dispositivo   | Avaliação|
|--------------|---------------------------|
| Redmi note 13 | Funcionou bem o layot ficou conforme oque configuramos|
| Motorola g73  | Funcionou bem o layot ficou conforme oque configuramos|
| Computador (1920x1080)| Funcionou bem o layot ficou conforme oque configuramos|
| Notebook (1366x768) | Funcionou bem o layot ficou conforme oque configuramos|







