## mod_proxy.so

> `/usr/libexec/apache2/mod_proxy.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 880.0.0.701.1
   __TEXT.__text: 0x28168
   __TEXT.__auth_stubs: 0x1140
-  __TEXT.__cstring: 0x4d0e
+  __TEXT.__cstring: 0x4d42
   __TEXT.__unwind_info: 0x1b8
   __DATA_CONST.__auth_got: 0x8a0
   __DATA_CONST.__got: 0x80
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apache/httpd/modules/proxy/mod_proxy.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/apache/httpd/modules/proxy/proxy_util.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apache/httpd/modules/proxy/mod_proxy.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/apache/httpd/modules/proxy/proxy_util.c"
```
