## libmalloc_exclaves_introspector

> `/System/Library/PrivateFrameworks/libmalloc_exclaves_introspector.framework/Versions/A/libmalloc_exclaves_introspector`

```diff

   __TEXT.__text: 0x3e2c
   __TEXT.__auth_stubs: 0x210
   __TEXT.__const: 0x83
-  __TEXT.__cstring: 0x1b83
+  __TEXT.__cstring: 0x1b4f
   __TEXT.__unwind_info: 0x108
   __DATA_CONST.__got: 0x20
   __DATA_CONST.__const: 0x128
CStrings:
+ "BUG IN LIBMALLOC: malloc assertion \"main_address\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc_frameworks/src/xzone/xzone_introspect.c:781)"
+ "BUG IN LIBMALLOC: malloc assertion \"zone\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libmalloc_frameworks/src/xzone/xzone_introspect.c:779)"
- "BUG IN LIBMALLOC: malloc assertion \"main_address\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone/xzone_introspect.c:781)"
- "BUG IN LIBMALLOC: malloc assertion \"zone\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/libmalloc_frameworks/src/xzone/xzone_introspect.c:779)"
```
