# Android Developer Resources

## Design

### Icons
* https://www.google.com/design/icons/


### Theme

* [Material Theming](https://developer.android.com/training/material/theme.html)


##### Color Palette
```xml
<color name="primary">#444</color>
<color name="primary_dark">#222</color>
<color name="accent">#EEE</color>

<style name="AppTheme" parent="android:Theme.Material.Light">
    <!--   your app branding color for the app bar -->
    <item name="colorPrimary">@color/primary</item>
    
    <!--   darker variant for the status bar and contextual app bars -->
    <item name="colorPrimaryDark">@color/primary_dark</item>
    
    <!--   theme UI controls like checkboxes and text fields -->
    <item name="colorAccent">@color/accent</item>
</style>
```
