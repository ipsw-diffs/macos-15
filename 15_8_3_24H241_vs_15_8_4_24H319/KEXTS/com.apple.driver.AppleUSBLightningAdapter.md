## com.apple.driver.AppleUSBLightningAdapter

> `com.apple.driver.AppleUSBLightningAdapter`

```diff

-64.0.0.700.1
+64.0.0.701.1
   __TEXT.__const: 0x8
   __TEXT.__cstring: 0x11ca
-  __TEXT.__os_log: 0xa8b
-  __TEXT_EXEC.__text: 0x5d20
+  __TEXT.__os_log: 0xac0
+  __TEXT_EXEC.__text: 0x5d34
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xc4
   __DATA.__common: 0x60

   __DATA_CONST.__kalloc_type: 0x80
   Functions: 107
   Symbols:   479
-  CStrings:  162
+  CStrings:  163
 
Functions:
~ __ZN27AppleUSBLightningAdapterBOS18_getCapabilityDataEPKN11StandardUSB13BOSDescriptorE : 504 -> 508
~ sub_9CB8 -> sub_fffffe000a57fb80 : 52 -> 68
CStrings:
+ "Invalid platform descriptor length for MikeyBus info! (bLength: %u, expectedDescriptorLength: %u)"
+ "Invalid platform descriptor length! (bLength: %u, expectedDescriptorBaseLength: %u)"
- "Invalid platform descriptor length!"
```
