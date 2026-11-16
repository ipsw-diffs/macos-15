## LaunchServices

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/LaunchServices.framework/Versions/A/LaunchServices`

```diff

-1378.19.3.3.0
-  __TEXT.__text: 0x2243f0
+1378.19.3.4.0
+  __TEXT.__text: 0x2235d8
   __TEXT.__auth_stubs: 0x3f10
-  __TEXT.__objc_methlist: 0xd11c
+  __TEXT.__objc_methlist: 0xd0ec
   __TEXT.__const: 0x9f0
-  __TEXT.__cstring: 0x28519
-  __TEXT.__oslogstring: 0x1cb1c
-  __TEXT.__gcc_except_tab: 0x2f770
+  __TEXT.__cstring: 0x283e7
+  __TEXT.__oslogstring: 0x1cb4e
+  __TEXT.__gcc_except_tab: 0x2f620
   __TEXT.__ustring: 0x1be
   __TEXT.__dof_LSFSNode: 0x2b6
-  __TEXT.__unwind_info: 0xc5d8
+  __TEXT.__unwind_info: 0xc578
   __TEXT.__eh_frame: 0x60
   __TEXT.__objc_classname: 0x1e06
-  __TEXT.__objc_methname: 0x1d891
-  __TEXT.__objc_methtype: 0xa42e
-  __TEXT.__objc_stubs: 0x10380
+  __TEXT.__objc_methname: 0x1d7f6
+  __TEXT.__objc_methtype: 0xa37b
+  __TEXT.__objc_stubs: 0x10340
   __DATA_CONST.__got: 0xcc8
   __DATA_CONST.__const: 0x3960
   __DATA_CONST.__objc_classlist: 0x660
   __DATA_CONST.__objc_catlist: 0x60
   __DATA_CONST.__objc_protolist: 0x158
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x63b8
+  __DATA_CONST.__objc_selrefs: 0x63a8
   __DATA_CONST.__objc_protorefs: 0xa0
   __DATA_CONST.__objc_superrefs: 0x518
   __DATA_CONST.__objc_arraydata: 0x230
   __AUTH_CONST.__auth_got: 0x1fa0
-  __AUTH_CONST.__const: 0x9968
-  __AUTH_CONST.__cfstring: 0x1b960
-  __AUTH_CONST.__objc_const: 0x13518
+  __AUTH_CONST.__const: 0x9908
+  __AUTH_CONST.__cfstring: 0x1b920
+  __AUTH_CONST.__objc_const: 0x13508
   __AUTH_CONST.__objc_intobj: 0x738
   __AUTH_CONST.__objc_arrayobj: 0x120
   __AUTH_CONST.__objc_dictobj: 0x118

   - /usr/lib/liboah.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 9779
-  Symbols:   16810
-  CStrings:  12058
+  Functions: 9769
+  Symbols:   16796
+  CStrings:  12047
 
Symbols:
+ GCC_except_table148
- -[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]
- -[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]
- __LSRegisterExtensionPointClient
- __LSUnregisterExtensionPoint
- __LSUnregisterExtensionPointClient
- ___101-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]_block_invoke
- ___92-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]_block_invoke
- ____LSRegisterExtensionPointClient_block_invoke
- ____LSRegisterExtensionPointClient_block_invoke_2
- ____LSUnregisterExtensionPointClient_block_invoke
- ____LSUnregisterExtensionPointClient_block_invoke_2
- ___block_descriptor_64_ea8_32s40s48bs_e42_v24?0"LSDBExecutionContext"8"NSError"16l
- ___block_descriptor_68_ea8_32s40s48s56bs_e42_v24?0"LSDBExecutionContext"8"NSError"16l
- _objc_msgSend$registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:
- _objc_msgSend$unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/TemplateApplications/LSTemplateApplicationCreation.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/TemplateApplications/LSTemplateApplicationLaunch.mm"
+ "cannot register extension points from a LS client"
+ "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1355:63)]"
+ "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1386:65)]"
+ "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1393:65)]"
+ "static id LaunchServices::PrefsStorage::_GetValueInPrefsArrayWithPredicate(NSArray *__strong, __unsafe_unretained Class, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1386:65)]"
+ "static id LaunchServices::PrefsStorage::_GetValueInPrefsArrayWithPredicate(NSArray *__strong, __unsafe_unretained Class, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1393:65)]"
- "-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]"
- "-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]_block_invoke"
- "-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]"
- "-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]_block_invoke"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/TemplateApplications/LSTemplateApplicationCreation.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/TemplateApplications/LSTemplateApplicationLaunch.mm"
- "invalid extensionPoint SDK dictionary"
- "invalid extensionPoint identifier"
- "registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:"
- "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1355:63)]"
- "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1386:65)]"
- "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1393:65)]"
- "static id LaunchServices::PrefsStorage::_GetValueInPrefsArrayWithPredicate(NSArray *__strong, __unsafe_unretained Class, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1386:65)]"
- "static id LaunchServices::PrefsStorage::_GetValueInPrefsArrayWithPredicate(NSArray *__strong, __unsafe_unretained Class, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1393:65)]"
- "unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:"
- "v48@0:8@\"NSString\"16I24@\"NSString\"28I36@?<v@?B@\"NSError\">40"
- "v48@0:8@16I24@28I36@?40"
- "v52@0:8@\"NSString\"16I24@\"NSURL\"28@\"NSDictionary\"36@?<v@?B@\"NSError\">44"
- "v52@0:8@16I24@28@36@?44"
```
