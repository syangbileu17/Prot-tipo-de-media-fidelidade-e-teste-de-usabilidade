# 🎓 Central de Autoatendimento Estudantil — v2.0

> Portal digital desktop para abertura, acompanhamento e gestão de solicitações acadêmicas — projetado para estudantes com diferentes níveis de familiaridade digital e alta necessidade de autonomia.

---

## 👩‍💻 Equipe

Projeto desenvolvido por:

- **Aline Herrero**
- **Jamilly Duda**
- **Syang de Battisti**

---

## 📌 Sobre o Projeto

A **Central de Autoatendimento Estudantil** é um portal digital desktop desenvolvido no contexto acadêmico-institucional, com foco no módulo de **Abertura e Acompanhamento de Solicitações**.

O produto permite que estudantes resolvam demandas administrativas de forma simples, rápida e sem depender de suporte humano — reduzindo a carga sobre setores como secretaria, coordenação e suporte técnico, e devolvendo autonomia ao usuário final.


---

## 🎯 Objetivos do Módulo

| # | Objetivo | Descrição |
|---|----------|-----------|
| 1 | 📝 Abrir solicitações | Fluxo guiado e simplificado para registrar novos chamados |
| 2 | 🗂️ Categorizar corretamente | Orientação para o usuário escolher o tipo de serviço adequado |
| 3 | 📊 Acompanhar status | Visualização clara do progresso e estado de cada chamado |
| 4 | 📁 Consultar histórico | Acesso organizado a solicitações anteriores |
| 5 | 💬 Receber feedback claro | Retorno visual sobre cada etapa do processo |

---

## 👤 Perfil do Usuário

- Pessoa com **pouca familiaridade técnica**
- Em geral, está com **pressa** e precisa resolver algo rapidamente
- Prefere **autonomia** a depender de atendimento humano
- Pode estar acessando o portal pela primeira vez ou com baixa frequência

---

## 📋 Tarefas

### Tarefa Principal
> Registrar uma nova solicitação de serviço e acompanhar seu status.

### Tarefas Secundárias
- Consultar histórico de solicitações
- Editar ou complementar uma solicitação aberta
- Filtrar solicitações por status ou categoria
- Visualizar detalhes completos de um chamado

---

## 🗺️ Fluxo Principal — Jornada do Usuário

```
[Login / Acesso ao Portal]
         ↓
[Dashboard] → visão geral e atalhos rápidos
         ↓
[Solicitações] → listagem com filtros por status e categoria
         ↓
[Nova Solicitação] → fluxo guiado em etapas:
     │
     ├─ Etapa 1 → Seleção do tipo de serviço
     ├─ Etapa 2 → Descrição e detalhamento
     ├─ Etapa 3 → Prioridade e anexos
     └─ Etapa 4 → Revisão e envio
         ↓
[Confirmação] → protocolo gerado (ex: #123-ABC)
         ↓
[Detalhes do Chamado] → status, tipo, prioridade, data, edição
         ↓
[Histórico] → consulta e filtros de chamados anteriores
```

---

## 🖥️ Telas Projetadas

### 🔐 Login
Acesso ao portal com identidade visual institucional, campo de autenticação e ilustração acolhedora.

### 🏠 Dashboard
Resumo das solicitações ativas, atalhos para as ações principais e navegação lateral estruturada via sidebar.

### 📋 Lista de Solicitações
Visualização de todos os chamados do usuário, com badges de status coloridos e filtros por categoria e situação.

### ➕ Nova Solicitação — Fluxo em 4 etapas

| Etapa | Conteúdo |
|-------|----------|
| **1 — Tipo de serviço** | Seleção guiada entre categorias (Problema Técnico, Solicitação de Serviço, Ajuste Acadêmico etc.) |
| **2 — Descrição** | Campo de descrição livre do problema ou necessidade |
| **3 — Prioridade e anexos** | Seleção de prioridade e upload opcional de arquivos |
| **4 — Revisão e envio** | Resumo completo antes da confirmação final |

### ✅ Confirmação de Envio
Protocolo único gerado (`#123-ABC`), mensagem de feedback positivo e opções para acompanhar ou criar nova solicitação.

### 🔍 Detalhes do Chamado
Informações completas do chamado (tipo, prioridade, status, data), campo para complementar informações e acesso à edição.

### ✏️ Editar / Complementar Solicitação
Interface para adicionar informações, enviar atualização ou cancelar a edição com segurança.

### 📁 Histórico de Solicitações
Listagem de todos os chamados com status visual, data de abertura e acesso direto aos detalhes.

### 🗃️ Minhas Solicitações
Cards resumidos com tipo, data e situação atual, com ações rápidas de acesso.

---


## 🧠 Decisões de UX

### Redução de fricção em formulários
O fluxo de nova solicitação foi dividido em **etapas curtas e focadas**, com barra de progresso visível — evitando sobrecarga cognitiva e abandono do processo.

### Orientação na categorização
A seleção do tipo de serviço é feita com **opções visuais claras e descrições objetivas**, guiando o usuário mesmo sem conhecimento prévio das categorias disponíveis.

### Organização de múltiplos atendimentos
A lista de solicitações usa **badges coloridos por status** e hierarquia visual clara, permitindo identificar rapidamente o estado de cada chamado sem precisar abri-lo.

### Feedback sobre estados e progresso
Cada etapa do fluxo apresenta **indicadores visuais de progresso**, e ações concluídas geram mensagens de confirmação explícitas com geração de protocolo único.

---

## ✅ Funcionalidades Implementadas

- [x] Login e acesso ao portal
- [x] Dashboard com resumo e atalhos
- [x] Lista de solicitações com filtros por status e categoria
- [x] Fluxo guiado de nova solicitação em 4 etapas
- [x] Confirmação com protocolo gerado automaticamente
- [x] Detalhes completos do chamado
- [x] Edição e complementação de solicitação
- [x] Histórico de atendimentos
- [x] Minhas solicitações com indicadores de status

---

## 📂 Estrutura do Arquivo Figma

```
📁 Central de Autoatendimento Estudantil — v2
│
├── 🔐 Frame 2        → Login
├── 🏠 Desktop 2      → Solicitações (visão geral)
├── 📁 Desktop 5      → Histórico de solicitações
├── ➕ Desktop 13     → Nova solicitação — Etapa 1 (tipo)
├── ✍️  Desktop 15     → Nova solicitação — Etapa 2 (descrição)
├── ✅ Desktop 15     → Confirmação de envio / protocolo
├── 📋 Desktop 16     → Minhas solicitações
├── 🔍 Desktop 17     → Detalhes do chamado
├── ✏️  Desktop 18     → Editar / complementar solicitação
├── 💻 Macbook        → Nova solicitação (variante)
└── 🔲 Componentes    → Variantes, estados e elementos reutilizáveis
```

---

## 🛠️ Ferramenta Utilizada

- **Figma** — prototipação de alta fidelidade

---

## 📚 Contexto Acadêmico

Projeto desenvolvido na disciplina de **Design de Interação / UX**, com foco em:

- Definição de perfil e jornada do usuário
- Arquitetura de informação
- Prototipação de interface desktop
- Aplicação de princípios de usabilidade e acessibilidade

---

*Desenvolvido por Aline Herrero, Jamilly Duda e Syang de Battisti — segunda versão.*
