# 🎯 Impact Leader — Formação de Líderes

> Instituto da Liderança · Diagnóstico de Liderança com IA + Painel de Gestão

---

## 🔗 Links

| | Link |
|---|---|
| 📋 **Formulário dos Participantes** | [https://sergiolbsm-coder.github.io/Impact-Leader/](https://sergiolbsm-coder.github.io/Impact-Leader/) |
| 📊 **Painel do Gestor** | [https://sergiolbsm-coder.github.io/Impact-Leader/painel.html](https://sergiolbsm-coder.github.io/Impact-Leader/painel.html) |

---

## 📌 O que é

Sistema completo de **diagnóstico de liderança** para o programa **Formação Impact Leader** do Instituto da Liderança. Substitui o Google Forms por uma aplicação inteligente que gera relatórios personalizados automaticamente.

---

## ⚙️ Funcionalidades

### Formulário (`index.html`)
- **50 perguntas** distribuídas em **15 dimensões** de liderança
- Escala visual de 0 a 10 com feedback de cores em tempo real
- Barra de progresso com validação completa antes do envio
- Geração automática de diagnóstico com radar de competências
- **Download do relatório em PDF** individual ao finalizar
- Envio automático das respostas para o Google Sheets
- Design responsivo — funciona em desktop e mobile

### Painel do Gestor (`painel.html`)
- **Worklist completa** de todos os respondentes com busca em tempo real
- Filtro por nível: Avançado · Consolidado · Em desenvolvimento · Iniciante
- Score global, nível de maturidade e foco prioritário por participante
- **PDF individual** de cada respondente com um clique
- **Exportar todos em PDF** com um único botão
- Resumo da turma: total de respondentes, média geral e dimensão mais crítica
- Sincronização direta com o Google Sheets via Apps Script

---

## 📐 As 15 Dimensões Avaliadas

| # | Dimensão | # | Dimensão |
|---|---|---|---|
| 01 | Objetivos | 09 | Comunicação |
| 02 | Estratégias | 10 | Assertividade |
| 03 | Execução | 11 | Energia |
| 04 | Resultados | 12 | Decisões |
| 05 | Bloqueios | 13 | Financeiro |
| 06 | Tempo | 14 | Proatividade |
| 07 | Inteligência Emocional | 15 | Conflitos |
| 08 | Relacionamentos | | |

---

## 🏗️ Arquitetura

```
Participante preenche formulário
        ↓
Apps Script (Google) recebe os dados
        ↓
Google Sheets salva as respostas
        ↓
Painel do Gestor lê e exibe em tempo real
        ↓
PDF gerado localmente no navegador (jsPDF)
```

---

## 🛠️ Tecnologias

- **HTML/CSS/JS** puro — sem frameworks, sem dependências de build
- **Google Apps Script** — backend serverless para gravar e ler da planilha
- **Google Sheets** — banco de dados das respostas
- **jsPDF** — geração de PDF no navegador
- **GitHub Pages** — hospedagem estática gratuita
- **Canvas API** — radar de competências renderizado nativamente

---

## 📁 Arquivos

| Arquivo | Descrição |
|---|---|
| `index.html` | Formulário de diagnóstico para os participantes |
| `painel.html` | Painel de gestão exclusivo do Instituto |
| `admin.html` | Painel administrativo complementar |

---

*Instituto da Liderança · [institutodaLideranca.com.br](https://institutodaLideranca.com.br)*
