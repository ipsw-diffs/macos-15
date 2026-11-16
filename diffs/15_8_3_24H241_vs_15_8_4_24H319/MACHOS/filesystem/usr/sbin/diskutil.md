## diskutil

> `/usr/sbin/diskutil`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 934.140.2.705.5
-  __TEXT.__text: 0xdfcc4
-  __TEXT.__auth_stubs: 0x24d0
+  __TEXT.__text: 0xdda18
+  __TEXT.__auth_stubs: 0x2460
   __TEXT.__objc_stubs: 0x5000
   __TEXT.__objc_methlist: 0x106c
-  __TEXT.__const: 0x5570
+  __TEXT.__const: 0x5559
   __TEXT.__objc_methname: 0x4fa7
-  __TEXT.__cstring: 0x1fc4f
+  __TEXT.__cstring: 0x1f3a9
   __TEXT.__objc_classname: 0xd2
   __TEXT.__objc_methtype: 0x5e6
   __TEXT.__ustring: 0x16

   __TEXT.__swift5_capture: 0x8a4
   __TEXT.__swift5_protos: 0x2c
   __TEXT.__swift5_mpenum: 0x70
-  __TEXT.__unwind_info: 0x2a50
-  __TEXT.__eh_frame: 0x369c
-  __DATA_CONST.__auth_got: 0x1278
-  __DATA_CONST.__got: 0x6b8
-  __DATA_CONST.__auth_ptr: 0xfa0
+  __TEXT.__unwind_info: 0x2a00
+  __TEXT.__eh_frame: 0x365c
+  __DATA_CONST.__auth_got: 0x1240
+  __DATA_CONST.__got: 0x6b0
+  __DATA_CONST.__auth_ptr: 0xf70
   __DATA_CONST.__const: 0x6380
-  __DATA_CONST.__cfstring: 0x88e0
+  __DATA_CONST.__cfstring: 0x85a0
   __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x8

   __DATA.__objc_data: 0x6d0
   __DATA.__data: 0x1c32
   __DATA.__common: 0x808
-  __DATA.__bss: 0xa224
+  __DATA.__bss: 0xa220
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/DiskArbitration.framework/Versions/A/DiskArbitration
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3956
-  Symbols:   1131
-  CStrings:  3344
+  Functions: 3931
+  Symbols:   1123
+  CStrings:  3308
 
Symbols:
- _CFDataAppendBytes
- _CFDataCreateMutableCopy
- _CFDataCreateWithBytesNoCopy
- _CFDataGetBytes
- _CFDataReplaceBytes
- _CFDataSetLength
- _kCFAllocatorMalloc
- _reallocf
CStrings:
+ " <array> \n<dict> \n<key>AppleRAID-LevelName</key><string>Stripe</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>None</string> \n<key>AppleRAID-CanBeConvertedTo</key><false/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Mirror</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n<string>AppleRAID-Spares</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><true/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><true/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>Any</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Concat</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><true/> \n<key>AppleRAID-RemovalAllowed</key><string>Last</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n </array> \n"
+ " <dict> \n<key>AppleRAID-HeaderVersion</key><integer size=\"32\">0x00020000</integer> \n<key>AppleRAID-LevelName</key><string>internal error</string> \n<key>AppleRAID-SetName</key><string>internal error</string> \n<key>AppleRAID-SetUUID</key><string>internal error</string> \n<key>AppleRAID-SequenceNumber</key><integer size=\"32\">1</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x00008000</integer> \n<key>AppleRAID-ChunkCount</key><integer size=\"64\">0</integer> \n<key>AppleRAID-Members</key><array/> \n<key>AppleRAID-Spares</key><array/> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>internal error</string> \n<key>AppleRAID-ContentHint</key><string/> \n </dict> \n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleCredentialManager_ClientLibs/ACMLib/ACMLib.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleCredentialManager_ClientLibs/common/CommonUtil.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleCredentialManager_ClientLibs/common/LibCall.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleCredentialManager_ClientLibs/common/LibCallBlock.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleCredentialManager_ClientLibs/common/LibSerialization.c"
- " <array> \n<dict> \n<key>AppleLVM-Type</key><string>concat</string> \n</dict> \n<dict> \n<key>AppleLVM-Type</key><string>snap ro</string> \n</dict> \n<dict> \n<key>AppleLVM-Type</key><string>snap rw</string> \n</dict> \n </array> \n"
- " <array> \n<dict> \n<key>AppleRAID-LevelName</key><string>Stripe</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-QuickRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>None</string> \n<key>AppleRAID-CanBeConvertedTo</key><false/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Mirror</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n<string>AppleRAID-Spares</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><true/> \n<key>AppleRAID-QuickRebuild</key><true/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><true/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>Any</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>Concat</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-QuickRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><true/> \n<key>AppleRAID-RemovalAllowed</key><string>Last</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n<dict> \n<key>AppleRAID-LevelName</key><string>LVG</string> \n<key>AppleRAID-MemberType</key><array> \n<string>AppleRAID-Members</string> \n</array> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">0</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x8000</integer> \n<key>AppleRAID-CanAddMembers</key><true/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><true/> \n<key>AppleRAID-RemovalAllowed</key><string>None</string> \n<key>AppleRAID-CanBeConvertedTo</key><true/> \n</dict> \n </array> \n"
- " <dict> \n<key>AppleLVM-Version</key><integer size=\"32\">0x00030000</integer> \n<key>AppleLVM-GroupUUID</key><string>internal error</string> \n<key>AppleLVM-VolumeUUID</key><string>internal error</string> \n<key>AppleLVM-Sequence</key><integer size=\"32\">0</integer> \n<key>AppleLVM-VolumeSize</key><integer size=\"64\">0x00000000</integer> \n<key>AppleLVM-ExtentCount</key><integer size=\"64\">0x00000001</integer> \n<key>AppleLVM-Type</key><string>internal error</string> \n<key>AppleLVM-Location</key><string/> \n<key>AppleLVM-ContentHint</key><string/> \n<key>AppleLVM-Name</key><string/> \n </dict> \n"
- " <dict> \n<key>AppleRAID-HeaderVersion</key><integer size=\"32\">0x00020000</integer> \n<key>AppleRAID-LevelName</key><string>internal error</string> \n<key>AppleRAID-SetName</key><string>internal error</string> \n<key>AppleRAID-SetUUID</key><string>internal error</string> \n<key>AppleRAID-SequenceNumber</key><integer size=\"32\">1</integer> \n<key>AppleRAID-ChunkSize</key><integer size=\"64\">0x00008000</integer> \n<key>AppleRAID-ChunkCount</key><integer size=\"64\">0</integer> \n<key>AppleRAID-Members</key><array/> \n<key>AppleRAID-Spares</key><array/> \n<key>AppleRAID-AutoRebuild</key><false/> \n<key>AppleRAID-QuickRebuild</key><false/> \n<key>AppleRAID-SetTimeout</key><integer size=\"32\">30</integer> \n<key>AppleRAID-CanAddMembers</key><false/> \n<key>AppleRAID-CanAddSpares</key><false/> \n<key>AppleRAID-SizesCanVary</key><false/> \n<key>AppleRAID-RemovalAllowed</key><string>internal error</string> \n<key>AppleRAID-ContentHint</key><string/> \n </dict> \n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleCredentialManager_ClientLibs/ACMLib/ACMLib.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleCredentialManager_ClientLibs/common/CommonUtil.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleCredentialManager_ClientLibs/common/LibCall.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleCredentialManager_ClientLibs/common/LibCallBlock.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleCredentialManager_ClientLibs/common/LibSerialization.c"
- "AppleLVM-"
- "AppleLVM-ExtentCount"
- "AppleLVM-GroupUUID"
- "AppleLVM-Location"
- "AppleLVM-ParentUUID"
- "AppleLVM-Sequence"
- "AppleLVM-Status"
- "AppleLVM-Type"
- "AppleLVM-VolumeSize"
- "AppleLVM-VolumeUUID"
- "AppleLVMNotificationVolumeChanged"
- "AppleLVMNotificationVolumeDiscovered"
- "AppleLVMNotificationVolumeTerminated"
- "AppleLVMVolume"
- "AppleRAID-LVGExtents"
- "AppleRAID-LVGFreeSpace"
- "AppleRAID-LVGVolumeCount"
- "AppleRAID-MemberStart"
- "AppleRAID-MetaData1Used"
- "AppleRAID-MetaData2Size"
- "AppleRAID-QuickRebuild"
- "AppleRAID: Failed to find the size of the mirror quick rebuild bitmap."
- "AppleRAID: Insufficent free space to create requested logical volume."
- "AppleRAID: Insufficent free space to resize the logical volume."
- "AppleRAIDPrimary"
- "AppleRAIDUserLib.c"
- "RAIDNoMedia"
- "_extent data_"
- "bitmap"
- "fast"
- "header->lvExtentsCount == 1"
- "master"
- "meta"
- "writeSecondaryMetaData"
```
