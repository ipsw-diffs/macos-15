## fsck_udf

> `/System/Library/Filesystems/udf.fs/Contents/Resources/fsck_udf`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-319.0.0.703.6
-  __TEXT.__text: 0x111a4
+319.0.0.702.4
+  __TEXT.__text: 0x11064
   __TEXT.__auth_stubs: 0x430
   __TEXT.__init_offsets: 0x8
-  __TEXT.__cstring: 0x36d6
+  __TEXT.__cstring: 0x35c9
   __TEXT.__const: 0x4f5d
-  __TEXT.__gcc_except_tab: 0x5b0
+  __TEXT.__gcc_except_tab: 0x5ac
   __TEXT.__unwind_info: 0x508
   __DATA_CONST.__auth_got: 0x220
   __DATA_CONST.__got: 0x50

   - /usr/lib/libc++.1.dylib
   Functions: 359
   Symbols:   85
-  CStrings:  395
+  CStrings:  390
 
Functions:
~ sub_1000015c8 : 304 -> 288
~ sub_100001b24 -> sub_100001b14 : 732 -> 676
~ sub_1000045b4 -> sub_10000456c : 280 -> 192
~ sub_10000604c -> sub_100005fac : 776 -> 756
~ sub_100009724 -> sub_100009670 : 492 -> 420
~ sub_100009a3c -> sub_100009940 : 880 -> 816
~ sub_100009dc4 -> sub_100009c88 : 380 -> 376
CStrings:
+ "non-memory resident sparing table is not implemented yet"
- "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
- "Illegal packet length %u in Sparable Partition"
- "L_EA + L_AD exceeds sector size\t ICB addr: %u"
- "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
- "Sparing table size %u cannot hold %u entries"
- "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
```
