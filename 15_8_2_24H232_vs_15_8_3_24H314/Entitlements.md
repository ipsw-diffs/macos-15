## 🔑 Entitlements

### filesystem

### com.apple.DFRSystemExtra.ScreenLock

> `/System/Library/CoreServices/ControlStrip.app/Contents/XPCServices/com.apple.DFRSystemExtra.ScreenLock.xpc/Contents/MacOS/com.apple.DFRSystemExtra.ScreenLock`

```diff

 	<array>
 		<string>com.apple.system.screen-lock</string>
 	</array>
-	<key>com.apple.private.sessionagent.spi</key>
-	<true/>
 </dict>
 </plist>
 

```
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
### loginwindow

> `/System/Library/CoreServices/loginwindow.app/Contents/MacOS/loginwindow`

```diff

 	<true/>
 	<key>com.apple.private.security.storage.universalaccess</key>
 	<true/>
-	<key>com.apple.private.securityd.keychain-master-key-extraction</key>
-	<true/>
 	<key>com.apple.private.securityd.stash</key>
 	<true/>
 	<key>com.apple.private.sessionagent.sessionowner</key>
 	<true/>
-	<key>com.apple.private.sessionagent.spi</key>
-	<true/>
 	<key>com.apple.private.sessionmanager</key>
 	<true/>
 	<key>com.apple.private.sharing.unlock-manager</key>

```


