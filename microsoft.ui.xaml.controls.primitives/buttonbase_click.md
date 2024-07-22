---
-api-id: E:Microsoft.UI.Xaml.Controls.Primitives.ButtonBase.Click
-api-type: winrt event
---

<!-- Event syntax
public event Windows.UI.Xaml.RoutedEventHandler Click
-->

# Microsoft.UI.Xaml.Controls.Primitives.ButtonBase.Click

## -description
Occurs when a button control is clicked.

## -xaml-syntax
```xaml
<button Click="eventhandler"/>
```


## -remarks

There is also a [UIElement.Tapped](https://docs.microsoft.com/windows/windows-app-sdk/api/winrt/Microsoft.UI.Xaml.UIElement.Tapped)
event that indicates that an element has been pressed and released with a pointer device, such as a mouse or touch.
But use this `Click` event as a general purpose notification that the button has been clicked,
because it also responds to a button having been clicked with the keyboard or Accessibility tools.


## -examples
The following example demonstrates handling the Click event and setting the [IsEnabled](../microsoft.ui.xaml.controls/control_isenabled.md) property of a [Button](../microsoft.ui.xaml.controls/button.md), which inherits from [ButtonBase](buttonbase.md).



[!code-xaml[4](../microsoft.ui.xaml/code/System.Windows.Controls.ButtonClickEx/csharp/Page.xaml#Snippet4)]


[!code-csharp[41](../microsoft.ui.xaml/code/System.Windows.Controls.ButtonClickEx/csharp/Page.xaml.cs#Snippet41)]

## -see-also
[Button](../microsoft.ui.xaml.controls/button.md)
