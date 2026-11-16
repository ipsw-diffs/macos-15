## StreamingZip

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/A/StreamingZip`

```diff

-226.120.1.0.0
-  __TEXT.__text: 0x27784
-  __TEXT.__auth_stubs: 0xcd0
+226.120.1.700.1
+  __TEXT.__text: 0x27b44
+  __TEXT.__auth_stubs: 0xce0
   __TEXT.__objc_methlist: 0xe84
   __TEXT.__const: 0x150
-  __TEXT.__cstring: 0x8761
+  __TEXT.__cstring: 0x8818
   __TEXT.__gcc_except_tab: 0x2b8
   __TEXT.__oslogstring: 0x544
-  __TEXT.__unwind_info: 0x458
+  __TEXT.__unwind_info: 0x460
   __TEXT.__eh_frame: 0xb4
   __TEXT.__objc_classname: 0x1b3
-  __TEXT.__objc_methname: 0x2fed
+  __TEXT.__objc_methname: 0x3040
   __TEXT.__objc_methtype: 0xd9f
-  __TEXT.__objc_stubs: 0x2420
+  __TEXT.__objc_stubs: 0x2460
   __DATA_CONST.__got: 0xb8
-  __DATA_CONST.__const: 0x768
+  __DATA_CONST.__const: 0x770
   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa98
-  __AUTH_CONST.__auth_got: 0x678
+  __DATA_CONST.__objc_selrefs: 0xaa8
+  __AUTH_CONST.__auth_got: 0x680
   __AUTH_CONST.__const: 0x620
-  __AUTH_CONST.__cfstring: 0x4680
+  __AUTH_CONST.__cfstring: 0x4720
   __AUTH_CONST.__objc_const: 0x1a30
   __AUTH.__objc_data: 0x280
   __DATA.__objc_protorefs: 0x10

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 394
-  Symbols:   1286
-  CStrings:  1504
+  Functions: 395
+  Symbols:   1291
+  CStrings:  1511
 
Symbols:
+ GCC_except_table351
+ GCC_except_table359
+ GCC_except_table384
+ _CopyClientNameForConnection
+ _SZExtractorQuarantineErrorDomain
+ _objc_msgSend$_getShouldTrustQuarantineOptions:forAuditToken:connection:error:
+ _objc_msgSend$processIdentifier
+ _proc_pidpath
- GCC_except_table350
- GCC_except_table358
- GCC_except_table383
Functions:
~ -[StreamingUnzipper setupUnzipperWithOutputPath:sandboxExtensionToken:options:withReply:] : 1768 -> 2440
+ _CopyClientNameForConnection
CStrings:
+ "%@ (pid %d)"
+ "SZExtractorQuarantineErrorDomain"
+ "Unable to determine quarantine state for caller %@."
+ "Unexpectedly handling IPC without necessary support compiled in!"
+ "Unknown Process Name"
+ "_getShouldTrustQuarantineOptions:forAuditToken:connection:error:"
+ "processIdentifier"
```
