## AppleAVE2FW_H14G.im4p

> `AssetData/boot/Firmware/ave/AppleAVE2FW_H14G.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xcafa0
+  __TEXT.__text: 0xcae60
   __TEXT._rtk_mtab: 0x320
   __TEXT.__const: 0x1b440
-  __TEXT.__cstring: 0x1154d
+  __TEXT.__cstring: 0x115fe
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x27f8

   __DATA.__zerofill: 0xc68b8
   Functions: 0
   Symbols:   1380
-  CStrings:  2119
+  CStrings:  2123
 
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
