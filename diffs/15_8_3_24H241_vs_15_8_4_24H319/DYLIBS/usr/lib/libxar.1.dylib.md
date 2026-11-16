## libxar.1.dylib

> `/usr/lib/libxar.1.dylib`

```diff

-501.0.0.702.1
-  __TEXT.__text: 0xc54c
+501.0.0.703.1
+  __TEXT.__text: 0xca50
   __TEXT.__auth_stubs: 0x8b0
-  __TEXT.__const: 0x168
+  __TEXT.__const: 0x170
   __TEXT.__cstring: 0xbf9
   __TEXT.__unwind_info: 0x2e8
   __DATA_CONST.__got: 0x18

   - /usr/lib/libbz2.1.0.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 222
-  Symbols:   369
+  Functions: 223
+  Symbols:   370
   CStrings:  192
 
Symbols:
+ _xar_io_get_decompress_chunk_size
Functions:
~ _xar_darwinattr_archive : 1868 -> 1872
~ _xar_bzip_fromheap_done : 80 -> 92
~ _xar_bzip_fromheap_in : 480 -> 824
~ _xar_darwinattr_extract : 1480 -> 1584
~ _xar_ea_write : 140 -> 268
~ _xar_data_extract : 424 -> 428
~ _xar_data_verify : 164 -> 180
+ _xar_io_get_decompress_chunk_size
~ _xar_attrcopy_from_heap : 716 -> 848
~ _xar_attrcopy_from_heap_to_stream_init : 260 -> 268
~ _xar_attrcopy_from_heap_to_stream : 624 -> 792
~ _xar_attrcopy_from_heap_to_stream_end : 156 -> 204
~ _xar_gzip_fromheap_done : 80 -> 92
~ _xar_gzip_fromheap_in : 588 -> 856
```
