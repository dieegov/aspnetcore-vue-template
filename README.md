# aspnetcore-vuejs-template
Template for creation of Vue JS aplications and Asp.Net Core 3.1 Web API

[![Nuget](https://img.shields.io/nuget/v/aspnetcore-vuejs-template.svg?style=for-the-badge&color=5b1096)](https://www.nuget.org/packages/aspnetcore-vuejs-template/)
[![Nuget Downloads](https://img.shields.io/nuget/dt/aspnetcore-vuejs-template.svg?label=Nuget%20Downloads&style=for-the-badge&color=b31ae7)](https://www.nuget.org/packages/aspnetcore-vuejs-template/)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge&color=e51384)](/LICENSE) 

---

# Features

- ASP.NET Core 3.1
    - WebApi
    - [VueCliMiddleware 3.1.1](https://www.nuget.org/packages/VueCliMiddleware)
- Vue
    - Vuex
    - Vuetify
    - Router

## Prerequisites

* [.NET Core](https://dotnet.microsoft.com/download) >= 3.1
* [NodeJS](https://nodejs.org/) >= 8.9
* [Vue CLI](https://cli.vuejs.org/) >= 4.0
* Your favourite editor (I prefer [VS Code](https://code.visualstudio.com/)), or VS 2017/19

---

## Getting started

* Download it via dotnet templates
```ts
// Make a directory
mkdir your-project-folder && cd your-project-folder

// Download the dotnet template
dotnet new -i aspnetcore-vuejs-template

// Run and install the template
dotnet new vue-vuetify

// Make sure you install the dependencies in CLientApp folder
npm install

// Run project
dotnet run
```
