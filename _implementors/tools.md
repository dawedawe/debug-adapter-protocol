---
layout: implementors
title:  "Tools supporting the DAP"
shortTitle: "Supporting Tools"
author: Microsoft
index: 2
---

The following table lists the known development tools (IDEs) that implement the Debug Adapter Protocol as a client.

| Development Tool              | Client ID    | Maintainer | Repository                                |
|-------------------------------|--------------|--------------------------------------------------------|
| Visual Studio Code            | vscode       | Microsoft  | [vscode](https://code.visualstudio.com)
| Visual Studio                 | visualstudio | Microsoft  |
| Visual Studio for Mac         | vsformac     | Microsoft  |
| Eclipse IDE (LSP4E connector) | lsp4e.debug  | Eclipse    | [Eclipse community](https://projects.eclipse.org/projects/technology.lsp4e/who), [Eclipse LSP4E](https://projects.eclipse.org/projects/technology.lsp4e)
{: .table .table-bordered .table-responsive}

The "client ID" is the identifier that a development tool sends to the debug adapter as part of the [**initialize**](../../specification#Requests_Initialize) request.

*If you are missing a development tool or if you want to register a client ID please create a pull request in GitHub against this markdown [document](https://github.com/Microsoft/debug-adapter-protocol/blob/gh-pages/_implementors/tools.md).*