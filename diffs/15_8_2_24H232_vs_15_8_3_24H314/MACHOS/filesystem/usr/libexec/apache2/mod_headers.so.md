## mod_headers.so

> `/usr/libexec/apache2/mod_headers.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 880.0.0.701.1
   __TEXT.__text: 0x2c4c
   __TEXT.__auth_stubs: 0x380
-  __TEXT.__cstring: 0x5c6
+  __TEXT.__cstring: 0x5e0
   __TEXT.__const: 0x2
   __TEXT.__unwind_info: 0x78
   __DATA_CONST.__auth_got: 0x1c0
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apache/httpd/modules/metadata/mod_headers.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apache/httpd/modules/metadata/mod_headers.c"
```
