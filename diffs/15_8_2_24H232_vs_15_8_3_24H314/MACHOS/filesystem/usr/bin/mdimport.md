## mdimport

> `/usr/bin/mdimport`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

   __TEXT.__objc_methlist: 0xd4
   __TEXT.__const: 0x14f8
   __TEXT.__gcc_except_tab: 0x288
-  __TEXT.__cstring: 0x6cfd
+  __TEXT.__cstring: 0x6d31
   __TEXT.__objc_methname: 0xda3
   __TEXT.__oslogstring: 0x8b0
   __TEXT.__objc_classname: 0x2f
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Spotlight_executables/spotlight/generic/MDSFileProcessor.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/file/file/src/softmagic.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Spotlight_executables/spotlight/generic/MDSFileProcessor.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/file/file/src/softmagic.c"
```
