# 🏆 Classificador de Nível de Herói

[![Node.js](https://img.shields.io/badge/Node.js-14.0+-green.svg)](https://nodejs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> **Projeto desenvolvido como parte do Bootcamp Santander 2024 - Fundamentos de Programação**

Um sistema interativo para classificar heróis com base em sua experiência (XP), implementando conceitos fundamentais de programação como estruturas condicionais, laços de repetição, funções e validação de entrada.

## 📋 Índice

- [Objetivo do Desafio](#objetivo)
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação](#-instalação)
  - [Windows](#windows)
  - [Linux](#linux)
  - [macOS](#macos)
- [Como Executar](#️-como-executar)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Lógica de Classificação](#-lógica-de-classificação)
- [Exemplos de Uso](#-exemplos-de-uso)
- [Testes](#-testes)
- [Contribuição](#-contribuição)
- [Licença](#-licença)
- [Autor](#-autor)

## Objetivo

### 🎯 Desafio Classificador de Nível de Herói

**O Que deve ser utilizado:**
- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisões

**Meta:** Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilize uma estrutura de decisão para apresentar a classificação baseada nos ranges:

| Range de XP | Nível |
|-------------|-------|
| 0 - 999 | Ferro |
| 1.000 - 2.000 | Bronze |
| 2.001 - 5.000 | Prata |
| 5.001 - 7.000 | Ouro |
| 7.001 - 8.000 | Platina |
| 8.001 - 9.000 | Ascendente |
| 9.001 - 10.000 | Imortal |
| 10.001+ | Radiante |

**Saída Esperada:** "O Herói de nome **{nome}** está no nível de **{nivel}**"

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