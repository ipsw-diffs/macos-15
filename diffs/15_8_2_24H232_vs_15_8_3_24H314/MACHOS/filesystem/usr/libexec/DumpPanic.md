## DumpPanic

> `/usr/libexec/DumpPanic`

### Sections with Same Size but Changed Content

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-326.100.5.702.1
-  __TEXT.__text: 0x27c88
-  __TEXT.__auth_stubs: 0xe30
-  __TEXT.__objc_stubs: 0x1f60
-  __TEXT.__objc_methlist: 0x640
-  __TEXT.__const: 0x2ba
-  __TEXT.__cstring: 0x2ab3
-  __TEXT.__objc_methname: 0x1990
+326.100.5.703.1
+  __TEXT.__text: 0x28b94
+  __TEXT.__auth_stubs: 0xec0
+  __TEXT.__objc_stubs: 0x1fc0
+  __TEXT.__objc_methlist: 0x658
+  __TEXT.__const: 0x2c2
+  __TEXT.__cstring: 0x2a97
+  __TEXT.__objc_methname: 0x19fa
   __TEXT.__constg_swiftt: 0x70
   __TEXT.__swift5_typeref: 0x47
   __TEXT.__swift5_reflstr: 0x1b
   __TEXT.__swift5_fieldmd: 0x28
-  __TEXT.__oslogstring: 0x4edc
+  __TEXT.__oslogstring: 0x53c6
   __TEXT.__swift5_types: 0x4
-  __TEXT.__gcc_except_tab: 0xc78
+  __TEXT.__gcc_except_tab: 0xc84
   __TEXT.__objc_classname: 0xde
   __TEXT.__objc_methtype: 0x427
-  __TEXT.__unwind_info: 0x5e0
-  __DATA_CONST.__auth_got: 0x728
+  __TEXT.__unwind_info: 0x5e8
+  __DATA_CONST.__auth_got: 0x770
   __DATA_CONST.__got: 0x1f8
   __DATA_CONST.__auth_ptr: 0x50
   __DATA_CONST.__const: 0x740

   __DATA_CONST.__objc_arraydata: 0x1d8
   __DATA_CONST.__objc_arrayobj: 0x150
   __DATA_CONST.__objc_dictobj: 0x140
-  __DATA.__objc_const: 0xda0
-  __DATA.__objc_selrefs: 0x848
-  __DATA.__objc_ivar: 0xb0
+  __DATA.__objc_const: 0xe00
+  __DATA.__objc_selrefs: 0x860
+  __DATA.__objc_ivar: 0xbc
   __DATA.__objc_data: 0x4b0
   __DATA.__data: 0x180
   __DATA.__bss: 0xa60

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 480
-  Symbols:   329
-  CStrings:  1251
+  Functions: 483
+  Symbols:   339
+  CStrings:  1282
 
Symbols:
+ __os_log_fault_impl
+ _arc4random
+ _dirname_r
+ _fdopen
+ _fgetxattr
+ _fsetxattr
+ _geteuid
+ _gzdopen
+ _mkstemp
+ _openat
+ _renameat
+ _snprintf
+ _unlinkat
- _getxattr
- _mktemp
- _rename
CStrings:
+ "%s no longer refers to the core we processed, not removing it"
+ "/private/var/tmp/panicregion.XXXXXXXX"
+ "2"
+ "Cannot remove untrusted staged '%{public}@' : %{public}@"
+ "DumpPanicDone cookie already exists at path %s"
+ "DumpPanicDone cookie at %s is not the file we wrote (mode 0%o uid %u)"
+ "Failed to open %s core compressed output file"
+ "Failed to rename compressed %s from %s to %s with error : %s"
+ "_input_core_dev"
+ "_input_core_fd"
+ "_input_core_ino"
+ "closeInputCore"
+ "directory %s was not owned by root:wheel (uid %u gid %u), taking ownership"
+ "failed to create DumpPanicDone cookie at path %s with error %s"
+ "failed to create a temporary file for the panic region. Error: %s"
+ "failed to create staged file %s with error: %s"
+ "failed to derive the directory holding %s with error: %s"
+ "failed to open directory %s with error: %s"
+ "failed to open the directory holding %s with error: %s"
+ "failed to remove %s with error: %s"
+ "fdopen of %s failed with error: %s"
+ "fgetxattr %s returned error : %s"
+ "fileSystemRepresentation"
+ "fstat of %s failed with error: %s"
+ "fstat of directory %s failed with error: %s"
+ "gzdopen of %s/%s failed"
+ "gzdopen(%s, wb) error: %s"
+ "lstat of %s failed with error: %s"
+ "lstat of staged '%{public}@' failed with error %s"
+ "open(%s) error: %s"
+ "refusing core at %s : not a regular file (mode 0%o)"
+ "refusing core at %s : owned by uid %u and not from a directory only uid %u can write"
+ "refusing core at %s : unexpected link count %u"
+ "refusing core at %s : writable by others (mode 0%o)"
+ "refusing to pull in staged '%{public}@' : not a file we wrote (mode 0%o uid %u nlink %u)"
+ "refusing untrusted directory %s (uid %u mode 0%o)"
+ "removeOriginalCore"
+ "staging compressed %s core at %s/%s"
+ "tempUserSpaceCore.%08x%08x"
- "/private/var/tmp/kernel_panics/staged/tempUserSpaceCore.XXX"
- "/private/var/tmp/panicregion.XXX"
- "Failed to open %s core compressed output file with error %s"
- "Failed to rename compressed %s from %s to %s"
- "failed to creat() DumpPanicDone cookie at path %s with error %s"
- "getxattr %s returned error : %s"
- "gzopen %s"
- "gzopen(%s, wb) error: %s"
```
