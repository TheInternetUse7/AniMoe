<div style="text-align: center; margin-top: 20px"><img src="https://i.imgur.com/XYZgXmP.png" width="100"></div>

<div style="text-align: center; margin-top: -30px"> <h1>AniMoe for AniList</h1>
 A Windows 10 & 11 Client for AniList. Track and Discover anime and manga with ease.

[![WinUI3 Packaged MSIX App](https://github.com/CosmicPredator/AniMoe/actions/workflows/ci-prod.yml/badge.svg)](https://github.com/CosmicPredator/AniMoe/actions/workflows/ci-prod.yml)

<img src="https://i.imgur.com/rzotm7h.jpg" width="400">

</div>

> [!NOTE]
> This is a Work in Progress Application

# Features
- Anime & Manga Tracker.
- Airing Notifications.
- Media Detection & Updation.
- Custom Markdown renderer for forums (future).

# Build from Source
- Install Visual Studio 2022.
- Install ".NET Desktop Development" along with
Windows App SDK C# Templates.
- Clone the repository.
- Add WinUi3 Labs NuGet Repository.
	```
	https://pkgs.dev.azure.com/dotnet/CommunityToolkit/_packaging/CommunityToolkit-Labs/nuget/v3/index.json
	```
- Open the solution with Visual Studio
- Build it.

# NuGet Packages Used
- `CommunityToolkit.MVVM`
- `CommunityToolkit.WinUI.UI.Behaviours`
- `Microsoft.Extensions.Configuration.Abstractions`
- `Microsoft.Extensions.DependencyInjection`
- `Microsoft.Windows.SDK.BuildTools`
- `Microsoft.WindowsAppSDK`
- `Newtonsoft.Json`
- `CommunityToolkit.Labs.WinUI.SegmentedControl`
- `CommunityToolkit.Labs.WinUI.SettingsControls`
- `CommunityToolkit.Labs.WinUI.Shimmer`
- `CommunityToolkit.WinUI.UI.Controls`
- `CommunityToolkit.WinUI.UI.Media`
- `LiveChartsCore.SkiaSharpView.WinUI`
- `Markdig`
- `PInvoke.User32`
- `Serilog`
- `Serilog.Sinks.Debug`
- `Serilog.Sinks.File`
- `Microsoft.Extensions.Caching.Abstractions`
- `Microsoft.Extensions.Configuration.Abstractions`
- `Microsoft.Extensions.Http`
- `Microsoft.Graphics.Win2D`
- `System.Net.Http`
