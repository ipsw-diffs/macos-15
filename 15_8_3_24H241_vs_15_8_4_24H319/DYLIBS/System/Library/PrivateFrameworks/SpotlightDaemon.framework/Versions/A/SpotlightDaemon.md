## SpotlightDaemon

> `/System/Library/PrivateFrameworks/SpotlightDaemon.framework/Versions/A/SpotlightDaemon`

```diff

-2333.57.1.13.0
-  __TEXT.__text: 0xa7b8c
+2333.57.1.14.0
+  __TEXT.__text: 0xa79a4
   __TEXT.__auth_stubs: 0x1bd0
-  __TEXT.__objc_methlist: 0x3e84
+  __TEXT.__objc_methlist: 0x3e8c
   __TEXT.__const: 0x350
-  __TEXT.__cstring: 0x7a5f
-  __TEXT.__oslogstring: 0x8ddb
-  __TEXT.__gcc_except_tab: 0x3d54
-  __TEXT.__unwind_info: 0x2058
-  __TEXT.__objc_classname: 0x469
-  __TEXT.__objc_methname: 0xd053
+  __TEXT.__cstring: 0x7a69
+  __TEXT.__oslogstring: 0x8dca
+  __TEXT.__gcc_except_tab: 0x3d64
+  __TEXT.__unwind_info: 0x2068
+  __TEXT.__objc_classname: 0x46a
+  __TEXT.__objc_methname: 0xd05d
   __TEXT.__objc_methtype: 0x227a
-  __TEXT.__objc_stubs: 0xa840
+  __TEXT.__objc_stubs: 0xa860
   __DATA_CONST.__got: 0x938
   __DATA_CONST.__const: 0x4a8
   __DATA_CONST.__objc_classlist: 0x150

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 2677
-  Symbols:   5352
-  CStrings:  4395
+  Functions: 2676
+  Symbols:   5354
+  CStrings:  4393
 
Symbols:
+ -[CSSearchAgent _queryContextFromXPCDictionary:searchConnection:]
+ GCC_except_table1483
+ GCC_except_table50
+ GCC_except_table52
+ GCC_except_table54
+ GCC_except_table59
+ GCC_except_table62
+ GCC_except_table65
+ GCC_except_table73
+ GCC_except_table76
+ GCC_except_table80
+ GCC_except_table82
+ GCC_except_table85
+ GCC_except_table97
+ _objc_msgSend$_queryContextFromXPCDictionary:searchConnection:
- -[SPCoreSpotlightTask _makeFilterQueryStringForQueryContext:]
- GCC_except_table49
- GCC_except_table51
- GCC_except_table53
- GCC_except_table58
- GCC_except_table61
- GCC_except_table63
- GCC_except_table71
- GCC_except_table75
- GCC_except_table79
- GCC_except_table87
- GCC_except_table96
- _OUTLINED_FUNCTION_42
Functions:
- -[SPCoreSpotlightTask _makeFilterQueryStringForQueryContext:]
~ -[SPCoreSpotlightIndexer _issueDiagnose:logQuery:completionHandler:] : 1076 -> 1084
~ -[SPCoreSpotlightIndexer _issueCommand:outFileDescriptor:searchContext:completionHandler:] : 21000 -> 20924
~ ___SPLogDirectory_block_invoke : 72 -> 116
~ _OUTLINED_FUNCTION_37 : 24 -> 12
~ _OUTLINED_FUNCTION_39 : 12 -> 28
~ _OUTLINED_FUNCTION_40 : 28 -> 12
~ _OUTLINED_FUNCTION_41 : 12 -> 32
- _OUTLINED_FUNCTION_42
+ -[CSSearchAgent _queryContextFromXPCDictionary:searchConnection:]
~ -[CSSearchAgent startSimpleQuery:] : 1336 -> 1340
~ -[SPCoreSpotlightIndexer _issueCommand:outFileDescriptor:searchContext:completionHandler:].cold.3 : 112 -> 156
~ _wait_for_apfs_kb_state.cold.1 : 112 -> 128
CStrings:
+ "/.resolve/1"
+ "2333.57.1.14"
+ "_queryContextFromXPCDictionary:searchConnection:"
- "("
- "2333.57.1.13"
- "E"
- "With filters: %@"
- "_makeFilterQueryStringForQueryContext:"
```
