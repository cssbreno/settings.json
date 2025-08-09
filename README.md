# Meus Arquivos de Configuração do VS Code

Bem-vindo ao meu repositório de configurações do Visual Studio Code! Este lugar centraliza as configurações que eu uso para otimizar meu ambiente de desenvolvimento, mantendo-o produtivo, consistente e visualmente agradável.

Aqui você encontrará duas versões das minhas configurações:

1.  **`myDefaultSettings.json`**: Minha configuração principal, completa, com mais recursos visuais e pronta para o dia a dia.
2.  **`minimalSettings.json`**: Uma configuração focada e minimalista, com forte padronização de formatação de código.

## ⚙️ Configurações Disponíveis

### 1. `myDefaultSettings.json` (Perfil Padrão)

Esta é a minha configuração principal e mais completa. Ela foi projetada para um ambiente de desenvolvimento rico em funcionalidades, com mais auxílios visuais e integrações que agilizam o fluxo de trabalho.

**Principais Características:**
* **Tema Visual**: [United Ubuntu](https://vscode.cool/themes/United-Ubuntu/cssbreno)
* **Tema de Ícones**: [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
* **Fonte do Editor**: `JetBrains Mono`
* **Fonte do Terminal**: `JetBrainsMono Nerd Font`
* **Funcionalidades Ativas**:
    * Minimapa e scroll suave habilitados.
    * Formatação ao salvar (`formatOnSave`) e ao digitar (`formatOnType`).
    * Integração total com Git, ESLint, e GitHub Copilot.
    * Aninhamento de arquivos (`file-nesting`) para organizar a árvore de projetos.
    * Linhas guia (`rulers`) em 120 colunas.

### 2. `minimalSettings.json` (Perfil Focado / Minimalista)

Este perfil foi criado para uma experiência de codificação "sem distrações" e com formatação de código altamente padronizada. Ele oculta alguns elementos da interface e impõe regras de estilo de código de forma automática.

**Principais Características:**
* **Tema Visual**: `Origamid Next`
* **Tema de Ícones**: `Symbols` (ícones minimalistas)
* **Fonte do Editor**: `'JetBrains Mono'`
* **Interface Limpa**:
    * **Barra de Status Oculta**: A `workbench.statusBar.visible` está desativada.
    * **Scrollbars Ocultas**: As barras de rolagem (`editor.scrollbar`) são escondidas.
    * **Breadcrumbs Desativado**: O caminho do arquivo no topo do editor (`breadcrumbs.enabled`) é removido.
* **Formatação Opinativa**:
    * **Formatador Padrão**: `Prettier` é o formatador padrão para a maioria das linguagens.
    * **Formatação em Python**: Usa o `Black Formatter`.
    * **Formatação em Java**: Usa o `Google Java Formatter`.
    * **Tamanho da Tabulação**: Padrão de 2 espaços, com exceção de linguagens como Python, Java, C#, Go, entre outras, que usam 4 espaços.
* **Verificação Ortográfica**: Configurado para Português do Brasil (`pt-BR`).

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

As fontes a seguir precisam estar instaladas no seu sistema para ambos os perfis:
* [**JetBrains Mono**](https://www.jetbrains.com/lp/mono/)
* [**JetBrainsMono Nerd Font**](https://www.nerdfonts.com/font-downloads) (essencial para os ícones no terminal)

### Extensões do VS Code

#### Comuns a Ambos os Perfis
* [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
* [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
* [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

#### Específicas do `myDefaultSettings.json`
* **Temas**: [United Ubuntu](https://vscode.cool/themes/United-Ubuntu/cssbreno), [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme), [Fluent Icons](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.fluent-icons)
* **Linguagens**: [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance), [XML](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml), [SQL Developer](https://marketplace.visualstudio.com/items?itemName=Oracle.sql-developer)

#### Específicas do `minimalSettings.json`
* **Temas**: [Origamid Next](https://marketplace.visualstudio.com/items?itemName=Origamid.origamid-next-theme), [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)
* **Formatadores**:
    * [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * [Black Formatter](https://marketplace.visualstudio.com/items?itemName=ms-python.black-formatter)
    * [Formatter for Java](https://marketplace.visualstudio.com/items?itemName=mngrm3a.vscode-google-java-formatter)
    * [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
* **Utilitários**:
    * [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) (para a regra `cSpell.language`)

## 📄 Licença

Sinta-se à vontade para usar, modificar e adaptar estas configurações para o seu próprio uso.