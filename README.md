# 🛰️ GeoRisk — Monitoramento de desastres naturais por satélite

## 🚀 Descrição do Projeto

O **GeoRisk** é uma plataforma web que simula um sistema de monitoramento ambiental capaz de detectar desastres naturais (enchentes, incêndios, deslizamentos, tempestades) por meio de satélites e disparar alertas direcionados aos usuários cadastrados em cada região afetada.

O site implementa, em HTML/CSS/JavaScript puros, a interface da Central de Monitoramento, um simulador de emissão de alertas e todo o conteúdo institucional do projeto.

## 🛠️ Tecnologias Utilizadas

O projeto GeoRisk é uma aplicação web estática, construída com foco na apresentação de conteúdo e interações básicas. As tecnologias empregadas incluem:

*   **HTML5**: Utilizado para a estruturação semântica e organização do conteúdo das páginas web.
*   **CSS3**: Responsável pela estilização visual, layout responsivo e elementos de design, seguindo uma arquitetura modular para facilitar a manutenção.
*   **JavaScript (ES6)**: Implementado para funcionalidades interativas específicas, como a navegação do menu, simulador de alertas e outras dinâmicas da interface.
*   **SVG inline**: Para ícones (zero dependências externas).
*   **Google Fonts**: Poppins + Inter.
*   **Git + GitHub**: Para versionamento.

Nenhum framework de UI (Bootstrap, Material, Tailwind, jQuery, etc.) foi utilizado, em conformidade com o regulamento da Global Solution.

## 📂 Estrutura de Pastas do Projeto

A organização do projeto segue uma estrutura lógica e modular, desenhada para otimizar o desenvolvimento e a manutenção:

```
georisk/
├── index.html              # Página inicial
├── sobre.html              # Sobre o projeto + diagrama UML
├── monitoramento.html      # Solução 1 — Dashboard ao vivo
├── alertas.html            # Solução 2 — Simulador de alertas
├── integrantes.html        # Equipe NextCode
├── faq.html                # Perguntas frequentes
├── contato.html            # Formulário funcional
├── README.md
├── assets/                 # Imagens, ícones e mídia
│   ├── logo.svg
│   ├── logo-nextcode.png
│   ├── hero-satelite.jpg
│   ├── dashboard-monitoramento.jpg
│   ├── diagrama-uml.png
│   └── integrante-1..5.{jpg,jpeg}
├── css/
│   ├── variaveis.css       # Tokens de design e tipografia
│   ├── base.css            # Layout, header, footer, componentes
│   ├── responsividade.css  # Media queries (mobile/tablet/desktop)
│   └── pages/
│       ├── inicio.css
│       ├── monitoramento.css
│       ├── alertas.css
│       ├── contato.css
│       └── faq.css
└── js/
    ├── icons.js            # Renderiza ícones SVG inline
    ├── main.js             # Menu, FAQ, tabs, modal, animações
    ├── alertas.js          # Simulador + validação
    └── contato.js          # Validação do formulário
```

### Detalhes da Estrutura CSS

As folhas de estilo são carregadas na seguinte sequência para garantir a aplicação correta e hierárquica dos estilos:

1.  `css/variaveis.css`: Define variáveis de design globais, estilos de reset e configurações de tipografia base.
2.  `css/base.css`: Contém estilos comuns a diversas partes do site, como cabeçalho, rodapé, botões, cards, containers e animações gerais.
3.  `css/pages/<pagina>.css`: Aplica estilos exclusivos para cada página específica, garantindo a individualidade visual quando necessário.
4.  `css/responsividade.css`: Agrupa todas as regras `@media` para adaptar o layout a diferentes tamanhos de tela, assegurando a experiência responsiva.

## 🧩 Páginas da solução

A Global Solution exige **no mínimo 2 páginas dedicadas à solução**. O GeoRisk entrega:

1.  **`monitoramento.html`** — painel da Central de Monitoramento com mapa interativo (pins de alerta clicáveis, modais), lista de eventos em tempo real e abas de indicadores (satélites / regiões / desastres).
2.  **`alertas.html`** — simulador funcional onde o usuário monta um alerta (região, tipo, severidade, mensagem), vê a pré-visualização atualizada em tempo real e dispara o alerta — com validação completa de formulário.

## ⚙️ Interatividade JavaScript

-   Menu hambúrguer responsivo
-   Acordeon de FAQ
-   Abas (tabs) no dashboard
-   Modais nos pinos do mapa e na Central de Monitoramento
-   Simulador de alertas com validação de formulário
-   Formulário de contato funcional

## 👥 Autores e Créditos

O projeto GeoRisk foi desenvolvido pelo grupo **NextCode** para a **Global Solution 2026 — FIAP** (1TDSPO). A equipe é composta por estudantes da turma 1TDSPO de Análise e Desenvolvimento de Sistemas da FIAP. A seguir, os membros da equipe com seus respectivos RMs e links para perfis profissionais:

| Nome                                | RM       | Turma    | LinkedIn | GitHub   |
| :---------------------------------- | :------- | :------- | :------- | :------- |
| Guilherme dos Santos Rocha          | 570005   | 1TDSPO   | [GR][li1] | [GR][gh1] |
| Giovanni Della Crucce Azevedo Santana | 572752   | 1TDSPO   | [GS][li2] | [GS][gh2] |
| César Anastácio dos Anjos Ledres    | 573833   | 1TDSPO   | [CL][li3] | [CL][gh3] |
| Caio Gonçalves Feixas               | 569956   | 1TDSPO   | [CF][li4] | [CF][gh4] |
| Théo Caria Gonçalves                | 572914   | 1TDSPO   | [TC][li5] | [TC][gh5] |

## 🖼️ Imagens e Representação do Projeto

Para uma visualização do projeto, apresentamos algumas capturas de tela da interface da plataforma GeoRisk:

### Sobre o Projeto

![Sobre o Projeto GeoRisk](https://files.manuscdn.com/user_upload_by_module/session_file/310519663460776134/XtsxzLoqHIHmcZFf.png)

*Visão geral do projeto GeoRisk, destacando a tecnologia espacial para detecção de riscos e o sistema de alerta direcionado.*

### Classificação de Risco

![Classificação de Risco GeoRisk](https://files.manuscdn.com/user_upload_by_module/session_file/310519663460776134/ODERbIYvbfrfojCl.png)

*Classificação de risco do sistema GeoRisk, com níveis Crítico, Moderado e Baixo para avaliação da gravidade dos alertas.*

## 🔗 Link do Repositório

O código-fonte completo do projeto GeoRisk está disponível publicamente no GitHub:

[https://github.com/Rochagx/GlobalSolution_GeoRisk](https://github.com/Rochagx/GlobalSolution_GeoRisk) 

## 📧 Contato

Para quaisquer dúvidas, sugestões, propostas de parceria ou necessidade de suporte, a equipe NextCode pode ser contatada através dos perfis do LinkedIn dos integrantes listados acima. Alternativamente, é possível utilizar o formulário de contato disponível na página dedicada do projeto.

*   **Localização:** FIAP — Av. Paulista, 1106 — São Paulo, SP
*   **Turma:** 1TDSPO

[li1]: https://www.linkedin.com/in/guilherme-rocha-tech/ "LinkedIn de Guilherme dos Santos Rocha"
[gh1]: https://github.com/Rochagx "GitHub de Guilherme dos Santos Rocha"
[li2]: https://www.linkedin.com/in/giovanni-santana-7bb590249/ "LinkedIn de Giovanni Della Crucce Azevedo Santana"
[gh2]: https://github.com/giovannidcas "GitHub de Giovanni Della Crucce Azevedo Santana"
[li3]: https://www.linkedin.com/in/césar-ledres-679240318/ "LinkedIn de César Anastácio dos Anjos Ledres"
[gh3]: https://github.com/cesarledres "GitHub de César Anastácio dos Anjos Ledres"
[li4]: https://www.linkedin.com/in/caio-gonçalves-450008322/ "LinkedIn de Caio Gonçalves Feixas"
[gh4]: https://github.com/Caiofeixas "GitHub de Caio Gonçalves Feixas"
[li5]: https://www.linkedin.com/in/theo-caria-801834395/ "LinkedIn de Théo Caria Gonçalves"
[gh5]: https://github.com/theo4321 "GitHub de Théo Caria Gonçalves"
