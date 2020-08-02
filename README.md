# .NET Core Extension Pack

This extension pack packages some of the most popular (and some of my favorite) **.NET Core** related extensions. If you like it, please leave your `Rating & Review` and share with your friends. If you have any idea on how to improve this extension pack, I'm looking forwarded to hear from you. Just [let me know](https://github.com/doggy8088/netcore-extension-pack/issues) your awesome ideas! 😊

## Extensions Included

### C# Productivity

* [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
  * The main C# extension for Visual Studio Code powered by [OmniSharp](http://www.omnisharp.net).
* [C# Extensions](https://marketplace.visualstudio.com/items?itemName=jchannon.csharpextensions)
  * The Quick Actions is really a productivity saver.
  * Explorer
    * New C# Class
    * New C# Interface
  * Quick Actions
    * Initialize field from parameter (In Constructor Parameter)
    * Initialize property from parameter (In Constructor Parameter)
    * Initialize readonly property from parameter (In Constructor Parameter)
    * Initialize ctor from properties (In Class Body)
* [Super Sharp (C# extensions)](https://marketplace.visualstudio.com/items?itemName=craigthomas.supersharp)
  * It provides some missing refactoring features for C#.
  * Some of the highlights:
    * Add DI in the constructor automatically!
    * Move class | enum | interface | struct to new file.
* [C# XML Documentation Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment)
  * Type "///", it auto-generates an XML doucumentation comment.
* [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  * It will highlight important comments in your code.
  * `// *` hightlight information
  * `// !` hightlight important stuff
  * `// ?` hightlight some questions
  * `// TODO:` highlight TODOs
  * `// @param PARAM` highlight parameter info
* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
  * It let you copy JSON and paste as Go, TypeScript, C#, C++ and more using [quicktype](https://app.quicktype.io/#l=cs).
* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
  * This can let you list all the `// TODO:` comments in the project. Neats!

### Testing Tools

* [.NET Core Test Explorer](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer)
  * It supports [MSTest](https://en.wikipedia.org/wiki/Visual_Studio_Unit_Testing_Framework), [NUnit](http://nunit.org/), and [xUnit](https://xunit.github.io).
  * Useful keyboard shortcuts:
    * `Alt+R Alt+A` - Run all tests
    * `Alt+R Alt+R` - Re-run last command
    * `Alt+R Alt+C` - Run test(s) in context

### NuGet & Build Tools

* [NuGet Package Manager](https://marketplace.visualstudio.com/items?itemName=jmrog.vscode-nuget-package-manager)
  * It lets you easily add or remove NuGet package references to/from your project's .csproj or .fsproj files using Code's Command Palette.
* [MSBuild project tools](https://marketplace.visualstudio.com/items?itemName=tintoy.msbuild-project-tools)
  * It provides [MSBuild language service](https://github.com/tintoy/msbuild-project-tools-server/) which contains intellisense for MSBuild project files, including auto-complete for `<PackageReference>` elements.
* [.NET Core Tools](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet)
  * Right click on a .csproj, .fsproj or .sln file in the explorer, then you can run .NET Core commands (Build/Run/Test) from context menu.
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * This provide you IntelliSense when entering `<ProjectReference Inlcude="..." />` path.
* [Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)
  * Shows the latest version for each package using code lens.

### ASP.NET Core Productivity

* [ASP.NET Core Switcher](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.asp-net-core-switcher)
  * Switch between Page and it's PageModel (`alt + o`)
  * Switch between View and Controller (`alt + i`)
  * Create View for Action (`alt + p`)
* [Essential ASP.NET Core Snippets](https://marketplace.visualstudio.com/items?itemName=doggy8088.netcore-snippets)
  * High quality ASP.NET Core snippets for Visual Studio Code.
  * It contains C#, ASP.NET Core, Razor, JSON (`appsettings.json`), EF Core snippets.
  * Here are some of the most used snippets:
    * `services-add-dbcontext`: Generates `AddDbContext()` in `Startup.ConfigureService()`
    * `ac-api-controller`: Generates API Controller class
    * `ac-mvc-action`: Generates MVC Action
    * `ac-api-action`: Generates API Action
    * `ef-dbcontext`: Generates API Controller class
    * `connstr`: Generates `ConnectionStrings` section in `appsettings.json`
    * `connstr-ip`: Generates `ConnectionStrings` item in `appsettings.json`
    * `connstr-trusted`: Generates `ConnectionStrings` item in `appsettings.json`
* [ASP.NET Helper](https://marketplace.visualstudio.com/items?itemName=schneiderpat.aspnet-helper)
  * It parses your project to enable IntelliSense for Razor pages within an ASP.NET MVC project.
  * There are Tag helper IntelliSense which are very useful
    * `asp-controller="ctrlName"`
      * Triggered by `Ctrl+Space` hotkey
    * `asp-action="actionName"`
      * Triggered by `Ctrl+Space` hotkey
      * The action method must have `[HttpGet]` attribute attached.
    * `asp-route-xxxParam="value"`
      * This will be triggered after `asp-action` been entered.
  * Known issue:
    * `@model` must appear in the first line of the Razor page when you want IntelliSense for `@Model` object.

### Misc

* [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
  * It providing Language support for .gitignore files.
  * It can also add local `.gitignore` by pulling file from the the [github/gitignore](https://github.com/github/gitignore) repository.

### Some other extensions you may need (Optional)

* [NuGet Reverse Package Search ("Add Package" support)](https://marketplace.visualstudio.com/items?itemName=jesschadwick.nuget-reverse-package-search)
  * Adds reverse .NET package lookup support like the "Add Package" context menu item in full Visual Studio.
* [mssql](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)
  * If you are using Microsoft SQL Server, you might need this awesome extension.
* [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
  * It's too informative for me. I turn it off all the time.
* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Adds real-time collaborative editing and debugging into VS Code.

### Recommended Settings

* Visual Studio Code

    Disable `renderCharacters` feature in minimap can improve display performance.

    ```json
    {
      "editor.minimap.renderCharacters": false
    }
    ```

* [C#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)

    The C# extension for VS Code already supports `.editorconfig` and [CodeStyle analysis](https://docs.microsoft.com/en-us/visualstudio/code-quality/roslyn-analyzers-overview?view=vs-2019). ([#648](https://github.com/dotnet/format/issues/648#issuecomment-614905524))

    ```json
    {
      "omnisharp.enableRoslynAnalyzers": true,
      "omnisharp.enableEditorConfigSupport": true
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
