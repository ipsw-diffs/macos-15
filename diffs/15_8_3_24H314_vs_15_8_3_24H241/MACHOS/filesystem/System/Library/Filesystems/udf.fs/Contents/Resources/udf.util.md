## udf.util

> `/System/Library/Filesystems/udf.fs/Contents/Resources/udf.util`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-319.0.0.703.6
-  __TEXT.__text: 0xa21c
+319.0.0.702.4
+  __TEXT.__text: 0xa100
   __TEXT.__auth_stubs: 0x380
-  __TEXT.__cstring: 0x1056
+  __TEXT.__cstring: 0xfa6
   __TEXT.__gcc_except_tab: 0x32c
   __TEXT.__const: 0x564
   __TEXT.__unwind_info: 0x3d0

   - /usr/lib/libc++.1.dylib
   Functions: 242
   Symbols:   70
-  CStrings:  139
+  CStrings:  136
 
Functions:
~ sub_1000014c4 : 304 -> 288
~ sub_100001a20 -> sub_100001a10 : 732 -> 676
~ sub_10000422c -> sub_1000041e4 : 240 -> 172
~ sub_100005930 -> sub_1000058a4 : 776 -> 756
~ sub_100008d50 -> sub_100008cb0 : 444 -> 388
~ sub_100009038 -> sub_100008f60 : 880 -> 816
~ sub_1000093c0 -> sub_1000092a8 : 352 -> 348
CStrings:
+ "non-memory resident sparing table is not implemented yet"
- "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
- "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
- "Sparing table size %u cannot hold %u entries"
- "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
```
