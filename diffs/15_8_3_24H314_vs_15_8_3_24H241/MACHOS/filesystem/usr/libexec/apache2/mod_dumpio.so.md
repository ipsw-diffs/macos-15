## mod_dumpio.so

> `/usr/libexec/apache2/mod_dumpio.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 880.0.0.701.1
   __TEXT.__text: 0x1780
   __TEXT.__auth_stubs: 0xa0
-  __TEXT.__cstring: 0x23c
+  __TEXT.__cstring: 0x222
   __TEXT.__unwind_info: 0x70
   __DATA_CONST.__auth_got: 0x50
   __DATA_CONST.__got: 0x8
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apache/httpd/modules/debugging/mod_dumpio.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apache/httpd/modules/debugging/mod_dumpio.c"
```
