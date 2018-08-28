# AcrylicBrushReference
UWP背景毛玻璃效果

初始化亚克力效果,需要在XAML的外层Grid中添加Span所有网格的内层Grid
并在页面初始化的方法中添加
```c#
AcrylicBrush.InitializeFrostedGlass(UIElement glassHost);
```
glassHost：内层Grid对象的名称(x:Name)
此方法要在InitializeComponent()之后添加
