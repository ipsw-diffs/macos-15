## slurpAPFSMeta

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/slurpAPFSMeta`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.704.3
-  __TEXT.__text: 0x38e14
+2332.140.13.705.3
+  __TEXT.__text: 0x38e54
   __TEXT.__auth_stubs: 0x830
-  __TEXT.__cstring: 0x976e
+  __TEXT.__cstring: 0x97f4
   __TEXT.__const: 0x260
   __TEXT.__unwind_info: 0x6e0
   __DATA_CONST.__auth_got: 0x418

   - /usr/lib/libSystem.B.dylib
   Functions: 545
   Symbols:   144
-  CStrings:  806
+  CStrings:  807
 
Functions:
~ sub_10001fe20 : 6512 -> 6580
~ sub_100027c50 -> sub_100027c94 : 176 -> 172
CStrings:
+ "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/fusion_mt.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/obj.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/fusion_mt.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/obj.c"
```
