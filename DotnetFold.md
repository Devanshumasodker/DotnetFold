# How to Create and Run a Blazor WebAssembly App in GitHub Codespace

## Introduction

Blazor WebAssembly (Blazor WASM) allows you to build interactive web UIs using C# and .NET. This guide will walk you through setting up, running, and deploying a Blazor WASM project inside GitHub Codespace.

---

## 1. Setting Up the Blazor WebAssembly App

### Steps:

1. Open your GitHub repository or create a new one.
2. Launch GitHub Codespace for your repository.
3. Run the following commands in the terminal:

   ```sh
   dotnet new blazorwasm -o MyBlazorApp
   cd MyBlazorApp
   dotnet run
