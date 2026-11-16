## libcups.2.dylib

> `/usr/lib/libcups.2.dylib`

```diff

-513.9.6.0.0
-  __TEXT.__text: 0x4a5e8
-  __TEXT.__auth_stubs: 0x1440
+513.9.7.0.0
+  __TEXT.__text: 0x4a6f4
+  __TEXT.__auth_stubs: 0x1460
   __TEXT.__const: 0x360
-  __TEXT.__cstring: 0x10f5d
+  __TEXT.__cstring: 0x10f79
+  __TEXT.__oslogstring: 0x28
   __TEXT.__unwind_info: 0xa20
   __TEXT.__eh_frame: 0x40
-  __DATA_CONST.__got: 0x160
+  __DATA_CONST.__got: 0x168
   __DATA_CONST.__const: 0x7a80
-  __AUTH_CONST.__auth_got: 0xa20
+  __AUTH_CONST.__auth_got: 0xa30
   __AUTH_CONST.__const: 0xb0
   __AUTH_CONST.__cfstring: 0x3e0
   __AUTH.__data: 0x28

   - /usr/lib/libiconv.2.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 804
-  Symbols:   972
-  CStrings:  3797
+  Functions: 805
+  Symbols:   975
+  CStrings:  3799
 
Symbols:
+ __cupsSanitizedMessageLookup
+ __os_log_default
+ __os_log_impl
+ _os_log_type_enabled
- __cupsMessageLookup
CStrings:
+ "%s: Rejecting key %s that contains CRLF"
+ "_cupsSanitizedMessageLookup"
```
