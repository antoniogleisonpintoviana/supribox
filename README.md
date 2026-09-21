# Supribem - Sistema de Caixa Local

Sistema web leve, ágil e totalmente offline desenvolvido para o controle de fechamento de caixa, sangrias e emissão de relatórios gerenciais de estabelecimentos.

---

## 🚀 Funcionalidades

* **Módulo de Fechamento de Caixa (`fechamento.html`):**
  * Lançamento de valores separados por forma de pagamento: **Dinheiro**, **Crédito**, **Débito**, **Alimentação**, **Pix** e **POS**.
  * Entrada rápida otimizada para teclado numérico com formatação automática de moeda (R$).
  * Atalho de teclado com a tecla `Enter` para agilizar o lançamento.
  * Painel superior com soma e acumulação automática por categoria e total geral em tempo real.
  * Histórico detalhado de lançamentos com marcação de horário e opção de exclusão individual ou limpeza total.

* **Módulo de Sangria / Retiradas (`sangria.html`):**
  * Controle de retiradas dividido por **Dinheiro (Depósitos)**, **Pix** e **Trocas**.
  * Painel de totais acumulados específicos para sangria e histórico individualizado.

* **Relatório Consolidado em PDF (`index.html`):**
  * Tela de menu principal para alternar de forma simples entre os módulos.
  * Botão de geração de relatório geral que consolida e resume todos os dados de fechamento e sangria salvos no navegador para impressão direta ou salvamento em PDF.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3** (Interface moderna com design responsivo e identidade visual customizada).
* **JavaScript Vanilla (ES6+)** (Lógica de funcionamento totalmente client-side).
* **LocalStorage API** (Persistência de dados local no navegador sem necessidade de banco de dados externo ou servidor web ativo).

---

## 📂 Estrutura de Arquivos

Na pasta do seu projeto (`projeto supribox`), certifique-se de manter a seguinte estrutura:

```text
📁 projeto supribox/
├── 📄 index.html          # Tela principal (Menu e Geração de PDF)
├── 📄 fechamento.html     # Tela de lançamentos do caixa
└── 📄 sangria.html        # Tela de registro de sangrias
