## AppleMediaServicesUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Versions/A/AppleMediaServicesUI`

```diff

-6.6.11.1.0
-  __TEXT.__text: 0x17ae6c
+6.6.11.3.0
+  __TEXT.__text: 0x17bcdc
   __TEXT.__auth_stubs: 0x38b0
-  __TEXT.__objc_methlist: 0xef7c
+  __TEXT.__objc_methlist: 0xefb4
   __TEXT.__const: 0x82b4
-  __TEXT.__cstring: 0xb934
-  __TEXT.__oslogstring: 0x86c5
-  __TEXT.__gcc_except_tab: 0x1730
+  __TEXT.__cstring: 0xba24
+  __TEXT.__oslogstring: 0x88d5
+  __TEXT.__gcc_except_tab: 0x17c4
   __TEXT.__dlopen_cstrs: 0x8d8
   __TEXT.__swift5_typeref: 0xba6e
   __TEXT.__swift5_reflstr: 0x1e85

   __TEXT.__swift_as_entry: 0xe4
   __TEXT.__swift_as_ret: 0x10c
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__unwind_info: 0x6ab0
+  __TEXT.__unwind_info: 0x6ac0
   __TEXT.__eh_frame: 0x3a68
   __TEXT.__objc_classname: 0x227a
-  __TEXT.__objc_methname: 0x22a3e
+  __TEXT.__objc_methname: 0x22c0d
   __TEXT.__objc_methtype: 0x7048
-  __TEXT.__objc_stubs: 0x18180
-  __DATA_CONST.__got: 0x14e8
-  __DATA_CONST.__const: 0x35d0
+  __TEXT.__objc_stubs: 0x18360
+  __DATA_CONST.__got: 0x14f0
+  __DATA_CONST.__const: 0x3620
   __DATA_CONST.__objc_classlist: 0x908
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x320
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7ff0
+  __DATA_CONST.__objc_selrefs: 0x8060
   __DATA_CONST.__objc_protorefs: 0xf0
   __DATA_CONST.__objc_superrefs: 0x638
-  __DATA_CONST.__objc_arraydata: 0x310
+  __DATA_CONST.__objc_arraydata: 0x3a0
   __AUTH_CONST.__auth_got: 0x1c68
   __AUTH_CONST.__const: 0x5d38
-  __AUTH_CONST.__cfstring: 0x9f20
-  __AUTH_CONST.__objc_const: 0x1cfc0
+  __AUTH_CONST.__cfstring: 0xa040
+  __AUTH_CONST.__objc_const: 0x1d020
   __AUTH_CONST.__objc_intobj: 0x2b8
-  __AUTH_CONST.__objc_dictobj: 0x208
+  __AUTH_CONST.__objc_dictobj: 0x320
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH.__objc_data: 0x53a0
   __AUTH.__data: 0x3e90
-  __DATA.__objc_ivar: 0xfcc
+  __DATA.__objc_ivar: 0xfd4
   __DATA.__data: 0x4e28
   __DATA.__bss: 0x8f18
   __DATA.__common: 0x238

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 11288
-  Symbols:   13865
-  CStrings:  8595
+  Functions: 11295
+  Symbols:   13893
+  CStrings:  8629
 
Symbols:
+ +[AMSUIWebView _resourceTrustRulesForDomains:]
+ +[AMSUIWebView _topDocumentTrustRulesForDomains:]
+ -[AMSUIWebClientContext disableResourceTrustRules]
+ -[AMSUIWebClientContext disableScriptMessageFrameCheck]
+ -[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]
+ GCC_except_table38
+ GCC_except_table50
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableResourceTrustRules
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableScriptMessageFrameCheck
+ ___57-[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]_block_invoke
+ ___75-[AMSUIWebView userContentController:didReceiveScriptMessage:replyHandler:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48s56s_e32_v28?0"NSArray"8B16"NSError"20ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e20_v20?0B8"NSError"12lw64l8s56l8s32l8s40l8s48l8
+ ___block_descriptor_81_e8_32s40s48s56s64bs72w_e5_v8?0lw72l8s64l8s32l8s40l8s48l8s56l8
+ _objc_msgSend$_handleScriptMessage:logKey:replyHandler:
+ _objc_msgSend$_resourceTrustRulesForDomains:
+ _objc_msgSend$_topDocumentTrustRulesForDomains:
+ _objc_msgSend$characterSetWithCharactersInString:
+ _objc_msgSend$disableResourceTrustRules
+ _objc_msgSend$disableScriptMessageFrameCheck
+ _objc_msgSend$escapedPatternForString:
+ _objc_msgSend$frameInfo
+ _objc_msgSend$isMainFrame
+ _objc_msgSend$protocol
+ _objc_msgSend$securityOrigin
+ _objc_msgSend$setHost:
+ _objc_msgSend$setScheme:
+ _objc_msgSend$stringByTrimmingCharactersInSet:
+ _objc_msgSend$valueWithError:
- GCC_except_table44
- ___block_descriptor_56_e8_32s40s48s_e32_v28?0"NSArray"8B16"NSError"20ls32l8s40l8s48l8
CStrings:
+ "%{public}@: [%{public}@] Rejecting script message from opaque origin"
+ "%{public}@: [%{public}@] Rejecting script message from subframe: %{public}@"
+ "%{public}@: [%{public}@] Rejecting script message from untrusted origin: %{public}@ %{public}@"
+ "%{public}@: [%{public}@] Rejecting script message, context is unavailable"
+ "%{public}@: [%{public}@] Resource trust rules disabled by bag."
+ "([^/@]+\\.)?"
+ "AMS INTERNAL ERROR: Context Unavailable"
+ "AMS INTERNAL ERROR: Untrusted Frame"
+ "AMS INTERNAL ERROR: Web View Deallocated"
+ "TB,R,N,V_disableResourceTrustRules"
+ "TB,R,N,V_disableScriptMessageFrameCheck"
+ "[%{public}@] %{public}@ present, resource trust rules will be disabled."
+ "[%{public}@] %{public}@ present, script message frame check will be disabled."
+ "^blob:"
+ "^https://%@%@(:[0-9]+)?/"
+ "_disableResourceTrustRules"
+ "_disableScriptMessageFrameCheck"
+ "_handleScriptMessage:logKey:replyHandler:"
+ "_resourceTrustRulesForDomains:"
+ "_topDocumentTrustRulesForDomains:"
+ "characterSetWithCharactersInString:"
+ "disableResourceTrustRules"
+ "disableScriptMessageFrameCheck"
+ "disableWebResourceTrustRules"
+ "disableWebScriptMessageFrameCheck"
+ "escapedPatternForString:"
+ "frameInfo"
+ "ignore-previous-rules"
+ "isMainFrame"
+ "protocol"
+ "securityOrigin"
+ "setHost:"
+ "stringByTrimmingCharactersInSet:"
+ "valueWithError:"
```
