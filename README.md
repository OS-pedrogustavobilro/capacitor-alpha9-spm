## Crash

Without a cordova plugin the iOS SPM app crashes on opening

```
Library not loaded: @rpath/Cordova.framework/Cordova
  Referenced from: <8D13AE37-5ABE-3673-9D6D-E20EF9EF3B08> /private/var/containers/Bundle/Application/0346EA7B-282A-4ADA-A0C8-31BBE777EA8E/App.app/Frameworks/Capacitor.framework/Capacitor
  Reason: tried: '/usr/lib/swift/Cordova.framework/Cordova' (no such file, not in dyld cache), '/private/preboot/Cryptexes/OS/usr/lib/swift/Cordova.framework/Cordova' (no such file), '/private/var/containers/Bundle/Application/0346EA7B-282A-4ADA-A0C8-31BBE777EA8E/App.app/Frameworks/Cordova.framework/Cordova' (no such file), '/private/var/containers/Bundle/Application/0346EA7B-282A-4ADA-A0C8-31BBE777EA8E/App.app/Frameworks/Capacitor.framework/Frameworks/Cordova.framework/Cordova' (no such file), '/usr/lib/swift/Cordova.framework/Cordova' (no such file, not in dyld cache), '/private/preboot/Cryptexes/OS/usr/lib/swift/Cordova.framework/Cordova' (no such file), '/Users/(username)/Library/Developer/Xcode/DerivedData/App-hkgfjywqypezxtfqhpccpanyslng/Build/Products/Debug-iphoneos
dyld config: DYLD_LIBRARY_PATH=/usr/lib/system/introspection DYLD_INSERT_LIBRARIES=/usr/lib/libLogRedirect.dylib:/usr/lib/libBacktraceRecording.dylib:/usr/lib/libMainThreadChecker.dylib:/usr/lib/libRPAC.dylib:/usr/lib/libViewDebuggerSupport.dylib
```

## Created with Capacitor Create App

This app was created using [`@capacitor/create-app`](https://github.com/ionic-team/create-capacitor-app),
and comes with a very minimal shell for building an app.

### Running this example

To run the provided example, you can use `npm start` command.

```bash
npm start
```
