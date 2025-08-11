# 🚀 Deploy Helper - Vite/React (Lovable)

> **Ferramenta profissional para automação de build e empacotamento de projetos Vite/React**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![PyQt5](https://img.shields.io/badge/PyQt5-5.15+-green.svg)](https://www.riverbankcomputing.com/software/pyqt/)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows)

## 📖 Sobre

**Deploy Helper** é uma ferramenta desktop desenvolvida em Python com PyQt5 que automatiza todo o processo de build e empacotamento de projetos Vite/React. Ideal para desenvolvedores que precisam de uma solução profissional e fácil de usar para deploy de aplicações web.

## ✨ Características Principais

- 🏗️ **Build Automatizado** - Suporte completo para Vite/React
- 📦 **Empacotamento Inteligente** - Gera executáveis standalone
- 🌐 **Preview Local** - Visualização em tempo real dos builds
- 💰 **Sistema de Doações** - Integrado com página personalizada
- 🔧 **Interface Intuitiva** - Design moderno estilo Steam
- 📁 **Gerenciamento de Projetos** - Arraste e solte para seleção
- 🚀 **Deploy FTP** - Upload automático para servidores
- 📝 **Editor de Código** - Editor integrado com syntax highlighting

## 🎯 Funcionalidades

### 🔨 Automação de Build
- Detecção automática de projetos Vite/React
- Suporte para `npm ci` e `npm install`
- Ajuste automático de base paths
- Geração de arquivos `.htaccess` para SPA

### 📦 Empacotamento
- Inclusão automática de dependências
- Ícones personalizados
- Arquivos estáticos empacotados

### 🌐 Preview e Deploy
- Servidor local para visualização
- Upload FTP integrado
- Gerenciamento de presets de servidor
- Logs detalhados de todas as operações

## 🚀 Instalação

### Pré-requisitos
- **Python 3.8+**
- **Windows 10/11**
- **Node.js** (para projetos Vite/React)


### 📦 Executável Standalone

Para usuários finais, baixe o executável pré-compilado:
- [DeployHelper.exe](https://github.com/seu-usuario/deploy-helper/releases)

## 📖 Como Usar

### 1. Seleção de Projeto
- **Arraste e solte** a pasta do projeto na interface
- Ou clique em **"Selecionar pasta"** para navegar

### 2. Configuração
- **Ajuste base do Vite** se necessário
- **Selecione ícone** personalizado (opcional)
- **Configure opções** de build

### 3. Build e Empacotamento
- Clique em **"Gerar Build e Zipar"**
- Aguarde a conclusão do processo
- Visualize o resultado com **"Visualizar no navegador"**

### 4. Deploy (Opcional)
- Use **"Exportar via FTP"** para upload
- Configure presets de servidor para reutilização

## 🛠️ Tecnologias Utilizadas

- **Backend**: Python 3.8+
- **Interface**: PyQt5
- **Empacotamento**: PyInstaller
- **Tema**: QDarkTheme
- **Build Tools**: Vite, npm, Node.js

## 📁 Estrutura do Projeto

```
deploy-helper/
├── app.py                      # Aplicação principal
├── requirements.txt            # Dependências Python
├── dev/                       # Pasta de desenvolvimento
│   ├── index.html            # Página de doações
│   ├── assets/               # Recursos estáticos
│   └── doc.html             # Documentação local
├── icon.ico                  # Ícone da aplicação
├── LICENSE.txt               # Licença MIT
└── LICENSE_INNO.txt          # Licença para Inno Setup
```

## 🔧 Desenvolvimento


### Estrutura de Build
O script gera:
- **Executável**: `dist/DeployHelper.exe`
- **Arquivos estáticos**: Incluídos automaticamente
- **Dependências**: Empacotadas com PyInstaller

### Personalização
- **Ícones**: Substitua `icon.ico`
- **Tema**: Modifique `build_steam_stylesheet()`
- **Funcionalidades**: Estenda as classes principais

## 📋 Requisitos do Sistema

- **Sistema Operacional**: Windows 10/11 (64-bit)
- **Python**: 3.8 ou superior
- **Memória RAM**: 4GB mínimo (8GB recomendado)
- **Espaço em Disco**: 500MB para instalação
- **Node.js**: 16.x ou superior (para projetos Vite)


## 🙏 Agradecimentos

- **Vite** - Build tool moderno
- **React** - Framework JavaScript
- **PyQt5** - Framework GUI Python
- **PyInstaller** - Empacotamento Python
- **Comunidade open source** - Suporte e contribuições

## 📞 Contato

- **Desenvolvedor**: Alexandre Henrique
- **Software**: Deploy Helper - Vite/React (Lovable)
- **Versão**: 1.0.0

Para suporte técnico, licenciamento comercial ou outras consultas, entre em contato.

---

⭐ **Se este projeto te ajudou, considere dar uma estrela no GitHub!**
