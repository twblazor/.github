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

## About

- The name is written in lowercase: twblazor.
- MIT licensed and free for personal and commercial projects.
- Built on .NET 10 and Tailwind CSS v4.
- The brand purple is `#9810fa`, Tailwind's purple-600.

[Docs](https://twblazor.com/) · [Get started](https://twblazor.com/get-started) · [API reference](https://twblazor.github.io/twblazor/) · [Discussions](https://github.com/twblazor/twblazor/discussions) · [Support development](https://buymeacoffee.com/twblazor)
