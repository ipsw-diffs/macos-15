## lsregister

> `/System/Library/Frameworks/CoreServices.framework/Versions/Current/Frameworks/LaunchServices.framework/Versions/Current/Support/lsregister`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA.__objc_classrefs`
- `__DATA.__data`

```diff

-1378.19.3.3.0
-  __TEXT.__text: 0x49a0
-  __TEXT.__auth_stubs: 0x630
-  __TEXT.__objc_stubs: 0x4c0
+1378.19.3.4.0
+  __TEXT.__text: 0x4644
+  __TEXT.__auth_stubs: 0x610
+  __TEXT.__objc_stubs: 0x400
   __TEXT.__const: 0x158
-  __TEXT.__gcc_except_tab: 0x494
-  __TEXT.__cstring: 0xd06
-  __TEXT.__oslogstring: 0x1c1
+  __TEXT.__gcc_except_tab: 0x3fc
+  __TEXT.__cstring: 0xc4f
+  __TEXT.__oslogstring: 0x19e
   __TEXT.__objc_classname: 0x1
-  __TEXT.__objc_methname: 0x348
-  __TEXT.__unwind_info: 0x168
-  __DATA_CONST.__auth_got: 0x328
+  __TEXT.__objc_methname: 0x2ed
+  __TEXT.__unwind_info: 0x160
+  __DATA_CONST.__auth_got: 0x318
   __DATA_CONST.__got: 0xa8
   __DATA_CONST.__const: 0x1b0
-  __DATA_CONST.__cfstring: 0x2e0
+  __DATA_CONST.__cfstring: 0x2c0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA.__objc_selrefs: 0x130
+  __DATA.__objc_selrefs: 0x100
   __DATA.__objc_classrefs: 0x40
   __DATA.__data: 0x8
   __DATA.__bss: 0x68

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 61
-  Symbols:   134
-  CStrings:  131
+  Functions: 60
+  Symbols:   132
+  CStrings:  120
 
Symbols:
- __LSExtensionsLog
- __LSRegisterPlatformFrameworkExtensionPointInfo
Functions:
~ sub_100000be0 : 80 -> 7584
- sub_100000c30
CStrings:
- "%s Registering extension point: %@"
- "SDKDictionary"
- "URL: `%@`"
- "extensionPointDefinitionEnumerator"
- "identifier"
- "int LSRegisterMain(int, const char **)"
- "lsregister: error %d registering Extension Point: `%s` platform: %d %s\n"
- "lsregister: registered Extension Point: `%s` platform: %d %s\n"
- "platform"
- "stringWithFormat:"
- "url"
```
