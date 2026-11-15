## libcompression.dylib

> `/usr/lib/libcompression.dylib`

```diff

-181.100.1.700.1
-  __TEXT.__text: 0x57f00
+181.100.1.701.2
+  __TEXT.__text: 0x57fd0
   __TEXT.__auth_stubs: 0x2f0
   __TEXT.__const: 0x76991
-  __TEXT.__cstring: 0x2e8
+  __TEXT.__cstring: 0x2f5
   __TEXT.__unwind_info: 0x698
   __TEXT.__eh_frame: 0x448
   __DATA_CONST.__got: 0x10

   - /usr/lib/liblzma.5.dylib
   Functions: 511
   Symbols:   673
-  CStrings:  48
+  CStrings:  49
 
Functions:
~ _lzfseDecode : 2792 -> 2828
~ _lzvn_decode_scratch_size : 16 -> 44
~ _ProcessCommands : 2460 -> 2540
~ _SafeProcessCommands : 2792 -> 2784
~ _SafeDecodeCommandBlockSwitch : 792 -> 804
~ _DecodeCommandBlockSwitch : 432 -> 444
~ _SafeDecodeLiteralBlockSwitch : 864 -> 876
~ _DecodeLiteralBlockSwitch : 496 -> 508
~ _SafeDecodeDistanceBlockSwitch : 812 -> 824
~ _DecodeDistanceBlockSwitch : 464 -> 476
CStrings:
+ "BLOCK_SWITCH"
```
