## MTLCompiler

> `/System/Library/PrivateFrameworks/MTLCompiler.framework/Versions/32023/MTLCompiler`

```diff

-368.54.1.0.0
-  __TEXT.__text: 0xb0540
+368.54.0.0.0
+  __TEXT.__text: 0xb0320
   __TEXT.__auth_stubs: 0x21a0
-  __TEXT.__gcc_except_tab: 0x9b78
+  __TEXT.__gcc_except_tab: 0x9b8c
   __TEXT.__const: 0xf80
-  __TEXT.__cstring: 0x7c57
-  __TEXT.__oslogstring: 0x3bd
+  __TEXT.__cstring: 0x7b76
+  __TEXT.__oslogstring: 0x367
   __TEXT.__unwind_info: 0x2c08
   __TEXT.__objc_classname: 0x1
   __TEXT.__objc_methname: 0x289

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2080
-  Symbols:   3444
-  CStrings:  1379
+  Functions: 2077
+  Symbols:   3443
+  CStrings:  1372
 
Symbols:
- _OUTLINED_FUNCTION_11
Functions:
~ __ZL22parseFunctionConstantsRN4llvm11LLVMContextEPKcmPj : 360 -> 328
~ __ZN17MTLCompilerObject20storeToBinaryArchiveEP29MTLBuildBinariesRequestHeadermRK20ReadModuleParametersRK24BackendCompilationOutput15MTLFunctionTypeR21FrameworkPassesOutputRKP20MTLOpaqueGPUArchiverPPc : 1960 -> 1844
~ __ZN17MTLCompilerObject13generateMachOEPKvmU13block_pointerFvjS1_mPKcE : 6580 -> 6320
- _OUTLINED_FUNCTION_11
- __ZL22parseFunctionConstantsRN4llvm11LLVMContextEPKcmPj.cold.1
~ __ZN17MTLCompilerObject18loadRuntimeModulesER17BinaryRequestData.cold.1 : 68 -> 76
~ __ZN17MTLCompilerObject18loadRuntimeModulesER17BinaryRequestData.cold.2 : 72 -> 80
~ __ZN17MTLCompilerObject18loadRuntimeModulesER17BinaryRequestData.cold.3 : 72 -> 80
- __ZN17MTLCompilerObject13generateMachOEPKvmU13block_pointerFvjS1_mPKcE.cold.7
CStrings:
- "Failed to allocate MachO binary request entries"
- "Failed to allocate function constants"
- "Invalid pipeline archiver unit id"
- "Invalid visible function request count"
- "MachO entry %llu reflection block out of bounds"
- "Unknown linked bitcode hash in MachO binary request"
- "Visible function hashes do not match the tools list"
```
