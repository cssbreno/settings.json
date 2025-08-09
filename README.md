# Meus Arquivos de Configuração do VS Code

Bem-vindo ao meu repositório de configurações do Visual Studio Code! Este lugar centraliza as configurações que eu uso para otimizar meu ambiente de desenvolvimento, mantendo-o produtivo e visualmente agradável.

Aqui você encontrará duas versões das minhas configurações:

1.  **`myDefaultSettings.json`**: Minha configuração principal, completa e pronta para o dia a dia.
2.  **`minimalSettings.json`**: Uma versão mais limpa e minimalista, ideal para focar totalmente no código.

## ⚙️ Configurações Disponíveis

### 1. `myDefaultSettings.json` (Perfil Padrão)

Esta é a minha configuração principal e mais completa. Ela foi projetada para um ambiente de desenvolvimento rico em funcionalidades, com ferramentas visuais e integrações que agilizam o fluxo de trabalho.

**Principais Características:**
* **Tema Visual**: [United Ubuntu](https://vscode.cool/themes/United-Ubuntu/cssbreno)
* **Tema de Ícones**: [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
* **Fonte do Editor**: `JetBrains Mono`
* **Fonte do Terminal**: `JetBrainsMono Nerd Font` para suporte a ícones e glyphs.
* **Funcionalidades Ativas**:
    * Minimapa e scroll suave habilitados.
    * Formatação ao salvar (`formatOnSave`) e ao digitar (`formatOnType`).
    * Integração total com Git, ESLint, e GitHub Copilot.
    * Aninhamento de arquivos (`file-nesting`) para organizar a árvore de projetos.
    * Linhas guia (`rulers`) em 120 colunas.
    * Zoom com o scroll do mouse habilitado.

### 2. `minimalSettings.json` (Perfil Minimalista)

Este perfil foi criado para uma experiência de codificação "sem distrações". Ele remove grande parte da interface gráfica do editor, permitindo que você se concentre exclusivamente no código.

**Principais Características:**
* **Tema Visual**: `Min Dark` (um tema escuro e simples).
* **Fonte do Editor**: `'JetBrains Mono'`
* **Interface Limpa**:
    * **Sem status bar**: A barra de status inferior é oculta.
    * **Sem minimapa**: O minimapa do editor é desativado.
    * **Sem scrollbars**: As barras de rolagem vertical e horizontal são ocultadas.
    * **Sem breadcrumbs**: O caminho do arquivo no topo do editor é removido.
* **Foco Total**: Mantém as configurações essenciais de formatação e integração com o terminal, mas com o mínimo de elementos visuais.

## 🚀 Como Usar

Para usar uma dessas configurações no seu VS Code, siga os passos abaixo:

1.  Abra o Visual Studio Code.
2.  Abra a paleta de comandos com `Ctrl+Shift+P` (ou `Cmd+Shift+P` no macOS).
3.  Digite e selecione a opção **`Preferences: Open User Settings (JSON)`**.
4.  Isso abrirá o seu arquivo `settings.json` pessoal.
5.  Copie todo o conteúdo do arquivo `myDefaultSettings.json` ou `minimalSettings.json` deste repositório.
6.  Cole o conteúdo no seu arquivo `settings.json`, substituindo o que já estiver lá.
7.  Salve o arquivo. As alterações serão aplicadas imediatamente.

## 📦 Pré-requisitos e Dependências

Para que as configurações funcionem como esperado, você precisará instalar as fontes e extensões listadas abaixo.

### Fontes

Você precisa ter as seguintes fontes instaladas no seu sistema:
* [**JetBrains Mono**](https://www.jetbrains.com/lp/mono/)
* [**JetBrainsMono Nerd Font**](https://www.nerdfonts.com/font-downloads) (essencial para os ícones no terminal)

### Extensões do VS Code

Estas são as extensões que minhas configurações utilizam. Recomendo instalá-las para uma experiência completa:

* **Temas e Ícones**
    * [United Ubuntu](https://vscode.cool/themes/United-Ubuntu/cssbreno)
    * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
    * [Fluent Icons](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.fluent-icons)
* **Desenvolvimento e Produtividade**
    * [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
    * [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    * [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)
    * [Tabnine AI Autocomplete](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)
* **Suporte a Linguagens e Ferramentas**
    * [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) (para Python)
    * [XML](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml) by Josh Johnson
    * [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
    * [SQL Developer](https://marketplace.visualstudio.com/items?itemName=Oracle.sql-developer) (para Oracle DB)
    * [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
    * [Kubernetes](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)

## 📄 Licença

Sinta-se à vontade para usar, modificar e adaptar estas configurações para o seu próprio uso.