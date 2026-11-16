## fsck_hfs

> `/System/Library/Filesystems/hfs.fs/Contents/Resources/fsck_hfs`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-683.120.3.706.5
-  __TEXT.__text: 0x2fdf8
+683.120.3.707.7
+  __TEXT.__text: 0x2ffdc
   __TEXT.__auth_stubs: 0x780
   __TEXT.__const: 0x112c
-  __TEXT.__cstring: 0x6e94
+  __TEXT.__cstring: 0x6fac
   __TEXT.__unwind_info: 0x508
   __DATA_CONST.__auth_got: 0x3c0
   __DATA_CONST.__got: 0x50

   - /usr/lib/libSystem.B.dylib
   Functions: 470
   Symbols:   135
-  CStrings:  786
+  CStrings:  792
 
Functions:
~ sub_1000054c4 : 1088 -> 1168
~ sub_10000f80c -> sub_10000f85c : 6872 -> 7184
~ sub_1000137f0 -> sub_100013978 : 592 -> 684
CStrings:
+ "has extra space"
+ "hfs_swap_BTNode: header node has %d records, should be 3\n"
+ "hfs_swap_BTNode: map node has %d records, should be 1\n"
+ "hfs_swap_HFSPlusBTInternalNode: catalog file record #%d has extra space\n"
+ "hfs_swap_HFSPlusBTInternalNode: catalog folder record #%d %s\n"
+ "hfs_swap_HFSPlusBTInternalNode: catalog thread record #%d has extra space\n"
+ "too big"
- "hfs_swap_HFSPlusBTInternalNode: catalog folder record #%d too big\n"
```
