## com.apple.filesystems.smbfs

> `com.apple.filesystems.smbfs`

```diff

-494.120.2.704.5
+494.120.2.705.5
   __TEXT.__const: 0xbf5
-  __TEXT.__cstring: 0x4677
+  __TEXT.__cstring: 0x4692
   __TEXT.__os_log: 0x16162
-  __TEXT_EXEC.__text: 0x7e32c
+  __TEXT_EXEC.__text: 0x7e408
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xdf8
   __DATA.__bss: 0x106c

   __DATA_CONST.__kalloc_var: 0x460
   Functions: 752
   Symbols:   2086
-  CStrings:  2488
+  CStrings:  2492
 
Symbols:
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6282
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6320
+ _AddRemoveByteRangeLockEntry.kalloc_type_view_6331
+ _smb2_smb_read_uio.kalloc_type_view_9042
+ _smb2_smb_read_uio.kalloc_type_view_9059
+ _smb2_smb_read_write_async.kalloc_type_view_9211
+ _smb2_smb_read_write_async.kalloc_type_view_9277
+ _smb2_smb_read_write_async.kalloc_type_view_9605
+ _smb2_smb_read_write_async.kalloc_type_view_9674
+ _smb2_smb_write_uio.kalloc_type_view_10834
+ _smb2_smb_write_uio.kalloc_type_view_10887
+ _smb2fs_reconnect.kalloc_type_view_3844
+ _smb2fs_reconnect.kalloc_type_view_4388
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3606
+ _smb2fs_reconnect_dur_handle.kalloc_type_view_3762
+ _smbfs_CloseChildren.kalloc_type_view_3397
+ _smbfs_clear_lockEntries.kalloc_type_view_6693
+ _smbfs_clear_lockEntries.kalloc_type_view_6723
+ _smbfs_free_locks_on_close.kalloc_type_view_6875
+ _smbfs_get_lockEntry.kalloc_type_view_7082
+ _smbfs_get_lockEntry.kalloc_type_view_7171
+ _smbfs_lease_hash_add.kalloc_type_view_6134
+ _smbfs_lease_hash_remove.kalloc_type_view_6234
+ _smbfs_nget.kalloc_type_view_1016
+ _smbfs_nget.kalloc_type_view_1071
+ _smbfs_nget.kalloc_type_view_1091
+ _smbfs_nget.kalloc_type_view_1098
+ _smbfs_nget.kalloc_type_view_1401
+ _smbfs_nget.kalloc_type_view_987
+ _smbfs_trigger_get_mount_args.kalloc_type_view_206
+ _smbfs_trigger_get_mount_args.kalloc_type_view_237
+ _smbfs_trigger_get_mount_args.kalloc_type_view_261
+ _smbfs_trigger_rel_mount_args.kalloc_type_view_307
+ _smbfs_vgetstrm.kalloc_type_view_1488
+ _smbfs_vgetstrm.kalloc_type_view_1495
+ _smbfs_vgetstrm.kalloc_type_view_1704
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6257
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6295
- _AddRemoveByteRangeLockEntry.kalloc_type_view_6306
- _smb2_smb_read_uio.kalloc_type_view_9031
- _smb2_smb_read_uio.kalloc_type_view_9048
- _smb2_smb_read_write_async.kalloc_type_view_9200
- _smb2_smb_read_write_async.kalloc_type_view_9266
- _smb2_smb_read_write_async.kalloc_type_view_9594
- _smb2_smb_read_write_async.kalloc_type_view_9663
- _smb2_smb_write_uio.kalloc_type_view_10823
- _smb2_smb_write_uio.kalloc_type_view_10876
- _smb2fs_reconnect.kalloc_type_view_3819
- _smb2fs_reconnect.kalloc_type_view_4363
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3581
- _smb2fs_reconnect_dur_handle.kalloc_type_view_3737
- _smbfs_CloseChildren.kalloc_type_view_3372
- _smbfs_clear_lockEntries.kalloc_type_view_6668
- _smbfs_clear_lockEntries.kalloc_type_view_6698
- _smbfs_free_locks_on_close.kalloc_type_view_6850
- _smbfs_get_lockEntry.kalloc_type_view_7057
- _smbfs_get_lockEntry.kalloc_type_view_7146
- _smbfs_lease_hash_add.kalloc_type_view_6109
- _smbfs_lease_hash_remove.kalloc_type_view_6209
- _smbfs_nget.kalloc_type_view_1046
- _smbfs_nget.kalloc_type_view_1066
- _smbfs_nget.kalloc_type_view_1073
- _smbfs_nget.kalloc_type_view_1376
- _smbfs_nget.kalloc_type_view_962
- _smbfs_nget.kalloc_type_view_991
- _smbfs_trigger_get_mount_args.kalloc_type_view_205
- _smbfs_trigger_get_mount_args.kalloc_type_view_236
- _smbfs_trigger_get_mount_args.kalloc_type_view_260
- _smbfs_trigger_rel_mount_args.kalloc_type_view_282
- _smbfs_vgetstrm.kalloc_type_view_1463
- _smbfs_vgetstrm.kalloc_type_view_1470
- _smbfs_vgetstrm.kalloc_type_view_1679
Functions:
~ _smbfs_trigger_get_mount_args : 816 -> 1024
~ _smbfs_trigger_rel_mount_args : 92 -> 108
~ _nb_put_name : 284 -> 280
CStrings:
+ ","
+ "noexec"
+ "quarantine"
+ "rdonly"
```
