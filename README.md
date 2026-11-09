# Reginald Alfret V — Portfolio (.NET 8 Blazor WASM)

> **C# & WebAssembly Standalone Implementation** of Reginald Alfret's Liquid-Glass Obsidian Resume Portfolio.

Explore the live unified multi-stack portfolio at [reginaldalfret.tech](https://reginaldalfret.tech) or the direct Blazor WASM build at [reginaldalfret.tech/stacks/blazor](https://reginaldalfret.tech/stacks/blazor).

---

## ⚡ Architecture & Tech Stack

- **Framework**: [.NET 8 Blazor WebAssembly Standalone](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor) (C# running client-side in WebAssembly)
- **Styling**: Tailwind CSS + Obsidian Glassmorphic Palette (`#512BD4` Blazor Purple branding)
- **Features**:
  - 30 Merged Open-Source PRs across Apple, Google, Microsoft, Meta, AWS, NVIDIA, NASA, Netflix, Linux Foundation & Apache
  - Professional Experience, Hackathon Victories, Research, and Certified Credentials
  - Interactive PDF Modal / Original Resume Viewer
  - Seamless Multi-Stack Cross-Navigation Dock & Switcher
  - Synchronous `is-embedded` iframe detection preventing duplicate navigation UI

---

## 🚀 Running Locally

```bash
# Ensure .NET 8 SDK is installed
dotnet --version

# Clone and run
git clone https://github.com/reginaldalfret/portfolio-blazor.git
cd portfolio-blazor

# Run the dev server
dotnet run --urls "http://127.0.0.1:8086"
```

Open [http://127.0.0.1:8086](http://127.0.0.1:8086) in your browser.

---

## 📦 Production Publish

```bash
dotnet publish -c Release -o bin/Release/net8.0/publish
```

The compiled standalone static assets (`index.html`, `_framework/`, WASM binaries, assets) can be hosted on Vercel, Netlify, GitHub Pages, or any static file host.
