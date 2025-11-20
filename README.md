# 🐾 PETSHOP_SCHEDULER.md

## Sistema de Agendamentos -- Documentação Oficial do Projeto

## 1. Visão Geral

Este documento define a estrutura oficial, requisitos, regras de
negócio, backlog e diretrizes de desenvolvimento do Sistema de
Agendamentos para Petshop.

## 2. Objetivo do Sistema

-   Organizar os agendamentos do Petshop.
-   Exibir agenda por períodos.
-   Garantir controle e evitar conflitos.
-   Facilitar cadastro e navegação.

## 3. Princípios do Sistema

1.  Simplicidade visual\
2.  Produtividade\
3.  Validação forte\
4.  Escalabilidade\
5.  Experiência fluida

## 4. Arquitetura da Aplicação

Estrutura sugerida:

    src/
     ├─ components/
     ├─ data/
     ├─ styles/
     └─ main.js

## 5. Requisitos Funcionais

### Agenda

-   Exibir por períodos: manhã, tarde, noite.
-   Cada card contém: horário, pet, tutor, telefone, serviço,
    observações.
-   Botão de apagar.

### Modal

-   Campos obrigatórios: tutor, pet, telefone, serviço, data, hora.
-   Bloqueio de fundo e foco inicial.
-   Criar agendamento e fechar modal.

## 6. Regras de Negócio

-   Proibir horários duplicados.
-   Bloquear horários fora da faixa.
-   Ordenação automática por horário.
-   Alterar data muda agenda exibida.

## 7. Backlog por Fases

### FASE 1 --- MVP

-   Criar layout base.
-   Criar modal.
-   Criar validações.

### FASE 2 --- Melhorias

-   Filtros.
-   Responsividade.
-   Animações.

### FASE 3 --- Expansão

-   Cadastro de pets/tutores.
-   Histórico.

### FASE 4 --- Versão Pro

-   Backend real.
-   Login.
-   Painel administrativo.

## 8. Diretrizes de UX

-   Layout limpo.
-   Navegação fluida.
-   Erros claros.

## 9. Entrega

-   Repositório no GitHub.
-   README com instruções.




