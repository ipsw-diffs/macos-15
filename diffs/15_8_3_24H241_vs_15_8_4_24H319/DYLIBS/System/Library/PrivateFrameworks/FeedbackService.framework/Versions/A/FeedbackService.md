## FeedbackService

> `/System/Library/PrivateFrameworks/FeedbackService.framework/Versions/A/FeedbackService`

```diff

-150.16.0.0.0
-  __TEXT.__text: 0x82e10
+150.16.1.0.0
+  __TEXT.__text: 0x82e80
   __TEXT.__auth_stubs: 0x13d0
   __TEXT.__objc_methlist: 0x1104
   __TEXT.__const: 0xa2e4
   __TEXT.__cstring: 0x30b8
   __TEXT.__ustring: 0xd8
-  __TEXT.__oslogstring: 0xcef
+  __TEXT.__oslogstring: 0xd1f
   __TEXT.__gcc_except_tab: 0x10c
   __TEXT.__constg_swiftt: 0x20ec
   __TEXT.__swift5_typeref: 0x2580

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3581
+  Functions: 3582
   Symbols:   1957
-  CStrings:  976
+  CStrings:  977
 
Functions:
~ +[FBKSSharedConstants appleSeedURLFromDefaults:withEnvironment:] : 368 -> 340
~ +[FBKSSharedConstants environment] : 132 -> 152
~ +[FBKSSharedConstants overrideEnvironment:host:] : 280 -> 332
+ +[FBKSSharedConstants overrideEnvironment:host:].cold.1
CStrings:
+ "Ignoring environment override on non-internal build"
```
