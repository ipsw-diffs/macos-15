## secd

> `/usr/libexec/secd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-61439.140.12.709.1
+61439.140.12.708.12
   __TEXT.__text: 0x2646cc
   __TEXT.__auth_stubs: 0x37a0
   __TEXT.__objc_stubs: 0x1ae80
   __TEXT.__objc_methlist: 0x147d8
   __TEXT.__const: 0x3ec
-  __TEXT.__cstring: 0x1f387
+  __TEXT.__cstring: 0x1f353
   __TEXT.__oslogstring: 0x295c1
   __TEXT.__dlopen_cstrs: 0x172
   __TEXT.__gcc_except_tab: 0xade4
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleCredentialManager_ClientLibs/ACMLib/ACMLib.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleCredentialManager_ClientLibs/common/LibCall.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleCredentialManager_ClientLibs/ACMLib/ACMLib.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleCredentialManager_ClientLibs/common/LibCall.c"
```
