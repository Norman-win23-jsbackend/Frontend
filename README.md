# 💻 Frontend WebApp (.NET Blazor)

This is a modern frontend application developed using **ASP.NET Core Blazor**, structured for component-based UI with routing, layouts, and authentication features.

🔗 **Live URL**: [https://norman-deen.github.io/Crito/](https://norman-deen.github.io/Crito/)

---

## 🧩 Features

- ⚙️ Built with .NET 8 and Blazor (WASM & Server)
- 🔐 Custom Authentication State Provider
- 🧭 Page routing with nested layouts
- 💬 Simple Chat Interface
- 🛠️ Fully componentized Razor UI

---

## 📁 Structure

```

Frontend/
├── Frontend.Client/           # Blazor client app
│   ├── Pages/                 # Razor pages (e.g., Auth, Chat)
│   ├── Program.cs             # Entry point for client
│   └── wwwroot/               # Static assets + appsettings
│
├── Frontend/                  # Shared components and logic
│   ├── Components/            # Razor UI components
│   ├── Program.cs             # Main entry point
│   └── appsettings.json       # Configuration
├── Frontend.sln               # Solution file

````

---

## 🚀 Getting Started

### Prerequisites
- [.NET SDK 8+](https://dotnet.microsoft.com/download)
- [Visual Studio 2022+](https://visualstudio.microsoft.com/)

### Run the project
```bash
dotnet build
dotnet run --project Frontend/Frontend.csproj
````

Then open `https://localhost:5001` in your browser.

---

## 📄 License

This project is created as part of a **school assignment at EC Utbildning**.
You may freely inspect, copy, or adapt it for educational and demo purposes.

---

👤 Created by [Nour Tinawi](https://www.linkedin.com/in/nour-tinawi) — .NET Fullstack Developer & 3D Designer
