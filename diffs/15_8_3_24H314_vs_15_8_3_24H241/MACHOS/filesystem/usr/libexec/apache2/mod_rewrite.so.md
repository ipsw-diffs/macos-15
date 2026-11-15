## mod_rewrite.so

> `/usr/libexec/apache2/mod_rewrite.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 880.0.0.701.1
   __TEXT.__text: 0xf080
   __TEXT.__auth_stubs: 0x930
-  __TEXT.__cstring: 0x1fb3
+  __TEXT.__cstring: 0x1f99
   __TEXT.__const: 0x211
   __TEXT.__unwind_info: 0xe8
   __DATA_CONST.__auth_got: 0x498
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apache/httpd/modules/mappers/mod_rewrite.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apache/httpd/modules/mappers/mod_rewrite.c"
```
