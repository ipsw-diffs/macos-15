## com.apple.Notes.QuickLookExtension

> `/System/Applications/Notes.app/Contents/PlugIns/com.apple.Notes.QuickLookExtension.appex/Contents/MacOS/com.apple.Notes.QuickLookExtension`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2998.63.0.2.0
-  __TEXT.__text: 0x8eae0
-  __TEXT.__auth_stubs: 0x18e0
-  __TEXT.__objc_stubs: 0x2860
+2998.63.0.3.0
+  __TEXT.__text: 0x8ece0
+  __TEXT.__auth_stubs: 0x1920
+  __TEXT.__objc_stubs: 0x28e0
   __TEXT.__objc_methlist: 0xf04
-  __TEXT.__objc_methname: 0x48d9
+  __TEXT.__objc_methname: 0x493a
   __TEXT.__objc_classname: 0x17c
   __TEXT.__objc_methtype: 0xddd
   __TEXT.__cstring: 0x1fb2

   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__unwind_info: 0x1a98
   __TEXT.__eh_frame: 0x2a38
-  __DATA_CONST.__auth_got: 0xc80
-  __DATA_CONST.__got: 0x728
-  __DATA_CONST.__auth_ptr: 0x4d8
-  __DATA_CONST.__const: 0x39d8
+  __DATA_CONST.__auth_got: 0xca0
+  __DATA_CONST.__got: 0x738
+  __DATA_CONST.__auth_ptr: 0x4e8
+  __DATA_CONST.__const: 0x3a08
   __DATA_CONST.__cfstring: 0x620
   __DATA_CONST.__objc_classlist: 0x78
   __DATA_CONST.__objc_catlist: 0x58

   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x30
   __DATA.__objc_const: 0x1a10
-  __DATA.__objc_selrefs: 0x1788
+  __DATA.__objc_selrefs: 0x17a8
   __DATA.__objc_ivar: 0x40
   __DATA.__objc_data: 0x758
   __DATA.__data: 0x2218

   - /System/Library/Frameworks/Quartz.framework/Versions/A/Quartz
   - /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
   - /System/Library/Frameworks/QuickLook.framework/Versions/A/QuickLook
+  - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/Frameworks/VisionKit.framework/Versions/A/VisionKit
   - /System/Library/Frameworks/WebKit.framework/Versions/A/WebKit
   - /System/Library/PrivateFrameworks/FeatureFlags.framework/Versions/A/FeatureFlags

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2269
-  Symbols:   307
-  CStrings:  1240
+  Functions: 2271
+  Symbols:   313
+  CStrings:  1244
 
Symbols:
+ _CFRelease
+ _NSExtensionErrorDomain
+ _SecTaskCreateWithAuditToken
+ _SecTaskGetCodeSignStatus
+ _kCFAllocatorDefault
+ _objc_retainBlock
CStrings:
+ "_extensionHostAuditToken"
+ "cancelRequestWithError:"
+ "errorWithDomain:code:userInfo:"
+ "extensionContext"
```
