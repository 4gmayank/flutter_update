# Flutter 3.7 Changes

API documentation cleanup 
Add AnimatedIcons previews and examples 
Add BuildContext.mounted 
Add Dialog.fullscreen and example 
Add Escaping Option for ICU MessageFormat Syntax 
Add Focus.parentNode to allow controlling the shape of the Focus tree. 
Add HitTestBehavior to TapRegion 
Add IndicatorShape to NavigationRailTheme and fix indicator ripple. 
Add Material 3 Popup Menu example and update existing example 
Add Material 3 ProgressIndicator examples 
Add Material 3 Slider example 
Add Material 3 support for BottomAppBar 
Add Material 3 support for BottomAppBar (reland #106525) 
Add Material 3 support for Slider - Part 1 
Add Material 3 support for Slider - Part 2 
Add Material 3 support for TabBar 
Add OvalBorder and BoxShape.oval 
Add Overlay.maybeOf, make Overlay.of return a non-nullable instance 
Add PointerScaleEvent and use in InteractiveViewer 
Add RenderRepaintBoundary.toImageSync() method 
Add RestorableEnumN<T> and RestorableEnum<T> to restorable primitive types 
Add SafeArea for NavigationRail 
Add SliverAnimatedGrid and AnimatedGrid 
Add SliverGrid.builder constructor 
Add Spell Check to Editable Text (iOS) 
Add Spellcheck to EditableText (Android) 
Add StarBorder and StarBorder.polygon, with example. 
Add UIApplicationSupportsIndirectInputEvents migration 
Add a matcher for Matrix4 that includes epsilon 
Add a snapAnimationDuration param in DraggableScrollableSheet 
Add a way to customize padding in BottomAppBar 
Add ability to show magnifier on long press 
Add an example for AppBar.notificationPredicate 
Add an example for how to hide default scrollbar on desktop platform. 
Add an interactive example for Overlay 
Add assertion to _CupertinoSwitchRenderObjectWidget, otherwise it is confusing why updateRenderObject omits state update 
Add asset manifest parsing benchmark 
Add avoid_redundant_argument_values ignores back 
Add bitcode deprecation note for add-to-app iOS developers 
Add branch coverage to flutter test 
Add button semantics in list tile 
Add checkbox and radio menu buttons 
Add clarification to CupertinoUserInterfaceLevel docs 
Add clip option for navigator 
Add clipBehavior and apply borderRadius to DataTable’s Material 
Add covariant to ThemeExtension.lerp 
Add doc note about when to dispose TextPainter 
Add error message when lerping between TextStyles different inherit values 
Add fontFamilyFallback to ThemeData 
Add friction coefficient to InteractiveViewer 
Add info project validator status 
Add inherit: false to material2018 text geometry text themes 
Add macOS-specific scroll physics 
Add maybeOf for all the cases where of returns nullable. 
Add missing deprecation notice for toggleableActiveColor 
Add more InkWell tests 
Add more logs to diagnose Gold flake 
Add more supported simulator debugging options and improve tests 
Add mouse region for InputDecorationIcons in the textfield 
Add onFocusChange property for ListTile widget 
Add onOpened callback to PopupMenuButton 
Add onTapOutside to TextFormField 
Add optional flag to determine assertiveness level in aria announcement for flutter web 
Add outlineVariant and scrim colors to ColorScheme 
Add overlay MaterialStateProperty property to Slider 
Add parentNode to FocusScope widget 
Add quotes to Gradle NDK version error message 
Add regression test for TextPainter.getWordBoundary 
Add selection feedback for both selection area and text field 
Add shadowColor and surfaceTintColor to Dialog and DialogTheme. 
Add some logs to catch flake 
Add splashColor property for ListTile widget 
Add support for Alt to CharacterActivator, add tests 
Add support for Material 3 Divider and VerticalDivider 
Add support for Material 3 Divider and VerticalDivider 
Add support for expression compilation when debugging integration tests 
Add support for fill, weight, grade, and optical size to Icon 
Add support for font variation based theming to Icon 
Add supportedDevices parameter to GestureDetector 
Add test where white text on white background fails contrast. 
Add transitionOnUserGestures to true on SnackBar for back swipe 
Add usage event when iOS app is archived 
Add usage event when macOS app is archived 
Add useSafeArea parameter to showModalBottomSheet 
Add width property to SnackBarThemeData 
Add –empty to the flutter create command 
add GeneralInfo project validator to analyze –suggestions 
add material slider secondary value 
  

Added Badge.count constructor 
Added Badge.isLabelVisible flag 
Added IconButtonTheme and apply it to IconButton in M3 
Added ShapeBorder to expansionTile 
Added Switch Animation for Material 3 
Added a clarification on scrollBehaviour in BoxScroll and ListView 
Added controller and onSelected properties to DropdownMenu 
Added documentation for AppBar actions 
Added example for Magnifier and TextMagnifier 
Added iconSize parameter in ButtonStyle 
Added iconTheme to RawChip in ChoiceChip 
Added keyboardType in CupertinoSearchTextField 
Added onSelectionChange callback to SelectionRegion and SelectionArea 
Added statesController to the button icon constructors. 
Added support for M3 filled and filled tonal buttons. 
Added token files for badges and lists. 
Adds PopupMenuPosition position to the PopupMenuThemeData 
Adds support for the Material Badge widget, BadgeTheme, BadgeThemeData 
Adjust Material 3 textfield padding to align with specs 
Allow Flutter golden file tests to be flaky 
Allow Hybrid Composition fallback for Android platform views 
Allow Navigator to inherit traversal policy from parent. 
Allow key reparenting between slots in SlottedMultiChildRenderObjectWidgetMixin 
Allow setting of TestWidgetsFlutterBinding.pointerEventSource 
Allow trackpad inertia cancel events 
Allows pushing page based route as pageless route 
Always invoke impeller ios shader target 
  
  
Annual spelling error fix 
Apply indexToItemIndex to indices returned by findChildIndexCallback in SliverAnimatedListState 
Apply multidex config in kotlin dsl gradle file 
AutomatedTestWidgetsFlutterBinding.pump provides wrong pump time stamp, probably because of forgetting the precision 
Avoid creating map literal in flutter.gradle multidex check 
Avoid sending zero transform semantic nodes to the engine 
BouncingScrollPhysics should propagate decelerationRate 
BufferLogger should log stacktrace 
Build command dependency injection 
Bump android SDK to 33 
Cache TextPainter plain text value to improve performance 
Can call ChangeNotifier.hasListeners after disposed 
Change ClipboardStatusNofifier parameter in buildToolbar to ValueLise… 
Change button and label text to sentence case for Material 3 
Change default text color of CupertinoAlertDialog to theme primary color 
Change default value of effectiveInactivePressedOverlayColor in Switch to refer to effectiveInactiveThumbColor 
Change some required nullable parameters in tool to non-null 
Change type in ImplicitlyAnimatedWidget to remove type cast to improve performance and style 
Change “Unicode scalar values” to “Unicode grapheme clusters” in maxLength docs 
Check device type using platformType instead of type check to support proxied devices. 
Check for analyzer rule names instead of descriptions in a flutter_tools test 
Check for bad characters in path on Windows build 
Check for watch companion in build settings 
Check for watch companion in build settings 
Clean up ScrollbarPainter 
Clean up _updateSelectionRects 
Clear the static _debugDoingBaseline flag if baseline calculation throws 
Composing text shouldn’t be part of undo/redo 
Consider Scrollable location in text selection drag events 
Context Menus 
Create DropdownMenu Widget to Support Material 3 
Create a main alias for master channel. 
Create an enum for widget inspector service extensions for use by tools 
Create class MemoryAllocations. 
Create consts for foundation service extension names so they can be accessed from tooling 
Create consts for rendering service extension names so they can be accessed from tooling 
Create consts for service extension names so they can be accessed from tooling 
Create containsSemantics to allow for partial matching of semantics in tests. 
Create enum for scheduler service extension names so they can be accessed from tooling 
Create enum for service extensions in services library 
Cupertino date picker fix for minDate, maxDate when using minuteInterval 
Dart registrant location 
Delegate TestWindow.updateSemantics to the wrapped SingletonFlutterWindow 
Delete errant .packages 
Delete flutter_migrate code 
Dependency injection Attach command 
  
Deprecate 2018 text theme parameters 
Deprecate AnimatedListItemBuilder and AnimatedListRemovedItemBuilder 
Deprecate ThemeData errorColor and backgroundColor 
Deprecate ThemeData.bottomAppBarColor 
Deprecate ThemeData.selectedRowColor 
Deprecate toggleableActiveColor 
Disable backspace/delete handling on iOS & macOS 
Disable jank metrics for web 
Disallow dispose during listener callback 
Dispose KeepAliveHandle. 
Dispose Paragraph objects 
Dispose _TextSpanEditingController. 
Dispose painters 
Dispose scaffold drawers. 
Dispose widgets to stop leaks. 
Do not assume that pub is the first command run by “flutter create” 
Do not codesign transitive dependency iOS pod resource bundles 
Do not copy the old selection when applying localization to dates in InputDatePickerFormField 
Do not crash when remove SelectableText during handle drag 
Do not strip architecture suffixes from host local-engine 
Doc fix, followerAnchor changed to targetAnchor 
Document that TooltipTriggerMode has no impact on hovering 
Document tristate value 
Don’t disable pointer interaction during trackpad scroll 
Don’t redefine SkSL builtin function ‘saturate’ 
Don’t specify libraries-spec argument if we are passing a platform dill. 
Dropdown height large scale text fix 
DropdownButton: Fix hint alignment when selectedItemBuilder is non-null. 
Enable android isolate platform channels tests 
Enable impeller flags for iOS simulator 
Error in docs: CustomPaint instead of CustomPainter 
Explain the “patching” protocol in KeyMessageManager.keyMessageHandler and add an example 
Explicitly call out documentation links in “flutter create” 
Export elapseBlocking to test binding, so slow sync work can be simulated such as a slow widget build 
Expose alwaysShowMiddle in CupertinoSliverNavigationBar 
Expose padding on RawScrollbar 
Expose text boundary combiner class 
Expose the duration and curve for theme animation in MaterialApp. 
FFI plugin bump FFIgen to 6.1.2
  
# Fixes  
Feat: dSYM debug info for iOS & macOS builds 
Fix Action.overridable example 
Fix Android Studio version string nullablity, fake AndroidStudio in test 
Fix Android platform view creation flow 
Fix AppBar centerTitle position with actions. 
Fix BottomNavigationBarItem tooltip defaults to label 
Fix CastError in StadiumBorder.lerpTo and StadiumBorder.lerpFrom when using BorderRadiusDirectional 
Fix Color Scheme Defaults in Material 3 
Fix CupertinoAlertDialog and CupertinoActionSheet, which mis-behave when orientation changes 
Fix CupertinoListTile`s onTap with delay throws exception 
Fix DDS do not support Curves.easeInOutBack curve 
Fix DraggableScrollableSheet and ListView has tiny scroll of one pixel 
Fix DraggableScrollableSheet rebuilding during drag 
Fix ExpansionTile shows children background when expanded 
Fix Image’s logical flow which disposes its image too early, causing errors such as “Cannot clone a disposed image” 
Fix InkRipple doesn’t respect rectCallback when rendering ink cir… 
Fix InputDecorator child vertical alignment 
Fix LayoutExplorer cycle 
Fix Magnifier crash 
Fix Material 3 BottomSheet example 
Fix NPE in coverage collector 
Fix NavigationBar ripple 
Fix NavigationRail highlight (#117320) 
Fix OutlineInputBorder with BorderRadius.zero is distorted 
Fix RangeSlider constructor reference to [value] 
Fix RangeSlider semantics node size 
Fix RenderEditable not able to update backgroundCursorColor when the user provides a new one 
Fix Scaffold setState during locked framework due to open drawer 
Fix ScrollPosition.isScrollingNotifier.value for pointer scrolling 
Fix Scrollbar thumb drag behavior on desktop. 
Fix Slider overlay and value indicator interactive behavior on desktop. 
Fix Slider semantics node size 
Fix SliverPinnedPersistentHeader, also not able to update stretchConfiguration and showOnScreenConfiguration 
Fix SliverScrollingPersistentHeader not able to update stretchConfiguration 
Fix StarBorder operator== 
Fix TabBar with padding is not centered 
Fix TabBarView with no animation not navigating 
Fix Text selection handler disappear when dragged to new words 
Fix TextField/CupertinoTextField hint style overflow not work. 
Fix Tooltip Issue on Switch 
Fix Transporter app name in log after upload 
Fix UiKitView which wrongly unconditionally repaints 
Fix a CupertinoScrollbar NNBD issue 
Fix a type casting error in text_input.dart 
Fix addToScene documentation 
Fix an exception in StarBorders that are scaled to small or infinite sizes 
Fix an issue that Dragging the iOS text selection handles is jumpy and iOS text selection update incorrectly. 
Fix an issue that semantics on TextField is not updated when changing obscureText 
Fix an reorderable list animation issue:”Reversed ReorderableListView drop animation moves item one row higher than it should #110949” 
Fix autocomplete selections 
Fix bar height changes when toggle keyboard 
Fix bug thattimeDilation is not reset, causing subsequent test errors, and add verifications to ensure such problem does not exist in the future 
Fix changing DraggableScrollableSheet controller 
Fix current day not being decorated when it was disabled for picking. 
Fix doc comment line accidentally removed 
Fix documentation for InputDecoration.focusColor 
Fix dragging while the text selection toolbar is up doesn’t hide toolbar 
Fix edge scrolling on platforms that select word by word on long press move 
Fix floatingActionButtonAnimator not being updated 
Fix for Issue #112983 
Fix formatting in BottomAppBar test 
Fix iOS selectWordEdge doesn’t account for affinity 
Fix incorrectly named “debug” prefix 
Fix lerp to eccentric circle. 
Fix logic error in markNeedsPaint 
Fix logical error in TimePickerDialog - the RenderObject forgets to update fields 
Fix macOS migration nothing-to-upgrade test 
Fix menu_anchor_test.dart’s state leak 
Fix null safety error in fuchsia_tester.dart 
Fix outdated comment about overflow 
Fix performance regression. 
Fix references to symbols to use brackets instead of backticks 
Fix scroll jump when NestedScrollPosition is inertia-cancelled. (#116… 
Fix scrollbar margins 
Fix selectWordsInRange when last word is located before the first word 
Fix selection area causes small scrollables to bounce 
Fix shrinkwrap on AnimatedList 
Fix some tap region bugs 
Fix some typos 
Fix spell_check_test 
Fix test in preparation of the Dart VM dropping support for language versions < 2.12.0 
Fix text direction nullability 
Fix text field label animation duration and curve 
Fix that RenderEditable (TextField) ignores offset in painting, making text selections shifted when offset is nonzero 
Fix the TimePicker hour/minute field’s input actions 
Fix todo format 
Fix typo in flutter.gradle 
Fix typo of PrimaryScrollController documentation 
Fix typos introduced typos in popup_menu_theme_test.dart 
Fix wasted memory caused by debug fields - 16 bytes per object (when adding that should-be-removed field crosses double-word alignment) 
Fix –local-engine for the new web/wasm mode 
Fixed an iconTheme lerping problem with ChipThemeData. 
Fixed an issue with FilterChips changing size when selected. 
Fixed label alignment 
Fixed leading button size on app bar 
Fixed one-frame InkWell overlay color problem on unhover 
Fixed some doc typos in OutlinedButton and TextButton.styleFrom deprecations 
Fixed the CircularProgressIndicator default size issue 
Fixed the color curve issue 
Fixed the default color of the trailing widget on app bar 
Fixed the leading IconButton size 
Fixes Text contrast test rect check 
Fixes a NestedScrollView UserScrollNotification issue 
Fixes a bug where dragging a collapsed handle in TextField does not v… 
Fixes issue with sheet reset on rebuild 
Fixing elevation issues with Material 3 
                                                                                      
# Improvements                                                                       
FloatingActionButton: add themeable mouse cursor 
Free library even if proc lookup fails 
Generate syntax for plugin registration that works both with and without null safety. 
Guard against usage after async callbacks in RenderAndroidView, unregister listener 
Handle dragging improvements 
Handle null exception case in ProxiedDevice.stopApp. 
Handle privatecommand messages that pass no data 
Handle updated error message when iOS device is locked 
Hide debug logs from a MemoryAllocations test that intentionally throws an exception 
Hint text semantics to be excluded in a11y read out if textfield is not empty and label text is provided 
ICU Message Syntax Parser 
Ignore NullThrownError deprecation 
Ignore body_might_complete_normally_catch_error violations 
Implement CupertinoListSection and CupertinoListTile 
Implement Material MenuBar and MenuAnchor 
Implements browser context menu in selectable region 
Improve Scrollbar drag behavior 
Improve ShapeDecoration performance. 
Improve coverage speed by using new caching option for package:coverage 
Improve dumpSemanticsTree error when semantics are unavailable 
Improve showSnackBar documentation 
Include initial offset when using PlatformViewSurface 
Include stdout in codesign failure output 
Incorrect rendering of SnapshotWidget 
Increase app minimum supported macOS version from 10.11 to 10.13 
Increase minimum supported macOS version from 10.13 to 10.14 
InkResponse highlights can be updated 
Instrument State, Layer, RenderObject and Element. 
Introduce debugWithActiveLayoutCleared to avoid duplicated code 
Introduce stubbed exclusive parameter to File.create-overridden method 
Isolate platform channels for macos 
Keep dirty manipulations private to Element base class 
Label should always be aligned with text in filled input decoration 
Layer ... was previously used as oldLayer assertion error in debug mode, and page being blank in release mode, caused by LeaderLayer addToScene bug 
Load assets in flutter_test without turning event loop. 
Loupe Android + iOS 
M3 Segmented Button widget 
M3 Text field UI update 
M3 snackbar [re-land] 
Mac Page Up / Page Down in text fields 
Make AndroidApk nullable in stopApp. 
Make Flutter Driver actively wait for runnable isolate 
Make FutureBuilder handle SynchronousFuture correctly, reland SynchronousFuture usage in test assets 
Make Logger required when injected in flutter_tool 
Make TextEditingDelta diagnosticable and override debugFillProperties for concrete TextEditingDelta implementations 
Make ink_sparkle use FragmentShader 
Make module tests pass on Xcode 14 
Make the cursor no longer blinking when move, as same as the effect of iOS platform. 
Makes TextBoundary and its subclasses public 
Manually update DWDS version to v.16.0.0 
Mark NavigationBar as non-const to match reality 
Material 3 navigation drawer 
Menu bar accelerators 
Migrate InputDecorator to Material 3 
Migrate ListTile unselected icon color to Material 3 
Migrate TextField to Material 3 
Migrate flutter_tools to use package:coverage 
Migrate package/flutter to JS static interop. 
Migrated Checkbox to Material 3 - Added Error State 
Migrated Checkbox to Material 3 Colors 
Migrated Switch to Material 3 
Minor change type nullability 
Minor code cleanup: remove redundant return 
Minor fix compendium 
Modify dataMap to include assertiveness only if it’s not set to polite 
Move AnimatedIcons example and fix typo in cupertino/text_selection_toolbar.dart 
Move MagnifierBuilder, MagnifierOverlayInfoBearer from text_selection.dart 
Move Widget Inspector service extensions from DevTools to Flutter 
Normalize examples 
Nth part of async FragmentProgram.fromAsset transition 
Null safety migration of packages/flutter_tools/bin 
Null safety migration of packages/flutter_tools/test/commands.shard/hermetic, part 1/3 
Null safety migration of packages/flutter_tools/test/commands.shard/hermetic, part 2/3 
Null safety migration of packages/flutter_tools/test/commands.shard/hermetic, part 3/3 
Null safety migration of packages/flutter_tools/test/commands.shard/permeable 
Null safety migration of packages/flutter_tools/test/general.shard, part 1/2 
Null safety migration of packages/flutter_tools/test/general.shard, part 2/2 
Null safety migration of packages/flutter_tools/test/web.shard 
Only run pod install on the first iOS build 
Only show iOS simulators, reduce output spew in verbose 
Optimize closure in input_decorator_theme 
Overlay always applies clip 
Override PlaceholderDimensions equality operator to avoid unnecessary TextPainter re-layouts 
Page Up / Page Down in text fields 
Pass device-user in machine mode 
Pass fit property to RenderIndexedStack 
PerformanceOverlay’s multiple fields are not updated when the user wants to update it 
Persistent BottomSheet are not dismissible via a11y 
Plugin FFI template bump ffigen to 6.0.1 
Pointer events: Allow hover events from trackpad 
PointerEvent asserts device kinds 
Preliminary PR for engine changes for Tristate checkboxes 
Prepare the framework for having RRect assert on negative radii 
Prevent committing text from triggering EditableText.onChanged 
Prevent tests from producing dill files alongside the test file 
Provide Material 3 defaults for vanilla Chip widget. 
Provide an option to update Focus semantics under FocusableActionDetector 
Provide more useful error message if a non-compliant DAP tool (or user) sends bad input to DAP server 
Provide test API for accessibility announcements 
Pub dependencies project validator 
Quick Documentation Fix for Sliver 
Re-Land “Refactor StrokeAlign to allow double values.” (#108339) 
Re-Land “Refactor StrokeAlign to allow double values.” (#109591) 
Re-add the ability to return null in ListView.builder 
Re-land Add Spell Check to EditableText 
Read dart_plugin_registrant path from FlutterProject to support non-standard path. 
Refactor Animated[List, Grid, SliverList, SliverGrid] to share common code 
Refactor DeviceManager.findTargetDevices() and FlutterCommand.findAllTargetDevices(), and add a flag to not show prompt. 
Refactor Message class to hold all translations 
Refactor StrokeAlign to allow double values. 
Refactor fix_data.yaml 
Refactor macOS text editing shortcuts 
Reland Added Badge.count constructor 
Reland Cupertino text input padding 
Reland isolate platform channels with conditional compilation 
Reland “Add shadowColor and surfaceTintColor to Dialog and DialogTheme.” 
Reland “Fix DraggableScrollableSheet rebuilding during drag” 
Reland “Keep dirty manipulations private to Element base class (#109401)” 
Reland “Migrate package/flutter to JS static interop. (#111315)” 
Reland “Null safety migration of packages/flutter_tools/bin” 
Reland “Scribble mixin” 
Reland “Single tap on the previous selection should toggle the toolbar on iOS #108913” 
Reland “Update MaterialBanner to support Material 3” 
Reland “Update accessibility contrast test coverage (#109784)” 
Reland “Upgrade Gradle and AGP versions to 7.5/7.2 and migrate benchmarks+examples” 
Reland “Upgrade Gradle and AGP versions to 7.5/7.2 and migrate benchmarks+examples” #108355 
Reland “Upgrade Gradle and AGP versions to 7.5/7.2 and migrate benchmarks+examples” #108472 
Reland “Upgrade targetSdkVersion and compileSdkVersion to 33” 
Reland “[text_input] introduce TextInputControl” 
Reland: Adds support for the Material Badge widget, BadgeTheme, BadgeThemeData (#114560) 
Reland: Fix Android platform view creation flow 
Reland: Set IconButton.visualDensity default to VisualDensity.standard 
Reland: Show output from pub get in flutter pub get 
Reland: Started handling messages from background isolates. 
Reland: “Add example and troubleshooting comment for showSnackBar” 
Reland: “Add outlineVariant and scrim colors to ColorScheme” 
Remerge “Fixed AnimatedSwitcher chain produced duplicates” after fixing issues with g3 
Remove .pub directories from iml templates 
Remove Deprecated RenderUnconstrainedBox 
Remove NavigationToolbar condition that leading widget cannot be larger than 1/3 the total space available. 
Remove RouteSetting.copyWith 
Remove Swift plugin Objective-C files 
Remove controller listener on CupertinoPicker dispose 
Remove deprecated Ruby File.exists? in helper script 
Remove deprecated ScrollBehavior.buildViewportChrome 
Remove deprecated drag anchor 
Remove deprecated updateSemantics API usage. 
Remove dev channel reference from build ios-frameworks error 
Remove doc for –ignore-deprecation and check for pubspec before v1 embedding check 
Remove errant double spaces 
Remove exclamation marks 
Remove no-longer-needed clamping of RRect radii 
Remove outdated Fuchsia concepts 
Remove outdated ignores 
Remove redundant arguments passed to redirecting factory constructors 
Remove shrinkWrap from samples that don’t need it 
Remove some outdated ignores from framework 
Remove the FocusScopeNode in the navigator 
Remove unneeded comparison to double.nan 
Remove unneeded comparison to double.nan 
Remove warnings when UnconstrainedBox and ConstraintsTransformBox are clipped 
Removed references to deprecated styleFrom parameters. 
Removes retries from “dart pub get” and un-buffers its stdout/stderr output 
Replace FocusTrap with TapRegionSurface 
Replace NavigatorObserver._navigator with a static expando. 
Replace _lerpProperties with MaterialStateProperty.lerp in button_style.dart 
Replace empty Container with const SizedBox 
Replace menu defaults with tokens 
Request DartPerformanceMode.latency during transitions 
Reset missing deprecation for ScrollbarThemeData.copyWith(showTrackOnHover) 
Return ErrorHandlingFileSystem backed objects in ErrorHandlingFileSystem file/directory APIs 
Return null rather than fall off nullable onError catchError handler. 
Return void from project migrate() 
Rev package:pub_semver to the latest version 
Revert Ballistic & Clamping simulation updates 
Revert DraggableScrollableSheet controller changes 
Revert file naming convention of .aar files to support fuzzy matching in build.gradle 
Revert isolate platform channels because of google integration tooling 
Revert part of “Terminate simulator app on “q” (#113581)” 
Revert “Add Material 3 support for BottomAppBar” 
Revert “Add Material 3 support for TabBar” 
Revert “Add Spellcheck to EditableText (Android)” 
Revert “Add button semantics in list tile” 
Revert “Add optional flag to determine assertiveness level in aria announcement for flutter web” 
Revert “Add outlineVariant and scrim colors to ColorScheme” 
Revert “Add shadowColor and surfaceTintColor to Dialog and DialogTheme.” 
Revert “Add support for Material 3 Divider and VerticalDivider” 
Revert “Added Badge.count constructor” 
Revert “Adds support for the Material Badge widget, BadgeTheme, BadgeThemeData” 
Revert “Allow Flutter golden file tests to be flaky” 
Revert “Allow setting of TestWidgetsFlutterBinding.pointerEventSource” 
Revert “AutomatedTestWidgetsFlutterBinding.pump provides wrong pump time stamp, probably because of forgetting the precision” 
Revert “Change ClipboardStatusNofifier parameter in buildToolbar to V… 
Revert “Check for watch companion in build settings” 
Revert “Fix Android platform view creation flow” 
Revert “Fix ExpansionTile shows children background when expanded” 
Revert “Fix Scrollbar thumb drag behavior on desktop.” 
Revert “Fix Slider semantics node size” 
Revert “Fix text field label animation duration and curve” 
Revert “Fixed leading button size on app bar” 
Revert “Keep dirty manipulations private to Element base class (#109401)” 
Revert “Load assets in flutter_test without turning event loop.” 
Revert “Migrate package/flutter to JS static interop. (#111315)” 
Revert “Minor change type nullability” 
Revert “Null safety migration of packages/flutter_tools/bin” 
Revert “Overlay always applies clip (#113770)” 
Revert “Re-Land “Refactor StrokeAlign to allow double values.” (#109805)” 
Revert “Read dart_plugin_registrant path from FlutterProject to support non-standard path.” 
Revert “Refactor StrokeAlign to allow double values.” 
Revert “Reland “Scribble mixin”” 
Revert “Reland “Upgrade Gradle and AGP versions to 7.5/7.2 and migrate benchmarks+examples” #108355” 
Revert “Reland “Upgrade Gradle and AGP versions to 7.5/7.2 and migrate benchmarks+examples”” 
Revert “Reland: Set IconButton.visualDensity default to VisualDensity.standard” 
Revert “Scribble mixin” 
Revert “Set IconButton.visualDensity default to VisualDensity.standard” 
Revert “Show output from pub get in flutter pub get” 
Revert “Single tap on the previous selection should toggle the toolbar on iOS…” 
Revert “Started handling messages from background isolates.” 
Revert “Switch the way we retrieve the vm_service_port from /hub to i… 
Revert “Update Cupertino text input padding” 
Revert “Update MaterialBanner to support Material 3” 
Revert “Update SnackBar to support Material 3” 
Revert “Update accessibility contrast test coverage” 
Revert “Upgrade Gradle and AGP versions to 7.5/7.2 and migrate examples/tests” 
Revert “Upgrade targetSdkVersion and compileSdkVersion to 33” 
Revert “Use semantics label for backbutton and closebutton for Android” 
Revert “Use the new pushImageFilter offset parameter to fix the transform of the children” 
Revert “[Fonts] Update icons” 
Revert “[Windows] Use dark title bar on dark system theme” 
Revert “[framework] SliverDecoration” 
Revert “[text_input] introduce TextInputControl” 
Revert “[tool] ⚡️ Install the corresponding APK in flutter run” 
Revert “[tools]validation basic Xcode settings for build ipa” 
Revert “[web] Add --local-web-sdk flag and use precompiled platform kernels for dart2js and ddc” 
Revert “disable new transition while toPictureSync is fixed” 
Revert “iOS 16 context menu” due to theme color mix up 
Roll ios-deploy iOS artifact to arm slice version 
Schedule tasks which are futures to completion 
Scramble order of operations of flutter.gradle 
Scribble mixin 
Scroll inertia cancel [framework] 
Scrollbar respect the NeverScrollableScrollPhysics physics 
Send progress notifications to clients during hot reload / hot restart 
Send text selection rects to engine on iPhone 
Set IconButton.visualDensity default to VisualDensity.standard 
Set Xcode build script phases to always run 
Show Xcode compilation errors at end of build, suppress stdout and stderr from Xcode 
Show output from pub get in flutter pub get 
Simplify mark needs build 
Single tap on the previous selection should toggle the toolbar on iOS… 
SingleChildScrollView does not clip semantics child 
Some changes needed to PlatformMenuBar before the MenuBar implementation change lands. 
Some misc changes needed for MenuBar implementation. 
Some miscellaneous changes found while making another PR 
Started handling messages from background isolates. 
Startup flutter faster (Only access globals.deviceManager if actually setting something) 
Startup flutter faster (faster wrapper script on Windows) 
Startup flutter faster (use app-jit snapshot) 
Stop embedding bitcode for iOS in tool 
Suggest Rosetta when x64 binary cannot be run 
Suggest predicate-based formatter in [FilteringTextInputFormatter] docs for whole string matching 
Support Material 3 in bottom sheet 
Support for FilterQuality in FadeInImage 
Support inputDecoration’s iconColor, prefixIconColor and suffixIconColor 
Support keyboard selection in SelectabledRegion 
Support single arch local engines for ‘build macos-framework’ and ‘ios-framework’ 
Support the –no-devtools flag in “flutter run –machine” 
Switch the way we retrieve the vm_service_port from /hub to iquery, on device. 
Switch the way we retrieve the vm_service_port from /hub to iquery, on device. 
Switched Element.renderObject to iterative implementation. 
TabBar should adjust scroll position when Controller is changed 
Temporarily remove a bogus warning until fixed by dwds update 
Terminate simulator app on “q” 
Terminate simulator app on “q” 
TextPainter throw with stack trace to help track down read-before-layout 
Tighten asset variant detection criteria to only include device-pixel-ratio variants 
Tiny code cleanup: remove unnecessary comparisons 
Tiny improvement of RouteSettings display 
Tooling
Track platform in MigratePlaformConfig and enforce metadata file being provided 
Treat assets as variants only if they share the same filename 
Turn off bitcode in existing iOS Xcode projects 
Typo in Documentation for Restoration with didChangeDependencies 
Typo in border_test.dart 
URI-decode asset paths before writing them to the asset manifest 
Unify analysis options 
Update AnimatedSlide example 
Update Ballistic animation & ClampingScrollSimulation 
Update Chips examples and rename files 
Update CircleAvatar to support Material 3 
Update Cupertino text input padding 
Update CupertinoContextMenu to iOS 16 visuals 
Update InheritedWidget example parameter naming 
Update ListTile and ListTile based widget docs for Material usage 
Update ListTile docs for color animation issues and add example 
Update MaterialBanner to support Material 3 
Update Popup Menu to support Material 3 
Update PopupRoute docs and add an example 
Update Radio button to material 3 
Update SnackBar to support Material 3 
Update TabBarView children after a transition to an adjacent tab 
Update Text field counter error style to material 3 
Update accessibility contrast test coverage 
Update comments in theme data files 
Update docs on ChangeNotifier.dispose and KeepAliveHandle.release 
Update docs to show ImageChunkEvent is an optional param 
Update documentation for PlatformException.stacktrace 
Update equalsIgnoringHashCodes to take a list of Strings 
Update flutter.gradle AGP to 7.2.0 and bump default NDK version 
Update issue reference for skipped hot restart tests 
Update null safety warnings in prep for Dart 3 
Update packages 
Update showCupertinoModalPopup documentation 
Update the documentation of IconButton’s color parameter. 
Update token v0.127 to v0.132 
Update web links for autofill 
Updated ProgressIndicator to M3 
Updated instructions for adding new localized messages. 
Updated the Action chip’s documentation regarding disabled states. 
Updated the M3 textTheme to use onSurface color for all styles. 
Updated the kotlinlang version url. 
Updated tokens to v0.127 
Updated tokens to v0.137. 
Updated tokens to v0.141 
Updated tokens to v0_143. 
Updated useMaterial3 documentation to include missing M3 components. 
Upgrade Gradle and AGP versions to 7.5/7.2 and migrate examples/tests 
Upgrade gradle for flutter tool to 7.3.0 
Upgrade targetSdkVersion and compileSdkVersion to 33 
Use AppBar.systemOverlayStyle to style system navigation bar 
Use FragmentProgram.fromAssetAsync 
Use Isolate.run as implementation for compute 
Use ScrollbarTheme instead Theme for Scrollbar 
Use UriConverter from context for test 
Use concrete factory constructor for DomXMLHttpRequest 
Use correct semantics for toggle buttons 
Use directory exists instead of path.dirname 
Use double.isNaN instead of ... == double.nan (which is always false) 
Use hasNoRemainingExpectations matcher for fake process manager in tool tests 
Use persistent hash map to store _inheritedWidgets 
Use raw fontFamilyFallback values without packages when constructing a merged TextStyle 
Use semantics label for backbutton and closebutton for Android 
Use the new pushImageFilter offset parameter to fix the transform of the children 
Use the new pushImageFilter offset parameter to fix the transform of the children 
Use toPictureSync for faster zoom page transition 
Use tristate checkbox engine changes 
Utility methods for measuring text 
Validate bins on path in doctor 
Wait for non-empty layout in platform view placeholder 
When updating packages, do not delete the simulated SDK directory until all pub invocations have finished 
WidgetController.startGesture trackpad support 
Windows version check in doctor 
Write crash report in temp directory if writing to CWD failed. 
[CP] Fix Snackbar TalkBack regression 
[CP] [flutter_tools] Add remap sampler support (#116861) 
[Dismissible]Fix a state lose issue 
[Docs] Clarify that Flex does not wrap 
[Fonts] Update icons 
[Fonts] Update icons 
[Impeller] Add shader include with FlutterFragCoord for use by FragmentProgram 
[Impeller] Build Impeller iOS runtime stage shaders when Impeller is enabled 
[Keyboard, iOS] Generate iOS’s special key mapping 
[Keyboard] Make CharacterActivator support Ctrl and Meta modifiers, and repeats 
[Material] Remove “down position” from toggleable ripple calculation 
[New Feature]Support mouse wheel event on the scrollbar widget 
[RawKeyboard] Allow inconsistent modifiers for Web 
[RawKeyboard] Allow inconsistent modifiers for iOS and Android 
[RawKeyboard] Fix Linux remapped CapsLock throws 
[Reland] Add Material 3 support for TabBar 
[RenderEditable] report real height when maxLines == 1. 
[SelectionOverlay]Move the debug statement to the scope of the assertion. 
[Windows] Hide app until first frame is drawn 
[Windows] Remove the usage of SETLOCAL ENABLEDELAYEDEXPANSION from bat scripts. 
[Windows] Use dark title bar on dark system theme 
[Windows] Use dark title bar on dark system theme 
[Windows] add generated plugins ignores 
[cleanup] remove unnecessary brace in string interpolation 
[dap] Don’t wait for appStarted before responding to launch/attach + don’t call app.stop for unstarted app 
[docs][FWW] DropdownButton, ScaffoldMessenger, and StatefulBuilder links 
[flutter roll] Revert “Reland “Add shadowColor and surfaceTintColor to Dialog and Di… 
[flutter_driver] make empty duration messages more helpful 
[flutter_driver] support send text input action 
[flutter_test] Add flag to send device pointer events to the framework 
[flutter_test] perf: find.ancestor 
[flutter_tool] Adds –enable-dart-profiling flag 
[flutter_tool] Allow includes relative to shader path 
[flutter_tool] Build shaders as .iplr and use FragmentProgram.fromAsset for ink_sparkle 
[flutter_tool] Don’t download CanvasKit if it’s already in flutter_web_sdk 
[flutter_tool] Include impellerc output in ShaderCompilerException 
[flutter_tools/dap] Add a base Flutter adapter class to avoid duplication between adapters 
[flutter_tools/dap] Add support for forwarding flutter run --machine exposeUrl requests to the DAP client 
[flutter_tools/dap] Map org-dartlang-sdk URIs to the location of the source files found by the analyzer 
[flutter_tools] Add flutter update-packages –synthetic-package-path 
[flutter_tools] Add support for compiling shaders to JSON bundle for web 
[flutter_tools] Add –dump-info, –no-frequency-based-minification flags 
[flutter_tools] Adds test of impellerc output file mode 
[flutter_tools] Catch more general XmlException rather than XmlParserException 
[flutter_tools] Decouple fatal-warnings check from fatal-infos 
[flutter_tools] Enable custom devices on all channels 
[flutter_tools] Fix _CastError in HotRunner._resetDirtyAssets 
[flutter_tools] Fix null check errors in attach command 
[flutter_tools] Fix race condition with completer in devfs_web 
[flutter_tools] Fix so that the value set by --dart-define-from-file can be passed to Gradle 
[flutter_tools] Fix tool crash for map cast 
[flutter_tools] Fix type error in ChromiumDevice.startApp 
[flutter_tools] Forward app.webLaunchUrl event from Flutter to DAP clients 
[flutter_tools] Generate Localizations on flutter run for web 
[flutter_tools] Implement NotifyingLogger.supportsColor 
[flutter_tools] Instantiate shutdown hooks before localfilesystem 
[flutter_tools] Introducing arg option for specifying the output directory for web 
[flutter_tools] Make android gradle builder test hermetic 
[flutter_tools] Make flutter test -v print timing of different phases 
[flutter_tools] Migrate commands.shard/hermetic/doctor_test to null-safety and make hermetic 
[flutter_tools] Migrate more tool tests to null-safety 
[flutter_tools] Pin package:archive and manual roll 
[flutter_tools] Pin path_provider_android 
[flutter_tools] Pin url_launcher_android and update packages 
[flutter_tools] Pull more arm64 artifacts on Apple Silicon 
[flutter_tools] Remove more shuffles 
[flutter_tools] Remove shuffle from doctor test 
[flutter_tools] Remove unused parameter when connecting DAP to VM Service 
[flutter_tools] Replace android v2 embedding broken doc link 
[flutter_tools] Suggest actions to fix failing FlutterValidator 
[flutter_tools] Test that DAP process terminates at the end of a session 
[flutter_tools] [dap] Add support for passing env variables to spawned processes 
[flutter_tools] [dap] Ensure DAP sends app.stop/app.detach during terminate 
[flutter_tools] add compilation failure tests for new cases added in impellerc 
[flutter_tools] add debug trace when compiling dart2js 
[flutter_tools] add deprecation message for “flutter format” 
[flutter_tools] add more debugging when pub get fails 
[flutter_tools] add test debugging for #111272 
[flutter_tools] add tool support for shader hot reload 
[flutter_tools] add uint compilation test 
[flutter_tools] allow flutter drive to take screenshots when sent a terminating signal 
[flutter_tools] analyze –suggestions –machine command 
[flutter_tools] cache more directories 
[flutter_tools] change the way version is calculated on master 
[flutter_tools] disable web compilation of shaders 
[flutter_tools] dont include material shaders in web builds (#116538) 
[flutter_tools] ensure setAssetDirectory uses windows path 
[flutter_tools] filter “Resolving dependencies…” from dart pub get output to fix test flakiness 
[flutter_tools] fix AndroidSdk.reinitialize bad state error 
[flutter_tools] fix RangeError in gen-l10n by checking for empty string 
[flutter_tools] join flutter specific with home cache 
[flutter_tools] migrate clean_test to null-safety 
[flutter_tools] migrate gradle errors and project test to null safety 
[flutter_tools] migrate some files to null safety 
[flutter_tools] normalize windows file path cases in flutter validator 
[flutter_tools] provide –timeout option to flutter drive 
[flutter_tools] reduce doctor timeout to debug 111686 
[flutter_tools] refactor stringsArg 
[flutter_tools] remove all body_might_complete_normally_catch_error ignores 
[flutter_tools] support github reporter 
[flutter_tools] support hot reload of font assets 
[flutter_tools] unpin path_provider_android and roll 
[flutter_tools] use absolute path for shader lib 
[framework] Animatable.fromCallback and code snippet 
[framework] SliverDecoration 
[framework] add ignores for platformDispatcher deprecation 
[framework] avoid compositing with visibility 
[framework] create animation from value listenable 
[framework] document backdropfilter antipattern 
[framework] load files through ImmutableBuffer.fromFilePath (if exact file type) 
[framework] re-rasterize page transition when layout size changes 
[framework] re-rasterize when window size or insets changes 
[framework] remove restriction on texture layer rasterization 
[framework] revert removal of opacity 
[framework] simplify raster widget, rename, combine painters 
[framework] use Visibility instead of Opacity 
[framework] work around to load self packages from packages/ 
[gen_l10n] Add option to format generated localizations files 
[gen_l10n] Improvements to gen_l10n 
[gen_l10n] Throw error when arb file does not exist 
[gen_l10n] Warn users when placeholder types are converted to ‘num’ when using pluralization 
[iOS] Update template icons 
[macOS] Flavors project throws no flavor specified for creating a project. 
[macOS] Use editing intents from engine 
[text_input] introduce TextInputControl 
[tool] Fix flutter.js regression with hot-reload on promise-based init. 
[tool] Install the corresponding APK in flutter run 
[tool] Proposal to support dart define config from a json file 
[tool] Support --flavor option for flutter install. 
[tool] ⚡️ Install the corresponding APK in flutter run 
[tools] Fix plugin_ffi template lint violation 
[tools]build ipa validate app icon size 
[tools]build ipa validate template icon files 
[tools]reland validation basic Xcode settings for build ipa 
[tools]validation basic Xcode settings for build ipa 
[web] Add --local-web-sdk flag and use precompiled platform kernels for dart2js and ddc 
[web] Add onEntrypointLoaded to FlutterLoader. 
[web] Changes to web keyboard selection shortcuts for more consistent behavior 
[web] Fix kIsWeb for Dart2wasm. 
[web] Migrate selectable_region to static interop. 
[web] Use TrustedTypes in flutter.js and other tools 
[web] define $flutterDriverResult variable early in driver test initalization 
[web] fix hot restart in entrypoint generated by flutter create 
[web] skip flaky date picker golden tests 
[web] skip more perspective text tests 
[web][debug] Remove RequireJS timeouts for debug builds. 

                                                                                      
                                                                                      
                                                                                      
check for pubspec instead of lib/ 
chore: enable Flutter Android workflow on aarch64 
disable new transition while toPictureSync is fixed 
enable combinators_ordering 
error handling when path to dir provided instead of file 
feat: [InteractiveViewer] provide a way to set the initial child’s alignment 
fix GestureDetector.onDoubleTapDown not getting called 
fix a CupertinoDatePicker bug 
fix a draggableScrollableSheet’s LocalHistoryEntry leaking 
fix a tabs indicator padding update bug 
fix flutter not finding custom device 
fix for flakey analyze test 
fix noop toString() diagnostics 
fix null safe check in RenderIndexedStack 
fix overflow error in CupertinoListTile 
fix permanent choice chip icon with material3 
fix some DSS bugs 
fix stretch effect with rtl support 
fix: bottom navigation bar colors 
fix: removed Widget type from child parameter in OutlinedButton 
fixed inconsistent file names for *_chip.dart files and added a test 
fixes FadeInImage for an edge case 
fixes for incoming linter 
flutter update-packages –force-upgrade + analyzer fix 
hintText TextOverflow 
iOS 16 context menu 
improve debugging when dart pub get call fails 
labeledTapTargetGuideline should passe if textfield does not have label 
let the plugin’s output generated in flutter/.android/plugins_build_output/${androidPlugin.name} 
link “iOS PlatformView BackdropFilter design doc” in the BackdropFilter widget’s documentation 
make ModalBottomSheetRoute public 
panningDirection parameter added to InteractiveViewer 
pushnamed can handle Object as type 
refactor: strip all local symbols from macOS and iOS App.framework - reduces app size 
remove passing –debugger-module-names to frontend server 
removing default values for [reporter] and [timeout] in flutter test 
shader warm up with canvaskit and corresponding test 
typo 
ui.PointerSignalKind forwards compatibility for scale 
unnecessary_stateful_widgets 
updateEditingValueWithDeltas should fail loudly when TextRange is invalid 
updateSemantics in TestWindow should always be implemented. 
use super parameters in framework 
when getting xcworkspace, exclude hidden files 
“Select All” Automatically scrolls EditableText to the end of the text field, which doesn’t happen on native iOS 
🎨 Improve exceptions thrown by asset bundle 
                                                                                      
                                                                                      
107866: Add support for verifying SemanticsNode ordering in widget tests 
109638: Windows framework_tests_misc is 2.06% flaky 
110598: expect() in semantic test producing unhelpful output 
