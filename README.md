# TripKey Hotels (`tripkey-hotels2`)

Plataforma web responsiva para busca, comparação de preços, gestão de favoritos e cadastro de hóspedes para reservas de hotéis.

## 📄 Documentação
* [Product Requirements Document (PRD)](docs/prd.md)
* [Especificação Técnica (Architecture)](docs/architecture.md)

## 💻 Tecnologias Utilizadas
* **HTML5 & CSS3 / SCSS**
* **Materialize CSS** (Framework CSS)
* **JavaScript / jQuery**
* **JSON Server** (API REST Fake)

---

## ✅ Checklist - Indicadores de Desempenho (ID)

### RA1 - Frameworks CSS e Responsividade
- [x] **ID 01** - Prototipa interfaces adaptáveis para no mínimo os tamanhos de tela mobile e desktop, usando ferramentas de design tradicionais (Figma, Quant UX ou Sketch) ou IA (Stitch).
- [ ] **ID 02** - Implementa layout responsivo com Framework CSS (Bootstrap, Materialize, Tailwind + DaisyUI) usando Flexbox ou Grid do próprio framework.
- [ ] **ID 03** - Implementa layout responsivo com CSS puro, usando Flexbox ou Grid Layout.
- [ ] **ID 04** - Utiliza componentes prontos de um Framework CSS (ex.: card, button) e componentes JavaScript do framework (ex.: modal, carousel).
- [ ] **ID 05** - Cria layout fluido usando unidades relativas (vw, vh, %, em, rem) no lugar de unidades fixas (px).
- [ ] **ID 06** - Aplica um Design System consistente (cores, tipografia, padrões de componentes) em toda a aplicação.
- [ ] **ID 07** - Utiliza Sass (SCSS) com ou sem framework, aplicando variáveis, mixins e funções para modularizar o código.
- [ ] **ID 08** - Aplica tipografia responsiva (media queries mobile first) ou tipografia fluida (função clamp() + unidades relativas).
- [ ] **ID 09** - Aplica técnicas de responsividade de imagens usando CSS (object-fit, containers com unidades relativas).
- [ ] **ID 10** - Otimiza imagens usando formatos modernos (WebP) e carregamento adaptativo (srcset, picture, ou parâmetros do Cloudinary).

### RA2 - Tratamento e Validação de Formulários
- [ ] **ID 11** - Implementa validação HTML nativa (campos obrigatórios, tipos, limites de caracteres) com mensagens de erro/sucesso no lado cliente.
- [ ] **ID 12** - Aplica expressões regulares (REGEX) para validações customizadas (e-mail, telefone, datas, etc.).
- [ ] **ID 13** - Utiliza elementos de seleção em formulários (checkbox, radio, select) para coleta de dados.
- [ ] **ID 14** - Implementa leitura e escrita no Web Storage (localStorage/sessionStorage) para persistir dados localmente.

### RA3 - Ferramentas de Otimização e Produtividade
- [ ] **ID 15** - Configura ambiente com Node.js e NPM para gerenciamento de pacotes e dependências.
- [ ] **ID 16** - Utiliza boas práticas de versionamento no Git/GitHub (branch main ou branches específicos, uso de .gitignore).
- [x] **ID 17** - Mantém um README.md padronizado, conforme template da disciplina, com checklist preenchido.
- [x] **ID 18** - Organiza arquivos do projeto de forma modular, seguindo padrão de exemplo fornecido.
- [ ] **ID 19** - Configura linters e formatadores (ESLint, Prettier) para manter qualidade e padronização do código.

### RA4 - Interatividade e Manipulação do DOM
- [ ] **ID 20** - Utiliza jQuery para manipulação do DOM e interatividade (eventos, animações, manipulação de elementos).
- [ ] **ID 21** - Integra e configura um plugin jQuery relevante (ex.: jQuery Mask Plugin).

### RA5 - Requisições Assíncronas e Consumo de APIs
- [ ] **ID 22** - Realiza requisições assíncronas para uma API fake (ex.: JSON Server) para persistir dados de um formulário.
- [ ] **ID 23** - Realiza requisições assíncronas para uma API fake para exibir dados na página.
- [ ] **ID 24** - Realiza requisições assíncronas para APIs públicas reais (OpenWeather, ViaCEP etc.), exibindo os dados e tratando erros.
