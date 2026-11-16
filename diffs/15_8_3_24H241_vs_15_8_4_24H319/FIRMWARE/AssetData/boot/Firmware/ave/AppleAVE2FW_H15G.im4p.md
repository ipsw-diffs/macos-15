## AppleAVE2FW_H15G.im4p

> `AssetData/boot/Firmware/ave/AppleAVE2FW_H15G.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xd768c
+  __TEXT.__text: 0xd757c
   __TEXT._rtk_mtab: 0x320
   __TEXT.__const: 0x1d2d0
-  __TEXT.__cstring: 0x12783
+  __TEXT.__cstring: 0x12834
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x28c8

   __DATA.__zerofill: 0xc68b8
   Functions: 0
   Symbols:   1451
-  CStrings:  2250
+  CStrings:  2254
 
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
