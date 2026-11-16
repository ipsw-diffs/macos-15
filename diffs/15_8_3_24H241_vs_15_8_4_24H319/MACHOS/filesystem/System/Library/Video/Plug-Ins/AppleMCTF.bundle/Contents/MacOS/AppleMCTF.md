## AppleMCTF

> `/System/Library/Video/Plug-Ins/AppleMCTF.bundle/Contents/MacOS/AppleMCTF`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-803.73.5.0.0
-  __TEXT.__text: 0x56cbc
+803.73.6.0.0
+  __TEXT.__text: 0x56cf0
   __TEXT.__auth_stubs: 0xce0
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x8
Functions:
~ sub_4c33c : 728 -> 780
CStrings:
+ "20:20:03"
+ "803.73.6"
+ "Nov 12 2026"
- "01:03:55"
- "803.73.5"
- "Oct 12 2026"
```
