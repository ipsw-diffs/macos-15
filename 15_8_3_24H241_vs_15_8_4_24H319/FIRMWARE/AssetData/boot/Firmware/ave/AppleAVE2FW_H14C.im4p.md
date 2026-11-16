## AppleAVE2FW_H14C.im4p

> `AssetData/boot/Firmware/ave/AppleAVE2FW_H14C.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xe54a8
+  __TEXT.__text: 0xe53e8
   __TEXT._rtk_mtab: 0x2d0
   __TEXT.__const: 0x1efa8
-  __TEXT.__cstring: 0x12da3
+  __TEXT.__cstring: 0x12e54
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x2950

   __DATA.__zerofill: 0xd03d8
   Functions: 0
   Symbols:   1464
-  CStrings:  2286
+  CStrings:  2290
 
CStrings:
+ "%s::%s ConfigureMCPUs failed (%d)"
+ "%s::%s GetSliceHeaderForFW rejected slice header (%d)"
+ "%s::%s prepSlicHeaderForCavlc rejected slice header"
+ "%s::%s slice header count (%d) out of range [0, %d]"
+ "%s::%s:%d %s | setPipe failed (%d)"
+ "8002.48.0"
- "%s::%s getPPSHeaderForFW count (%d) > length (%d)"
- "8002.47.0"
```
