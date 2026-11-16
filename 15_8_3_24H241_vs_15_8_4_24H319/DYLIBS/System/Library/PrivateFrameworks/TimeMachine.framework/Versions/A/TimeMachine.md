## TimeMachine

> `/System/Library/PrivateFrameworks/TimeMachine.framework/Versions/A/TimeMachine`

```diff

-2436.2.1.0.0
-  __TEXT.__text: 0xd8ffc
-  __TEXT.__auth_stubs: 0x26a0
-  __TEXT.__objc_methlist: 0x5840
+2436.2.2.0.0
+  __TEXT.__text: 0xda200
+  __TEXT.__auth_stubs: 0x26e0
+  __TEXT.__objc_methlist: 0x5850
   __TEXT.__const: 0x2b74
-  __TEXT.__cstring: 0xb7dc
+  __TEXT.__cstring: 0xc00c
   __TEXT.__gcc_except_tab: 0x1e8c
   __TEXT.__dlopen_cstrs: 0xb0
   __TEXT.__ustring: 0x4

   __TEXT.__swift5_builtin: 0x17c
   __TEXT.__swift5_protos: 0x10
   __TEXT.__swift5_mpenum: 0xd8
-  __TEXT.__unwind_info: 0x3200
+  __TEXT.__unwind_info: 0x3210
   __TEXT.__eh_frame: 0x3538
   __TEXT.__objc_classname: 0x8ce
-  __TEXT.__objc_methname: 0xcd16
+  __TEXT.__objc_methname: 0xcdbd
   __TEXT.__objc_methtype: 0x25f9
-  __TEXT.__objc_stubs: 0x9740
-  __DATA_CONST.__got: 0xaf0
+  __TEXT.__objc_stubs: 0x97e0
+  __DATA_CONST.__got: 0xaf8
   __DATA_CONST.__const: 0xa70
   __DATA_CONST.__objc_classlist: 0x290
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0xd8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x32b0
+  __DATA_CONST.__objc_selrefs: 0x32d8
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x220
   __DATA_CONST.__objc_arraydata: 0x108
-  __AUTH_CONST.__auth_got: 0x1368
-  __AUTH_CONST.__const: 0x5470
-  __AUTH_CONST.__cfstring: 0x8060
+  __AUTH_CONST.__auth_got: 0x1388
+  __AUTH_CONST.__const: 0x54c0
+  __AUTH_CONST.__cfstring: 0x82a0
   __AUTH_CONST.__objc_const: 0x8988
   __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x90

   __AUTH.__data: 0x388
   __DATA.__objc_ivar: 0x478
   __DATA.__data: 0x9240
-  __DATA.__bss: 0x3e30
+  __DATA.__bss: 0x3e40
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0x4b0
   __DATA_DIRTY.__bss: 0x40

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3888
-  Symbols:   5740
-  CStrings:  3889
+  Functions: 3895
+  Symbols:   5759
+  CStrings:  3914
 
Symbols:
+ +[NSData(TMExtensions) _tm_dataByReadingRegularFileAtURL:error:]
+ -[NSURL(TMAdditions) tm_FULLFSYNCItemsNamed:error:]
+ _NSCocoaErrorDomain
+ _TMOpenContainingDirectory
+ _TMReadErrorForErrno
+ ___42-[TMDiskImage writeTimeMachineInfo:error:]_block_invoke
+ ___42-[TMDiskImage writeTimeMachineInfo:error:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e15_v32?0816^B24l
+ _fstatat
+ _objc_msgSend$_tm_dataByReadingRegularFileAtURL:error:
+ _objc_msgSend$dictionaryWithCapacity:
+ _objc_msgSend$enumerateKeysAndObjectsUsingBlock:
+ _objc_msgSend$initWithFileDescriptor:closeOnDealloc:
+ _objc_msgSend$readDataToEndOfFileAndReturnError:
+ _objc_msgSend$tm_FULLFSYNCItemsNamed:error:
+ _openat
+ _renameat
+ _unlinkat
+ _writeTimeMachineInfo:error:.knownKeys
+ _writeTimeMachineInfo:error:.onceToken
- _objc_msgSend$dataWithContentsOfURL:options:error:
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/BackupDataSource/TMAPFSBackupListener.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/BackupDataSource/TMBackupDataSource.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/BackupDataSource/TMHFSBackupListener.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Configuration/TMConfiguration.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/AttrList.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/AttrListDisk.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMAPFSDisk.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMDADisk.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMDisk.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMDiskImage.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMFSUtilities.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMOtherIODisk.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMSnapshot.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMVolumeUtilities.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Extensions/DMManager+TMExtensions.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Extensions/Locks.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Extensions/NSData+TMExtensions.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Extensions/NSURL+TMAdditions.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/IPC/TMLocalSnapshotMessenger.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/IPC/TMXPCListener.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/IPC/XPC.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Logging/TMLog.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Misc/BackupCompareInternal.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Misc/TMMessageSerializer.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Misc/TMSystemInformation.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Misc/TMThinningAlgorithm.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/NodeCache/TMNodeCache.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/RulesEngine/TMDeviceRulesEngine.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/RulesEngine/TMRulesEngine.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/RulesEngine/TMRulesEngineBuilder.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Session/TMBackupProxy.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Session/TMSession+Finder.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Session/TMSession.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Session/TMTargetCache.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Structure/TMMonoStructure.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Structure/TMStructure+CoreStructures.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Structure/TMStructure.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/Structure/TMStructureMetadata.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/StructureModels/TMAPFSBackup.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/StructureModels/TMAPFSMachineStore.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/StructureModels/TMBackup.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/StructureModels/TMBackupStorage.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/StructureModels/TMInProgressContainer.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/StructureModels/TMMachineStore.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/StructureModels/TMReadOnlyBackup.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/StructureModels/TMVolumeStore.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/TestingSupport/TMImageDisk.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/backupd/TimeMachine-Framework/TestingSupport/TMTestDisk.m"
+ "Dropping unrecognized key '%@' from the Time Machine info for '%@'"
+ "FULLFSYNC failed for '%@', error: %d"
+ "FULLFSYNC failed to open '%@', error: %d"
+ "FULLFSYNC failed under '%@', error: %@"
+ "Failed to remove '%@', error: %d - the write will fail"
+ "Ignoring '%@' - not a real file or directory"
+ "Ignoring non-TimeMachine orphan diskimage '%@' with devices: %@"
+ "Refusing to read '%@' - it is a symbolic link"
+ "Refusing to read '%@' - it is not a regular file"
+ "Refusing to use '%@' - it is a symbolic link"
+ "SafeFileIO"
+ "Unexpected non-regular file at '%@' - removing it before writing"
+ "VerificationDate"
+ "VerificationExtendedSkip"
+ "VerificationID"
+ "VerificationSkeletonCaptureDate"
+ "VerificationState"
+ "_tm_dataByReadingRegularFileAtURL:error:"
+ "dictionaryWithCapacity:"
+ "enumerateKeysAndObjectsUsingBlock:"
+ "initWithFileDescriptor:closeOnDealloc:"
+ "readDataToEndOfFileAndReturnError:"
+ "timemachine"
+ "tm_FULLFSYNCItemsNamed:error:"
+ "v32@?0@8@16^B24"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/BackupDataSource/TMAPFSBackupListener.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/BackupDataSource/TMBackupDataSource.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/BackupDataSource/TMHFSBackupListener.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Configuration/TMConfiguration.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/AttrList.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/AttrListDisk.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMAPFSDisk.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMDADisk.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMDisk.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMDiskImage.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMFSUtilities.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMOtherIODisk.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMSnapshot.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/DisksAndFilesystems/TMVolumeUtilities.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Extensions/DMManager+TMExtensions.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Extensions/Locks.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Extensions/NSURL+TMAdditions.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/IPC/TMLocalSnapshotMessenger.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/IPC/TMXPCListener.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/IPC/XPC.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Logging/TMLog.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Misc/BackupCompareInternal.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Misc/TMMessageSerializer.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Misc/TMSystemInformation.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Misc/TMThinningAlgorithm.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/NodeCache/TMNodeCache.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/RulesEngine/TMDeviceRulesEngine.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/RulesEngine/TMRulesEngine.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/RulesEngine/TMRulesEngineBuilder.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Session/TMBackupProxy.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Session/TMSession+Finder.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Session/TMSession.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Session/TMTargetCache.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Structure/TMMonoStructure.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Structure/TMStructure+CoreStructures.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Structure/TMStructure.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/Structure/TMStructureMetadata.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/StructureModels/TMAPFSBackup.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/StructureModels/TMAPFSMachineStore.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/StructureModels/TMBackup.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/StructureModels/TMBackupStorage.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/StructureModels/TMInProgressContainer.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/StructureModels/TMMachineStore.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/StructureModels/TMReadOnlyBackup.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/StructureModels/TMVolumeStore.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/TestingSupport/TMImageDisk.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/backupd/TimeMachine-Framework/TestingSupport/TMTestDisk.m"
- "dataWithContentsOfURL:options:error:"
```
