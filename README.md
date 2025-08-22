<div align="center">

# 🧮 Modern Calculator App

### Calculadora moderna e responsiva com Next.js e TypeScript

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)

**Uma calculadora moderna e elegante construída com as mais recentes tecnologias web, oferecendo uma experiência de usuário excepcional.**

[🚀 Demo Live](#-demo-live) • [✨ Features](#-features) • [🛠️ Instalação](#️-instalação) • [📱 Screenshots](#-screenshots)

---

</div>

## 🚀 Demo Live

**🌐 [Experimente Agora](https://calculator-app-beta-eight.vercel.app/)**

> Calculadora totalmente funcional hospedada na Vercel com performance otimizada

## ✨ Features

### 🧮 **Funcionalidades Principais**
- ✅ **Operações básicas:** Adição, subtração, multiplicação e divisão
- ✅ **Números decimais:** Suporte completo a casas decimais
- ✅ **Operações avançadas:** Porcentagem e mudança de sinal
- ✅ **Histórico:** Visualização da operação atual
- ✅ **Validação:** Prevenção de erros matemáticos

### 🎨 **Design & UX**
- 🌙 **Tema automático:** Modo claro/escuro baseado na preferência do sistema
- 📱 **Totalmente responsivo:** Otimizado para desktop, tablet e mobile
- ✨ **Animações suaves:** Transições elegantes e feedback visual
- 🎯 **Interface intuitiva:** Design limpo e fácil de usar
- ♿ **Acessibilidade:** Suporte a leitores de tela e navegação por teclado

### 🚀 **Performance & Tecnologia**
- ⚡ **Next.js 15:** Framework React de última geração
- 🔧 **TypeScript:** Código type-safe e mais confiável
- 🎨 **Tailwind CSS:** Estilização moderna e eficiente
- 📦 **Bundle otimizado:** Carregamento rápido e eficiente
- 🌐 **SEO otimizado:** Meta tags e estrutura semântica

## 🛠️ Stack Tecnológica

### **Frontend**
- **Next.js 15** - Framework React para produção
- **React 19** - Biblioteca para interfaces de usuário
- **TypeScript** - Tipagem estática para JavaScript
- **Tailwind CSS** - Framework CSS utilitário

### **Desenvolvimento**
- **ESLint** - Linter para qualidade de código
- **Prettier** - Formatação automática de código
- **Vercel** - Deploy e hospedagem

### **Ferramentas**
- **Git** - Controle de versão
- **VS Code** - Editor recomendado
- **Node.js 18+** - Runtime JavaScript

## 🚀 Início Rápido

### Pré-requisitos
- Node.js 18+
- npm, yarn, pnpm ou bun
- Git

### Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/cauaprjct/calculator-app.git
cd calculator-app
```

2. **Instale as dependências**
```bash
npm install
# ou
yarn install
# ou
pnpm install
```

3. **Execute o servidor de desenvolvimento**
```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
```

4. **Acesse a aplicação**
```
http://localhost:3000
```

## 📱 Screenshots

<div align="center">

### Desktop - Modo Claro
<img src="screenshots/desktop-light.png" alt="Desktop Modo Claro" width="600"/>

### Mobile - Modo Escuro
<img src="screenshots/mobile-dark.png" alt="Mobile Modo Escuro" width="300"/>

</div>

## 🏗️ Estrutura do Projeto

```
calculator-app/
├── src/
│   ├── app/                  # App Router (Next.js 13+)
│   │   ├── globals.css       # Estilos globais
│   │   ├── layout.tsx        # Layout principal
│   │   └── page.tsx          # Página inicial
│   ├── components/           # Componentes React
│   │   ├── Calculator.tsx    # Componente principal
│   │   ├── Button.tsx        # Botão da calculadora
│   │   └── Display.tsx       # Display dos números
│   ├── hooks/                # Custom hooks
│   │   └── useCalculator.ts  # Lógica da calculadora
│   ├── types/                # Definições TypeScript
│   │   └── calculator.ts     # Tipos da calculadora
│   └── utils/                # Utilitários
│       └── calculator.ts     # Funções auxiliares
├── public/                   # Arquivos estáticos
├── tailwind.config.js        # Configuração Tailwind
├── tsconfig.json            # Configuração TypeScript
└── package.json             # Dependências e scripts
```

## 🎯 Funcionalidades Detalhadas

### Operações Matemáticas
- ➕ **Adição:** Soma de números com precisão decimal
- ➖ **Subtração:** Diferença entre números
- ✖️ **Multiplicação:** Produto de números
- ➗ **Divisão:** Quociente com proteção contra divisão por zero
- 📊 **Porcentagem:** Cálculos percentuais
- 🔄 **Mudança de sinal:** Alternar entre positivo/negativo

### Controles Especiais
- 🗑️ **Clear (C):** Limpa a operação atual
- ⬅️ **Backspace:** Remove o último dígito
- 🟰 **Igual (=):** Executa o cálculo
- 🔢 **Decimal (.):** Adiciona ponto decimal

## 🧪 Scripts Disponíveis

```bash
# Desenvolvimento
npm run dev          # Inicia servidor de desenvolvimento

# Build
npm run build        # Cria build de produção
npm run start        # Inicia servidor de produção

# Qualidade de código
npm run lint         # Executa ESLint
npm run lint:fix     # Corrige problemas do ESLint automaticamente

# Tipo checking
npm run type-check   # Verifica tipos TypeScript
```

## 🚀 Deploy

### Vercel (Recomendado)
1. Conecte seu repositório GitHub à Vercel
2. Configure as variáveis de ambiente (se necessário)
3. Deploy automático a cada push na branch main

### Outros Provedores
```bash
# Build para produção
npm run build

# Os arquivos estarão em .next/
```

## 🤝 Contribuindo

Contribuições são muito bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'feat: adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

### Diretrizes
- Use TypeScript para type safety
- Siga os padrões do ESLint
- Adicione testes para novas funcionalidades
- Mantenha a documentação atualizada

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🙏 Agradecimentos

- [Next.js Team](https://nextjs.org/) pelo framework incrível
- [Vercel](https://vercel.com/) pela hospedagem gratuita
- [Tailwind CSS](https://tailwindcss.com/) pelo framework CSS
- [TypeScript](https://typescriptlang.org/) pela tipagem estática

---

<div align="center">

**Desenvolvido com ❤️ por [Cauã](https://github.com/cauaprjct)**

⭐ **Se este projeto foi útil, deixe uma estrela!**

</div>