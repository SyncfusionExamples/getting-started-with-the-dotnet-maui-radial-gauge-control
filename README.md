# Getting Started with the .NET MAUI Radial Gauge Control

The [.NET MAUI Radial Gauge](https://www.syncfusion.com/maui-controls/maui-radial-gauge?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples) is a multipurpose data visualization control that displays numerical values on a circular scale. This article shows how to create and configure the Syncfusion .NET MAUI Radial Gauge. This project also includes a code snippet to set a specific axis pointer value, customize the gauge axis as well as how to animate the gauge, animate the pointer, and add multiple axis ranges. 

## Supported platforms

.NET Multi-platform App UI (.NET MAUI) apps can be written for the following platforms:

* Android 5.0 (API 21) or higher.
* iOS 11 or higher, using the latest release of Xcode.
* macOS 10.15 or higher, using Mac Catalyst.
* Windows 11 and Windows 10 version 1809 or higher, using [Windows UI Library (WinUI) 3](https://learn.microsoft.com/en-us/windows/apps/winui/winui3/).

## Requirements to run the sample

* [Visual Studio 2022 Preview](https://learn.microsoft.com/en-us/visualstudio/releases/2022/release-notes-preview) version 17.6.0 (.NET MAUI version 6.0.552) with .NET 6.0 and .NET 7.0
* [Microsoft Visual Studio 2022](https://learn.microsoft.com/en-us/visualstudio/releases/2022/release-notes) version 17.5.1 with (.NET MAUI version 6.0.552) with .NET 6.0 and .NET 7.0
* [Visual Studio 2022 for Mac Preview](https://visualstudio.microsoft.com/vs/mac/preview/) version 17.5 (.NET MAUI version 6.0.552) with .NET 6.0 and .NET 7.0

Refer to the following link for more details: [System Requirements](https://help.syncfusion.com/maui/system-requirements)

## How to run the sample

1. Clone the sample and open it in Visual Studio 2022 preview.

   *Note: If you download the sample using the "Download ZIP" option, right-click it, select Properties, and then select Unblock.*

2. Register your license key in the App.cs file as demonstrated in the following code.

		public App()
		{
			//Register Syncfusion license
			Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
		
			InitializeComponent();
		
			MainPage = new MainPage();
		}
		
	Refer to this [link](https://help.syncfusion.com/maui/licensing/overview) for more details.

3. Clean and build the application.

4. Run the application.

## License

Syncfusion has no liability for any damage or consequence that may arise from using or viewing the samples. The samples are for demonstrative purposes. If you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.

## Features and Benefits

### Ranges
Radial range is a visual element that helps to quickly visualize a value where it falls on the axis.

### Pointers 
[Pointer](https://help.syncfusion.com/maui/radial-gauge/pointers?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples) is used to indicate values on an axis. Radial gauge has three types of pointers: needle pointer, shape pointer, content pointer and range pointer. All the pointers can be customized as needed.

### Pointer animation 
[Animates](https://help.syncfusion.com/maui/radial-gauge/animation?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples) the pointer in a visually appealing way when the pointer moves from one value to another.

### Pointer interaction
Radial gauge provides an option to drag a pointer from one value to another. It is used to change the value at run time.

### Annotations
Add multiple views such as text and image as an [annotation](https://help.syncfusion.com/maui/radial-gauge/annotation?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples) to a specific point of interest in a radial gauge.

## Related links
[Learn More about .NET MAUI Radial Gauge](https://www.syncfusion.com/maui-controls/maui-radial-gauge?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)

[Download Free Trial](https://www.syncfusion.com/downloads/maui?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)

[Pricing](https://www.syncfusion.com/sales/teamlicense?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)

[Documentation](https://help.syncfusion.com/maui/radial-gauge/getting-started?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)

[View Demos](https://github.com/SyncfusionExamples/getting-started-with-the-dotnet-maui-radial-gauge-control?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)

[Community Forums](https://www.syncfusion.com/forums/maui?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)

[Suggest a feature or report a bug](https://www.syncfusion.com/feedback/maui?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)

[Online example](https://github.com/syncfusion/maui-demos/tree/master/MAUI/Gauges/SampleBrowser.Maui.Gauges/Samples/RadialGauge?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)

## About Syncfusion .NET MAUI Controls

Syncfusion's [.NET MAUI UI Controls](https://www.syncfusion.com/maui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples) library is the only suite that you will ever need to build an application since it contains over 40 high-performance, lightweight, modular, and responsive UI Controls in a single package. In addition to Radial Gauge, we provide popular .NET MAUI Controls such as [DataGrid](https://www.syncfusion.com/maui-controls/maui-datagrid?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)[Charts](https://www.syncfusion.com/maui-controls/maui-cartesian-charts?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [Scheduler](https://www.syncfusion.com/maui-controls/maui-scheduler?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [ListView](https://www.syncfusion.com/maui-controls/maui-listview?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), and [Excel Library](https://www.syncfusion.com/document-processing/excel-framework/maui?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples).

### About Syncfusion
Founded in 2001 and headquartered in Research Triangle Park, N.C., Syncfusion has more than 29,000 customers and more than 1 million users, including large financial institutions, Fortune 500 companies, and global IT consultancies.

Today, we provide 1800+ components and frameworks for web ([Blazor](https://www.syncfusion.com/blazor-components?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [ASP.NET Core](https://www.syncfusion.com/aspnet-core-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [ASP.NET MVC](https://www.syncfusion.com/aspnet-mvc-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [ASP.NET WebForms](https://www.syncfusion.com/jquery/aspnet-webforms-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [JavaScript](https://www.syncfusion.com/javascript-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [Angular](https://www.syncfusion.com/angular-components?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [React](https://www.syncfusion.com/react-components?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [Vue](https://www.syncfusion.com/vue-components?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), and [Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)), mobile ([Xamarin](https://www.syncfusion.com/xamarin-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [UWP](https://www.syncfusion.com/uwp-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [JavaScript](https://www.syncfusion.com/javascript-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), and [.NET MAUI](https://www.syncfusion.com/maui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)), and desktop development ([WinForms](https://www.syncfusion.com/winforms-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [WPF](https://www.syncfusion.com/wpf-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [WinUI](https://www.syncfusion.com/winui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples),[UWP](https://www.syncfusion.com/uwp-ui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), [Flutter](https://www.syncfusion.com/flutter-widgets?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples), and [.NET MAUI](https://www.syncfusion.com/maui-controls?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples)). We provide ready-to-deploy enterprise software for dashboards, reports, data integration, and big data processing. Many customers have saved millions in licensing fees by deploying our software.

<hr style="height:0.3px;border:none;color:lightgrey;background-color:lightgrey;" />

<p align="center">
<a href="mailto:sales@syncfusion.com?Subject=Syncfusion .NET MAUI Radial Gauge - GitHub" target="_top">sales@syncfusion.com</a> | <a href="https://www.syncfusion.com?utm_source=github&utm_medium=listing&utm_campaign=maui-radial-gauge-github-samples">www.syncfusion.com</a> | Toll Free: 1-888-9 DOTNET <br>
</p>