## com.apple.StreamingUnzipService

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/A/XPCServices/com.apple.StreamingUnzipService.xpc/Contents/MacOS/com.apple.StreamingUnzipService`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA.__objc_const`
- `__DATA.__objc_protorefs`
- `__DATA.__objc_classrefs`
- `__DATA.__objc_superrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-226.120.1.0.0
-  __TEXT.__text: 0x1c098
-  __TEXT.__auth_stubs: 0xa10
-  __TEXT.__objc_stubs: 0x2480
-  __TEXT.__objc_methlist: 0xeac
+226.120.1.700.1
+  __TEXT.__text: 0x1cfd0
+  __TEXT.__auth_stubs: 0xaa0
+  __TEXT.__objc_stubs: 0x24a0
+  __TEXT.__objc_methlist: 0xec4
   __TEXT.__const: 0x158
-  __TEXT.__cstring: 0x50a0
+  __TEXT.__cstring: 0x5626
   __TEXT.__gcc_except_tab: 0x2b8
-  __TEXT.__objc_classname: 0x1d2
-  __TEXT.__objc_methname: 0x3004
-  __TEXT.__objc_methtype: 0xddb
+  __TEXT.__objc_classname: 0x1dd
+  __TEXT.__objc_methname: 0x3045
+  __TEXT.__objc_methtype: 0xdf8
   __TEXT.__oslogstring: 0x6fb
-  __TEXT.__unwind_info: 0x3b8
+  __TEXT.__unwind_info: 0x3c8
   __TEXT.__eh_frame: 0xb4
-  __DATA_CONST.__auth_got: 0x518
+  __DATA_CONST.__auth_got: 0x560
   __DATA_CONST.__got: 0x88
   __DATA_CONST.__auth_ptr: 0x18
   __DATA_CONST.__const: 0x720
-  __DATA_CONST.__cfstring: 0x27e0
+  __DATA_CONST.__cfstring: 0x2a60
   __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA.__objc_const: 0x1b40
-  __DATA.__objc_selrefs: 0xaa0
+  __DATA.__objc_selrefs: 0xaa8
   __DATA.__objc_protorefs: 0x10
   __DATA.__objc_classrefs: 0x108
   __DATA.__objc_superrefs: 0x38
   __DATA.__objc_ivar: 0x16c
   __DATA.__objc_data: 0x2d0
   __DATA.__data: 0x4b0
-  __DATA.__bss: 0xb1
+  __DATA.__bss: 0xc1
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
+  - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /usr/lib/libSystem.B.dylib
+  - /usr/lib/libbsm.0.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 347
-  Symbols:   213
-  CStrings:  1187
+  Functions: 350
+  Symbols:   222
+  CStrings:  1212
 
Symbols:
+ _SecTaskCreateWithAuditToken
+ _SecTaskGetCodeSignStatus
+ __qtn_proc_alloc
+ __qtn_proc_apply_to_self
+ __qtn_proc_free
+ __qtn_proc_get_flags
+ _audit_token_to_pid
+ _csops_audittoken
+ _qtn_proc_init_with_pid
CStrings:
+ "22:15:48"
+ "B72@0:8^B16{?=[8I]}24@56^@64"
+ "Caller %@ has %@ entitlement; forcing untrusted quarantine handling"
+ "Caller %@ has %@ entitlement; trusting any supplied quarantine parameters, or none if unspecified"
+ "Caller %@ has process quarantine flags 0x%x"
+ "Caller %@ is NOT a platform binary (csFlags 0x%x, validation category %u); ignoring supplied quarantine parameters, and adopting caller's process quarantine state"
+ "Caller %@ is a platform binary; trusting any supplied quarantine parameters, or none if unspecified"
+ "Caller %@ is not quarantined"
+ "Caller %@ quarantine flags 0x%x already adopted; skipping redundant apply"
+ "Failed to apply caller %@ quarantine state to extractor process."
+ "Failed to create qtn_proc object."
+ "Failed to read quarantine state for caller %@."
+ "Failed to read quarantine state for caller %@: QTN_MATCH_UNAVAILABLE"
+ "Failed to read quarantine state for caller %@: unknown quarantine error %d"
+ "Failed to read validation category for caller %@: %s; treating as NOT a platform binary"
+ "IPCSupport"
+ "Nov  8 2026"
+ "Quarantine is unavailable/not supported; treating caller %@ as not quarantined"
+ "SZExtractorQuarantineErrorDomain"
+ "SecTaskCreateWithAuditToken failed for caller %@."
+ "Unable to determine quarantine state for caller %@."
+ "Unexpectedly handling IPC without necessary support compiled in!"
+ "Unknown Process Name"
+ "_AdoptCallerQuarantineState"
+ "_GetCallerIsTrustedQuarantineProvider"
+ "_getShouldTrustQuarantineOptions:forAuditToken:connection:error:"
+ "com.apple.private.SZExtractor.force-untrusted-quarantine-provider"
+ "com.apple.private.SZExtractor.trusted-quarantine-provider"
- "21:32:04"
- "Nov  2 2026"
- "Unknown Process Name (pid %d)"
```
