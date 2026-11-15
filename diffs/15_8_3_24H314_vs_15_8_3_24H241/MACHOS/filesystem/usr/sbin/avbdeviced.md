## avbdeviced

> `/usr/sbin/avbdeviced`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1350.2.0.0.0
-  __TEXT.__text: 0x43564
+1320.3.0.0.0
+  __TEXT.__text: 0x4311c
   __TEXT.__auth_stubs: 0x460
-  __TEXT.__objc_stubs: 0x5780
+  __TEXT.__objc_stubs: 0x56e0
   __TEXT.__objc_methlist: 0x1a7c
-  __TEXT.__cstring: 0x1f37
-  __TEXT.__const: 0x110
+  __TEXT.__cstring: 0x1d92
+  __TEXT.__const: 0xfc
   __TEXT.__gcc_except_tab: 0x5bc
-  __TEXT.__oslogstring: 0x4142
-  __TEXT.__objc_methname: 0x6667
+  __TEXT.__oslogstring: 0x3fe0
+  __TEXT.__objc_methname: 0x6600
   __TEXT.__objc_classname: 0x3eb
   __TEXT.__objc_methtype: 0x1001
   __TEXT.__unwind_info: 0x820
   __DATA_CONST.__auth_got: 0x240
-  __DATA_CONST.__got: 0x2c0
+  __DATA_CONST.__got: 0x2b0
   __DATA_CONST.__const: 0x14e0
-  __DATA_CONST.__cfstring: 0x1700
+  __DATA_CONST.__cfstring: 0x16a0
   __DATA_CONST.__objc_classlist: 0xb8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x78

   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA.__objc_const: 0x3b78
-  __DATA.__objc_selrefs: 0x1a80
+  __DATA.__objc_selrefs: 0x1a58
   __DATA.__objc_ivar: 0x268
   __DATA.__objc_data: 0x730
   __DATA.__data: 0x5b0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 828
-  Symbols:   179
-  CStrings:  1675
+  Symbols:   177
+  CStrings:  1665
 
Symbols:
- _OBJC_CLASS_$_AVB17221AEMMemoryObjectData
- _OBJC_CLASS_$_AVBCustomVirtualAudioEntityAEMValidator
Functions:
~ sub_100038b44 : 1576 -> 1248
~ sub_10003b060 -> sub_10003af18 : 1340 -> 572
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/AVBKit/MediaClocking/AVBMediaClockConnection.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/ADDReconnectController.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/AcquireMode/ADDAcquireMode.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/AcquireMode/ADDAcquireModeEntity.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualAudioInputStream.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualAudioOutputStream.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualEntity.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualMediaClockInputStream.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualMediaClockOutputStream.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntityState/ADDEntityIDManager.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntityState/ADDVirtualEntityPersistentInfoManager.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/VirtualMode/ADDAudioDriver.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbdeviced/VirtualMode/ADDVirtualAudio.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/AVBKit/MediaClocking/AVBMediaClockConnection.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/ADDReconnectController.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/AcquireMode/ADDAcquireMode.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/AcquireMode/ADDAcquireModeEntity.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualAudioInputStream.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualAudioOutputStream.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualEntity.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualMediaClockInputStream.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntity/ADDVirtualMediaClockOutputStream.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntityState/ADDEntityIDManager.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/VirtualEntityState/ADDVirtualEntityPersistentInfoManager.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/VirtualMode/ADDAudioDriver.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbdeviced/VirtualMode/ADDVirtualAudio.m"
- "Custom virtual entity \"%{public}@\" has a memory object (configuration %hu, descriptor %hu) whose content this daemon will not resolve; it will not be served to controllers"
- "Custom virtual entity \"%{public}@\" has a memory object (configuration %hu, descriptor %hu) whose descriptor claims %llu bytes but which holds %lu; reads are bounded by what it holds"
- "Custom virtual entity model failed validation."
- "ValidationErrors"
- "ValidationWarnings"
- "data"
- "succeeded"
- "validateCustomVirtualAudioEntityWithModelFromPlist:"
- "validationErrors"
- "validationWarnings"
```
