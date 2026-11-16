## AppleMediaServicesUI

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Versions/A/AppleMediaServicesUI`

```diff

-6.6.11.1.0
-  __TEXT.__text: 0x17b07c
+6.6.11.3.0
+  __TEXT.__text: 0x17c134
   __TEXT.__auth_stubs: 0x3210
-  __TEXT.__objc_methlist: 0xd3cc
+  __TEXT.__objc_methlist: 0xd40c
   __TEXT.__const: 0x8654
-  __TEXT.__gcc_except_tab: 0x1314
-  __TEXT.__oslogstring: 0x79c5
-  __TEXT.__cstring: 0xbd14
+  __TEXT.__gcc_except_tab: 0x13ac
+  __TEXT.__oslogstring: 0x7bd5
+  __TEXT.__cstring: 0xbe14
   __TEXT.__dlopen_cstrs: 0x85b
   __TEXT.__swift5_typeref: 0xb906
   __TEXT.__swift5_reflstr: 0x21c5

   __TEXT.__swift_as_ret: 0x114
   __TEXT.__swift5_protos: 0x2c
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__unwind_info: 0x6790
+  __TEXT.__unwind_info: 0x67a8
   __TEXT.__eh_frame: 0x3afc
   __TEXT.__objc_classname: 0x1d5c
-  __TEXT.__objc_methname: 0x1cbee
+  __TEXT.__objc_methname: 0x1cdb9
   __TEXT.__objc_methtype: 0x5b29
-  __TEXT.__objc_stubs: 0x14200
-  __DATA_CONST.__got: 0x1318
+  __TEXT.__objc_stubs: 0x143e0
+  __DATA_CONST.__got: 0x1320
   __DATA_CONST.__const: 0x11c0
   __DATA_CONST.__objc_classlist: 0x858
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x298
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6cd0
+  __DATA_CONST.__objc_selrefs: 0x6d40
   __DATA_CONST.__objc_protorefs: 0xe0
   __DATA_CONST.__objc_superrefs: 0x5b8
-  __DATA_CONST.__objc_arraydata: 0x318
+  __DATA_CONST.__objc_arraydata: 0x3a8
   __AUTH_CONST.__auth_got: 0x1918
-  __AUTH_CONST.__const: 0x8910
-  __AUTH_CONST.__cfstring: 0x96e0
-  __AUTH_CONST.__objc_const: 0x1a7a0
+  __AUTH_CONST.__const: 0x8940
+  __AUTH_CONST.__cfstring: 0x9800
+  __AUTH_CONST.__objc_const: 0x1a800
   __AUTH_CONST.__objc_intobj: 0x258
-  __AUTH_CONST.__objc_dictobj: 0x280
+  __AUTH_CONST.__objc_dictobj: 0x398
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x120
   __AUTH.__objc_data: 0x4a58
   __AUTH.__data: 0x4558
-  __DATA.__objc_ivar: 0xe94
+  __DATA.__objc_ivar: 0xe9c
   __DATA.__data: 0x4980
   __DATA.__bss: 0x9360
   __DATA.__common: 0x248

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 10925
-  Symbols:   12412
-  CStrings:  7669
+  Functions: 10933
+  Symbols:   12441
+  CStrings:  7703
 
Symbols:
+ +[AMSUIWebView _resourceTrustRulesForDomains:]
+ +[AMSUIWebView _topDocumentTrustRulesForDomains:]
+ -[AMSUIWebClientContext disableResourceTrustRules]
+ -[AMSUIWebClientContext disableScriptMessageFrameCheck]
+ -[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]
+ GCC_except_table29
+ GCC_except_table60
+ GCC_except_table65
+ _OBJC_CLASS_$_NSCharacterSet
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableResourceTrustRules
+ _OBJC_IVAR_$_AMSUIWebClientContext._disableScriptMessageFrameCheck
+ ___57-[AMSUIWebView _handleScriptMessage:logKey:replyHandler:]_block_invoke
+ ___75-[AMSUIWebView userContentController:didReceiveScriptMessage:replyHandler:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48s56s_e32_v28?0"NSArray"8B16"NSError"20l
+ ___block_descriptor_72_e8_32s40s48s56bs64w_e20_v20?0B8"NSError"12l
+ ___copy_helper_block_e8_32s40s48s56b64w
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
- GCC_except_table58
- ___block_descriptor_56_e8_32s40s48s_e32_v28?0"NSArray"8B16"NSError"20l
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
+ "TB,R,V_disableResourceTrustRules"
+ "TB,R,V_disableScriptMessageFrameCheck"
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
