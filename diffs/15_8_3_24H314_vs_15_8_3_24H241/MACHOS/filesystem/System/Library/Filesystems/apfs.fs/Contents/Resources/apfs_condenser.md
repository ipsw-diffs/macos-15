## apfs_condenser

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_condenser`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2332.140.13.705.3
-  __TEXT.__text: 0x4f670
+2332.140.13.704.3
+  __TEXT.__text: 0x4f624
   __TEXT.__auth_stubs: 0x8b0
-  __TEXT.__cstring: 0x10a56
+  __TEXT.__cstring: 0x109b6
   __TEXT.__const: 0x2c0
   __TEXT.__unwind_info: 0x878
   __DATA_CONST.__auth_got: 0x458

   - /usr/lib/libutil.dylib
   Functions: 695
   Symbols:   157
-  CStrings:  1363
+  CStrings:  1362
 
Functions:
~ sub_100043c5c : 6580 -> 6512
~ sub_10004f704 -> sub_10004f6c0 : 100 -> 92
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
