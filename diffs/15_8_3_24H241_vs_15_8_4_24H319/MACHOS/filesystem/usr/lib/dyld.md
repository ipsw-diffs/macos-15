## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`

```diff

 1286.12.0.0.0
   __TEXT.__text: 0x876bc
   __TEXT.__const: 0x2420
-  __TEXT.__cstring: 0x1012a
+  __TEXT.__cstring: 0x10144
   __TEXT.__unwind_info: 0x4a8
   __DATA_CONST.__auth_ptr: 0x80
   __DATA_CONST.__const: 0x76e8
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/libignition/install/Symbols/ignition_core"
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Mon Nov  9 22:17:05 PST 2026; root:libignition-56~62749/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Mon Nov  9 22:17:05 PST 2026; root:libignition-56~62749/libignition_core/RELEASE_ARM64E"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/libignition/install/Symbols/ignition_core"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Sun Oct 11 23:13:40 PDT 2026; root:libignition-56~62713/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Sun Oct 11 23:13:40 PDT 2026; root:libignition-56~62713/libignition_core/RELEASE_ARM64E"
```
