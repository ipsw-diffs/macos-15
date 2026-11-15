## udf.util

> `/System/Library/Filesystems/udf.fs/Contents/Resources/udf.util`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-319.0.0.702.4
-  __TEXT.__text: 0xa100
+319.0.0.703.6
+  __TEXT.__text: 0xa21c
   __TEXT.__auth_stubs: 0x380
-  __TEXT.__cstring: 0xfa6
+  __TEXT.__cstring: 0x1056
   __TEXT.__gcc_except_tab: 0x32c
   __TEXT.__const: 0x564
   __TEXT.__unwind_info: 0x3d0

   - /usr/lib/libc++.1.dylib
   Functions: 242
   Symbols:   70
-  CStrings:  136
+  CStrings:  139
 
Functions:
~ sub_1000014c4 : 288 -> 304
~ sub_100001a10 -> sub_100001a20 : 676 -> 732
~ sub_1000041e4 -> sub_10000422c : 172 -> 240
~ sub_1000058a4 -> sub_100005930 : 756 -> 776
~ sub_100008cb0 -> sub_100008d50 : 388 -> 444
~ sub_100008f60 -> sub_100009038 : 816 -> 880
~ sub_1000092a8 -> sub_1000093c0 : 348 -> 352
CStrings:
+ "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
+ "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
+ "Sparing table size %u cannot hold %u entries"
+ "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
- "non-memory resident sparing table is not implemented yet"
```
