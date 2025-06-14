# KUB Extension pack

Common VSCode extensions for KUB Developers.

## Included Extensions

### Linting

#### [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

Javascript linting.

#### [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)

Java linting.

#### [MarkdownLint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

Markdown linting.

#### [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

Spell checking your code.

### Formatting/Syntax

#### [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

Change your default formatter to Prettier by adding this to your settings.json:

```json
"editor.defaultFormatter": "esbenp.prettier-vscode"
```

#### [Prettier Java Plugin](https://marketplace.visualstudio.com/items?itemName=RudraPatel.prettier-plugin-java-vscode&ssr=false#overview)

Specify the formatter for Java files by adding this to your settings.json:

```json
"[java]": {
  "editor.defaultFormatter": "RudraPatel.prettier-plugin-java-vscode"
}
```

Prettier plugin to format Java.

#### [Handlebars](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

Syntax highlighting and code snippets.

### Ember.js Development

#### [Ember.js](https://marketplace.visualstudio.com/items?itemName=EmberTooling.emberjs)

Autocompletion for ember components and helpers. It also has integration with `ember-template-lint`.

Add the following settings to your `settings.json`:

```json
"eslint.validate": [
  "glimmer-ts",
  "glimmer-js"
],
"[handlebars]": {
  "editor.defaultFormatter": "esbenp.prettier-vscode"
},
```

#### [Ember Module Snippets](https://marketplace.visualstudio.com/items?itemName=candidmetrics.ember-module-snippets)

Snippets to make importing Ember modules a snap in VSCode.

#### [Glint](https://marketplace.visualstudio.com/items?itemName=typed-ember.glint-vscode)

Type safety for Glimmer component templates.

Add the following settings to your `settings.json`:

```json
"[glimmer-js]": {
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.foldingStrategy": "indentation"
},
"[glimmer-ts]": {
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.foldingStrategy": "indentation"
},
```

Also, if you don't have the `prettier.documentSelectors` setting in your `settings.json`, add it. If you do, add the `**/*.gjs` and `**/*.gts` entries.

```json
"prettier.documentSelectors": [
  "**/*.js",
  "**/*.ts",
  "**/*.json",
  "**/*.html",
  "**/*.css",
  "**/*.scss",
  "**/*.md",
  "**/*.yaml",
  "**/*.yml",
  "**/*.hbs",
  "**/*.gjs",
  "**/*.gts"
],
```

### Source Control

#### [GitLens - Git Supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

Numerous features for Git. Spend some time exploring them in their docs.

### Remote Development

#### [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)

SSH servers as development environments.

#### [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

Docker Containers as full development environments.

#### [Remote - WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)

VS Code integration in WSL.

### Java

#### [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

Collection of extensions for Java development.

#### [Red Hat Extension Pack](https://marketplace.visualstudio.com/items?itemName=redhat.java)

### Node.js

#### [Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)

Shows the latest version for your dependencies in your `package.json`.

### .NET

#### [.NET Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-pack)

Collection of extensions for .NET development.

Add the following settings to your `settings.json`:

```json
"[csharp]": {
  "editor.defaultFormatter": "ms-dotnettools.csharp"
},
```

#### [.NET Core User Secrets](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.user-secrets)

Manage .NET Core user secrets in VS Code.

#### [Azure Tools for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-node-azure-pack)

Azure Tools for Visual Studio Code.

#### [SQL Server (mssql)](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)

MSSQL extension for Visual Studio Code.

**Enjoy!**
