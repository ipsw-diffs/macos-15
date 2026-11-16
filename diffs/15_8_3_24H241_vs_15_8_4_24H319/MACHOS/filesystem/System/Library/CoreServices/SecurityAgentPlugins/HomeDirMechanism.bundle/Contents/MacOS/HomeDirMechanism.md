## HomeDirMechanism

> `/System/Library/CoreServices/SecurityAgentPlugins/HomeDirMechanism.bundle/Contents/MacOS/HomeDirMechanism`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-109.0.0.0.0
-  __TEXT.__text: 0x5b14
-  __TEXT.__auth_stubs: 0x4d0
+109.100.0.0.0
+  __TEXT.__text: 0x6260
+  __TEXT.__auth_stubs: 0x540
   __TEXT.__objc_stubs: 0xe00
   __TEXT.__objc_methlist: 0x424
   __TEXT.__gcc_except_tab: 0x38
-  __TEXT.__cstring: 0x1e3d
+  __TEXT.__cstring: 0x217a
   __TEXT.__objc_classname: 0x9b
   __TEXT.__objc_methname: 0xc3f
   __TEXT.__objc_methtype: 0x4da
-  __TEXT.__unwind_info: 0x188
-  __DATA_CONST.__auth_got: 0x278
+  __TEXT.__unwind_info: 0x190
+  __DATA_CONST.__auth_got: 0x2b0
   __DATA_CONST.__got: 0x128
+  __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0xb0
   __DATA_CONST.__cfstring: 0x10c0
   __DATA_CONST.__objc_classlist: 0x30

   - /usr/lib/libcsfde.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsandbox.1.dylib
-  Functions: 99
-  Symbols:   156
-  CStrings:  412
+  Functions: 102
+  Symbols:   164
+  CStrings:  431
 
Symbols:
+ ___chkstk_darwin
+ ___memcpy_chk
+ ___memmove_chk
+ ___strlcpy_chk
+ _getattrlist
+ _readlink
+ _snprintf
+ _strchr
CStrings:
+ "%s%s"
+ "%s/%.*s"
+ "ERROR | %s | %s: %s is not a directory (%s)"
+ "ERROR | %s | %s: %s links to an unsupported target (%s)"
+ "ERROR | %s | %s: cannot look up %s (errno %d) (%s)"
+ "ERROR | %s | %s: cannot readlink %s (errno %d) (%s)"
+ "ERROR | %s | %s: cannot stat (errno %d) (%s)"
+ "ERROR | %s | %s: exists but is not a directory (%s)"
+ "ERROR | %s | %s: path contains a '.' or '..' component (%s)"
+ "ERROR | %s | %s: path is not absolute (%s)"
+ "ERROR | %s | %s: path is too long (%s)"
+ "ERROR | %s | %s: path is too long after %s (%s)"
+ "ERROR | %s | %s: too many symlinks (%s)"
+ "ERROR | %s | Refusing network home premount: path contains a '.' or '..' component (home=%s path=%s)"
+ "Refusing network home premount: derived mount point"
+ "Refusing network home premount: home path"
+ "Refusing to mount home directory"
+ "hdmHomePathIsAbsentOrDirectory"
+ "hdmStatIsAbsentOrDirectory"
```
