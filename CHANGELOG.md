# Change Log

All notable changes to the **.NET Core Extension Pack** will be documented in this file.

## 1.7.0 - 2022-04-12

* Add [NuGet Gallery](https://marketplace.visualstudio.com/items?itemName=patcx.vscode-nuget-gallery) extension.

## 1.6.1 - 2022-04-11

* Add [.NET Core EditorConfig Generator](https://marketplace.visualstudio.com/items?itemName=doggy8088.netcore-editorconfiggenerator) extension.
* Update README.md

## 1.5.2 - 2021-08-12

* Add `license`, `galleryBanner`, `keywords` in package.json
* Update `LICENSE`

## 1.5.1 - 2021-05-31

* Add [Peek Hidden Files](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.toggle-hidden) extension.
* Add [C# to TypeScript](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.csharp-to-typescript) extension.
* Add [Blazor Snippet Pack](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.blazor-snippet-pack) extension.
* Replace [C# Extensions](https://marketplace.visualstudio.com/items?itemName=jchannon.csharpextensions) (`jchannon`) with [C# Extensions](https://marketplace.visualstudio.com/items?itemName=kreativ-software.csharpextensions) (`JosKreativ`).
* Replace [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype) (`quicktype`) with [Paste JSON as Code (Refresh)](https://marketplace.visualstudio.com/items?itemName=doggy8088.quicktype-refresh) (`Will 保哥`).
  * It because the original [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype) extension is not updating since **9/20/2018, 11:48:28 PM**. Many of the already fixed bugs/issues are not released. That's why I published this extension with latest version from the [quicktype/quicktype-vscode](https://github.com/quicktype/quicktype-vscode) repo.
* Update `README.md`

## 1.4.0 - 2020-09-13

* Add [C# Namespace Autocompletion](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.namespace) extension
* Add [Run Terminal Command](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.terminal-commands) extension
* Add [LibMan Tools](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.libman) extension
* Add [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) extension

## 1.3.0 - 2020-09-12

* Add [.NET Core Add Reference](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.add-reference) extension
* Add [.NET Core User Secrets](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.user-secrets) extension
* Remove [Super Sharp (C# extensions)](https://marketplace.visualstudio.com/items?itemName=craigthomas.supersharp) extension
  * All of the feature in this extension can be replaced by [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) extension
* Remove [ASP.NET Helper](https://marketplace.visualstudio.com/items?itemName=schneiderpat.aspnet-helper) extension
  * All of the feature in this extension can be replaced by [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) extension

## 1.2.0 - 2020-08-22

* Add [vscode-proto3](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3) extension.

## 1.1.1 - 2020-08-03

* Update README
  * Update [Essential ASP.NET Core Snippets](https://marketplace.visualstudio.com/items?itemName=doggy8088.netcore-snippets) descriptions

## 1.1.0 - 2020-08-02

* Remove [C# FixFormat](https://marketplace.visualstudio.com/items?itemName=Leopotam.csharpfixformat) extension. The [GitHub repo](https://github.com/Leopotam/vscode-csharpfixformat) has been removed from the author and most of the features can be replaced by [C#](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp) extension nowadays.
* Update README
  * Move all recommended settings into standalone section `Recommended Settings`.

## 1.0.0 - 2020-07-29

* The [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) extension has been changed it's publisher id. So I have to update this extension pack to align with it.
* The minimal version of vscode must larger than `1.44.0`.

## 0.10.0 - 2019-12-04

* Add [ASP.NET Core Switcher](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.asp-net-core-switcher) extension.

## 0.9.0 - 2019-11-09

* Remove [C# Snippets](https://marketplace.visualstudio.com/items?itemName=jorgeserrano.vscode-csharp-snippets) extension. It's been lack of maintenance for a while. Some of the snippets are just wrong.

## 0.8.0 - 2019-02-22

* Add missing [C#](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp) extension.

## 0.7.2 - 2018-08-17

* Use `extensionPack` instead of `extensionDependencies` ( VSCode 1.26.0+ )
  * `extensionDependencies` is mainly used to define functional dependencies among extensions that prevents uninstalling or disabling an extension dependency without uninstalling or disabling the dependent extension.
* Update `READMEmd`

## 0.6.1 - 2018-07-16

* Add [.NET Core Test Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer) extension.

## 0.5.0 - 2018-06-18

* Add [Essential ASP.NET Core Snippets](https://marketplace.visualstudio.com/items?itemName=doggy8088.netcore-snippets) extension.

## 0.4.0 - 2018-06-16

* Add [C# FixFormat](https://marketplace.visualstudio.com/items?itemName=Leopotam.csharpfixformat) recommended settings.

## 0.3.0 - 2018-02-11

* Add [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) extension.

## 0.2.2 - 2018-02-06

* Change a new Icon for better recognizing!

## 0.2.0 - 2018-02-04

* Add [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) extension.
* Add [Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens) extension.

## 0.1.6 - 2018-02-03

* Add [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) extension.

## 0.1.0 - 2018-01-24

* Initial release
