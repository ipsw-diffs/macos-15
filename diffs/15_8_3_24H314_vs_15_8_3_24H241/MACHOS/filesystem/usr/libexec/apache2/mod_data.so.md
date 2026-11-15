## mod_data.so

> `/usr/libexec/apache2/mod_data.so`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

 880.0.0.701.1
   __TEXT.__text: 0x988
   __TEXT.__auth_stubs: 0x150
-  __TEXT.__cstring: 0xe5
+  __TEXT.__cstring: 0xcb
   __TEXT.__const: 0x28
   __TEXT.__unwind_info: 0x60
   __DATA_CONST.__auth_got: 0xa8
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apache/httpd/modules/filters/mod_data.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apache/httpd/modules/filters/mod_data.c"
```
