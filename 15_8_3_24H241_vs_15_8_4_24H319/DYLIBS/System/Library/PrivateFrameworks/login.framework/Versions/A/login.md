## login

> `/System/Library/PrivateFrameworks/login.framework/Versions/A/login`

```diff

-259.5.1.102.0
-  __TEXT.__text: 0x16df0
+259.5.1.103.0
+  __TEXT.__text: 0x16f6c
   __TEXT.__auth_stubs: 0x570
-  __TEXT.__objc_methlist: 0x120c
+  __TEXT.__objc_methlist: 0x126c
   __TEXT.__const: 0x68
   __TEXT.__gcc_except_tab: 0xc54
-  __TEXT.__cstring: 0x369f
+  __TEXT.__cstring: 0x36c2
   __TEXT.__dlopen_cstrs: 0xf5
-  __TEXT.__unwind_info: 0x968
-  __TEXT.__objc_classname: 0x339
-  __TEXT.__objc_methname: 0x26de
+  __TEXT.__unwind_info: 0x978
+  __TEXT.__objc_classname: 0x36d
+  __TEXT.__objc_methname: 0x271c
   __TEXT.__objc_methtype: 0x8f4
-  __TEXT.__objc_stubs: 0x1f80
+  __TEXT.__objc_stubs: 0x1fc0
   __DATA_CONST.__got: 0x228
   __DATA_CONST.__const: 0x338
   __DATA_CONST.__objc_classlist: 0xb8
-  __DATA_CONST.__objc_protolist: 0x70
+  __DATA_CONST.__objc_catlist: 0x8
+  __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xab0
-  __DATA_CONST.__objc_protorefs: 0x50
+  __DATA_CONST.__objc_selrefs: 0xac0
+  __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0x90
   __AUTH_CONST.__auth_got: 0x2c8
   __AUTH_CONST.__const: 0x878
-  __AUTH_CONST.__cfstring: 0x2540
-  __AUTH_CONST.__objc_const: 0x44c0
+  __AUTH_CONST.__cfstring: 0x2560
+  __AUTH_CONST.__objc_const: 0x4570
   __AUTH.__objc_data: 0x730
-  __DATA.__objc_ivar: 0xa8
-  __DATA.__data: 0x550
+  __DATA.__objc_ivar: 0xac
+  __DATA.__data: 0x5b0
   __DATA.__bss: 0x140
   __DATA.__common: 0x98
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /System/Library/PrivateFrameworks/login.framework/Versions/A/Frameworks/loginsupport.framework/Versions/A/loginsupport
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 539
-  Symbols:   1407
-  CStrings:  1063
+  Functions: 544
+  Symbols:   1425
+  CStrings:  1068
 
Symbols:
+ +[NSXPCConnection(LFEntitlement) lf_boolValueForEntitlementValue:]
+ -[LFSessionAgentListener .cxx_destruct]
+ -[LFSessionAgentListener privilegedInterface]
+ -[LFSessionAgentListener setPrivilegedInterface:]
+ -[NSXPCConnection(LFEntitlement) lf_connectionHasEntitlement:]
+ _OBJC_IVAR_$_LFSessionAgentListener._privilegedInterface
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSXPCConnection_$_LFEntitlement
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSXPCConnection_$_LFEntitlement
+ __OBJC_$_CATEGORY_NSXPCConnection_$_LFEntitlement
+ __OBJC_$_INSTANCE_VARIABLES_LFSessionAgentListener
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_LFSessionAgentListenerPublicInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_LFSessionAgentListenerPublicInterface
+ __OBJC_$_PROTOCOL_REFS_LFSessionAgentListenerPublicInterface
+ __OBJC_LABEL_PROTOCOL_$_LFSessionAgentListenerPublicInterface
+ __OBJC_PROTOCOL_$_LFSessionAgentListenerPublicInterface
+ __OBJC_PROTOCOL_REFERENCE_$_LFSessionAgentListenerPublicInterface
+ _objc_msgSend$lf_boolValueForEntitlementValue:
+ _objc_msgSend$lf_connectionHasEntitlement:
CStrings:
+ "LFEntitlement"
+ "LFSessionAgentListenerPublicInterface"
+ "com.apple.private.sessionagent.spi"
+ "lf_boolValueForEntitlementValue:"
+ "lf_connectionHasEntitlement:"
```
