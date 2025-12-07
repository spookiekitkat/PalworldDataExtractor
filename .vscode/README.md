# VS Code workspace for PalworldDataExtractor

Quick notes:

- Open the workspace file `PalworldDataExtractor.code-workspace` to load recommended extensions and settings.
- Common tasks are available under `Terminal > Run Task`:
  - `Build Solution` — builds `PalworldDataExtractor.sln`.
  - `Run Cli` — runs the `Cli` project (`dotnet run --project Cli/Cli.csproj`).
  - `Run Tests` — runs tests in `Tests/Tests.csproj`.
- Use the `Launch Cli` configuration in the Run view to start the CLI with the debugger attached (it runs a build first).

Recommended extensions (auto-suggested by the workspace): C# (`ms-dotnettools.csharp`) and the Test Adapter Converter.

If you want, I can also add more tasks (e.g., separate unit/integration test tasks) or adjust formatting rules.
