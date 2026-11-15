## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/Versions/A/AirPlayReceiver`

```diff

-870.14.25.2.0
-  __TEXT.__text: 0xd2c18
+870.14.25.4.0
+  __TEXT.__text: 0xd2cec
   __TEXT.__auth_stubs: 0x3360
   __TEXT.__objc_methlist: 0x8e4
   __TEXT.__const: 0xd2c5
   __TEXT.__dlopen_cstrs: 0xad
   __TEXT.__gcc_except_tab: 0x710
-  __TEXT.__cstring: 0x274c1
-  __TEXT.__unwind_info: 0x1080
+  __TEXT.__cstring: 0x2750d
+  __TEXT.__unwind_info: 0x1088
   __TEXT.__objc_classname: 0x12c
   __TEXT.__objc_methname: 0x1e06
   __TEXT.__objc_methtype: 0x1482

   __DATA_CONST.__objc_arraydata: 0x10
   __AUTH_CONST.__auth_got: 0x19c0
   __AUTH_CONST.__const: 0x4b28
-  __AUTH_CONST.__cfstring: 0x9c20
+  __AUTH_CONST.__cfstring: 0x9c40
   __AUTH_CONST.__objc_const: 0x1338
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0x320

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/Versions/A/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1265
-  Symbols:   3157
-  CStrings:  4603
+  Functions: 1266
+  Symbols:   3158
+  CStrings:  4606
 
Symbols:
+ GCC_except_table1002
+ GCC_except_table1010
+ GCC_except_table1012
+ GCC_except_table876
+ GCC_except_table895
+ GCC_except_table946
+ GCC_except_table950
+ _airplayReqProcessor_ensurePairingServices
- GCC_except_table1001
- GCC_except_table1009
- GCC_except_table1011
- GCC_except_table875
- GCC_except_table894
- GCC_except_table945
- GCC_except_table949
CStrings:
+ "870.14.25.4"
+ "CoreUtils"
+ "OSStatus airplayReqProcessor_ensurePairingServices(APReceiverRequestProcessorRef, Boolean, APSTransportMessageProcessingStatus *)"
+ "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, CFDataRef, CFDataRef *, Boolean *)"
+ "[%{ptr}] Created %s pairing services [%{ptr}]\n"
+ "airplayReqProcessor_ensurePairingServices"
+ "disablePairSetupThrottling"
+ "legacy"
- "870.14.25.2"
- "OSStatus coreUtilsPairing_HandleSetup(APPairingServicesRef, CFStringRef, APSecurityMode, CFDataRef, CFDataRef *, Boolean *)"
- "[%{ptr}] Created legacy pairing services [%{ptr}]\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-setup.\n"
- "[%{ptr}] Created pairing services [%{ptr}] for pair-verify\n"
```
