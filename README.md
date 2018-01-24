# .NET Core Extension Pack

This extension pack packages some of the most popular (and some of my favorite) **.NET Core** related extensions.  If you like it, please leave your `Rating & Review` and share with your friends.  If you have any idea on how to improve this extension pack, I'm looking forwarded to hear from you.  Just [let me know](https://github.com/doggy8088/netcore-extension-pack/issues) your awesome ideas! 😊

## Extensions Included

### C# Productivity

- [C#](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)
    - The C# extension for Visual Studio Code is a MUST.
- [C# Snippets](https://marketplace.visualstudio.com/items?itemName=jorgeserrano.vscode-csharp-snippets)
    - In addition to C# [built-in snippets](https://msdn.microsoft.com/en-us/library/z41h7fat.aspx), there are some code snippets still very useful.
    - C# Built-in Snippets
        - #if, #region
        - class, enum, interface, namespace, exception, 
        - ctor, indexer, iterator, prop, propfull, propg
        - if, else, for, forrr, do, while, lock, using, switch
        - try, tryf
        - cw
    - Class Snippets
        - classd, classa
    - Method Snippets
        - pum, pvm
    - Property Snippets
        - propi
    - Guid Snippets
        - guid, guidn
    - Console Snippets
        - cr, cgo
    - LINQ Snippets
        - linq_distinct, linq_where
    - Design Pattern Snippets
        - singleton, singletonl, singletonts
        - immutable
- [C# Extensions](https://marketplace.visualstudio.com/items?itemName=jchannon.csharpextensions)
    - The Quick Actions is really a productivity saver.
    - Explorer
        - New C# Class
        - New C# Interface
    - Quick Actions
        - Initialize field from parameter (In Constructor Parameter)
        - Initialize property from parameter (In Constructor Parameter)
        - Initialize readonly property from parameter (In Constructor Parameter)
        - Initialize ctor from properties (In Class Body)
- [C# FixFormat](https://marketplace.visualstudio.com/items?itemName=Leopotam.csharpfixformat)
    - This replace [C#](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp) built-in C# formatter.
    - Some of the highlights:
        - Sort usings in alphabetical order. Doubles will be removed automatically.
        - Fix indent size for all lines (omnisharp still cant do it for wrapped lines).
        - Cleanup empty lines with allowed limit in row.
        - It provides **batch mode** that you can batch formatting all your C# files in a folder.  You can launch this feature when right-click on a folder in EXPLORER pane.
- [Super Sharp (C# extensions)](https://marketplace.visualstudio.com/items?itemName=craigthomas.supersharp)
    - It provides some missing refactoring features for C#.
    - Some of the highlights:
        - Add DI in the constructor automatically!
        - Move class | enum | interface | struct to new file!!
- [C# XML Documentation Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment)
    - Type "///", it auto-generates an XML doucumentation comment.
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
    - It will highlight important comments in your code.
    - `// *` hightlight information
    - `// !` hightlight important stuff
    - `// ?` hightlight some questions
    - `// TODO:` highlight TODOs
    - `// @param PARAM` highlight parameter info
- [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
    - It let you copy JSON and paste as Go, TypeScript, C#, C++ and more using [quicktype](https://app.quicktype.io/#l=cs).

### NuGet & Build Tools

- [NuGet Package Manager](https://marketplace.visualstudio.com/items?itemName=jmrog.vscode-nuget-package-manager)
    - It lets you easily add or remove NuGet package references to/from your project's .csproj or .fsproj files using Code's Command Palette.
- [MSBuild project tools](https://marketplace.visualstudio.com/items?itemName=tintoy.msbuild-project-tools)
    - It provides [MSBuild language service](https://github.com/tintoy/msbuild-project-tools-server/) which contains intellisense for MSBuild project files, including auto-complete for <PackageReference> elements.
- [.NET Core Tools](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet)
    - Right click on a .csproj, .fsproj or .sln file in the explorer, then you can run .NET Core commands (Build/Run/Test) from context menu.

### ASP.NET Core

- [ASP.NET Core Snippets](https://marketplace.visualstudio.com/items?itemName=rahulsahay.csharp-aspnetcore)
    - A collection of ASP.NET Core snippets for Visual Studio Code.
    - Here are my most frequently used snippets:
        - `mvc-core-action`, `mvc-core-async-action`
        - `mvc-core-get`, `mvc-core-get-async`
        - `mvc-core-post`, `mvc-core-post-async`
        - `mvc-core-put`, `mvc-core-put-async`
        - `mvc-core-delete`, `mvc-core-delete-async`
- [ASP.NET Helper](https://marketplace.visualstudio.com/items?itemName=schneiderpat.aspnet-helper)
    - It parses your project to enable IntelliSense for Razor pages within an ASP.NET MVC project.
    - Known issues:
        - `@model` must appear in the first line of the Razor page when you want IntelliSense for @Model object.

### Some other extensions you may need (Optional) (You need to install the following extensions manually.)

- [mssql](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)
    - If you are using Microsoft SQL Server, you might need this awesome extension.
- [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    - It's too informative for me.  I turn it off all the time.

### Other manual setup (Optional)

- Recommended Settings
    - `"editor.minimap.renderCharacters": false`
        - Enhanced minimap performance by disabling render characters in minimap.

**Enjoy!**