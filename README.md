# 🚀 Tech Week — UniCesumar Londrina 2026

O maior evento de tecnologia da UniCesumar Londrina. Palestras, workshops, projetos e networking em uma semana épica.

**📅 1 a 3 de Junho, 2026 — Londrina, PR**

---

## 📁 Estrutura do Projeto (Clean Struct)

Optamos pela organização **Clean Struct** para garantir melhor visualização, manutenção e escalabilidade do projeto. Cada tipo de arquivo possui sua própria pasta dedicada, facilitando a navegação e colaboração entre os membros do grupo.

```
Trabalho-Leonardo-WeekTech/
│
├── index.html                  ← Landing page principal
├── env.js                      ← Credenciais Supabase (⚠️ gitignored)
├── .gitignore
├── README.md
│
├── assets/
│   └── logos/                  ← Imagens e logos do projeto
│       ├── unicesumar.png
│       ├── caco.png
│       ├── custodio.png
│       └── vitorios.png
│
├── css/
│   ├── style.css               ← Estilos da landing page
│   ├── dashboard.css           ← Estilos do painel administrativo
│   └── checkin.css             ← Estilos das telas de check-in
│
├── js/
│   ├── script.js               ← Lógica da landing page + inscrições
│   ├── dashboard.js            ← Lógica do painel administrativo
│   └── checkin.js              ← Lógica do check-in de presença
│
├── pages/
│   ├── dashboard.html          ← Painel administrativo (login necessário)
│   ├── checkin-day1.html       ← Check-in presença — Dia 1 (01/06)
│   ├── checkin-day2.html       ← Check-in presença — Dia 2 (02/06)
│   └── checkin-day3.html       ← Check-in presença — Dia 3 (03/06)
│
└── docs/                       ← Documentação do projeto
```

### Por que Clean Struct?

- **Organização visual**: cada tipo de arquivo (HTML, CSS, JS, imagens) em seu lugar
- **Facilidade de manutenção**: encontre qualquer arquivo rapidamente
- **Escalabilidade**: fácil adicionar novas páginas, estilos ou scripts
- **Colaboração**: todos do grupo sabem exatamente onde colocar novos arquivos

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura das páginas |
| **CSS3** | Estilização com design system customizado |
| **JavaScript (ES6+)** | Lógica, interatividade e integração |
| **Supabase** | Backend (banco de dados, autenticação, realtime) |
| **Chart.js** | Gráficos no dashboard administrativo |
| **Font Awesome** | Ícones |
| **Google Fonts** | Tipografia (Syne + JetBrains Mono) |

---

## ⚙️ Como Rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Pedrolucassss/Trabalho-Leonardo-WeekTech.git
   ```

2. Crie o arquivo `env.js` na raiz com suas credenciais Supabase:
   ```js
   window.ENV = {
     SUPABASE_URL: 'sua-url-aqui',
     SUPABASE_KEY: 'sua-chave-aqui'
   };
   ```

3. Abra o `index.html` no navegador (ou use Live Server no VS Code).

> ⚠️ **Importante**: O arquivo `env.js` está no `.gitignore` para não vazar as chaves da API. Cada membro do grupo deve criar o seu localmente.

---

## 👥 Funcionalidades

- **Landing Page** — Página principal com informações do evento, programação, palestrantes e projetos
- **Inscrições** — Formulários para participantes, palestrantes e projetos (salvos no Supabase)
- **Login Administrativo** — Autenticação via Supabase Auth
- **Dashboard** — Painel com KPIs, gráficos, tabela de dados e exportação CSV
- **Check-in de Presença** — Telas por dia do evento para confirmação via RA
- **Chatbot** — Assistente TechBot para dúvidas sobre o evento
- **Coffee Break** — Sistema de confirmação com modal de compromisso

---

## 👨‍💻 Desenvolvido por

Alunos de **Análise e Desenvolvimento de Sistemas** e **Engenharia de Software** da UniCesumar Londrina.
