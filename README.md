
# IoTSharp WinForms DataVisualization

This repository maintains the Windows Forms chart controls for .NET 10. It is an actively maintained continuation for applications that need the classic charting API on modern WinForms.

The NuGet package is `IoTSharp.WinForms.DataVisualization`. Existing source code keeps using the original `System.Windows.Forms.DataVisualization` namespaces, so applications can migrate by changing the package reference without changing charting namespaces.


# Data Visualization

This repository contains the `System.Windows.Forms.DataVisualization` namespace and provides charting for WinForms applications targeting .NET 10.


## Getting started with Chart Controls

The best way to learn about Chart Controls is by looking at the [sample solution](https://github.com/dotnet/winforms-datavisualization/tree/master/sample) where via interactive experience with the app you can learn about every chart type and every major feature. While modifying the control parameters and instantly seeing how that affects the look of the control, you can also get the generated C# or Visual Basic code to use in your apps.

![Chart Controls](sample-screenshot.png)

There is also a [.NET Framework version](https://code.msdn.microsoft.com/Windows-Forms-Samples-26bf2a53) of this sample available on Microsoft samples portal.

The package is available from [NuGet Gallery](https://www.nuget.org/packages/IoTSharp.WinForms.DataVisualization).

```xml
<PackageReference Include="IoTSharp.WinForms.DataVisualization" Version="10.0.0" />
```
