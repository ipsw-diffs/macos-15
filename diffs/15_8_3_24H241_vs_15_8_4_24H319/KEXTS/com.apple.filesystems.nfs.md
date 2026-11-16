## com.apple.filesystems.nfs

> `com.apple.filesystems.nfs`

```diff

-327.140.2.701.5
-  __TEXT.__cstring: 0x8cfb
+327.140.2.702.4
+  __TEXT.__cstring: 0x8d6e
   __TEXT.__const: 0x3dc
-  __TEXT_EXEC.__text: 0x8c940
+  __TEXT_EXEC.__text: 0x8ca14
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xee0
   __DATA.__common: 0xc94

   __DATA_CONST.__kalloc_var: 0x320
   Functions: 948
   Symbols:   1586
-  CStrings:  1051
+  CStrings:  1053
 
Symbols:
+ _nfs3_vnop_mkdir.kalloc_type_view_5608
+ _nfs3_vnop_mkdir.kalloc_type_view_5722
+ _nfs3_vnop_rmdir.kalloc_type_view_5779
+ _nfs3_vnop_rmdir.kalloc_type_view_5855
+ _nfs3_vnop_symlink.kalloc_type_view_5419
+ _nfs3_vnop_symlink.kalloc_type_view_5539
+ _nfs_sillyrename.kalloc_type_view_7046
+ _nfs_sillyrename.kalloc_type_view_7105
+ _nfs_vnop_remove.kalloc_type_view_4882
- _nfs3_vnop_mkdir.kalloc_type_view_5593
- _nfs3_vnop_mkdir.kalloc_type_view_5707
- _nfs3_vnop_rmdir.kalloc_type_view_5764
- _nfs3_vnop_rmdir.kalloc_type_view_5840
- _nfs3_vnop_symlink.kalloc_type_view_5404
- _nfs3_vnop_symlink.kalloc_type_view_5524
- _nfs_sillyrename.kalloc_type_view_7031
- _nfs_sillyrename.kalloc_type_view_7090
- _nfs_vnop_remove.kalloc_type_view_4867
Functions:
~ _nfs_request_finish : 3104 -> 3108
~ _nfs_buf_read_finish : 364 -> 480
~ _nfs_vnop_pageout : 4924 -> 4948
~ _nfs_loadattrcache : 2104 -> 2172
CStrings:
+ "%s: %d: clamping nb_validend %lld to EOF: boff %lld, nb_endio %lld, nb_bufsize %u, n_size %llu"
+ "nfs_buf_read_finish"
```
