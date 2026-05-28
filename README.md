## Issue

With Capacitor Plugins but no cordova plugin the iOS SPM app cannot resolve the dependencies due to a duplicated comma. Running `xcodebuild -resolvePackageDependencies -project ios/App/App.xcodeproj` highlights the error:

```
capacitor-alpha9-spm/ios/App/CapApp-SPM/Package.swift:22:76: error: expected expression in container literal
20 |             name: "CapApp-SPM",
21 |             dependencies: [
22 |                 .product(name: "Capacitor", package: "capacitor-swift-pm"),,
   |                                                                            `- error: expected expression in container literal
23 |                 .product(name: "CapacitorDialog", package: "CapacitorDialog"),
24 |                 .product(name: "CapacitorNetwork", package: "CapacitorNetwork")
```

## Created with Capacitor Create App

This app was created using [`@capacitor/create-app`](https://github.com/ionic-team/create-capacitor-app),
and comes with a very minimal shell for building an app.

### Running this example

To run the provided example, you can use `npm start` command.

```bash
npm start
```
