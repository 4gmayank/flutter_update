Flutter 3.7 release notes

[Flutter Release Notes](https://docs.flutter.dev/development/tools/sdk/release-notes)
[New In Flutter](https://medium.com/flutter/whats-new-in-flutter-3-7-38cbea71133c)



Material 3 updates with iOS improvements
### New in your App: 
+ create custom menu bars
+ create cascading menus
+ tools to better support internationalization
+ new debugging tools

### Refine Flutter Feature
+ global selection 
+ faster rendering with Impeller
+ DevTools
+ As always, performance! refined



## Enhanced Material 3 support
Enable Material3 in your main: 
```
// in latest flutter sdk, for theme
MaterialApp(
  theme: ThemeData(
     useMaterial3: true, ///Turn Material3 flag true, 
    colorSchemeSeed: Colors.green, ///M3 Color Scheme
  ),
  // …
);
```

### M3 Color Scheme
[theme builder tool](https://m3.material.io/theme-builder#/custom) 
a single seed color using the ,  colorSchemeSeed parameter,  of the ThemeData constructor:
color scheme=> https://api.flutter.dev/flutter/material/ThemeData-class.html
<!-- [Sample](https://flutter.github.io/samples/#) -->

## Widgets Migrated to Material3
- Badge
- BottomAppBar
- Filled and Filled Tonal buttons
- SegmentedButton
- Checkbox
- Divider
- Menus
- DropdownMenu
- Drawer and NavigationDrawer
- ProgressIndicatordkdk
- Radio buttons
- Slider
- SnackBar
- TabBar
- TextFields and InputDecorator
- Banner


# Background isolates




Issues
[Umberealla Issue](https://github.com/flutter/flutter/issues/91605)
