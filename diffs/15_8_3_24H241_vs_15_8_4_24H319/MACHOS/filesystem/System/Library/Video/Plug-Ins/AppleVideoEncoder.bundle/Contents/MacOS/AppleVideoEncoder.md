## AppleVideoEncoder

> `/System/Library/Video/Plug-Ins/AppleVideoEncoder.bundle/Contents/MacOS/AppleVideoEncoder`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-803.73.5.0.0
-  __TEXT.__text: 0xe26f8
+803.73.6.0.0
+  __TEXT.__text: 0xe2820
   __TEXT.__auth_stubs: 0xf50
   __TEXT.__objc_stubs: 0x20
   __TEXT.__init_offsets: 0x8
-  __TEXT.__cstring: 0x5ab84
+  __TEXT.__cstring: 0x5ac4e
   __TEXT.__const: 0x15de8
   __TEXT.__gcc_except_tab: 0x604
   __TEXT.__objc_methname: 0xb

   - /usr/lib/libobjc.A.dylib
   Functions: 663
   Symbols:   548
-  CStrings:  5750
+  CStrings:  5754
 
Functions:
~ sub_86da0 : 2612 -> 2616
~ sub_c4d58 -> sub_c4d5c : 728 -> 780
~ sub_cb070 -> sub_cb0a8 : 1380 -> 1404
~ sub_dc5f4 -> sub_dc644 : 476 -> 692
CStrings:
+ "%lld %d AVE %s: %s:%d %s | too many DRL entries %d (max %d)"
+ "%lld %d AVE %s: %s:%d %s | too many DRL entries %d (max %d)\n"
+ "20:19:39"
+ "20:19:40"
+ "803.73.6"
+ "Nov 12 2026"
+ "num <= 2"
+ "pInfo->num_negative_pics <= 16 && pInfo->num_positive_pics <= 16 && (pInfo->num_negative_pics + pInfo->num_positive_pics) <= 16"
- "01:03:31"
- "803.73.5"
- "Oct 12 2026"
- "pInfo->num_negative_pics <= 16 && pInfo->num_positive_pics <= 16"
```
