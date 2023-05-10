# Flutter Open Store

😎 Simple flutter package to open app page in store
😍 Without native platform code

## Getting Started

### Add dependency

   ```
   dependencies:
  open_store: ^0.4.0
   ```

### Add import package

   ```
   import 'package:open_store/open_store.dart';
   ```

### Easy to use

Add method calling when you need open app page in store

   ```
   OpenStore.instance.open(
        appStoreId: '284815942', // AppStore id of your app for iOS
        appStoreIdMacOS: '284815942', // AppStore id of your app for MacOS (appStoreId used as default)
        androidAppBundleId: 'com.google.android.googlequicksearchbox', // Android app bundle package name
        windowsProductId: '9NZTWSQNTD0S' // Microsoft store id for Widnows apps
    );
   ```


