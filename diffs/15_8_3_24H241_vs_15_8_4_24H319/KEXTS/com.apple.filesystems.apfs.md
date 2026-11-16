## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

```diff

-2332.140.13.704.3
+2332.140.13.705.4
   __TEXT.__const: 0xaf8
-  __TEXT.__cstring: 0x577a8
-  __TEXT_EXEC.__text: 0x184e80
+  __TEXT.__cstring: 0x57950
+  __TEXT_EXEC.__text: 0x185020
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xd48
   __DATA.__bss: 0xb10

   __DATA_CONST.__kalloc_type: 0x6180
   __DATA_CONST.__kalloc_var: 0x3250
   __DATA_CONST.__assert: 0x294
-  Functions: 2629
-  Symbols:   4771
-  CStrings:  7512
+  Functions: 2630
+  Symbols:   4772
+  CStrings:  7517
 
Symbols:
+ __fs_add_xattr.kalloc_type_view_22846
+ __fs_add_xattr.kalloc_type_view_22852
+ __fs_add_xattr.kalloc_type_view_22855
+ __fs_add_xattr.kalloc_type_view_22909
+ __fs_add_xattr.kalloc_type_view_22910
+ _apfs_punch_out_ranges_in_fext.kalloc_type_view_21108
+ _apfs_punch_out_ranges_in_fext.kalloc_type_view_21115
+ _apfs_update_reserved_ranges.kalloc_type_view_21251
+ _apfs_update_reserved_ranges.kalloc_type_view_21256
+ _arle_alloc_pending_entry.kalloc_type_view_20693
+ _change_crypto_id_prot_class.kalloc_type_view_9867
+ _change_crypto_id_prot_class.kalloc_type_view_9933
+ _clone_fexts_.kalloc_type_view_14062
+ _clone_fexts_.kalloc_type_view_14075
+ _clone_fexts_.kalloc_type_view_14133
+ _create_new_crypto_state_for_id.kalloc_type_view_7584
+ _create_new_crypto_state_for_id.kalloc_type_view_7589
+ _create_new_crypto_state_for_id.kalloc_type_view_7609
+ _create_sibling_link.kalloc_type_view_11466
+ _create_sibling_link.kalloc_type_view_11482
+ _dir_rec_alloc_with_hash.kalloc_type_view_11121
+ _dir_rec_alloc_with_hash.kalloc_type_view_11127
+ _dir_rec_alloc_with_hash.kalloc_type_view_11151
+ _dump_extents_of_stream.kalloc_type_view_18130
+ _ek_to_crypto_state.kalloc_type_view_32763
+ _er_state_allocate_roll_buffers.kalloc_type_view_8150
+ _er_state_allocate_roll_buffers.kalloc_type_view_8169
+ _er_state_allocate_roll_buffers.kalloc_type_view_8175
+ _er_state_destroy_obj.kalloc_type_view_8857
+ _er_state_free_roll_buffers.kalloc_type_view_8084
+ _er_state_free_roll_buffers.kalloc_type_view_8092
+ _er_state_free_roll_buffers.kalloc_type_view_8101
+ _er_state_obj_create_phys_from_previous_version.kalloc_type_view_8217
+ _er_state_upgrade_version.kalloc_type_view_8370
+ _extent_evict_range.kalloc_type_view_25460
+ _extent_evict_range.kalloc_type_view_25560
+ _fext_collector.kalloc_type_view_13826
+ _fext_collector.kalloc_type_view_13833
+ _fext_collector_cleanup.kalloc_type_view_13808
+ _fext_collector_reset.kalloc_type_view_13797
+ _free_linkids.kalloc_type_view_11658
+ _fs_get_xattr_in_snap.kalloc_type_view_22944
+ _fs_get_xattr_in_snap.kalloc_type_view_22963
+ _fs_init_bootcache_inodes_dstreams_info.kalloc_type_view_27389
+ _fs_iterate_snapshots.kalloc_type_view_26623
+ _fs_iterate_snapshots.kalloc_type_view_26670
+ _fs_map_file_offset_ext.kalloc_type_view_21663
+ _fs_map_file_offset_ext.kalloc_type_view_21695
+ _fs_map_file_offset_ext.kalloc_type_view_21733
+ _fs_map_file_offset_ext.kalloc_type_view_21756
+ _fs_remove_xattr_with_nstream_inode.kalloc_type_view_23058
+ _fs_remove_xattr_with_nstream_inode.kalloc_type_view_23074
+ _fs_remove_xattr_with_nstream_inode.kalloc_type_view_23095
+ _fs_remove_xattr_with_nstream_inode.kalloc_type_view_23212
+ _icp_new_crypto.kalloc_type_view_7903
+ _icp_new_crypto.kalloc_type_view_7915
+ _icp_new_crypto.kalloc_type_view_7949
+ _icp_new_crypto.kalloc_type_view_7974
+ _icp_new_crypto.kalloc_type_view_7989
+ _insert_linkid.kalloc_type_view_11606
+ _jobj_allocate.kalloc_type_view_2636
+ _jobj_allocate.kalloc_type_view_2639
+ _jobj_allocate.kalloc_type_view_2643
+ _jobj_allocate.kalloc_type_view_2649
+ _jobj_allocate.kalloc_type_view_2653
+ _jobj_allocate.kalloc_type_view_2659
+ _jobj_allocate.kalloc_type_view_2662
+ _jobj_allocate.kalloc_type_view_2665
+ _jobj_allocate.kalloc_type_view_2668
+ _jobj_allocate.kalloc_type_view_2671
+ _jobj_allocate.kalloc_type_view_2675
+ _jobj_allocate.kalloc_type_view_2678
+ _jobj_allocate.kalloc_type_view_2681
+ _jobj_allocate.kalloc_type_view_2688
+ _jobj_allocate.kalloc_type_view_2691
+ _jobj_allocate.kalloc_type_view_2700
+ _jobj_allocate.kalloc_type_view_2703
+ _jobj_allocate.kalloc_type_view_2706
+ _jobj_release.kalloc_type_view_2728
+ _jobj_release.kalloc_type_view_2731
+ _jobj_release.kalloc_type_view_2734
+ _jobj_release.kalloc_type_view_2739
+ _jobj_release.kalloc_type_view_2743
+ _jobj_release.kalloc_type_view_2746
+ _jobj_release.kalloc_type_view_2752
+ _jobj_release.kalloc_type_view_2759
+ _jobj_release.kalloc_type_view_2763
+ _jobj_release.kalloc_type_view_2766
+ _jobj_release.kalloc_type_view_2769
+ _jobj_release.kalloc_type_view_2776
+ _jobj_release.kalloc_type_view_2783
+ _jobj_release.kalloc_type_view_2793
+ _jobj_release.kalloc_type_view_2797
+ _jobj_release.kalloc_type_view_2803
+ _legacy_get_ek.kalloc_type_view_34245
+ _lookup_unfoldable_name_iterator.kalloc_type_view_17558
+ _lookup_unfoldable_name_iterator.kalloc_type_view_17564
+ _lookup_unfoldable_name_iterator.kalloc_type_view_17576
+ _simple_remove_xattr.kalloc_type_view_22982
+ _simple_remove_xattr.kalloc_type_view_22995
+ _spaceman_iterate_handle_free_extent_callback
+ _xattr_cloner.kalloc_type_view_16287
+ _xattr_cloner.kalloc_type_view_16329
+ _xattr_ek_to_crypto_state.kalloc_type_view_33438
- __fs_add_xattr.kalloc_type_view_22801
- __fs_add_xattr.kalloc_type_view_22807
- __fs_add_xattr.kalloc_type_view_22810
- __fs_add_xattr.kalloc_type_view_22864
- __fs_add_xattr.kalloc_type_view_22865
- _apfs_punch_out_ranges_in_fext.kalloc_type_view_21063
- _apfs_punch_out_ranges_in_fext.kalloc_type_view_21070
- _apfs_update_reserved_ranges.kalloc_type_view_21206
- _apfs_update_reserved_ranges.kalloc_type_view_21211
- _arle_alloc_pending_entry.kalloc_type_view_20648
- _change_crypto_id_prot_class.kalloc_type_view_9822
- _change_crypto_id_prot_class.kalloc_type_view_9888
- _clone_fexts_.kalloc_type_view_14017
- _clone_fexts_.kalloc_type_view_14030
- _clone_fexts_.kalloc_type_view_14088
- _create_new_crypto_state_for_id.kalloc_type_view_7582
- _create_new_crypto_state_for_id.kalloc_type_view_7587
- _create_new_crypto_state_for_id.kalloc_type_view_7607
- _create_sibling_link.kalloc_type_view_11421
- _create_sibling_link.kalloc_type_view_11437
- _dir_rec_alloc_with_hash.kalloc_type_view_11076
- _dir_rec_alloc_with_hash.kalloc_type_view_11082
- _dir_rec_alloc_with_hash.kalloc_type_view_11106
- _dump_extents_of_stream.kalloc_type_view_18085
- _ek_to_crypto_state.kalloc_type_view_32718
- _er_state_allocate_roll_buffers.kalloc_type_view_8148
- _er_state_allocate_roll_buffers.kalloc_type_view_8167
- _er_state_allocate_roll_buffers.kalloc_type_view_8173
- _er_state_destroy_obj.kalloc_type_view_8855
- _er_state_free_roll_buffers.kalloc_type_view_8082
- _er_state_free_roll_buffers.kalloc_type_view_8090
- _er_state_free_roll_buffers.kalloc_type_view_8099
- _er_state_obj_create_phys_from_previous_version.kalloc_type_view_8215
- _er_state_upgrade_version.kalloc_type_view_8368
- _extent_evict_range.kalloc_type_view_25415
- _extent_evict_range.kalloc_type_view_25515
- _fext_collector.kalloc_type_view_13781
- _fext_collector.kalloc_type_view_13788
- _fext_collector_cleanup.kalloc_type_view_13763
- _fext_collector_reset.kalloc_type_view_13752
- _free_linkids.kalloc_type_view_11613
- _fs_get_xattr_in_snap.kalloc_type_view_22899
- _fs_get_xattr_in_snap.kalloc_type_view_22918
- _fs_init_bootcache_inodes_dstreams_info.kalloc_type_view_27344
- _fs_iterate_snapshots.kalloc_type_view_26578
- _fs_iterate_snapshots.kalloc_type_view_26625
- _fs_map_file_offset_ext.kalloc_type_view_21618
- _fs_map_file_offset_ext.kalloc_type_view_21650
- _fs_map_file_offset_ext.kalloc_type_view_21688
- _fs_map_file_offset_ext.kalloc_type_view_21711
- _fs_remove_xattr_with_nstream_inode.kalloc_type_view_23013
- _fs_remove_xattr_with_nstream_inode.kalloc_type_view_23029
- _fs_remove_xattr_with_nstream_inode.kalloc_type_view_23050
- _fs_remove_xattr_with_nstream_inode.kalloc_type_view_23167
- _icp_new_crypto.kalloc_type_view_7901
- _icp_new_crypto.kalloc_type_view_7911
- _icp_new_crypto.kalloc_type_view_7947
- _icp_new_crypto.kalloc_type_view_7972
- _icp_new_crypto.kalloc_type_view_7987
- _insert_linkid.kalloc_type_view_11561
- _jobj_allocate.kalloc_type_view_2634
- _jobj_allocate.kalloc_type_view_2637
- _jobj_allocate.kalloc_type_view_2641
- _jobj_allocate.kalloc_type_view_2647
- _jobj_allocate.kalloc_type_view_2651
- _jobj_allocate.kalloc_type_view_2657
- _jobj_allocate.kalloc_type_view_2660
- _jobj_allocate.kalloc_type_view_2663
- _jobj_allocate.kalloc_type_view_2666
- _jobj_allocate.kalloc_type_view_2669
- _jobj_allocate.kalloc_type_view_2673
- _jobj_allocate.kalloc_type_view_2676
- _jobj_allocate.kalloc_type_view_2679
- _jobj_allocate.kalloc_type_view_2686
- _jobj_allocate.kalloc_type_view_2689
- _jobj_allocate.kalloc_type_view_2698
- _jobj_allocate.kalloc_type_view_2701
- _jobj_allocate.kalloc_type_view_2704
- _jobj_release.kalloc_type_view_2726
- _jobj_release.kalloc_type_view_2729
- _jobj_release.kalloc_type_view_2732
- _jobj_release.kalloc_type_view_2737
- _jobj_release.kalloc_type_view_2741
- _jobj_release.kalloc_type_view_2744
- _jobj_release.kalloc_type_view_2750
- _jobj_release.kalloc_type_view_2757
- _jobj_release.kalloc_type_view_2761
- _jobj_release.kalloc_type_view_2764
- _jobj_release.kalloc_type_view_2767
- _jobj_release.kalloc_type_view_2774
- _jobj_release.kalloc_type_view_2781
- _jobj_release.kalloc_type_view_2791
- _jobj_release.kalloc_type_view_2795
- _jobj_release.kalloc_type_view_2801
- _legacy_get_ek.kalloc_type_view_34200
- _lookup_unfoldable_name_iterator.kalloc_type_view_17513
- _lookup_unfoldable_name_iterator.kalloc_type_view_17519
- _lookup_unfoldable_name_iterator.kalloc_type_view_17531
- _simple_remove_xattr.kalloc_type_view_22937
- _simple_remove_xattr.kalloc_type_view_22950
- _xattr_cloner.kalloc_type_view_16242
- _xattr_cloner.kalloc_type_view_16284
- _xattr_ek_to_crypto_state.kalloc_type_view_33393
Functions:
~ _sanity_check_alloced_blocks : 1388 -> 1372
~ _encryption_rolling_mount_check : 4192 -> 4472
~ _spaceman_iterate_free_extents_internal : 7264 -> 7224
+ _spaceman_iterate_handle_free_extent_callback
~ _grow_data : 184 -> 192
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
+ "%s:%d: extent exceeds checksums buf, idx 0x%llx, len 0x%llx, left 0x%llx\n"
+ "%s:%d: extent exceeds rolled buf, idx 0x%llx, extent_size 0x%llx, buf_size 0x%lx\n"
+ "%s:%d: extent exceeds unrolled buf, idx 0x%llx, len 0x%llx, left 0x%llx\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs/kext/apfs_filter.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs/kext/apfs_ioctls.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs/kext/apfs_vnops.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs/nx/jobj.c"
+ "2026/11/12"
+ "20:01:33"
+ "20:01:34"
+ "2332.140.13.705.4"
+ "Nov 12 2026"
+ "apfs-2332.140.13.705.4"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs/kext/apfs_filter.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs/kext/apfs_ioctls.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs/kext/apfs_vnops.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs/nx/jobj.c"
- "2026/10/11"
- "2332.140.13.704.3"
- "23:14:39"
- "Oct 11 2026"
- "apfs-2332.140.13.704.3"
```
