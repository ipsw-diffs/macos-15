## diskarbitrationd

> `/usr/libexec/diskarbitrationd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-490.140.8.703.2
-  __TEXT.__text: 0x1bec0
-  __TEXT.__auth_stubs: 0x16e0
+490.140.8.704.1
+  __TEXT.__text: 0x1befc
+  __TEXT.__auth_stubs: 0x16f0
   __TEXT.__objc_stubs: 0x540
   __TEXT.__init_offsets: 0x8
   __TEXT.__objc_methlist: 0xc8

   __TEXT.__objc_methtype: 0x102
   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0x5f8
-  __DATA_CONST.__auth_got: 0xb80
+  __DATA_CONST.__auth_got: 0xb88
   __DATA_CONST.__got: 0x160
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0xd90

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
   Functions: 524
-  Symbols:   421
+  Symbols:   422
   CStrings:  681
 
Symbols:
+ _strnlen
Functions:
~ sub_10000abe4 : 380 -> 440
```
