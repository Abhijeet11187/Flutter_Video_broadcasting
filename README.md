# Issue

Application does not run in debug mode

## How to Resolve issue ?

### create proguard-rules.pro  in the andriod/app
#Flutter Wrapper<br />
-keep class io.agora.**{*;} <br />
-keep class io.flutter.app.** { *; } <br />
-keep class io.flutter.plugin.**  { *; } <br />
-keep class io.flutter.util.**  { *; }<br />
-keep class io.flutter.view.**  { *; }<br />
-keep class io.flutter.**  { *; }<br />
-keep class io.flutter.plugins.**  { *; }<br />
