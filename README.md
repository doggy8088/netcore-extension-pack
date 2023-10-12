# .NET Core Extension Pack

This extension pack packages some of the most popular (and some of my favorite) **.NET Core** related extensions. If you like it, please leave your `Rating & Review` and share with your friends. If you have any idea on how to improve this extension pack, I'm looking forwarded to hear from you. Just [let me know](https://github.com/doggy8088/netcore-extension-pack/issues) your awesome ideas! 😊

## Extensions Included

### C# Productivity

* [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
  * It provides rich language support for C# and is shipped along with [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit). Powered by a [Language Server Protocol](https://microsoft.github.io/language-server-protocol/) (LSP) server, this extension integrates with open source components like [Roslyn](https://github.com/dotnet/roslyn) and [Razor](https://github.com/dotnet/razor) to provide rich type information and a faster, more reliable C# experience.
* [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)
  * C# Dev Kit helps you manage your code with a solution explorer and test your code with integrated unit test discovery and execution, elevating your C# development experience wherever you like to develop (Windows, macOS, Linux, and even in a Codespace).
* [C# Namespace Autocompletion](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.namespace)
  * Use the `namespace-fill` snippet to insert full namespace autocompletion for C#
* [C# Extensions](https://marketplace.visualstudio.com/items?itemName=kreativ-software.csharpextensions)
  * The Quick Actions is really a productivity saver.
  * Explorer
    * New C# Class
    * New C# Interface
    * New C# Enum
    * New C# Controller
    * New C# Api Controller
    * New C# Razor Page
* [C# XML Documentation Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment)
  * Type "///", it auto-generates an XML doucumentation comment.
* [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  * It will highlight important comments in your code.
  * `// *` hightlight information
  * `// !` hightlight important stuff
  * `// ?` hightlight some questions
  * `// TODO:` highlight TODOs
  * `// @param PARAM` highlight parameter info
* [Paste JSON as Code (Refresh)](https://marketplace.visualstudio.com/items?itemName=doggy8088.quicktype-refresh)
  * `quicktype` infers types from sample JSON data, then outputs strongly typed models and serializers for working with that data in your desired programming language. For more explanation, read [A first look at quicktype](http://blog.quicktype.io/first-look/).
  * It supports `C#`, `Go`, `C++`, `Java`, `TypeScript`, `Swift`, `Elm`, and `JSON Schema`.  I have to say THIS IS AWESOME! Just try it.
* [C# to TypeScript](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.csharp-to-typescript)
  * Convert C# Models, ViewModels and DTOs into their TypeScript equivalents.
  * Useful keyboard shortcuts:
    * `Alt + /` - Run **C# to TypeScript (To Clipboard)** command
    * `Alt + .` - Run **C# to TypeScript (Paste As)** command
* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
  * This can let you list all the `// TODO:` comments in the project. Neats!

### Testing Tools

* [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
  * REST Client allows you to send HTTP request and view the response in Visual Studio Code directly.
* [.NET Core Test Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer)
  * It supports [MSTest](https://en.wikipedia.org/wiki/Visual_Studio_Unit_Testing_Framework), [NUnit](http://nunit.org/), and [xUnit](https://xunit.github.io).
  * Useful keyboard shortcuts:
    * `Alt+R Alt+A` - Run all tests
    * `Alt+R Alt+R` - Re-run last command
    * `Alt+R Alt+C` - Run test(s) in context

### NuGet & Build Tools

* [NuGet Package Manager](https://marketplace.visualstudio.com/items?itemName=jmrog.vscode-nuget-package-manager)
  * It lets you easily add or remove NuGet package references to/from your project's `.csproj` or `.fsproj` files using Code's Command Palette.
* [MSBuild project tools](https://marketplace.visualstudio.com/items?itemName=tintoy.msbuild-project-tools)
  * It provides [MSBuild language service](https://github.com/tintoy/msbuild-project-tools-server/) which contains intellisense for MSBuild project files, including auto-complete for `<PackageReference>` elements.
* [.NET Core Tools](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet)
  * Right click on a `.csproj`, `.fsproj` or `.sln` file in the explorer, then you can run .NET Core commands (Build/Run/Test) from context menu.
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * This provide you IntelliSense when entering `<ProjectReference Inlcude="..." />` path.
* [Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)
  * Shows the latest version for each package using code lens.

### .NET Core Productivity

* [NuGet Gallery](https://marketplace.visualstudio.com/items?itemName=patcx.vscode-nuget-gallery)
  * It makes installing and uninstalling NuGet packages much easier just like Vsual Studio!
  * Use `F1` > `NuGet: Open NuGet Gallery` command to open NuGet Gallery window.
* [.NET Core User Secrets](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.user-secrets)
  * Extension mimicking Visual Studio's "**Manage User Secrets**" functionality.
  * Right-click on a `.csproj` file in the Explorer and select "**Manage User Secrets**" from the context menu to insert auto-generated `UserSecretsId` element and/or open associated `secrets.json` file.
* [.NET Core Add Reference](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.add-reference)
  * Add or remove project references for your .NET Core projects.
  * Right-click on a `.csproj` file in the Explorer and select "**Add Reference**" from the context menu.
  * You can **Add** or **Remove** project references by using the same "**Add Reference**" from the context menu.
* [vscode-proto3](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3)
  * Protobuf 3 support for Visual Studio Code
* [Run Terminal Command](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.terminal-commands)
  * Run predefined terminal commands from Explorer context menu or Command Palette.

### ASP.NET Core Productivity

* [Essential ASP.NET Core Snippets](https://marketplace.visualstudio.com/items?itemName=doggy8088.netcore-snippets)
  * High quality ASP.NET Core snippets for Visual Studio Code.
  * It contains C#, ASP.NET Core, Razor, JSON (`appsettings.json`), EF Core, SignalR, gRPC snippets.
  * Most of the snippets are context-aware. The snippet suggestion only show up when filename pattern match.
  * Here are some of the most used snippets:
    * `**/Startup*.cs`
      * `services-add-dbcontext`: Generates `AddDbContext()` in `Startup.ConfigureService()`
    * `**/*Controller.cs`
      * `api-controller`: Generates API Controller class
      * `mvc-action`: Generates MVC Action
      * `api-action`: Generates API Action
    * `**/*Context.cs` or `**/*Entities.cs`
      * `ef-dbcontext`: Generates API Controller class
    * `**/appsettings*.json`
      * `connstr`: Generates `ConnectionStrings` section in `appsettings.json`
      * `connstr-ip`: Generates `ConnectionStrings` item in `appsettings.json`
      * `connstr-trusted`: Generates `ConnectionStrings` item in `appsettings.json`
* [ASP.NET Core Switcher](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.asp-net-core-switcher)
  * Switch between **Page** and it's **PageModel** (`alt + o`)
  * Switch between **View** and **Controller** (`alt + i`)
  * Create **View** for Action (`alt + p`)
* [LibMan Tools](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.libman)
  * Basic [LibMan](https://docs.microsoft.com/en-us/aspnet/core/client-side/libman/libman-cli?view=aspnetcore-3.1&WT.mc_id=DT-MVP-4015686) support for VSCode
* [Blazor Snippet Pack](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.blazor-snippet-pack)
  * A snippet pack for Blazor.

### Misc

* [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
  * It providing Language support for `.gitignore` files.
  * It can also add local `.gitignore` by pulling file from the the [github/gitignore](https://github.com/github/gitignore) repository.
* [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
  * EditorConfig Support for Visual Studio Code
* [.NET Core EditorConfig Generator](https://marketplace.visualstudio.com/items?itemName=doggy8088.netcore-editorconfiggenerator)
  * The **Generate .editorconfig for C# project** command can generate a Roslyn-inspired `.editorconfig` file just for any C# projects.
* [Peek Hidden Files](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.toggle-hidden)
  * Toggle visibility of excluded files. You can easily toggle hidden `bin` and `obj` folders in your project.

### Some other extensions you may need (Optional)

* [Git Extension Pack](https://marketplace.visualstudio.com/items?itemName=doggy8088.git-extension-pack)
  * This extension offer your a set of popular Git-related extensions.
* [NuGet Reverse Package Search ("Add Package" support)](https://marketplace.visualstudio.com/items?itemName=jesschadwick.nuget-reverse-package-search)
  * Adds reverse .NET package lookup support like the "Add Package" context menu item in full Visual Studio.
* [SQL Server (mssql)](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)
  * If you are using Microsoft SQL Server, you might need this awesome extension.
* [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Adds real-time collaborative editing and debugging into VS Code.
* [.NET Install Tool for Extension Authors](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-runtime)
  * Allows acquisition of the **.NET runtime** specifically for VSCode extension authors.
* [.NET Core Snippet Pack](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.asp-net-core-snippet-pack)
  * A pack of around 120 snippets for .NET Core.

### Recommended Settings

* Visual Studio Code

    Disable `renderCharacters` feature in minimap can improve display performance.

    ```json
    {
      "editor.minimap.renderCharacters": false
    }
    ```

* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

    Add `**/*.cs` into `todohighlight.include` setting.

    ```json
    {
      "todohighlight.include": [
        "**/*.js",
        "**/*.jsx",
        "**/*.ts",
        "**/*.tsx",
        "**/*.html",
        "**/*.php",
        "**/*.css",
        "**/*.scss",
        "**/*.cs"
      ]
    }
    ```

* [MSBuild project tools](https://marketplace.visualstudio.com/items?itemName=tintoy.msbuild-project-tools)

    If you'd like to configure all the `*.csproj` file that associate with `MSBuild` language mode. You can use the following user settings in your VSCode.

    ```json
    "files.associations": {
      "*.csproj": "msbuild"
    }
    ```

**Enjoy!**
