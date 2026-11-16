## 🔑 Entitlements

### filesystem

### NotificationCenter

> `/System/Library/CoreServices/NotificationCenter.app/Contents/MacOS/NotificationCenter`

```diff

 		<string>kTCCServiceSystemPolicyAppBundles</string>
 		<string>kTCCServiceSystemPolicyAppData</string>
 	</array>
+	<key>com.apple.private.usernotifications.content-extension-host</key>
+	<true/>
 	<key>com.apple.private.usernotifications.forwarding</key>
 	<true/>
 	<key>com.apple.private.windowmanager</key>

```
### mobiletimerd

> `/System/Library/PrivateFrameworks/MobileTimer.framework/Executables/mobiletimerd`

```diff

 <?xml version="1.0" encoding="UTF-8"?>
 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
-<dict>
-	<key>application-identifier</key>
-	<string>com.apple.mobiletimerd</string>
-	<key>aps-environment</key>
-	<string>development</string>
-	<key>com.apple.chrono.invalidate-timelines</key>
-	<true/>
-	<key>com.apple.chronoservices</key>
-	<true/>
-	<key>com.apple.coreduetd.allow</key>
-	<true/>
-	<key>com.apple.coreduetd.context</key>
-	<true/>
-	<key>com.apple.developer.ubiquity-container-identifiers</key>
-	<string></string>
-	<key>com.apple.healthlite.spi.sleepTracker</key>
-	<true/>
-	<key>com.apple.locationd.activity</key>
-	<true/>
-	<key>com.apple.nano.nanoregistry.generalaccess</key>
-	<true/>
-	<key>com.apple.private.ClockAngel.client</key>
-	<true/>
-	<key>com.apple.private.activitykit.ephemeralActivityRequester</key>
-	<true/>
-	<key>com.apple.private.activitykit.unboundedActivityRequester</key>
-	<true/>
-	<key>com.apple.private.biome.read-write</key>
-	<array>
-		<string>Alarm</string>
-	</array>
-	<key>com.apple.private.corespotlight.internal</key>
-	<true/>
-	<key>com.apple.private.donotdisturb.mode.assertion.client-identifiers</key>
-	<array>
-		<string>com.apple.mobiletimer.bedtime-mode</string>
-	</array>
-	<key>com.apple.private.healthkit</key>
-	<true/>
-	<key>com.apple.private.healthkit.authorization_bypass</key>
-	<true/>
-	<key>com.apple.private.healthkit.feature-availability.read-write</key>
-	<array>
-		<string>SleepCoaching</string>
-	</array>
-	<key>com.apple.private.healthkit.source.identities</key>
-	<array>
-		<string>com.apple.mobiletimer</string>
-		<string>com.apple.private.health.localdevice</string>
-	</array>
-	<key>com.apple.private.ids.messaging</key>
-	<array>
-		<string>com.apple.private.alloy.mobiletimersync</string>
-	</array>
-	<key>com.apple.private.mobileinstall.allowedSPI</key>
-	<array>
-		<string>WaitForSystemAppMigrationToComplete</string>
-	</array>
-	<key>com.apple.private.sessionkit.custom-platter-target</key>
-	<true/>
-	<key>com.apple.private.sessionkit.customPushProcessIdentifier</key>
-	<true/>
-	<key>com.apple.private.sessionkit.permitMultipleProcessInputs</key>
-	<true/>
-	<key>com.apple.private.sessionkit.sessionRequest</key>
-	<true/>
-	<key>com.apple.private.sleepd</key>
-	<true/>
-	<key>com.apple.private.usernotifications.bundle-identifiers</key>
-	<array>
-		<string>com.apple.mobiletimer</string>
-		<string>com.apple.NanoAlarm</string>
-		<string>com.apple.private.NanoTimer</string>
-		<string>com.apple.clock</string>
-	</array>
-	<key>com.apple.security.exception.mach-lookup.global-name</key>
-	<array>
-		<string>com.apple.chronoservices</string>
-		<string>com.apple.sessionservices</string>
-		<string>com.apple.ClockAngel.mach</string>
-	</array>
-	<key>com.apple.telephonyutilities.callservicesd</key>
-	<array>
-		<string>access-calls</string>
-	</array>
-</dict>
+<dict/>
 </plist>
 

```
### com.apple.StreamingUnzipService.privileged

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/A/XPCServices/com.apple.StreamingUnzipService.privileged.xpc/Contents/MacOS/com.apple.StreamingUnzipService.privileged`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.quarantine.control</key>
+	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>
 	<string>StreamingUnzipService</string>
 	<key>com.apple.rootless.storage.MobileAssetDownload</key>

```
### com.apple.StreamingUnzipService

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/A/XPCServices/com.apple.StreamingUnzipService.xpc/Contents/MacOS/com.apple.StreamingUnzipService`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.quarantine.control</key>
+	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>
 	<string>StreamingUnzipService</string>
 </dict>

```
### com.apple.StreamingUnzipService.privileged

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/Current/XPCServices/com.apple.StreamingUnzipService.privileged.xpc/Contents/MacOS/com.apple.StreamingUnzipService.privileged`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.quarantine.control</key>
+	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>
 	<string>StreamingUnzipService</string>
 	<key>com.apple.rootless.storage.MobileAssetDownload</key>

```
### com.apple.StreamingUnzipService

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/Current/XPCServices/com.apple.StreamingUnzipService.xpc/Contents/MacOS/com.apple.StreamingUnzipService`

```diff

 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
+	<key>com.apple.private.quarantine.control</key>
+	<true/>
 	<key>com.apple.private.sandbox.profile:embedded</key>
 	<string>StreamingUnzipService</string>
 </dict>

```
### bird

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Versions/A/Support/bird`

```diff

 	<true/>
 	<key>com.apple.private.foundation.fileprovideridentifier</key>
 	<string>com.apple.bird</string>
+	<key>com.apple.private.genstore.icd-fpfs-migration</key>
+	<true/>
 	<key>com.apple.private.iaaccounts</key>
 	<true/>
 	<key>com.apple.private.kernel.global-proc-info</key>

```
### tmdiagnose

> `/usr/bin/tmdiagnose`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.private.backupd.session</key>
+	<string>tmdiagnose</string>
+</dict>
+</plist>
 

```


