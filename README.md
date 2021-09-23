<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/397263924/19.2.12%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1022676)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# WPF MVVM Behaviors - Display a Theme Selector Based on a GalleryControl

[GalleryThemeSelectorBehavior](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.GalleryThemeSelectorBehavior) automatically populates the associated [GalleryControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.GalleryControl) with all available themes and allows you to choose a theme applied to your application.

<img width="590" alt="GalleryThemeSelectorBehavior_HZYtESplP2" src="https://user-images.githubusercontent.com/12169834/129886501-469218c1-56ce-49ab-a37c-e84d8642e91d.png">


## Persist Theme Selection between Application Runs

Use can save the application's theme and palette to the configuration file and restore them on the next application run.

To save an applied theme and palette, use the static [ApplicationThemeHelper.SaveApplicationThemeName](https://docs.devexpress.com/WPF/DevExpress.Xpf.Core.ApplicationThemeHelper.SaveApplicationThemeName) method to save the theme name specified in the static [ApplicationThemeHelper.ApplicationThemeName](https://docs.devexpress.com/WPF/DevExpress.Xpf.Core.ApplicationThemeHelper.ApplicationThemeName) property.

Call the static [ApplicationThemeHelper.UpdateApplicationThemeName](https://docs.devexpress.com/WPF/DevExpress.Xpf.Core.ApplicationThemeHelper.UpdateApplicationThemeName) method to retrieve the theme name from the configuration file.


## Hide a Theme from a Theme Selector

You can use the behavior's inherited [Theme.ShowInThemeSelector](https://docs.devexpress.com/WPF/DevExpress.Xpf.Core.Theme.ShowInThemeSelector) property to specify whether a theme or a theme category is visible in the **GalleryThemeSelectorBehavior**. 

<!-- default file list -->
## Files to Look At

* [MainWindow.xaml](./CS/GalleryThemeSelectorBehavior/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/GalleryThemeSelectorBehavior/MainWindow.xaml))
* [App.xaml.cs](./CS/GalleryThemeSelectorBehavior/App.xaml.cs) (VB: [Application.xaml.vb](./VB/GalleryThemeSelectorBehavior/Application.xaml.vb))
<!-- default file list end -->
## Documentation

- [GalleryThemeSelectorBehavior](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.GalleryThemeSelectorBehavior)
- [Behaviors](https://docs.devexpress.com/WPF/17442/mvvm-framework/behaviors)

## More Examples
- [WPF MVVM Behaviors - Display Theme Selectors Based on BarItems and Hide Themes from List](https://github.com/DevExpress-Examples/wpf-mvvm-behaviors-barItems-based-theme-selectors)
- [WPF MVVM Behaviors - Display a Theme Selector Based on a Hamburger Sub Menu](https://github.com/DevExpress-Examples/wpf-mvvm-behaviors-hamburger-based-theme-selector)
