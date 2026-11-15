## apfs_invert

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_invert`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.705.3
-  __TEXT.__text: 0x5400c
+2332.140.13.704.3
+  __TEXT.__text: 0x53fc0
   __TEXT.__auth_stubs: 0x7e0
-  __TEXT.__cstring: 0x11b9b
+  __TEXT.__cstring: 0x11afb
   __TEXT.__const: 0x8378
   __TEXT.__unwind_info: 0x950
   __DATA_CONST.__auth_got: 0x3f0

   - /usr/lib/libutil.dylib
   Functions: 760
   Symbols:   141
-  CStrings:  1456
+  CStrings:  1455
 
Functions:
~ sub_1000477e0 : 6580 -> 6512
~ sub_100053338 -> sub_1000532f4 : 100 -> 92
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/fusion_mt.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/jobj_snap.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apfs_executables/nx/obj.c"
+ "2332.140.13.704.3"
- "%s:%d: %s error: chunk info index %u out of range for cib %u chunk info count %u\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/fusion_mt.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/jobj_snap.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apfs_executables/nx/obj.c"
- "2332.140.13.705.3"
```
