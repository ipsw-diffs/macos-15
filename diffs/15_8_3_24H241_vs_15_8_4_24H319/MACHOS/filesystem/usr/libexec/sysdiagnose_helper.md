## sysdiagnose_helper

> `/usr/libexec/sysdiagnose_helper`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1438.140.5.0.0
-  __TEXT.__text: 0x3f464
+1438.140.5.700.1
+  __TEXT.__text: 0x3f5bc
   __TEXT.__auth_stubs: 0xdb0
-  __TEXT.__objc_stubs: 0x19c0
+  __TEXT.__objc_stubs: 0x1a20
   __TEXT.__objc_methlist: 0x738
   __TEXT.__const: 0x3a8
-  __TEXT.__cstring: 0x43e9b
-  __TEXT.__objc_methname: 0x1b35
+  __TEXT.__cstring: 0x43ebd
+  __TEXT.__objc_methname: 0x1b6c
   __TEXT.__oslogstring: 0x2243
   __TEXT.__objc_classname: 0x132
   __TEXT.__objc_methtype: 0x51b

   __DATA_CONST.__got: 0x208
   __DATA_CONST.__auth_ptr: 0x78
   __DATA_CONST.__const: 0x680
-  __DATA_CONST.__cfstring: 0x1880
+  __DATA_CONST.__cfstring: 0x18e0
   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__objc_intobj: 0x48
   __DATA.__objc_const: 0x958
-  __DATA.__objc_selrefs: 0x7e8
+  __DATA.__objc_selrefs: 0x800
   __DATA.__objc_ivar: 0x38
   __DATA.__objc_data: 0x230
   __DATA.__data: 0x1838

   - /usr/lib/libtailspin.dylib
   - /usr/lib/libtzupdate.dylib
   - @rpath/CoreRepairCore.framework/Versions/A/CoreRepairCore
-  Functions: 348
+  Functions: 349
   Symbols:   295
-  CStrings:  5422
+  CStrings:  5428
 
CStrings:
+ "/.nofollow"
+ "/.nofollow/"
+ "/.resolve/"
+ "hasPrefix:"
+ "isAbsolutePath"
+ "rangeOfString:options:range:"
```
