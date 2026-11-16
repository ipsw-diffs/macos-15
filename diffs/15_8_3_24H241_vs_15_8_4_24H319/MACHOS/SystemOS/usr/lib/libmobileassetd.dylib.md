## libmobileassetd.dylib

> `/usr/lib/libmobileassetd.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_protorefs`
- `__DATA.__objc_classrefs`
- `__DATA.__objc_superrefs`
- `__DATA.__objc_data`
- `__DATA.__data`
- `__DATA.__s_async_hook`

```diff

-1487.140.26.701.1
-  __TEXT.__text: 0x2b8b1c
+1487.140.26.702.2
+  __TEXT.__text: 0x2b965c
   __TEXT.__auth_stubs: 0x2390
-  __TEXT.__objc_stubs: 0x228e0
-  __TEXT.__objc_methlist: 0x1069c
+  __TEXT.__objc_stubs: 0x22960
+  __TEXT.__objc_methlist: 0x106d4
   __TEXT.__const: 0x477e
-  __TEXT.__cstring: 0x38016
-  __TEXT.__objc_methname: 0x3e0f0
+  __TEXT.__cstring: 0x380b6
+  __TEXT.__objc_methname: 0x3e1aa
   __TEXT.__objc_classname: 0xea8
   __TEXT.__objc_methtype: 0x3ba4
-  __TEXT.__oslogstring: 0x4ca1d
+  __TEXT.__oslogstring: 0x4cd2e
   __TEXT.__gcc_except_tab: 0x30b0
   __TEXT.__swift5_typeref: 0x1093
   __TEXT.__constg_swiftt: 0x14fc

   __TEXT.__swift5_protos: 0x60
   __TEXT.__swift5_capture: 0x30
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x4840
+  __TEXT.__unwind_info: 0x4848
   __TEXT.__eh_frame: 0x332c
   __DATA_CONST.__auth_got: 0x11d8
   __DATA_CONST.__got: 0x680
   __DATA_CONST.__auth_ptr: 0x968
-  __DATA_CONST.__const: 0x6980
-  __DATA_CONST.__cfstring: 0x2bc40
+  __DATA_CONST.__const: 0x69e8
+  __DATA_CONST.__cfstring: 0x2bca0
   __DATA_CONST.__objc_classlist: 0x400
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9960
+  __DATA_CONST.__objc_selrefs: 0x9980
   __DATA_CONST.__objc_intobj: 0x558
   __DATA_CONST.__objc_arraydata: 0xb70
   __DATA_CONST.__objc_arrayobj: 0x270

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 8482
-  Symbols:   15144
-  CStrings:  16298
+  Functions: 8486
+  Symbols:   15151
+  CStrings:  16309
 
Symbols:
+ +[MADAutoAssetAuthorizationPolicy _accessibleAssetTypesContainSoftwareUpdateAssetType:]
+ +[MADAutoAssetAuthorizationPolicy _assetTypes:authorizedForAccessibleAssetTypes:]
+ +[MADAutoAssetAuthorizationPolicy authorizationAssetTypesFromMessage:alreadyOnStateQueue:]
+ +[MADAutoAssetSecure isPersonalized:forDescriptor:]
+ GCC_except_table80
+ _objc_msgSend$_accessibleAssetTypesContainSoftwareUpdateAssetType:
+ _objc_msgSend$_assetTypes:authorizedForAccessibleAssetTypes:
+ _objc_msgSend$authorizationAssetTypesFromMessage:alreadyOnStateQueue:
+ _objc_msgSend$isPersonalized:forDescriptor:
- GCC_except_table24
- GCC_except_table79
CStrings:
+ "\n[AUTO-SECURE][AUTO-PERSONALIZATION][STARTUP] {DecideNeedPersonalize} [singleton] newer asset-version already personalized, not personalizing older | assetType:%{public}@ | assetSpecifier:%{public}@ | assetVersion:%{public}@ | personalizedVersion:%{public}@"
+ "%@:isPersonalized"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileAssetBrain/ControlManager.m"
+ "; the stage-target-all sentinel needs a software-update asset type"
+ "GlowSecurityFizzC"
+ "MAAutoAssetStage-target-all-asset-types"
+ "Starting built-in MobileAsset brain built Nov  8 2026 22:15:25"
+ "Starting downloaded MobileAsset brain (version: %@) built Nov  8 2026 22:15:25"
+ "_accessibleAssetTypesContainSoftwareUpdateAssetType:"
+ "_assetTypes:authorizedForAccessibleAssetTypes:"
+ "authorizationAssetTypesFromMessage:alreadyOnStateQueue:"
+ "isPersonalized:forDescriptor:"
+ "{_assetTypes:authorizedForAccessibleAssetTypes:} accessible-asset-types entitlement is %{public}@, expected an array | assetType:%{public}@"
+ "{_assetTypes:authorizedForAccessibleAssetTypes:} asset type not covered by accessible-asset-types entitlement (exact entry or com.apple.MobileAsset.<prefix>.* wildcard)%{public}@ | assetType:%{public}@, accessibleAssetTypes:%{public}@"
+ "{authorizationAssetTypesFromMessage} Found asset types: %{public}@, for message: %{public}@"
+ "{authorizationAssetTypesFromMessage} Found multiple asset types (not formally supported): %{public}@, for message: %{public}@, authorizing all of them"
+ "{isConnection:authorizedForMessage:}(%{public}@) Client does not have all requested asset types: %{public}@ (found: %{public}@)"
+ "{isConnection:authorizedForMessage:}(%{public}@) Ignoring bypass entitlement of unexpected type: %{public}@ (expected a BOOL or a string)"
+ "{isConnection:authorizedForMessage:}(%{public}@) Request had no asset type listed for message: %{public}@"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileAssetBrain/ControlManager.m"
- "GlowSecurityFizzB"
- "Starting built-in MobileAsset brain built Oct 12 2026 03:00:09"
- "Starting downloaded MobileAsset brain (version: %@) built Oct 12 2026 03:00:09"
- "{MADAutoAssetAuthorizationPolicy}(%{public}@) Client does not have requested asset type: %@ (found: %@)"
- "{MADAutoAssetAuthorizationPolicy}(%{public}@) Request had no asset type listed for message: %{public}@"
- "{MADAutoAssetAuthorizationPolicy}(authorizationAssetTypeFromMessage) Found asset type: %{public}@, for message: %{public}@"
- "{MADAutoAssetAuthorizationPolicy}(authorizationAssetTypeFromMessage) Found multiple asset types: %{public}@, for message: %{public}@"
```
