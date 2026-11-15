## smbd

> `/usr/sbin/smbd`

### Sections with Same Size but Changed Content

- `__TEXT.__dof_ntvfs`
- `__TEXT.__dof_smbd`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

   __TEXT.__const: 0x1277
   __TEXT.__gcc_except_tab: 0x5dcc
   __TEXT.__oslogstring: 0x9f61
-  __TEXT.__cstring: 0x10475
+  __TEXT.__cstring: 0x10441
   __TEXT.__dof_ntvfs: 0x1eed
   __TEXT.__dof_smbd: 0x7aa
   __TEXT.__unwind_info: 0x21e8
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/smbx/ext/gflags-1.1/src/gflags_reporting.cc"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/smbx/src/cmd/smbd/smbd.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/smbx/ext/gflags-1.1/src/gflags_reporting.cc"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/smbx/src/cmd/smbd/smbd.cpp"
```
