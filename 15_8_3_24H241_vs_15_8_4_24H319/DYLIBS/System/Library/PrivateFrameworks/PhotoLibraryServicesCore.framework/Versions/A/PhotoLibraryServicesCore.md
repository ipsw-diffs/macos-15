## PhotoLibraryServicesCore

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/Versions/A/PhotoLibraryServicesCore`

```diff

-770.0.181.0.0
-  __TEXT.__text: 0xd14e0
-  __TEXT.__auth_stubs: 0x1a40
-  __TEXT.__objc_methlist: 0x7fbc
+770.0.188.0.0
+  __TEXT.__text: 0xd2060
+  __TEXT.__auth_stubs: 0x1a50
+  __TEXT.__objc_methlist: 0x7ffc
   __TEXT.__const: 0x22fc
-  __TEXT.__cstring: 0x1398b
+  __TEXT.__cstring: 0x13934
   __TEXT.__dlopen_cstrs: 0xe1
-  __TEXT.__gcc_except_tab: 0x7090
-  __TEXT.__oslogstring: 0xa23a
-  __TEXT.__unwind_info: 0x2f20
+  __TEXT.__gcc_except_tab: 0x7094
+  __TEXT.__oslogstring: 0xa30e
+  __TEXT.__unwind_info: 0x2f38
   __TEXT.__objc_classname: 0x110e
-  __TEXT.__objc_methname: 0x16184
+  __TEXT.__objc_methname: 0x16239
   __TEXT.__objc_methtype: 0x4c9a
-  __TEXT.__objc_stubs: 0xc3e0
-  __DATA_CONST.__got: 0xa50
+  __TEXT.__objc_stubs: 0xc480
+  __DATA_CONST.__got: 0xa58
   __DATA_CONST.__const: 0x2080
   __DATA_CONST.__objc_classlist: 0x410
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x158
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4d78
+  __DATA_CONST.__objc_selrefs: 0x4da0
   __DATA_CONST.__objc_protorefs: 0xc0
   __DATA_CONST.__objc_superrefs: 0x268
   __DATA_CONST.__objc_arraydata: 0x408
-  __AUTH_CONST.__auth_got: 0xd30
+  __AUTH_CONST.__auth_got: 0xd38
   __AUTH_CONST.__const: 0x4ef0
-  __AUTH_CONST.__cfstring: 0x106c0
+  __AUTH_CONST.__cfstring: 0x10700
   __AUTH_CONST.__objc_const: 0xac48
   __AUTH_CONST.__objc_intobj: 0x948
   __AUTH_CONST.__objc_dictobj: 0x50

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libperfcheck.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 3821
-  Symbols:   9158
-  CStrings:  7214
+  Functions: 3834
+  Symbols:   9178
+  CStrings:  7223
 
Symbols:
+ +[PLFileUtilities statFileAtPath:error:]
+ +[PLFileUtilities statFileAtURL:error:]
+ -[PLLibraryBookmarkManager newSandboxExtensionDataForClient:clientOwnedPath:writable:]
+ -[PLPhotoLibraryPathManagerCore createPrivateDirectoryIfNeededWithBundleIdentifier:]
+ -[PLPhotoLibraryPathManagerCore internalCreateClientOwnedDirectoryAtPath:]
+ -[PLPhotoLibraryPathManagerCore privateDirectoryWithBundleIdentifier:]
+ GCC_except_table1453
+ GCC_except_table1611
+ GCC_except_table1618
+ GCC_except_table1654
+ GCC_except_table1666
+ GCC_except_table1686
+ GCC_except_table1704
+ GCC_except_table1706
+ GCC_except_table1711
+ GCC_except_table1714
+ GCC_except_table1717
+ GCC_except_table1720
+ GCC_except_table1723
+ GCC_except_table1726
+ GCC_except_table1729
+ GCC_except_table1732
+ GCC_except_table1735
+ GCC_except_table1738
+ GCC_except_table1741
+ GCC_except_table1746
+ GCC_except_table1748
+ GCC_except_table1751
+ GCC_except_table1754
+ GCC_except_table1757
+ GCC_except_table1760
+ GCC_except_table1763
+ GCC_except_table1765
+ GCC_except_table1768
+ GCC_except_table1771
+ GCC_except_table1774
+ GCC_except_table1777
+ GCC_except_table1780
+ GCC_except_table1783
+ GCC_except_table1794
+ GCC_except_table1797
+ GCC_except_table1800
+ GCC_except_table1803
+ GCC_except_table1806
+ GCC_except_table1808
+ GCC_except_table1811
+ GCC_except_table1814
+ GCC_except_table1817
+ GCC_except_table1827
+ GCC_except_table1835
+ GCC_except_table1844
+ GCC_except_table1953
+ GCC_except_table1972
+ GCC_except_table2167
+ GCC_except_table2170
+ GCC_except_table2173
+ GCC_except_table2300
+ GCC_except_table2376
+ GCC_except_table2416
+ GCC_except_table2464
+ GCC_except_table2467
+ GCC_except_table2470
+ GCC_except_table2473
+ GCC_except_table2476
+ GCC_except_table2479
+ GCC_except_table2482
+ GCC_except_table2485
+ GCC_except_table2509
+ GCC_except_table2546
+ GCC_except_table2549
+ GCC_except_table2556
+ GCC_except_table2559
+ GCC_except_table2565
+ GCC_except_table2573
+ GCC_except_table2577
+ GCC_except_table2580
+ GCC_except_table2582
+ GCC_except_table2586
+ GCC_except_table2590
+ GCC_except_table2594
+ GCC_except_table2598
+ GCC_except_table2602
+ GCC_except_table2606
+ GCC_except_table2621
+ GCC_except_table2625
+ GCC_except_table2629
+ GCC_except_table2633
+ GCC_except_table2641
+ GCC_except_table2648
+ GCC_except_table2653
+ GCC_except_table2656
+ GCC_except_table2658
+ GCC_except_table2661
+ GCC_except_table2668
+ GCC_except_table2671
+ GCC_except_table2674
+ GCC_except_table2677
+ GCC_except_table2680
+ GCC_except_table2683
+ GCC_except_table2686
+ GCC_except_table2689
+ GCC_except_table2692
+ GCC_except_table2695
+ GCC_except_table2701
+ GCC_except_table2704
+ GCC_except_table2707
+ GCC_except_table2709
+ GCC_except_table2826
+ GCC_except_table2829
+ GCC_except_table2896
+ GCC_except_table2950
+ GCC_except_table2962
+ GCC_except_table2964
+ GCC_except_table2968
+ GCC_except_table2970
+ GCC_except_table2988
+ GCC_except_table2997
+ GCC_except_table3001
+ GCC_except_table3166
+ GCC_except_table3169
+ GCC_except_table3172
+ GCC_except_table3204
+ GCC_except_table3209
+ GCC_except_table3270
+ GCC_except_table3284
+ GCC_except_table3452
+ GCC_except_table3462
+ GCC_except_table3467
+ GCC_except_table3471
+ GCC_except_table3478
+ GCC_except_table3532
+ GCC_except_table3542
+ GCC_except_table3548
+ GCC_except_table3552
+ GCC_except_table3556
+ GCC_except_table3560
+ GCC_except_table3564
+ GCC_except_table3587
+ GCC_except_table3592
+ GCC_except_table3614
+ GCC_except_table3632
+ GCC_except_table3640
+ GCC_except_table3642
+ GCC_except_table3647
+ GCC_except_table3651
+ GCC_except_table3657
+ GCC_except_table3665
+ GCC_except_table3672
+ GCC_except_table3675
+ GCC_except_table3681
+ GCC_except_table3693
+ GCC_except_table3699
+ GCC_except_table3702
+ GCC_except_table3705
+ GCC_except_table3709
+ GCC_except_table3726
+ GCC_except_table3729
+ GCC_except_table3774
+ GCC_except_table3800
+ GCC_except_table3801
+ GCC_except_table3802
+ GCC_except_table3804
+ GCC_except_table3808
+ GCC_except_table3809
+ GCC_except_table3812
+ GCC_except_table3819
+ _PLCanonicalParentPath
+ _PLFileStatResultFileExists
+ _PLGetSandboxExtensionTokenCanonical
+ _PLGetSandboxExtensionTokenForProcessCanonical
+ _PLNoFollowPath
+ _PLVettedResourcePath
+ _SANDBOX_EXTENSION_CANONICAL
+ ___block_descriptor_64_e8_32s40s48s56r_e35_v32?0"NSString"8"NSNumber"16^B24l
+ ___block_descriptor_72_e8_32s40s48s56s64r_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64r
+ ___destroy_helper_block_e8_32s40s48s56s64r
+ _objc_msgSend$createPrivateDirectoryIfNeededWithBundleIdentifier:
+ _objc_msgSend$descriptionWithPath:
+ _objc_msgSend$internalCreateClientOwnedDirectoryAtPath:
+ _objc_msgSend$newSandboxExtensionDataForClient:clientOwnedPath:writable:
+ _objc_msgSend$privateDirectoryWithBundleIdentifier:
+ _objc_msgSend$statFileAtPath:error:
+ _sandbox_check_by_audit_token
- -[PLPhotoLibraryPathManagerCore privateDirectoryWithBundleIdentifier:createIfNeeded:]
- GCC_except_table1451
- GCC_except_table1608
- GCC_except_table1615
- GCC_except_table1651
- GCC_except_table1662
- GCC_except_table1682
- GCC_except_table1698
- GCC_except_table1700
- GCC_except_table1707
- GCC_except_table1710
- GCC_except_table1713
- GCC_except_table1716
- GCC_except_table1719
- GCC_except_table1722
- GCC_except_table1725
- GCC_except_table1728
- GCC_except_table1731
- GCC_except_table1734
- GCC_except_table1737
- GCC_except_table1740
- GCC_except_table1742
- GCC_except_table1747
- GCC_except_table1750
- GCC_except_table1753
- GCC_except_table1756
- GCC_except_table1759
- GCC_except_table1761
- GCC_except_table1764
- GCC_except_table1767
- GCC_except_table1770
- GCC_except_table1773
- GCC_except_table1776
- GCC_except_table1779
- GCC_except_table1782
- GCC_except_table1793
- GCC_except_table1796
- GCC_except_table1799
- GCC_except_table1802
- GCC_except_table1804
- GCC_except_table1807
- GCC_except_table1810
- GCC_except_table1813
- GCC_except_table1823
- GCC_except_table1831
- GCC_except_table1839
- GCC_except_table1948
- GCC_except_table1967
- GCC_except_table2157
- GCC_except_table2163
- GCC_except_table2165
- GCC_except_table2295
- GCC_except_table2365
- GCC_except_table2405
- GCC_except_table2437
- GCC_except_table2442
- GCC_except_table2445
- GCC_except_table2462
- GCC_except_table2465
- GCC_except_table2468
- GCC_except_table2471
- GCC_except_table2474
- GCC_except_table2498
- GCC_except_table2535
- GCC_except_table2538
- GCC_except_table2540
- GCC_except_table2545
- GCC_except_table2548
- GCC_except_table2554
- GCC_except_table2558
- GCC_except_table2566
- GCC_except_table2571
- GCC_except_table2575
- GCC_except_table2579
- GCC_except_table2583
- GCC_except_table2587
- GCC_except_table2591
- GCC_except_table2595
- GCC_except_table2599
- GCC_except_table2603
- GCC_except_table2607
- GCC_except_table2622
- GCC_except_table2626
- GCC_except_table2630
- GCC_except_table2634
- GCC_except_table2639
- GCC_except_table2642
- GCC_except_table2644
- GCC_except_table2647
- GCC_except_table2652
- GCC_except_table2657
- GCC_except_table2660
- GCC_except_table2669
- GCC_except_table2672
- GCC_except_table2675
- GCC_except_table2678
- GCC_except_table2681
- GCC_except_table2684
- GCC_except_table2687
- GCC_except_table2690
- GCC_except_table2693
- GCC_except_table2696
- GCC_except_table2815
- GCC_except_table2818
- GCC_except_table2885
- GCC_except_table2939
- GCC_except_table2951
- GCC_except_table2953
- GCC_except_table2957
- GCC_except_table2959
- GCC_except_table2977
- GCC_except_table2986
- GCC_except_table2990
- GCC_except_table3139
- GCC_except_table3144
- GCC_except_table3158
- GCC_except_table3193
- GCC_except_table3198
- GCC_except_table3259
- GCC_except_table3262
- GCC_except_table3439
- GCC_except_table3449
- GCC_except_table3454
- GCC_except_table3458
- GCC_except_table3465
- GCC_except_table3519
- GCC_except_table3522
- GCC_except_table3529
- GCC_except_table3539
- GCC_except_table3543
- GCC_except_table3547
- GCC_except_table3551
- GCC_except_table3574
- GCC_except_table3579
- GCC_except_table3588
- GCC_except_table3619
- GCC_except_table3627
- GCC_except_table3629
- GCC_except_table3634
- GCC_except_table3638
- GCC_except_table3644
- GCC_except_table3649
- GCC_except_table3652
- GCC_except_table3655
- GCC_except_table3659
- GCC_except_table3673
- GCC_except_table3676
- GCC_except_table3680
- GCC_except_table3683
- GCC_except_table3692
- GCC_except_table3700
- GCC_except_table3716
- GCC_except_table3761
- GCC_except_table3787
- GCC_except_table3788
- GCC_except_table3789
- GCC_except_table3791
- GCC_except_table3793
- GCC_except_table3795
- GCC_except_table3796
- GCC_except_table3799
- ___block_descriptor_56_e8_32s40s48r_e35_v32?0"NSString"8"NSNumber"16^B24l
- ___block_descriptor_64_e8_32s40s48s56r_e5_v8?0l
- _objc_msgSend$privateDirectoryWithBundleIdentifier:createIfNeeded:
CStrings:
+ "/.nofollow"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Photos/Projects/PhotoLibraryServicesCore/Sources/PLTaggedPointer.m"
+ "Failed to create client-owned directory %@: %@"
+ "Failed to remove non-directory at client-owned path %@ (%{darwin.errno}d)"
+ "Not creating client-owned directory %@: %@"
+ "Refusing to map '%@': redirected or non-regular."
+ "Replacing non-directory at client-owned path %@"
+ "createPrivateDirectoryIfNeededWithBundleIdentifier:"
+ "internalCreateClientOwnedDirectoryAtPath:"
+ "newSandboxExtensionDataForClient:clientOwnedPath:writable:"
+ "privateDirectoryWithBundleIdentifier:"
+ "statFileAtPath:error:"
+ "statFileAtURL:error:"
- "-[PLPhotoLibraryPathManagerCore privateDirectoryWithBundleIdentifier:createIfNeeded:]"
- "-[PLPhotoLibraryPathManagerUBF _externalDirectoryWithBundleIdentifier:createIfNeeded:]"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Photos/Projects/PhotoLibraryServicesCore/Sources/PLTaggedPointer.m"
- "privateDirectoryWithBundleIdentifier:createIfNeeded:"
```
