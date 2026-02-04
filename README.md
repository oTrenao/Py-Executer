# Py Executer

[🇧🇷 Português](#português) | [🇺🇸 English](#english)

---

## English

### 🚀 Advanced Control Panel for Python Developers

**Py Executer** is an advanced control panel for Python developers, built as an HTA (HTML Application). It provides a comprehensive interface for managing Python environments, compiling executables, and automating development workflows.

#### ✨ Key Features

##### 🧹 Clean Build (Temp Venv)
- Creates temporary virtual environments for isolated builds
- Ensures clean compilation without interference from global packages
- Automatically manages and cleans up temporary environments
- Guarantees reproducible builds every time

##### ⚡ Smart Scan System
- **Intelligent Dependency Detection**: Automatically scans your Python project to detect all required dependencies
- **Import Analysis**: Parses Python files to identify imported modules
- **Requirements Generation**: Automatically generates `requirements.txt` based on detected dependencies
- **Missing Package Detection**: Identifies missing packages that need to be installed

##### 🔧 Build Integration
- **Nuitka Integration**: Compile Python code to native C++ executables for maximum performance
  - Produces standalone executables
  - Optimizes code at compilation time
  - Supports various optimization levels
  - Cross-platform compilation support
  
- **PyInstaller Integration**: Create portable executables with ease
  - One-file and one-folder modes
  - Bundle dependencies automatically
  - Icon and resource management
  - Windows, macOS, and Linux support

#### 📋 Requirements
- Windows with HTA support (or compatible environment)
- Python 3.6 or higher
- Nuitka (optional, for C++ compilation)
- PyInstaller (optional, for executable packaging)

#### 🛠️ Installation
1. Clone this repository
2. Install required Python packages (if using build features):
   ```bash
   pip install nuitka pyinstaller
   ```
3. Open the HTA application

#### 📚 Documentation
Technical documentation and guides are available in the [`docs/`](./docs/) folder.

#### 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

#### 👨‍💻 Author
Created by **Sthevan Pinter Kairys** (oTrenao)

---

## Português

### 🚀 Painel de Controle Avançado para Desenvolvedores Python

**Py Executer** é um painel de controle avançado para desenvolvedores Python, criado como uma HTA (HTML Application). Fornece uma interface completa para gerenciar ambientes Python, compilar executáveis e automatizar fluxos de trabalho de desenvolvimento.

#### ✨ Funcionalidades Principais

##### 🧹 Build Limpo (Venv Temp)
- Cria ambientes virtuais temporários para builds isolados
- Garante compilação limpa sem interferência de pacotes globais
- Gerencia e limpa automaticamente ambientes temporários
- Garante builds reproduzíveis todas as vezes

##### ⚡ Sistema Smart Scan
- **Detecção Inteligente de Dependências**: Escaneia automaticamente seu projeto Python para detectar todas as dependências necessárias
- **Análise de Imports**: Analisa arquivos Python para identificar módulos importados
- **Geração de Requirements**: Gera automaticamente `requirements.txt` baseado nas dependências detectadas
- **Detecção de Pacotes Faltantes**: Identifica pacotes faltantes que precisam ser instalados

##### 🔧 Integração de Build
- **Integração com Nuitka**: Compila código Python para executáveis nativos C++ para máxima performance
  - Produz executáveis standalone
  - Otimiza código em tempo de compilação
  - Suporta vários níveis de otimização
  - Suporte a compilação multiplataforma
  
- **Integração com PyInstaller**: Cria executáveis portáteis com facilidade
  - Modos one-file e one-folder
  - Empacota dependências automaticamente
  - Gerenciamento de ícones e recursos
  - Suporte para Windows, macOS e Linux

#### 📋 Requisitos
- Windows com suporte HTA (ou ambiente compatível)
- Python 3.6 ou superior
- Nuitka (opcional, para compilação C++)
- PyInstaller (opcional, para empacotamento de executáveis)

#### 🛠️ Instalação
1. Clone este repositório
2. Instale os pacotes Python necessários (se usar recursos de build):
   ```bash
   pip install nuitka pyinstaller
   ```
3. Abra a aplicação HTA

#### 📚 Documentação
Documentação técnica e guias estão disponíveis na pasta [`docs/`](./docs/).

#### 📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

#### 👨‍💻 Autor
Criado por **Sthevan Pinter Kairys** (oTrenao)

---

### 🤝 Contributing / Contribuindo

Contributions are welcome! Feel free to open issues or submit pull requests.

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
