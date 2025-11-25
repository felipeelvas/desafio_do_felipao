
 
Instruções para eDesafio
# 1️⃣ Desafio Classificador de nível de Herói

**O Que deve ser utilizado**

- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisões

## Objetivo

Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilize uma estrutura de decisão para apresentar alguma das mensagens abaixo:

Se XP for menor do que 1.000 = Ferro
Se XP for entre 1.001 e 2.000 = Bronze
Se XP for entre 2.001 e 5.000 = Prata
Se XP for entre 5.001 e 7.000 = Ouro
Se XP for entre 7.001 e 8.000 = Platina
Se XP for entre 8.001 e 9.000 = Ascendente
Se XP for entre 9.001 e 10.000= Imortal
Se XP for maior ou igual a 10.001 = Radiante

## Saída

Ao final deve se exibir uma mensagem:
"O Herói de nome **{nome}** está no nível de **{nivel}**"

# 🏆 Classificador de Nível de Herói

[![Node.js](https://img.shields.io/badge/Node.js-14.0+-green.svg)](https://nodejs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> **Projeto desenvolvido como parte do Bootcamp Santander 2024 - Fundamentos de Programação**

Um sistema interativo para classificar heróis com base em sua experiência (XP), implementando conceitos fundamentais de programação como estruturas condicionais, laços de repetição, funções e validação de entrada.

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
  - [Windows](#windows)
  - [Linux](#linux)
  - [macOS](#macos)
- [Como Executar](#como-executar)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Lógica de Classificação](#lógica-de-classificação)
- [Exemplos de Uso](#exemplos-de-uso)
- [Testes](#testes)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Autor](#autor)

## 🎯 Sobre o Projeto

Este projeto implementa um **sistema de classificação de heróis** baseado em pontos de experiência (XP), seguindo os requisitos do desafio proposto pela DIO (Digital Innovation One). O sistema categoriza heróis em diferentes níveis, desde **Ferro** até **Radiante**, proporcionando uma experiência interativa e educativa.

### 🎮 Conceitos Aplicados

- **Variáveis**: Armazenamento de dados do herói
- **Operadores**: Comparações e validações lógicas
- **Estruturas de Decisão**: Classificação baseada em condições
- **Laços de Repetição**: Validação robusta de entrada
- **Funções**: Modularização e reutilização de código

## ⚡ Funcionalidades

### Funcionalidades Principais
- ✅ **Classificação Automática**: Sistema de níveis baseado em XP
- ✅ **Validação de Entrada**: Tratamento robusto de dados inválidos
- ✅ **Interface Interativa**: Terminal com prompts amigáveis
- ✅ **Formatação Visual**: Emojis e elementos visuais

### Funcionalidades Avançadas
- 🚀 **Sistema de Progressão**: Cálculo de XP necessário para próximo nível
- 🧪 **Testes Automatizados**: Verificação de todos os cenários
- 📊 **Formatação Numérica**: Separadores de milhares
- 🎨 **Interface Rica**: Design visual atraente

## 🛠 Tecnologias Utilizadas

```json
{
  "runtime": "Node.js 14.0+",
  "linguagem": "JavaScript ES6+",
  "dependências": {
    "prompt-sync": "^4.2.0"
  },
  "ferramentas": [
    "npm",
    "Git",
    "VS Code"
  ]
}