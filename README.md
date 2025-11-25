
 
Instruções para o Desafio
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


> **Projeto desenvolvido como parte do Bootcamp Santander 2025 - Fundamentos de Programação**

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
```

## Pré-requisitos
### Antes de executar o projeto, certifique-se de ter instalado:

- Node.js (versão 14.0 ou superior)

- npm (geralmente vem com Node.js)
- Git (para clonar o repositório)

# Verificar versões instaladas
```bash
node --version
npm --version
git --version
```

# 🚀 Instalação

## 🪟 Windows

```bash
# 1. Verificar se Node.js está instalado
node --version
npm --version

# 2. Se não estiver instalado, baixe em: https://nodejs.org/
# Escolha a versão LTS (recomendada)

# 3. Clonar o repositório
git clone https://github.com/seu-usuario/classificador-heroi.git

# 4. Navegar para o diretório
cd classificador-heroi

# 5. Instalar dependências
npm install

# 6. Executar o projeto
node src/index.js
```
## 🐧Linux
```bash
# 1. Instalar Node.js via gerenciador de pacotes
# Ubuntu/Debian:
sudo apt update
sudo apt install nodejs npm

# CentOS/RHEL/Fedora:
sudo dnf install nodejs npm
# ou
sudo yum install nodejs npm

# 2. Verificar instalação
node --version
npm --version

# 3. Clonar o repositório
git clone https://github.com/seu-usuario/classificador-heroi.git

# 4. Navegar para o diretório
cd classificador-heroi

# 5. Instalar dependências
npm install

# 6. Executar o projeto
node src/index.js
```

## 🍎 macOS
```bash
# 1. Instalar Node.js via Homebrew (recomendado)
# Primeiro instale o Homebrew se não tiver:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Depois instale o Node.js:
brew install node

# Alternativa: Baixar diretamente de https://nodejs.org/

# 2. Verificar instalação
node --version
npm --version

# 3. Clonar o repositório
git clone https://github.com/seu-usuario/classificador-heroi.git

# 4. Navegar para o diretório
cd classificador-heroi

# 5. Instalar dependências
npm install

# 6. Executar o projeto
node src/index.js
```

# Como Executar

## Execução Padrão
```bash
# Executar o programa principal
node src/index.js

# Ou usando npm script (se configurado)
npm start
```

## Execução com Parâmetros de Debug
```bash
# Executar com informações de debug
node --inspect src/index.js
```

# 👨‍💻 Autor
Felipe Elvas Barbosa

🎓 Graduando em Sistemas de Informação

💻 Desenvolvedor Mobile em formação

🌱 Especializando em Flutter, Java e IA

Conecte-se comigo:

🐙 [GitHub]("https://github.com/felipeelvas")

💼 [LinkedIn]("https://www.linkedin.com/in/felipe-elvas/")


# 🎯 Próximos Passos

### Este projeto faz parte da minha jornada de aprendizado em programação. Próximas implementações planejadas:

 🎮 Sistema de classes (Guerreiro, Mago, Arqueiro)

 ⚔️ Sistema de combate entre heróis

 💾 Persistência de dados em JSON

 🌐 Interface web com HTML/CSS/JavaScript

 📱 Versão mobile em Flutter

🏆 Agradecimentos

DIO (Digital Innovation One) - Pela oportunidade de aprendizado

Santander Bootcamp - Pelo programa de formação
Comunidade Dev - Pelo suporte e inspiração

⭐ Se este projeto te ajudou, deixe uma estrela!

💡 Dúvidas ou sugestões? Abra uma issue!

Desenvolvido com ❤️ por Felipe
