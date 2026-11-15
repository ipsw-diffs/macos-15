## newfs_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/newfs_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-319.0.0.703.6
-  __TEXT.__text: 0x125b0
+319.0.0.702.4
+  __TEXT.__text: 0x12494
   __TEXT.__auth_stubs: 0x5d0
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x658
   __TEXT.__gcc_except_tab: 0x384
-  __TEXT.__cstring: 0x39f2
+  __TEXT.__cstring: 0x3942
   __TEXT.__unwind_info: 0x530
   __DATA_CONST.__auth_got: 0x2f0
   __DATA_CONST.__got: 0x78

   - /usr/lib/libutil.dylib
   Functions: 337
   Symbols:   116
-  CStrings:  333
+  CStrings:  330
 
Functions:
~ sub_100000c30 : 304 -> 288
~ sub_100001190 -> sub_100001180 : 732 -> 676
~ sub_1000021fc -> sub_1000021b4 : 444 -> 388
~ sub_1000024e4 -> sub_100002464 : 880 -> 816
~ sub_10000286c -> sub_1000027ac : 352 -> 348
~ sub_10000c7bc -> sub_10000c6f8 : 240 -> 172
~ sub_10000ef14 -> sub_10000ee0c : 776 -> 756
CStrings:
+ "non-memory resident sparing table is not implemented yet"
- "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
- "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
- "Sparing table size %u cannot hold %u entries"
- "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
```
