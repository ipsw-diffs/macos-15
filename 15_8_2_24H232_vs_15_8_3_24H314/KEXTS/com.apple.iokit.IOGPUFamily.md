## com.apple.iokit.IOGPUFamily

> `com.apple.iokit.IOGPUFamily`

```diff

-104.6.5.0.0
+104.6.12.0.0
   __TEXT.__cstring: 0x582c
-  __TEXT.__os_log: 0x3d9f
+  __TEXT.__os_log: 0x3e2e
   __TEXT.__const: 0xd4
-  __TEXT_EXEC.__text: 0x3f3c0
+  __TEXT_EXEC.__text: 0x3f4d8
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x410
   __DATA.__common: 0x7c8

   __DATA_CONST.__kalloc_var: 0xf00
   __DATA_CONST.__assert: 0x78
   Functions: 1905
-  Symbols:   3117
-  CStrings:  805
+  Symbols:   3119
+  CStrings:  807
 
Symbols:
+ __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2308
+ __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2314
+ __ZZN13IOGPUResource10initializeEP11IOGPUDeviceP20IOGPUNewResourceArgsyE21kalloc_type_view_1091
+ __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_1933
+ __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_1981
+ __ZZN13IOGPUResource31newResourceWithParentResourceIDEP5IOGPUP11IOGPUDevice13eIOGPUResTypeyyyyPyjE11_os_log_fmt_7
+ __ZZN13IOGPUResource31newResourceWithParentResourceIDEP5IOGPUP11IOGPUDevice13eIOGPUResTypeyyyyPyjE11_os_log_fmt_8
+ __ZZN17IOGPUCommandQueue4freeEvE20kalloc_type_view_203
- __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2301
- __ZZN11IOGPUDevice19group_add_resourcesEjPKjmE21kalloc_type_view_2307
- __ZZN13IOGPUResource10initializeEP11IOGPUDeviceP20IOGPUNewResourceArgsyE21kalloc_type_view_1073
- __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_1908
- __ZZN13IOGPUResource19add_group_resourcesEPPS_jE21kalloc_type_view_1956
- __ZZN17IOGPUCommandQueue4freeEvE20kalloc_type_view_199
Functions:
~ __ZN13IOGPUResource31newResourceWithParentResourceIDEP5IOGPUP11IOGPUDevice13eIOGPUResTypeyyyyPyj : 1008 -> 1188
~ __ZNK13IOGPUResource17getMappingOptionsEP20IOGPUNewResourceArgsy : 372 -> 396
~ __ZN11IOGPUDevice12new_resourceEP20IOGPUNewResourceArgsP26IOGPUNewResourceReturnDatayPj : 2616 -> 2664
~ __ZN17IOGPUCommandQueue13clientReleaseEv : 112 -> 140
CStrings:
+ "%s: child resource (offset=0x%llx, size=0x%llx) exceeds parent memory size 0x%llx.\n"
+ "%s: client_buffer (0x%llx) precedes client_base (0x%llx).\n"
```
