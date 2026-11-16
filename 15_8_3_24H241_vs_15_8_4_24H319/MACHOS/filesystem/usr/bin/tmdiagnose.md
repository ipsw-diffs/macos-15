## tmdiagnose

> `/usr/bin/tmdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2436.2.1.0.0
+2436.2.2.0.0
   __TEXT.__text: 0xc668
   __TEXT.__auth_stubs: 0x640
   __TEXT.__objc_stubs: 0x2560
   __TEXT.__objc_methlist: 0xb9c
   __TEXT.__const: 0x40
   __TEXT.__gcc_except_tab: 0xfc
-  __TEXT.__cstring: 0x2c96
+  __TEXT.__cstring: 0x2cb0
   __TEXT.__objc_classname: 0x106
   __TEXT.__objc_methname: 0x224d
   __TEXT.__objc_methtype: 0x585
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/tmdiagnose/TMTaskAuthority.m"
+ "Nov 12 2026"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/tmdiagnose/TMTaskAuthority.m"
- "Oct 12 2026"
```
