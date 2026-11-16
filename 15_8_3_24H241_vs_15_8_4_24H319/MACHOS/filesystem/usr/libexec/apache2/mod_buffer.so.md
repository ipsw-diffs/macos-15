## mod_buffer.so

> `/usr/libexec/apache2/mod_buffer.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 880.0.0.701.1
   __TEXT.__text: 0xf0c
   __TEXT.__auth_stubs: 0xe0
-  __TEXT.__cstring: 0x115
+  __TEXT.__cstring: 0x12f
   __TEXT.__const: 0x7
   __TEXT.__unwind_info: 0x58
   __DATA_CONST.__auth_got: 0x70
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apache/httpd/modules/filters/mod_buffer.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apache/httpd/modules/filters/mod_buffer.c"
```
