## sharingd

> `/usr/libexec/sharingd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 2060.80.31.1.14
-  __TEXT.__text: 0x63e7dc
+  __TEXT.__text: 0x63e7f4
   __TEXT.__auth_stubs: 0x89f0
   __TEXT.__objc_stubs: 0x27200
   __TEXT.__objc_methlist: 0x1a3a4
-  __TEXT.__cstring: 0x36008
+  __TEXT.__cstring: 0x35d44
   __TEXT.__objc_methname: 0x38b9f
   __TEXT.__objc_classname: 0x25f7
   __TEXT.__objc_methtype: 0x83e1

   __TEXT.__eh_frame: 0x207f8
   __DATA_CONST.__auth_got: 0x4508
   __DATA_CONST.__got: 0x2a78
-  __DATA_CONST.__auth_ptr: 0x1848
+  __DATA_CONST.__auth_ptr: 0x1930
   __DATA_CONST.__const: 0x17798
   __DATA_CONST.__cfstring: 0x14280
   __DATA_CONST.__objc_classlist: 0xd18
Functions:
~ sub_100279a7c : 2924 -> 2928
~ sub_1002940c4 -> sub_1002940c8 : 4312 -> 4316
~ sub_10038e3bc -> sub_10038e3c4 : 780 -> 784
~ sub_10038f530 -> sub_10038f53c : 1904 -> 1908
~ sub_1003fd4dc -> sub_1003fd4ec : 2940 -> 2944
~ sub_1005e190c -> sub_1005e1920 : 220 -> 224
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleCredentialManager_ClientLibs/ACMLib/ACMLib.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleCredentialManager_ClientLibs/common/LibCall.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/Network+SFAirDropMessage.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropAskFanoutHelper.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropContentHandler+Default.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerCredentialLinks.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerGenericLinks.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerIPA.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerPeerPayment.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerPhotos.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerUnsupportedFileType.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerUnsupportedLinkType.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerUtilities.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropMessage.Ask.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropNearFieldService.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropReceiveClassroomHandler.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropReceiveCompressionAdapter.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropReceiveHandler.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropReceiveStateMachine+Runner.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropSendCompressionAdapter.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropSendStateMachine+Runner.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAirDropSendStateMachine.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAuthentication.LTKSession.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAuthenticationAKSAuthSession.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDAuthenticationOperationInputs.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDTempPairingConnection.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SDTempPairingServer.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/Daemon/SFAirDropReceive.AskRequest+LegacySupport.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/Sharing_executables/SDAppleIDAccountInfoStore.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleCredentialManager_ClientLibs/ACMLib/ACMLib.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleCredentialManager_ClientLibs/common/LibCall.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/Network+SFAirDropMessage.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropAskFanoutHelper.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropContentHandler+Default.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerCredentialLinks.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerGenericLinks.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerIPA.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerPeerPayment.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerPhotos.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerUnsupportedFileType.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerUnsupportedLinkType.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropContentHandlerUtilities.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropMessage.Ask.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropNearFieldService.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropReceiveClassroomHandler.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropReceiveCompressionAdapter.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropReceiveHandler.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropReceiveStateMachine+Runner.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropSendCompressionAdapter.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropSendStateMachine+Runner.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAirDropSendStateMachine.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAuthentication.LTKSession.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAuthenticationAKSAuthSession.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDAuthenticationOperationInputs.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDTempPairingConnection.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SDTempPairingServer.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/Daemon/SFAirDropReceive.AskRequest+LegacySupport.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Sharing_executables/SDAppleIDAccountInfoStore.swift"
```
