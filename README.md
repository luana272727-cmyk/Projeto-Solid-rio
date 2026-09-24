# 🤝 Projeto Solidário

O **Projeto Solidário** é uma plataforma web desenvolvida para engajar voluntários, arrecadar doações, divulgar eventos e gerenciar serviços comunitários focados na transformação social de pessoas em situação de vulnerabilidade.

---

## 📌 Índice
- [Sobre o Projeto](#-sobre-o-projeto)
- [Estrutura do Site e Funcionalidades](#-estrutura-do-site-e-funcionalidades)
- [Arquitetura do Código](#-arquitetura-do-código)
- [Fluxo de Git (GitFlow)](#-fluxo-de-git-gitflow)
- [Como Executar o Projeto](#-como-executar-o-projeto)

---

## 🚀 Sobre o Projeto

O portal atua como o ponto central de conexão entre a instituição e a comunidade. Suas principais frentes são:
- **Engajamento:** Cadastro de voluntários e participação em grupos comunitários.
- **Arrecadação:** Doações pontuais e gestão de assinaturas recorrentes.
- **Transparência & Impacto:** Divulgação de histórias de impacto e prestação de contas.
- **Agendamentos:** Inscrição em eventos e marcação de atendimentos/serviços online.

---

## 🗺️ Estrutura do Site e Funcionalidades

A aplicação possui um **Layout Global** (Header e Footer) e é dividida nas seguintes áreas centrais:

### 🌐 1. Páginas Públicas / Institucionais
* **Home (`/`)**: Apresentação da causa, formulário *Hero* para novos cadastros, seção de voluntariado, botão de doação rápida e histórias de impacto.
* **Eventos (`/eventos`) & Detalhes (`/informacoes-evento`)**: Lista de eventos promovidos com páginas dedicadas para ver detalhes e se inscrever.
* **Programação (`/programacao`)**: Agenda detalhada com os horários e locais das atividades.
* **Página de Serviço (`/pagina-servico` / `/inquiry-services`)**: Informações e formulário de contato para serviços comunitários.

### 💰 2. E-Commerce e Doações
* **Donate (`/donate`)**: Seleção de valores e envio de contribuições.
* **Carrinho (`/carrinho`)**: Listagem dos itens ou doações selecionadas.
* **Checkout (`/checkout`)**: Formulário de resumo do pedido e informações de pagamento.
* **Página de Agradecimento (`/pagina-agradecimento`)**: Confirmação do recebimento da doação.

### 👤 3. Área do Membro / Minha Conta
* **Perfil (`/perfil`)**: Exibição dos dados do voluntário/doador.
* **Configurações da Conta (`/configuracoes-da-conta`)**: Gestão de dados pessoais e senhas.
* **Meus Pedidos (`/meus-pedidos`) & Minhas Assinaturas (`/minhas-assinaturas`)**: Histórico de contribuições.
* **Notificações (`/notifications`)**: Central de avisos para o usuário.
* **Grupos (`/grupos` / `/my-groups`)**: Participação em grupos e frentes de ação da comunidade.

### 📅 4. Agendamentos
* **Agendamento Online (`/agendamento-online` / `/calendario-agendamentos`)**: Escolha de datas e horários para atendimentos.
* **Formulário de Agendamento (`/formulario-agendamento`)**: Preenchimento das informações para confirmação da vaga.

---

## 🛠️ Arquitetura do Código

O código foi construído seguindo boas práticas de HTML5 semântico e CSS modular:

* **HTML5 Semântico:** Uso correto de tags como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, e `<footer>` para melhor acessibilidade e SEO.
* **Metodologia BEM (Block Element Modifier):** A estilização das classes CSS segue a convenção BEM (ex: `.site-header__brand`, `.button--primary`).
* **Acessibilidade (a11y):** Utilização de atributos `aria-label`, `aria-hidden` e `aria-labelledby` para suportar leitores de tela.

---

## 🌿 Fluxo de Git (GitFlow)

O desenvolvimento deste repositório segue o padrão **GitFlow**:

* `main` / `master`: Código estável atualmente em produção.
* `develop`: Branch de integração para desenvolvimento contínuo.
* `feature/*`: Branches temporárias criadas a partir da `develop` para construção de novas telas ou componentes.
* `hotfix/*`: Correções urgentes aplicadas diretamente na `main` e integradas na `develop`.

---

## 💻 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone (https://github.com/luana272727-cmyk/Projeto-Solid-rio)
