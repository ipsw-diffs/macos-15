## com.apple.filesystems.udf

> `com.apple.filesystems.udf`

```diff

-319.0.0.703.6
+319.0.0.702.4
   __TEXT.__const: 0x1b28
-  __TEXT.__cstring: 0x31a4
-  __TEXT_EXEC.__text: 0x303c0
+  __TEXT.__cstring: 0x308d
+  __TEXT_EXEC.__text: 0x301b8
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x4f8
   __DATA.__common: 0x4d8

   __DATA_CONST.__const: 0x1140
   __DATA_CONST.__kalloc_type: 0x80
   __DATA_CONST.__kalloc_var: 0xa0
-  Functions: 860
+  Functions: 861
   Symbols:   1179
-  CStrings:  354
+  CStrings:  349
 
Symbols:
+ __ZN15UDFDeviceBufferC2EP8UDFMountm
+ __ZN18UDFDeviceBufferLRUC1EP8UDFMountm
+ __ZN18UDFDeviceBufferLRUC2EP8UDFMountm
- __ZN15UDFDeviceBufferC2EP8UDFMountj
- __ZN18UDFDeviceBufferLRUC1EP8UDFMountj
- __ZN18UDFDeviceBufferLRUC2EP8UDFMountj
CStrings:
+ "\"non-memory resident sparing table is not implemented yet\" @%s:%d"
+ "UDFPartition.cpp"
- "Device buffer hash too large: %zu entries"
- "Device buffer too large: %u packets of %zu bytes"
- "FE/EFE L_EA exceeds sector size (partRef %u, lbn %u)"
- "Sparing table is not memory resident, cannot translate logicalBlkNum %u"
- "Sparing table size %u cannot hold %u entries"
- "embedded data end exceeds sector size"
- "embedded data length %llu exceeds L_AD %u (partRef %u, lbn %u)"
```
