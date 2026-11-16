## libAppleEXR.dylib

> `/usr/lib/libAppleEXR.dylib`

```diff

-3.1.20.2.0
-  __TEXT.__text: 0x9ad24
+3.1.20.3.0
+  __TEXT.__text: 0x9b17c
   __TEXT.__auth_stubs: 0x430
   __TEXT.__objc_methlist: 0x254
   __TEXT.__const: 0x210bc
-  __TEXT.__gcc_except_tab: 0x594
-  __TEXT.__cstring: 0x42b9
+  __TEXT.__gcc_except_tab: 0x598
+  __TEXT.__cstring: 0x469c
   __TEXT.__oslogstring: 0x3
   __TEXT.__unwind_info: 0x900
   __TEXT.__eh_frame: 0xf8

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 735
-  Symbols:   964
-  CStrings:  506
+  Functions: 737
+  Symbols:   966
+  CStrings:  512
 
Symbols:
+ __ZN14AXRChunkHeader11GetMipLevelE11ChunkLayout
+ __ZN4Part11InitOffsetsEPKvmRmm11axr_flags_t
+ __ZNK4Part20CheckChunkPartNumberEPKvmmm11axr_flags_t
+ __ZZN4Part11InitOffsetsEPKvmRmm11axr_flags_tE13kRowSizeProcs
- __ZN4Part11InitOffsetsEPKvmRm11axr_flags_t
- __ZZN4Part11InitOffsetsEPKvmRm11axr_flags_tE13kRowSizeProcs
CStrings:
+ "%s error: expected rowBytes for channel size (%lu) x RGBA channel count (%lu) x width (%u) = %lu bytes\n\tThe provided destination row bytes is only %lu and the data will not fit.\n\tSkipping operation."
+ "EXR File corrupted: chunk appears in the offset table for part %lu, but reports it belongs to part %d"
+ "Interleave_Uncompressed: header runLength=%lu exceeds destination row capacity (%lu pixels for %lu rowBytes, %u channels x %zu bytes); clamping to prevent OOB write.\n"
+ "TileDecoder_PIZ::Interleave: header runLength=%u exceeds destination row capacity (%lu pixels for %lu rowBytes, %u channels x %zu bytes); clamping to prevent OOB write.\n"
+ "TileDecoder_PXR24::Interleave: header runLength=%u exceeds destination row capacity (%lu pixels for %lu rowBytes, %u channels x %zu bytes); clamping to prevent OOB write.\n"
+ "TileDecoder_ScanlineCompressed::Interleave: header runLength=%u exceeds destination row capacity (%lu pixels for %lu rowBytes, %u channels x %zu bytes); clamping to prevent OOB write.\n"
```
