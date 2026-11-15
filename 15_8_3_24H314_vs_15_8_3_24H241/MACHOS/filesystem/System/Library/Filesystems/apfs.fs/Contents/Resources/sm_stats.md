## sm_stats

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/sm_stats`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.705.3
-  __TEXT.__text: 0x458bc
+2332.140.13.704.3
+  __TEXT.__text: 0x4587c
   __TEXT.__auth_stubs: 0x720
-  __TEXT.__cstring: 0xdada
+  __TEXT.__cstring: 0xda54
   __TEXT.__const: 0x278
   __TEXT.__unwind_info: 0x760
   __DATA_CONST.__auth_got: 0x390

   - /usr/lib/libutil.dylib
   Functions: 602
   Symbols:   128
-  CStrings:  1107
+  CStrings:  1106
 
Functions:
~ sub_10000b730 : 6580 -> 6512
~ sub_100026e90 -> sub_100026e4c : 496 -> 500
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/fusion_mt.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/obj.c"
- "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/fusion_mt.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/obj.c"
```
