[![twblazor: Tailwind CSS components for Blazor](https://raw.githubusercontent.com/twblazor/twblazor/main/images/readme-banner.png)](https://twblazor.com/)

twblazor is an open source Tailwind CSS component library for Blazor Server and WebAssembly. Every style is a plain Tailwind class in one typed theme file, so changing the look means editing that file instead of overriding built-in CSS.

## Repositories

### [twblazor](https://github.com/twblazor/twblazor)

The component library, published on NuGet as `twblazor`. It has over 100 components, from buttons and form inputs to data tables, dialogs, charts and chat. Components come with ARIA attributes and keyboard navigation, and their built-in text is translated into 24 languages, with right to left support.

```bash
dotnet add package twblazor
```

### [twblazor.templates](https://github.com/twblazor/twblazor.templates)

A .NET tool that creates a Blazor Web App already set up with twblazor and Tailwind. You choose a dashboard, sidebar, navbar or blank layout, and Server, WebAssembly or Auto interactivity.

```bash
dotnet tool install -g twblazor.templates
twblazor new MyApp
```

## About the repositories

- Both repositories are MIT licensed and free for personal and commercial projects.
- They target .NET 10 and Tailwind CSS v4.
- Each component has a page on [twblazor.com](https://twblazor.com/) with live examples and the code to copy.
- twblazor publishes four skills for Claude Code and other AI coding agents, covering setup, theming, components and localization, so an agent writes markup with the real parameters.
- Every twblazor pull request runs the unit tests, and an axe-core accessibility scan runs on each merge into develop and main.
- Issues, ideas and pull requests are welcome in either repository.

[![twblazor on NuGet](https://img.shields.io/nuget/v/twblazor?label=twblazor&color=9810fa)](https://www.nuget.org/packages/twblazor)
[![twblazor downloads](https://img.shields.io/nuget/dt/twblazor?label=downloads&color=9810fa)](https://www.nuget.org/packages/twblazor)
[![twblazor.templates on NuGet](https://img.shields.io/nuget/v/twblazor.templates?label=twblazor.templates&color=ec4899)](https://www.nuget.org/packages/twblazor.templates)
[![twblazor stars](https://img.shields.io/github/stars/twblazor/twblazor?style=flat&label=stars&color=9810fa)](https://github.com/twblazor/twblazor/stargazers)

[Docs](https://twblazor.com/) · [Get started](https://twblazor.com/get-started) · [API reference](https://twblazor.github.io/twblazor/) · [Discussions](https://github.com/twblazor/twblazor/discussions) · [Support development](https://buymeacoffee.com/twblazor)
