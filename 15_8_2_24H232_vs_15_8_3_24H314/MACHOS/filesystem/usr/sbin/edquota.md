## edquota

> `/usr/sbin/edquota`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA.__data`

```diff

-737.140.4.700.1
-  __TEXT.__text: 0x1d10
-  __TEXT.__auth_stubs: 0x330
-  __TEXT.__cstring: 0x57a
-  __TEXT.__unwind_info: 0xa0
-  __DATA_CONST.__auth_got: 0x198
+737.140.4.701.1
+  __TEXT.__text: 0x1df0
+  __TEXT.__auth_stubs: 0x340
+  __TEXT.__cstring: 0x59b
+  __TEXT.__unwind_info: 0xa8
+  __DATA_CONST.__auth_got: 0x1a0
   __DATA_CONST.__got: 0x20
   __DATA.__data: 0x40
   __DATA.__bss: 0x4de
   - /usr/lib/libSystem.B.dylib
   Functions: 21
-  Symbols:   57
-  CStrings:  64
+  Symbols:   58
+  CStrings:  65
 
Symbols:
+ _fstat
Functions:
~ sub_100000aac : 180 -> 304
~ sub_100001474 -> sub_1000014f0 : 828 -> 940
~ sub_100002118 -> sub_100002204 : 84 -> 72
CStrings:
+ "edquota: %s: not a regular file\n"
```
