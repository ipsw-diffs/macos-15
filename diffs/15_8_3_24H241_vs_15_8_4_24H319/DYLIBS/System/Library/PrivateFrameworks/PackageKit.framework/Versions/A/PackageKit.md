## PackageKit

> `/System/Library/PrivateFrameworks/PackageKit.framework/Versions/A/PackageKit`

```diff

-1474.140.7.707.2
-  __TEXT.__text: 0x87568
+1474.140.7.708.4
+  __TEXT.__text: 0x88318
   __TEXT.__auth_stubs: 0x2130
-  __TEXT.__objc_methlist: 0x7824
+  __TEXT.__objc_methlist: 0x788c
   __TEXT.__const: 0x340
-  __TEXT.__cstring: 0x11c08
+  __TEXT.__cstring: 0x11ed1
   __TEXT.__constg_swiftt: 0x188
   __TEXT.__swift5_typeref: 0x7c
   __TEXT.__swift5_reflstr: 0x21
   __TEXT.__swift5_fieldmd: 0x5c
   __TEXT.__swift5_types: 0x8
-  __TEXT.__gcc_except_tab: 0x14c4
+  __TEXT.__gcc_except_tab: 0x1558
   __TEXT.__oslogstring: 0x19
   __TEXT.__dof_PackageKi: 0x1ba4
-  __TEXT.__unwind_info: 0x2090
+  __TEXT.__unwind_info: 0x20a8
   __TEXT.__eh_frame: 0x40
   __TEXT.__objc_classname: 0x1091
-  __TEXT.__objc_methname: 0x11d85
-  __TEXT.__objc_methtype: 0x254a
-  __TEXT.__objc_stubs: 0xdf60
+  __TEXT.__objc_methname: 0x11f0e
+  __TEXT.__objc_methtype: 0x2623
+  __TEXT.__objc_stubs: 0xe080
   __DATA_CONST.__got: 0x9b0
   __DATA_CONST.__const: 0xc78
   __DATA_CONST.__objc_classlist: 0x448
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4540
+  __DATA_CONST.__objc_selrefs: 0x4588
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x3a8
   __DATA_CONST.__objc_arraydata: 0x68
   __AUTH_CONST.__auth_got: 0x10a8
   __AUTH_CONST.__const: 0x17a0
   __AUTH_CONST.__cfstring: 0xb7c0
-  __AUTH_CONST.__objc_const: 0xbbd8
+  __AUTH_CONST.__objc_const: 0xbc68
   __AUTH_CONST.__objc_intobj: 0x468
   __AUTH_CONST.__objc_arrayobj: 0x48
   __AUTH.__objc_data: 0x2af0
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0xa04
+  __DATA.__objc_ivar: 0xa10
   __DATA.__data: 0x810
   __DATA.__crash_info: 0x40
   __DATA.__bss: 0x230

   - /usr/lib/swift/libswift_time.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2806
-  Symbols:   7381
-  CStrings:  5425
+  Functions: 2815
+  Symbols:   7402
+  CStrings:  5456
 
Symbols:
+ +[PKBundleComponent _enumerateDirectoryWithFileDescriptor:anchor:relativePath:intoReferenceArray:droppedEntries:]
+ +[PKFileReference fileReferenceWithAnchor:relativePath:fileStat:parentStat:error:]
+ -[PKBundleComponent onDiskSubpathFileReferences]
+ -[PKFileReference _openAndStatAnchoredParentWithOpenOptions:outStatBuf:error:]
+ -[PKFileReference anchorParentRange]
+ -[PKFileReference anchor]
+ -[PKFileReference fileMode]
+ -[PKFileReference initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:fileMode:]
+ -[PKFileReference setAnchor:]
+ -[PKFileReference setAnchorParentRange:]
+ -[PKFileReference setFileMode:]
+ _CFHashBytes
+ _OBJC_IVAR_$_PKFileReference._anchor
+ _OBJC_IVAR_$_PKFileReference._anchorParentRange
+ _OBJC_IVAR_$_PKFileReference._fileMode
+ _objc_msgSend$_enumerateDirectoryWithFileDescriptor:anchor:relativePath:intoReferenceArray:droppedEntries:
+ _objc_msgSend$_openAndStatAnchoredParentWithOpenOptions:outStatBuf:error:
+ _objc_msgSend$anchor
+ _objc_msgSend$anchorParentRange
+ _objc_msgSend$fileMode
+ _objc_msgSend$initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:fileMode:
+ _objc_msgSend$onDiskSubpathFileReferences
+ _objc_msgSend$setAnchor:
+ _objc_msgSend$setAnchorParentRange:
+ _objc_msgSend$setFileMode:
- +[PKFileReference fileReferenceWithPath:error:]
- -[PKFileReference initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:]
- _objc_msgSend$initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:
- _truncate
CStrings:
+ "@52@0:8@16i24Q28i36Q40S48"
+ "PackageKit: %lu entries of PKComponent(%s) were left out of its references in total."
+ "PackageKit: Cannot obsolete expected directory (%s) and its .DS_Store has already been removed, unlinkat() has failed. %s"
+ "PackageKit: Cannot obsolete expected directory (%s), removing its .DS_Store failed. %s"
+ "PackageKit: Cannot obsolete expected directory (%s), unlinkat() has failed. %s"
+ "PackageKit: Failed to fstat directory for reference enumeration: %s"
+ "PackageKit: Leaving %s out of the bundle's references: %s"
+ "PackageKit: Not descending into %s: it changed between being stat'd and opened."
+ "PackageKit: Recording %s without its contents: %s"
+ "PackageKit: Refusing to enumerate references for PKComponent(%s): no validated bundle reference."
+ "PackageKit: Will not obsolete bundle %s: its on-disk contents could not be enumerated through a validated descriptor."
+ "S"
+ "S16@0:8"
+ "T@\"PKFileReference\",&,N,V_anchor"
+ "TS,N,V_fileMode"
+ "T{_NSRange=QQ},N,V_anchorParentRange"
+ "_anchor"
+ "_anchorParentRange"
+ "_enumerateDirectoryWithFileDescriptor:anchor:relativePath:intoReferenceArray:droppedEntries:"
+ "_fileMode"
+ "_openAndStatAnchoredParentWithOpenOptions:outStatBuf:error:"
+ "anchor"
+ "anchorParentRange"
+ "fileMode"
+ "i36@0:8i16^{stat=iSSQIIi{timespec=qq}{timespec=qq}{timespec=qq}{timespec=qq}qqiIIi[2q]}20^@28"
+ "initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:fileMode:"
+ "onDiskSubpathFileReferences"
+ "setAnchor:"
+ "setAnchorParentRange:"
+ "setFileMode:"
+ "v20@0:8S16"
+ "v32@0:8{_NSRange=QQ}16"
+ "v52@0:8i16@20@28@36^Q44"
+ "{_NSRange=\"location\"Q\"length\"Q}"
+ "{_NSRange=QQ}16@0:8"
- "@48@0:8@16i24Q28i36Q40"
- "PackageKit: Cannot obsolete expected directory (%s), removefileat() has failed. %s"
- "PackageKit: Error creating reference for %s: %s"
- "initWithPath:parentDeviceID:parentInode:fileDeviceID:fileInode:"
```
