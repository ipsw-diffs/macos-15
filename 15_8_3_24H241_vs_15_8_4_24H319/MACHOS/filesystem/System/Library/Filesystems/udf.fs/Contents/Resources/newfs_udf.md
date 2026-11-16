## newfs_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/newfs_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-319.0.0.702.4
-  __TEXT.__text: 0x12494
+319.0.0.703.8
+  __TEXT.__text: 0x1260c
   __TEXT.__auth_stubs: 0x5d0
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x658
-  __TEXT.__gcc_except_tab: 0x384
-  __TEXT.__cstring: 0x3942
+  __TEXT.__gcc_except_tab: 0x37c
+  __TEXT.__cstring: 0x3aa3
   __TEXT.__unwind_info: 0x530
   __DATA_CONST.__auth_got: 0x2f0
   __DATA_CONST.__got: 0x78

   - /usr/lib/libutil.dylib
   Functions: 337
   Symbols:   116
-  CStrings:  330
+  CStrings:  337
 
Functions:
~ sub_100000c30 : 288 -> 304
~ sub_100001180 -> sub_100001190 : 676 -> 732
~ sub_1000021b4 -> sub_1000021fc : 388 -> 444
~ sub_100002464 -> sub_1000024e4 : 816 -> 880
~ sub_1000027ac -> sub_10000286c : 348 -> 352
~ sub_100002bb8 -> sub_100002c7c : 844 -> 936
~ sub_10000c6f8 -> sub_10000c818 : 172 -> 240
~ sub_10000ee0c -> sub_10000ef70 : 756 -> 776
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
