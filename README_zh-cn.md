# Windows UI Library

[![在 Twitter 上关注 WinUI](https://img.shields.io/twitter/follow/windowsui.svg?label=在%20Twitter%20上关注%20WinUI&style=social)](https://twitter.com/intent/follow?screen_name=windowsui)

WinUI 是一个包含用于构建 Windows 应用程序的现代控件和样式的用户界面层。作为 Windows 中的本机用户界面层，它体现了 [Fluent Design](https://www.microsoft.com/design/fluent/#/)，为每个 Windows 应用程序提供了客户期望的精致感。

WinUI 2 是一个控件库，提供了官方的本机 Microsoft UI 控件和功能，适用于 Windows [UWP 应用](https://docs.microsoft.com/windows/uwp/index)。WinUI 2 可以在任何运行在 Windows 10 上的 UWP XAML 应用程序中使用，或者在使用 [本机视图嵌入](https://docs.microsoft.com/xamarin/xamarin-forms/platform/native-views) 的 Windows 10 上运行的 Xamarin.Forms 应用程序中使用。

WinUI 3 是 WinUI 框架的下一代。它将 WinUI 大幅扩展为一个完整的 UX 框架，使 WinUI 可用于所有桌面 Windows 应用程序，作为用户界面层。

## WinUI 社区通话

WinUI 社区通话是您每月了解使用 WinUI 进行本机 UX 开发的机会。

在这些通话中，我们将讨论 WinUI 的 [路线图](docs/roadmap.md)，我们的状态以及您的反馈。

您可以在 YouTube 的 [Windows Developer 频道](https://www.youtube.com/channel/UCzLbHrU7U3cUDNQWWAqjceA) 上在线观看它们。

## 使用 WinUI 3

您可以使用 WinUI 3 构建新的 Windows 应用程序，它作为 Windows App SDK 的一部分发布。最新可用的稳定版本是 Windows App SDK 1.4（以前称为 Project Reunion）。通过此版本，您可以将生产桌面应用程序发布到 Microsoft Store。

请参阅 [安装说明](https://docs.microsoft.com/windows/apps/windows-app-sdk/set-up-your-development-environment)，以及有关 [创建您的第一个 WinUI 3 应用程序](https://docs.microsoft.com/windows/apps/winui/winui3/create-your-first-winui3-app) 的指南。

WinUI 3 的源代码可以在 [此处](https://github.com/microsoft/microsoft-ui-xaml/tree/winui3/main) 找到。

## 使用 WinUI 2
您可以使用 NuGet 包管理器下载并使用 WinUI 包：有关详细信息，请参阅 [Windows UI Library 入门](https://docs.microsoft.com/uwp/toolkits/winui/getting-started) 页面。

WinUI 2 的源代码可以在 [此处](https://github.com/microsoft/microsoft-ui-xaml/tree/winui2/main) 找到。

### 包

| NuGet 包 | 构建状态 | 最新版本 | 文档 |
| --- | --- | --- | --- |
| [Microsoft.UI.Xaml](https://www.nuget.org/packages/Microsoft.UI.Xaml) <br /> 用于 UWP 应用的控件和 Fluent Design | [![Build Status](https://dev.azure.com/ms/microsoft-ui-xaml/_apis/build/status/WinUI-Public-MUX-CI?branchName=main)](https://dev.azure.com/ms/microsoft-ui-xaml/_build/latest?definitionId=20?branchName=main) | [![最新稳定版本](https://img.shields.io/nuget/v/Microsoft.UI.Xaml.svg)](https://www.nuget.org/packages/Microsoft.UI.Xaml) <br /> [![最新预览版本](https://img.shields.io/nuget/vpre/Microsoft.UI.Xaml.svg)](https://www.nuget.org/packages/Microsoft.UI.Xaml/absoluteLatest) | [2.8 版本](https://docs.microsoft.com/windows/apps/winui/winui2/release-notes/winui-2.8) |
| [Microsoft.UI.Xaml.Core.Direct](https://www.nuget.org/packages/Microsoft.UI.Xaml.Core.Direct) <br /> 用于中间件组件的低级 API | | [![最新预览版本](https://img.shields.io/nuget/vpre/Microsoft.UI.Xaml.Core.Direct.svg)](https://www.nuget.org/packages/Microsoft.UI.Xaml.Core.Direct/absoluteLatest) | [2.0 预览版](https://docs.microsoft.com/uwp/api/microsoft.ui.xaml.core.direct) |

您还可以根据源代码自己构建 WinUI 包。有关构建和贡献到 WinUI 的更多信息，请参阅 [贡献到 Windows UI Library](CONTRIBUTING.md)。

## 文档

要找到 Windows UI 2.8 的资源，例如 [Figma 设计工具包](https://aka.ms/WinUI/3.0-figma-toolkit)，Segoe UI 可变字体和示例，请访问 [Windows 应用程序的设计工具包和示例](https://docs.microsoft.com/windows/apps/design/downloads/)。

如果您在 Windows UI 工具包中发现任何问题，可以在 [此处](https://aka.ms/WinUIToolkitBug) 提交错误。

**WinUI 使用文档**：  
https://docs.microsoft.com/windows/apps/winui/

**WinUI 2 发行说明**：  
https://docs.microsoft.com/windows/apps/winui/winui2/release-notes/

**WinUI 3 发行说明**：
https://docs.microsoft.com/windows/apps/windows-app-sdk/stable-channel

**示例代码**：  
要以交互式格式查看 WinUI 控件，请查看 Xaml 控件库（适用于 WinUI 2）和 WinUI 3 控件库：
* 从 [Microsoft Store](https://www.microsoft.com/store/productId/9MSVH128X2ZT) 获取 XAML 控件库应用程序，或者从 [GitHub](https://github.com/Microsoft/Xaml-Controls-Gallery) 获取源代码
* 从 [Microsoft Store](https://www.microsoft.com/p/winui-3-controls-gallery/9p3jfpwwdzrc) 获取 WinUI 3 控件库应用程序，或者从 [GitHub](https://github.com/microsoft/Xaml-Controls-Gallery/tree/winui3) 获取源代码

[

WinUI](https://microsoft.github.io/microsoft-ui-xaml/) 还有自己的网站，您可以在那里了解更多信息。

## 贡献到 WinUI
WinUI 团队欢迎您的反馈！

要了解我们如何处理提出的功能请求和错误，请参阅我们的 [贡献处理](docs/contribution_handling.md) 指南。

有关如何贡献的信息，请参阅 [贡献到 Windows UI Library](CONTRIBUTING.md)。

有关通过非代码贡献对 WinUI 产生影响的准则，请参阅 [贡献思路、反馈和请求](CONTRIBUTING_feedback_and_requests.md)。

## WinUI 特性

### 好处

在为 Windows 10 构建应用程序时，WinUI 2 提供了一些有用的好处：

1. **帮助您保持更新**  
WinUI 有助于使您的应用程序与 [UWP XAML](https://docs.microsoft.com/windows/uwp/xaml-platform/xaml-overview) 和 [Fluent Design 系统](https://www.microsoft.com/design/fluent) 的关键控件和功能的最新版本保持同步

2. **提供向后兼容性**  
WinUI 与广泛范围的 Windows 10 版本向后兼容：即使用户不在 Windows 10 的最新版本上，您也可以立即开始构建和发布具有新 XAML 功能的应用程序

3. **使构建版本自适应的应用程序更简单**  
您不需要版本检查或条件性的 XAML 标记来使用 WinUI 控件或功能：WinUI 会自动适应用户的操作系统版本

### 版本支持

Microsoft.UI.Xaml 2.8 NuGet 包在构建时要求您的项目具有 TargetPlatformVersion &gt;= 10.0.18362.0 和 TargetPlatformMinVersion &gt;= 10.0.17763.0。

您的应用程序的用户可以处于以下任何受支持的 Windows 10 版本上：

 * Windows 10 1809 - Build 17763（创作者更新，也称为“Redstone 5”）及更高版本（包括 Windows Insider 预览版）

一些功能在较旧版本上可能具有减少或稍有不同的用户体验。

对于 WinUI 3，您的应用程序的用户必须在 Windows 10 1809 - Build 17763 或更高版本上（包括 Windows Insider 预览版）。

## 路线图

有关 WinUI 发布时间表和高层计划的信息，请参阅 [Windows UI Library 路线图](docs/roadmap.md)。

## WinUI 3 是 Windows App SDK 家族的一部分
[Windows App SDK](https://github.com/microsoft/ProjectReunion) 是一组库、框架、组件和工具，您可以在应用程序中使用它们，以从 Windows 的许多版本上的各种应用程序中访问强大的 Windows 平台功能。Windows App SDK 结合了 Win32 本机应用程序与现代 API 使用技术的力量，因此您的应用程序可以在用户所在的任何地方运行。

其他 Windows App SDK 组件包括：[WebView2](https://docs.microsoft.com/microsoft-edge/webview2/)、[MSIX（MSIX-Core）](https://docs.microsoft.com/windows/msix/overview)、[C++/WinRT](https://github.com/microsoft/cppwinrt)、[Rust/WinRT](https://github.com/microsoft/winrt-rs) 和 [C#/WinRT](https://github.com/microsoft/cswinrt)。如果您想了解更多并为 Windows App SDK 做贡献，或者有 **UWP/应用程序模型相关的问题**，请访问我们的 [GitHub 仓库](https://github.com/microsoft/WindowsAppSDK)。

要详细了解我们计划在 WinAppSDK 中发布的功能，请查看 [Windows App SDK 功能路线图](https://github.com/microsoft/WindowsAppSDK/blob/main/docs/roadmap.md)。

## 数据/遥测

此项目收集使用数据并将其发送到 Microsoft，以帮助改进我们的产品和服务。但请注意，当使用您的私人构建时，不进行任何数据收集。


# 行为准则

该项目已采用 [Microsoft 开源行为准则](https://opensource.microsoft.com/codeofconduct/)。

有关更多信息，请参阅 [行为准则常见问题解答](https://opensource.microsoft.com/codeofconduct/faq/) 或通过 [opencode@microsoft.com](mailto:opencode@microsoft.com) 联系我们，以获取任何其他问题或意见。