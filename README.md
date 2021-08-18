# How to Implement a Theme Selector Based on a Gallery

[GalleryThemeSelectorBehavior](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.GalleryThemeSelectorBehavior) automatically populates the associated [GalleryControl](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.GalleryControl) with all available themes and allows you to choose a theme applied to your application.

<img width="590" alt="GalleryThemeSelectorBehavior_HZYtESplP2" src="https://user-images.githubusercontent.com/12169834/129886501-469218c1-56ce-49ab-a37c-e84d8642e91d.png">

Refer to the [MainWindow.xaml](https://github.com/DevExpress-Examples/how-to-implement-a-theme-selector-based-on-a-gallery/blob/19.2.12%2B/CS/GalleryThemeSelectorBehavior/MainWindow.xaml) (VB: [MainWindow.xaml](https://github.com/DevExpress-Examples/how-to-implement-a-theme-selector-based-on-a-gallery/blob/19.2.12%2B/VB/GalleryThemeSelectorBehavior/MainWindow.xaml)) file to get the code sample that displays a GalleryControl with a theme selector.

## Hide a Theme from a Theme Selector

You can use the [Theme.ShowInThemeSelector](https://docs.devexpress.com/WPF/DevExpress.Xpf.Core.Theme.ShowInThemeSelector) property to specify whether a theme or a theme category is visible in the **GalleryThemeSelectorBehavior**. 

Refer to the [App.xaml.cs](https://github.com/DevExpress-Examples/how-to-implement-a-theme-selector-based-on-a-gallery/blob/19.2.12%2B/CS/GalleryThemeSelectorBehavior/App.xaml.cs) (VB: [Application.xaml.vb](https://github.com/DevExpress-Examples/how-to-implement-a-theme-selector-based-on-a-gallery/blob/19.2.12%2B/VB/GalleryThemeSelectorBehavior/Application.xaml.vb)) file to get the code sample that hides [Office2007](https://docs.devexpress.com/WPF/7407#office-2007-themes) and [Metropolis](https://docs.devexpress.com/WPF/7407#metropolis-themes) theme categories, the [DeepBlue](https://docs.devexpress.com/WPF/7407#other-themes) application theme from the theme selector.

