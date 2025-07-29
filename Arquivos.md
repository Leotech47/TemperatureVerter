# 📁 Arquivos do Projeto TemperatureVerter

## 📄 README.md

```markdown
# 🌡️ TemperatureVerter

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.2.0-blue.svg)](https://reactjs.org/)
[![PWA](https://img.shields.io/badge/PWA-Ready-green.svg)](https://web.dev/progressive-web-apps/)
[![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-brightgreen.svg)](/)

**Conversor de Temperatura Ultra-Avançado com 8 escalas, conversão em tempo real e interface futurística.**

## ✨ Funcionalidades

- 🌡️ **8 Escalas Suportadas**: Celsius, Fahrenheit, Kelvin, Rankine, Delisle, Newton, Réaumur, Rømer
- ⚡ **Conversão em Tempo Real**: Resultado instantâneo enquanto digita
- 🎨 **5 Temas Personalizáveis**: Cyber, Fire, Ice, Sunset, Neon
- 📚 **Histórico Inteligente**: Salva últimas 10 conversões com favoritos
- 📱 **PWA Completo**: Instalável como app nativo
- 🔄 **Offline First**: Funciona sem internet
- 📊 **Exportação CSV**: Baixe seu histórico
- 🌐 **Responsivo**: Perfeito em mobile, tablet e desktop

## 🚀 Demo ao Vivo

[**Experimente Agora →**](https://temperatureverter.vercel.app)

![Demo](docs/images/demo.gif)

## 📱 Instalação PWA

### Android/Chrome:
1. Abra o app no Chrome
2. Toque no banner "Instalar"
3. Confirme "Adicionar à tela inicial"

### iOS/Safari:
1. Toque no botão compartilhar (⬆️)
2. Selecione "Adicionar à Tela Inicial"
3. Confirme "Adicionar"

## 🛠️ Tecnologias

- **Frontend**: React 18.2, Hooks, Context API
- **Styling**: Tailwind CSS 3.3, CSS Grid, Flexbox
- **Icons**: Lucide React
- **PWA**: Service Worker, Web App Manifest
- **Build**: Create React App, Webpack
- **Deploy**: Vercel, Netlify ready

## 🏃‍♂️ Início Rápido

### Pré-requisitos
- Node.js 18+
- npm ou yarn

### Instalação
```bash
# Clone o repositório
git clone https://github.com/seuusuario/TemperatureVerter.git

# Entre no diretório
cd TemperatureVerter

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm start
```

### Build para Produção
```bash
# Gere build otimizado
npm run build

# Teste localmente
npm install -g serve
serve -s build
```

## 📊 Escalas Suportadas

| Escala | Símbolo | Fórmula para Celsius |
|--------|---------|---------------------|
| Celsius | °C | C |
| Fahrenheit | °F | (F-32)×5/9 |
| Kelvin | K | K-273.15 |
| Rankine | °R | (R-491.67)×5/9 |
| Delisle | °De | 100-De×2/3 |
| Newton | °N | N×100/33 |
| Réaumur | °Ré | Ré×5/4 |
| Rømer | °Rø | (Rø-7.5)×40/21 |

## 🎨 Temas Disponíveis

- 🟢 **Cyber**: Verde neon futurístico
- 🔴 **Fire**: Vermelho ardente
- 🔵 **Ice**: Azul gelado
- 🟠 **Sunset**: Laranja por do sol
- 🟣 **Neon**: Roxo vibrante

## 📁 Estrutura do Projeto

```
src/
├── components/          # Componentes React
├── hooks/              # Custom Hooks
├── utils/              # Utilitários e conversões
├── styles/             # Estilos CSS
└── assets/             # Imagens e fontes
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Veja [CONTRIBUTING.md](docs/CONTRIBUTING.md) para detalhes.

### Como Contribuir:
1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Add: MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📝 Changelog

Veja [CHANGELOG.md](docs/CHANGELOG.md) para histórico de versões.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autor

**Seu Nome**
- GitHub: [@seuusuario](https://github.com/seuusuario)
- LinkedIn: [Seu LinkedIn](https://linkedin.com/in/seuusuario)
- Email: seu.email@exemplo.com

## 🙏 Agradecimentos

- [React](https://reactjs.org/) - Framework utilizado
- [Tailwind CSS](https://tailwindcss.com/) - Estilização
- [Lucide](https://lucide.dev/) - Ícones
- [Vercel](https://vercel.com/) - Hospedagem

## 📊 Estatísticas

![GitHub Stars](https://img.shields.io/github/stars/seuusuario/TemperatureVerter?style=social)
![GitHub Forks](https://img.shields.io/github/forks/seuusuario/TemperatureVerter?style=social)
![GitHub Issues](https://img.shields.io/github/issues/seuusuario/TemperatureVerter)
![GitHub Last Commit](https://img.shields.io/github/last-commit/seuusuario/TemperatureVerter)

---

⭐ **Se este projeto te ajudou, deixe uma estrela!** ⭐
```

## 📄 package.json

```json
{
  "name": "temperature-verter",
  "version": "1.0.0",
  "description": "Conversor de Temperatura Ultra-Avançado com 8 escalas, conversão em tempo real e interface futurística",
  "keywords": [
    "temperature",
    "converter",
    "celsius",
    "fahrenheit",
    "kelvin",
    "pwa",
    "react",
    "responsive"
  ],
  "author": {
    "name": "Seu Nome",
    "email": "seu.email@exemplo.com",
    "url": "https://github.com/seuusuario"
  },
  "license": "MIT",
  "repository": {
    "type": "git",
    "url": "https://github.com/seuusuario/TemperatureVerter.git"
  },
  "homepage": "https://temperatureverter.vercel.app",
  "bugs": {
    "url": "https://github.com/seuusuario/TemperatureVerter/issues"
  },
  "private": false,
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1",
    "lucide-react": "^0.263.1",
    "web-vitals": "^3.3.2"
  },
  "devDependencies": {
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "tailwindcss": "^3.3.0",
    "autoprefixer": "^10.4.14",
    "postcss": "^8.4.24"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject",
    "lint": "eslint src/",
    "lint:fix": "eslint src/ --fix",
    "deploy": "npm run build && npx serve -s build",
    "analyze": "npm run build && npx webpack-bundle-analyzer build/static/js/*.js"
  },
  "eslintConfig": {
    "extends": [
      "react-app",
      "react-app/jest"
    ]
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  }
}
```

## 📄 manifest.json

```json
{
  "short_name": "TemperatureVerter",
  "name": "TemperatureVerter - Conversor de Temperatura",
  "description": "Conversor de temperatura com 8 escalas e conversão em tempo real",
  "icons": [
    {
      "src": "icons/icon-72x72.png",
      "sizes": "72x72",
      "type": "image/png",
      "purpose": "any"
    },
    {
      "src": "icons/icon-96x96.png",
      "sizes": "96x96",
      "type": "image/png",
      "purpose": "any"
    },
    {
      "src": "icons/icon-128x128.png",
      "sizes": "128x128",
      "type": "image/png",
      "purpose": "any"
    },
    {
      "src": "icons/icon-144x144.png",
      "sizes": "144x144",
      "type": "image/png",
      "purpose": "any"
    },
    {
      "src": "icons/icon-152x152.png",
      "sizes": "152x152",
      "type": "image/png",
      "purpose": "any"
    },
    {
      "src": "icons/icon-192x192.png",
      "sizes": "192x192",
      "type": "image/png",
      "purpose": "any maskable"
    },
    {
      "src": "icons/icon-384x384.png",
      "sizes": "384x384",
      "type": "image/png",
      "purpose": "any"
    },
    {
      "src": "icons/icon-512x512.png",
      "sizes": "512x512",
      "type": "image/png",
      "purpose": "any maskable"
    }
  ],
  "start_url": ".",
  "display": "standalone",
  "theme_color": "#22c55e",
  "background_color": "#000000",
  "orientation": "portrait-primary",
  "scope": "/",
  "lang": "pt-BR",
  "categories": ["utilities", "productivity", "education"],
  "screenshots": [
    {
      "src": "screenshots/desktop-screenshot.png",
      "sizes": "1280x720",
      "type": "image/png",
      "form_factor": "wide"
    },
    {
      "src": "screenshots/mobile-screenshot.png",
      "sizes": "375x812",
      "type": "image/png",
      "form_factor": "narrow"
    }
  ]
}
```

## 📄 .gitignore

```gitignore
# Dependencies
/node_modules
/.pnp
.pnp.js

# Testing
/coverage

# Production build
/build

# Environment variables
.env
.env.local
.env.development.local
.env.test.local
.env.production.local

# IDE
.vscode/
.idea/
*.swp
*.swo

# OS
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db

# Logs
npm-debug.log*
yarn-debug.log*
yarn-error.log*
lerna-debug.log*

# Runtime data
pids
*.pid
*.seed
*.pid.lock

# Optional npm cache directory
.npm

# Optional eslint cache
.eslintcache

# Output of 'npm pack'
*.tgz

# Yarn Integrity file
.yarn-integrity

# dotenv environment variables file
.env

# parcel-bundler cache (https://parceljs.org/)
.cache
.parcel-cache

# next.js build output
.next

# nuxt.js build output
.nuxt

# vuepress build output
.vuepress/dist

# Serverless directories
.serverless/

# FuseBox cache
.fusebox/

# DynamoDB Local files
.dynamodb/

# TernJS port file
.tern-port

# Stores VSCode versions used for testing VSCode extensions
.vscode-test
```

## 📄 LICENSE

```
MIT License

Copyright (c) 2024 Seu Nome

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 📄 .env.example

```env
# API Configuration
REACT_APP_API_URL=https://api.anthropic.com/v1/messages
REACT_APP_API_KEY=your_api_key_here

# PWA Configuration
REACT_APP_PWA_NAME=TemperatureVerter
REACT_APP_PWA_SHORT_NAME=TempVerter
REACT_APP_PWA_THEME_COLOR=#22c55e

# Analytics (opcional)
REACT_APP_GA_TRACKING_ID=your_ga_id_here

# Environment
REACT_APP_ENV=production
REACT_APP_VERSION=1.0.0
```

## 📄 tailwind.config.js

```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {
      colors: {
        // Cores personalizadas dos temas
        cyber: {
          50: '#f0fdf4',
          500: '#22c55e',
          900: '#14532d',
        },
        fire: {
          50: '#fef2f2',
          500: '#ef4444',
          900: '#7f1d1d',
        },
        ice: {
          50: '#eff6ff',
          500: '#3b82f6',
          900: '#1e3a8a',
        },
        sunset: {
          50: '#fff7ed',
          500: '#f97316',
          900: '#9a3412',
        },
        neon: {
          50: '#faf5ff',
          500: '#a855f7',
          900: '#581c87',
        }
      },
      fontFamily: {
        'mono': ['JetBrains Mono', 'monospace'],
      },
      animation: {
        'pulse-slow': 'pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite',
        'bounce-slow': 'bounce 2s infinite',
      }
    },
  },
  plugins: [],
  safelist: [
    // Garantir que classes dinâmicas não sejam removidas
    'text-green-400',
    'text-red-400',
    'text-blue-400',
    'text-orange-400',
    'text-purple-400',
    'border-green-500',
    'border-red-500',
    'border-blue-500',
    'border-orange-500',
    'border-purple-500',
    'bg-green-600',
    'bg-red-600',
    'bg-blue-600',
    'bg-orange-600',
    'bg-purple-600',
  ]
}
```

## 📄 GitHub Workflow (.github/workflows/ci.yml)

```yaml
name: CI/CD Pipeline

on:
  push:
    branches: [ main, develop ]
  pull_request:
    branches: [ main ]

jobs:
  test:
    runs-on: ubuntu-latest
    
    strategy:
      matrix:
        node-version: [16.x, 18.x]
    
    steps:
    - name: Checkout code
      uses: actions/checkout@v3
    
    - name: Setup Node.js ${{ matrix.node-version }}
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}
        cache: 'npm'
    
    - name: Install dependencies
      run: npm ci
    
    - name: Run tests
      run: npm test -- --coverage --watchAll=false
    
    - name: Run linter
      run: npm run lint
    
    - name: Build application
      run: npm run build
    
    - name: Upload coverage to Codecov
      uses: codecov/codecov-action@v3
      with:
        file: ./coverage/lcov.info

  deploy:
    needs: test
    runs-on: ubuntu-latest
    if: github.ref == 'refs/heads/main'
    
    steps:
    - name: Checkout code
      uses: actions/checkout@v3
    
    - name: Setup Node.js
      uses: actions/setup-node@v3
      with:
        node-version: '18'
        cache: 'npm'
    
    - name: Install dependencies
      run: npm ci
    
    - name: Build application
      run: npm run build
    
    - name: Deploy to Vercel
      uses: amondnet/vercel-action@v20
      with:
        vercel-token: ${{ secrets.VERCEL_TOKEN }}
        vercel-org-id: ${{ secrets.ORG_ID }}
        vercel-project-id: ${{ secrets.PROJECT_ID }}
        vercel-args: '--prod'
```
