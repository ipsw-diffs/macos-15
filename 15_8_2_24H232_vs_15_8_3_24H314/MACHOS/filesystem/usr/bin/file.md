## file

> `/usr/bin/file`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

   __TEXT.__text: 0x15c44
   __TEXT.__auth_stubs: 0x7f0
   __TEXT.__const: 0x13fd
-  __TEXT.__cstring: 0x4151
+  __TEXT.__cstring: 0x416b
   __TEXT.__unwind_info: 0x2d8
   __DATA_CONST.__auth_got: 0x3f8
   __DATA_CONST.__got: 0x38
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/file/file/src/softmagic.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/file/file/src/softmagic.c"
```
