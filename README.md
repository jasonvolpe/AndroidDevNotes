# Android Developer Resources

## Design

### Icons
* https://www.google.com/design/icons/

### Dependencies

* [Support Library](http://developer.android.com/tools/support-library/features.html)
    * Design ```compile "com.android.support:design:22.2.0"```

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
    
    <!-- colorAccent is used as the default value for colorControlActivated,
         which is used to tint widgets and text fields -->
    <item name="colorAccent">@color/accent</item>
    
    <!-- You can also set colorControlNormal, colorControlActivated
         colorControlHighlight, and colorSwitchThumbNormal. -->
</style>
```

## Security
* [Android Secure Coding Standard by CMU](https://www.securecoding.cert.org/confluence/display/android/Android+Secure+Coding+Standard)
