# Summary
Template-generated .NET 8.0 MAUI project with the ability to build and run (debug) in VSCode

Refer to the files within `.vscode/` folder

## Prerequisites
It is better to follow a tutorial on how to get started with .NET MAUI than to use this file as your guide.

1. VSCode Extensions
    - [.NET MAUI VSCode Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-maui) (C# and C# Dev Kit extensions will be included upon installation)
2. .NET 8.0 SDK

## Concerns (As of 2023/12/03)
- **No Hot Reload** for debugging, though you are free to attempt implementation at your own risk (refer to the relevant links)
- **No XAML Intellisense** for VSCode
    - Though there are certain extensions available in the marketplace that provide *some* Intellisense, it does not provide the right tags used for MAUI

## Useful Links
- [.NET MAUI Vanilla Tutorial](https://dotnet.microsoft.com/en-us/learn/maui/first-app-tutorial/intro)
- [.NET MAUI VSCode Tutorial](https://learn.microsoft.com/en-us/dotnet/maui/get-started/installation?view=net-maui-8.0&tabs=visual-studio-code)
- [Non-official VSCode Launch Tutorial](https://egvijayanand.in/2021/04/04/net-maui-project-debug-with-vs-code/)
- [Hot Reload not yet ready for VSCode](https://github.com/dotnet/maui/discussions/3111)
- [Hot Reload Reddit Thread](https://www.reddit.com/r/dotnetMAUI/comments/10qgghg/hot_reload_with_vs_code_and_ios/)
    - [Experimental Comet Framework](https://github.com/dotnet/Comet) built on top of MAUI
    - [Setup-heavy Workaround](https://github.com/rdavisau/tbc)
- [XAML Intellisense not yet ready for VSCode](https://github.com/microsoft/vscode-dotnettools/issues/565)