## apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_checkseal`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.705.3
-  __TEXT.__text: 0x51848
+2332.140.13.704.3
+  __TEXT.__text: 0x517fc
   __TEXT.__auth_stubs: 0x770
   __TEXT.__const: 0x570
-  __TEXT.__cstring: 0x10fef
+  __TEXT.__cstring: 0x10f4f
   __TEXT.__unwind_info: 0x938
   __DATA_CONST.__auth_got: 0x3b8
   __DATA_CONST.__got: 0x50

   - /usr/lib/libutil.dylib
   Functions: 755
   Symbols:   133
-  CStrings:  1359
+  CStrings:  1358
 
Functions:
~ sub_1000444c8 : 6580 -> 6512
~ sub_100051aa4 -> sub_100051a60 : 100 -> 92
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/fusion_mt.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/jobj_snap.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/obj.c"
- "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/fusion_mt.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/jobj_snap.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/obj.c"
```
