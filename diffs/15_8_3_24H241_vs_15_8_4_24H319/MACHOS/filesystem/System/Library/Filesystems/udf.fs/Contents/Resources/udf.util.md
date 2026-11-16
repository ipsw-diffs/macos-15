## udf.util

> `/System/Library/Filesystems/udf.fs/Contents/Resources/udf.util`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-319.0.0.702.4
-  __TEXT.__text: 0xa100
+319.0.0.703.8
+  __TEXT.__text: 0xa278
   __TEXT.__auth_stubs: 0x380
-  __TEXT.__cstring: 0xfa6
-  __TEXT.__gcc_except_tab: 0x32c
+  __TEXT.__cstring: 0x1107
+  __TEXT.__gcc_except_tab: 0x324
   __TEXT.__const: 0x564
   __TEXT.__unwind_info: 0x3d0
   __DATA_CONST.__auth_got: 0x1c8

   - /usr/lib/libc++.1.dylib
   Functions: 242
   Symbols:   70
-  CStrings:  136
+  CStrings:  143
 
Functions:
~ sub_1000014c4 : 288 -> 304
~ sub_100001a10 -> sub_100001a20 : 676 -> 732
~ sub_1000041e4 -> sub_10000422c : 172 -> 240
~ sub_1000058a4 -> sub_100005930 : 756 -> 776
~ sub_100008cb0 -> sub_100008d50 : 388 -> 444
~ sub_100008f60 -> sub_100009038 : 816 -> 880
~ sub_1000092a8 -> sub_1000093c0 : 348 -> 352
~ sub_1000096b4 -> sub_1000097d0 : 844 -> 936
CStrings:
+ "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
+ "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
+ "Sparing table size %u cannot hold %u entries"
+ "The VAT has too many entries"
+ "The VAT information length exceeds the VAT stream length"
+ "The VAT is too small to hold its tail"
+ "The lengthOfHeader in VAT ICB exceeds the VAT length"
+ "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
- "non-memory resident sparing table is not implemented yet"
```
