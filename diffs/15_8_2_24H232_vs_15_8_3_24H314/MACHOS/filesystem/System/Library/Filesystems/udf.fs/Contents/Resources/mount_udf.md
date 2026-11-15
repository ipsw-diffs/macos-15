## mount_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/mount_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-319.0.0.702.4
-  __TEXT.__text: 0x9fd8
+319.0.0.703.6
+  __TEXT.__text: 0xa0f4
   __TEXT.__auth_stubs: 0x3d0
-  __TEXT.__cstring: 0x1092
+  __TEXT.__cstring: 0x1142
   __TEXT.__gcc_except_tab: 0x308
   __TEXT.__const: 0x564
   __TEXT.__unwind_info: 0x3c8

   - /usr/lib/libutil.dylib
   Functions: 246
   Symbols:   78
-  CStrings:  149
+  CStrings:  152
 
Functions:
~ sub_1000012d0 : 288 -> 304
~ sub_10000181c -> sub_10000182c : 676 -> 732
~ sub_100003ff0 -> sub_100004038 : 172 -> 240
~ sub_1000056b0 -> sub_10000573c : 756 -> 776
~ sub_100008abc -> sub_100008b5c : 388 -> 444
~ sub_100008d6c -> sub_100008e44 : 816 -> 880
~ sub_1000090b4 -> sub_1000091cc : 348 -> 352
CStrings:
+ "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
+ "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
+ "Sparing table size %u cannot hold %u entries"
+ "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
- "non-memory resident sparing table is not implemented yet"
```
