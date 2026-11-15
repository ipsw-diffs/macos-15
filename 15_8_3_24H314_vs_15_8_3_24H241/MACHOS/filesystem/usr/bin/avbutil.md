## avbutil

> `/usr/bin/avbutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1350.2.0.0.0
-  __TEXT.__text: 0x1549c
+1320.3.0.0.0
+  __TEXT.__text: 0x1548c
   __TEXT.__auth_stubs: 0x2e0
-  __TEXT.__objc_stubs: 0x1780
+  __TEXT.__objc_stubs: 0x1760
   __TEXT.__objc_methlist: 0x72c
-  __TEXT.__objc_methname: 0x1500
+  __TEXT.__objc_methname: 0x14de
   __TEXT.__cstring: 0x43f4
   __TEXT.__objc_classname: 0x111
   __TEXT.__objc_methtype: 0x528

   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x68
   __DATA.__objc_const: 0x1398
-  __DATA.__objc_selrefs: 0x778
+  __DATA.__objc_selrefs: 0x770
   __DATA.__objc_ivar: 0x54
   __DATA.__objc_data: 0x460
   __DATA.__data: 0x180

   - /usr/lib/libobjc.A.dylib
   Functions: 112
   Symbols:   102
-  CStrings:  724
+  CStrings:  723
 
Functions:
~ sub_100001b54 : 944 -> 928
CStrings:
- "setURLBackedMemoryObjectsAllowed:"
```
