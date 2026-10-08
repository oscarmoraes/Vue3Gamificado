# 🚀 Funil Gamificado Vue.js 3 — Trilha SENAI Dev (Aulas 01 a 35)

> Aplicação web interativa, minimalista e gamificada desenvolvida para a trilha de **Desenvolvimento Frontend Moderno com Vue.js 3 do SENAI**, baseada no curso completo de **Vue.js 3** ministrado por Tiago Matos.

---

## 🎯 Sobre o Projeto

O objetivo deste projeto é transformar o aprendizado do ecossistema Vue.js 3 em uma **experiência gamificada em funil**:
- **Avanço Sequencial com Bloqueio Real**: O aluno assiste à aula e só consegue liberar o próximo vídeo após responder corretamente à pergunta técnica de validação.
- **Banco de Dados em JSON (`data/database.json`)**: Estrutura simples e desacoplada contendo todas as 35 aulas, perguntas de múltipla escolha com 4 alternativas, explicações didáticas, dicas e conquistas.
- **Design Mobile-First com Tailwind CSS**: Interface compacta, responsiva e focada na usabilidade em smartphones e desktops.
- **Barras de Rolagem Estilizadas**: Customização completa eliminando barras nativas cinzas do sistema operacional.
- **Sistema de Gamificação**:
  - ⚡ **Pontos de Experiência (XP)**: Ganho de XP a cada acerto (+100 XP a +200 XP por aula, totalizando 4.220 XP).
  - 🎖️ **Patentes / Níveis Dev SENAI**: Evolução progressiva de *Aprendiz Vue 3* até *Mestre Vue.js 3 & Arquiteto Frontend SENAI*.
  - 🏆 **Galeria de Conquistas (Badges)**: 35 medalhas exclusivas desbloqueadas ao longo da trilha.
  - 🎵 **Efeitos Sonoros Nativos**: Síntese de áudio via Web Audio API (sem dependência de arquivos externos de áudio).
  - 🎓 **Certificado Final**: Modal de graduação comemorativo com confetes e opção de impressão ao concluir todas as 35 aulas.
  - 💾 **Persistência no Navegador**: O progresso (etapas liberadas, XP e conquistas) fica salvo automaticamente no `localStorage`.

---

## 📚 Grade Curricular do Funil (Aulas 01 ao 35)

| Aula | Título da Aula | Competência Desenvolvida | Recompensa |
|:---:|:---|:---|:---:|
| **01** | Introdução ao Vue.js 3 | Compreensão da arquitetura de SPAs e do modelo conceitual do Vue.js 3. | 🌱 Boas-vindas ao Vue 3 (+ 100 XP) |
| **02** | Instalação e Ambiente Vue 3 | Configuração de ambiente de desenvolvimento moderno com Node.js e ferramentas de bundling para Vue. | ⚡ Setup Moderno (+ 100 XP) |
| **03** | Single File Components (SFC) | Estruturação modular de interfaces utilizando a especificação de Single File Components (.vue). | 🧩 Arquiteto de SFC (+ 100 XP) |
| **04** | Diretivas Condicionais (v-if e v-show) | Controle eficiente de exibição de elementos no DOM baseado no estado da aplicação. | 🔀 Mestre da Condicional (+ 100 XP) |
| **05** | Diretiva de Repetição (v-for) | Iteração de listas de dados e manutenção da identidade de elementos no Virtual DOM com chaves únicas. | 🔁 Mago dos Loops (+ 100 XP) |
| **06** | Atributos Dinâmicos e Data Binding (v-bind) | Vinculação reativa de propriedades HTML e atributos aos estados do modelo de dados. | 🔗 Especialista em Binding (+ 100 XP) |
| **07** | Classes e Estilos Dinâmicos | Controle programático de classes e estilos CSS condicionados ao estado da aplicação. | 🎨 Modelador Visual (+ 100 XP) |
| **08** | Two-Way Data Binding (v-model) | Criação de formulários reativos e sincronização em tempo real de dados de entrada do usuário. | 📝 Mestre do v-model (+ 110 XP) |
| **09** | Manipulação de Eventos (v-on) | Captura e tratamento de interações do usuário com métodos e modificadores de eventos. | 🎯 Manipulador de Eventos (+ 100 XP) |
| **10** | Propriedades Computadas (computed) | Otimização de cálculos e formatações derivadas com cache inteligente via computed properties. | 🧠 Gênio do Computed (+ 120 XP) |
| **11** | Observadores (watch) | Monitoramento de mutações de estado e execução de efeitos colaterais assíncronos. | 👁️ Olhar Atento (+ 110 XP) |
| **12** | Ciclo de Vida dos Componentes | Gerenciamento temporal de componentes e inicialização correta de recursos externos no DOM. | 🔄 Mestre do Ciclo de Vida (+ 120 XP) |
| **13** | Componentes e Slots | Criação de componentes genéricos reutilizáveis através da projeção de conteúdo com slots. | 📥 Escultor de Slots (+ 110 XP) |
| **14** | CSS Scoped e Global | Modularização e encapsulamento de estilos CSS em componentes evitando vazamento de regras. | 🛡️ Estilista Scoped (+ 100 XP) |
| **15** | Passagem de Dados via Props | Modelagem de interfaces desacopladas com contratos formais de entrada de dados via Props. | 📤 Provedor de Props (+ 120 XP) |
| **16** | Comunicação Filho para Pai (emit) | Implementação do padrão de eventos customizados para notificar componentes ascendentes sobre ações do usuário. | 📢 Emissor de Eventos (+ 110 XP) |
| **17** | Introdução ao Vue Router (Parte 1) | Configuração da camada de navegação e roteamento de URLs em aplicações cliente no Vue 3. | 🧭 Navegador de Rotas (+ 120 XP) |
| **18** | Introdução ao Vue Router (Parte 2) | Construção de rotas com parâmetros dinâmicos e navegação imperativa no Vue Router. | 🗺️ Mestre dos Parâmetros (+ 120 XP) |
| **19** | Introdução ao Vuex (State) | Centralização do estado global da aplicação para evitar acoplamento excessivo na árvore de componentes. | 🏦 Iniciador do Vuex (+ 120 XP) |
| **20** | Vuex: Mutations (Parte 1) | Modificação previsível e rastreável do estado global através de Mutations. | ⚡ Operador de Mutations (+ 110 XP) |
| **21** | Vuex: Mutations (Parte 2) | Depuração avançada com time-travel debugging e manutenção da integridade síncrona de mutações. | ⏱️ Mestre do Sincronismo (+ 120 XP) |
| **22** | Vuex: Getters | Modelagem de dados derivados e filtros reutilizáveis a partir do estado da store. | 🔍 Guru dos Getters (+ 110 XP) |
| **23** | Vuex: Actions | Orquestração de fluxos assíncronos e consumo de APIs REST no ecossistema de store. | 🚀 Arquiteto de Actions (+ 120 XP) |
| **24** | Composition API: setup | Transição arquitetural da Options API para a Composition API no Vue 3. | 💡 Pioneiro da Composition (+ 130 XP) |
| **25** | Composition API: Reatividade (ref & reactive) | Criação e controle de referências reativas primitivas e complexas com ref() e reactive(). | 🔮 Mestre da Reatividade (+ 130 XP) |
| **26** | Composition API: Computed e Watch | Construção de computadas e observadores desacoplados e componíveis. | 🧪 Alquimista Reativo (+ 130 XP) |
| **27** | Composition API: Lifecycle Hooks | Uso de hooks de ciclo de vida importáveis na Composition API. | 🪝 Especialista em Hooks (+ 120 XP) |
| **28** | Composition API: Props e Emits | Comunicação padronizada entre componentes utilizando macros de compilação modernas. | 📐 Mestre dos Macros (+ 130 XP) |
| **29** | Projeto Prático (Aula 01) | Iniciação e planejamento arquitetural de um projeto frontend completo. | 🏗️ Construtor de Projetos (+ 140 XP) |
| **30** | Projeto Prático (Aula 02) | Desenvolvimento de componentes modulares e estilização responsiva de formulários. | 🎨 Arquiteto de Interface (+ 140 XP) |
| **31** | Projeto Prático (Aula 03) | Integração de regras de validação e manipulação reativa de coleções no frontend. | ⚙️ Lapidador de Lógica (+ 140 XP) |
| **32** | Projeto Prático (Aula 04) | Conexão de componentes de tela a stores de estado global para persistência de dados em sessão. | 🌐 Integrador de Estado (+ 140 XP) |
| **33** | Projeto Prático (Aula 05) | Refinamento de experiência do usuário (UX), animações e persistência de dados no cliente. | ✨ Especialista em UX (+ 150 XP) |
| **34** | Refatoração com Composition API (Parte 1) | Modernização de bases de código legadas aplicando refatoração para a Composition API. | 🧹 Refatorador Pro (+ 150 XP) |
| **35** | Refatoração com Composition API (Parte 2) | Criação de Composables customizados e domínio pleno da arquitetura moderna do Vue.js 3. | 👑 Mestre Supremo Vue 3 (+ 200 XP) |

---

## 🛠️ Tecnologias Utilizadas

- **[Vue.js 3](https://vuejs.org/)** (Composition API, reatividade e renderização declarativa no frontend)
- **[Tailwind CSS](https://tailwindcss.com/)** (Design mobile-first utilitário e responsivo)
- **HTML5 Semântico** & **CSS3 Moderno** (Scrollbars personalizadas e micro-animações)
- **Web Audio API** (Sons sintetizados em tempo real)
- **Canvas Confetti** (Efeitos visuais comemorativos)
- **JSON nativo** (Banco de dados desacoplado)
- **LocalStorage API** (Salvamento automático do progresso)

---

## 📂 Estrutura de Arquivos

```text
Vue3Gamificado/
├── data/
│   ├── database.json        # Banco de dados com as 35 aulas e perguntas
│   └── database.fallback.js # Fallback de execução direta sem servidor HTTP
├── css/
│   └── style.css            # Tratamento avançado de scrollbars e animações
├── js/
│   └── app.js               # Aplicação reativa Vue 3 e lógica do funil
├── index.html               # Interface única (Mobile-First)
├── .gitignore               # Arquivos ignorados pelo Git
└── README.md                # Documentação completa do projeto
```

---

## 💻 Como Executar o Projeto

### Opção 1: Direto no Navegador (Sem Instalação)
Basta abrir o arquivo `index.html` em qualquer navegador web moderno (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari, etc.). O projeto conta com fallback local integrado (`data/database.fallback.js`).

### Opção 2: Via VS Code (Live Server)
1. Abra a pasta do projeto no VS Code.
2. Com a extensão **Live Server**, clique com o botão direito sobre o arquivo `index.html` e selecione **Open with Live Server**.

### Opção 3: Via Servidor Web Local
Você pode servir a pasta com qualquer servidor local:
- **Node.js**:
  ```bash
  npx serve .
  ```
- **Python**:
  ```bash
  python -m http.server 8000
  ```
- **PHP**:
  ```bash
  php -S localhost:8000
  ```
- **Apache / Nginx / XAMPP**:
  Copie a pasta para o diretório raiz do seu servidor web (ex: pasta `htdocs` ou `www`) e acesse via `http://localhost/sua-pasta/`.

---

## 🌐 Publicação no GitHub Pages

Para publicar este projeto online gratuitamente:
1. Acesse seu repositório no GitHub (`https://github.com/oscarmoraes/Vue3Gamificado`).
2. Vá em **Settings** > **Pages**.
3. Na seção **Build and deployment**, selecione a branch `main` e a pasta `/ (root)`.
4. Clique em **Save**. Em alguns minutos a página estará online!

---

## 👨‍🏫 Créditos e Referências

- Conteúdo didático baseado na playlist pública de **Vue.js 3** por Tiago Matos no YouTube.
- Adaptação pedagógica e arquitetura gamificada em funil desenvolvida para a capacitação em tecnologia do **SENAI**.
