## apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_vol_converter`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.704.3
-  __TEXT.__text: 0x595e8
+2332.140.13.705.3
+  __TEXT.__text: 0x59634
   __TEXT.__auth_stubs: 0x9d0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x12883
+  __TEXT.__cstring: 0x1293d
   __TEXT.__const: 0x320
   __TEXT.__gcc_except_tab: 0x5a4
   __TEXT.__unwind_info: 0xbe8

   - /usr/lib/libutil.dylib
   Functions: 865
   Symbols:   181
-  CStrings:  1644
+  CStrings:  1645
 
Functions:
~ sub_10004c4dc : 6512 -> 6580
~ sub_100059c1c -> sub_100059c60 : 92 -> 100
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/fscommon/purging.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/fusion_mt.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/jobj_snap.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/obj.c"
+ "2332.140.13.705.3"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/fscommon/purging.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/fusion_mt.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/jobj_snap.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/obj.c"
- "2332.140.13.704.3"
```
