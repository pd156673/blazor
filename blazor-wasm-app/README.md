# blazor-wasm-app

Dieses Projekt ist eine Blazor WebAssembly-Anwendung, die es ermöglicht, interaktive Webanwendungen mit C# zu erstellen. Es besteht aus mehreren Projekten, die zusammenarbeiten, um eine vollständige Anwendung bereitzustellen.

## Projektstruktur

- **BlazorWasmApp.Client**: Enthält die Client-seitige Blazor WebAssembly-Anwendung.
  - **wwwroot/index.html**: Die Haupt-HTML-Datei, die die Blazor-Anwendung lädt.
  - **Pages/Index.razor**: Die Razor-Komponente für die Startseite der Anwendung.
  - **Program.cs**: Der Einstiegspunkt der Blazor WebAssembly-Anwendung.
  - **App.razor**: Definiert die Hauptanwendungskomponente und die Routing-Logik.

- **BlazorWasmApp.Server**: Enthält die Server-seitige Logik und API-Controller.
  - **Controllers/WeatherForecastController.cs**: Ein Controller, der Wettervorhersagedaten bereitstellt.
  - **Program.cs**: Der Einstiegspunkt der Blazor Server-Anwendung.
  - **Startup.cs**: Konfiguriert die Dienste und Middleware-Pipeline.
  - **appsettings.json**: Enthält Konfigurationseinstellungen für die Serveranwendung.

- **BlazorWasmApp.Shared**: Enthält gemeinsam genutzte Datenstrukturen.
  - **WeatherForecast.cs**: Definiert die Datenstruktur für die Wettervorhersage.

- **BlazorWasmApp.sln**: Die Lösung für das gesamte Projekt, die alle Projekte innerhalb der Lösung referenziert.

## Installation

Um die Anwendung auszuführen, stellen Sie sicher, dass Sie die erforderlichen .NET SDKs installiert haben. Klonen Sie das Repository und führen Sie die folgenden Befehle aus:

```bash
cd BlazorWasmApp.Client
dotnet run
```

## Verwendung

Nach dem Start der Anwendung können Sie im Browser auf `https://localhost:5001` zugreifen, um die Blazor WebAssembly-Anwendung zu sehen. Die Startseite wird durch die `Index.razor`-Komponente dargestellt.

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz.