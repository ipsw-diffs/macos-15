## MailCore

> `/System/Library/PrivateFrameworks/MailCore.framework/Versions/A/MailCore`

```diff

-3826.700.81.1.11
-  __TEXT.__text: 0x8a3d8
+3826.700.81.1.12
+  __TEXT.__text: 0x8a3d0
   __TEXT.__auth_stubs: 0x1220
   __TEXT.__objc_methlist: 0x80e4
   __TEXT.__const: 0x4b0
-  __TEXT.__cstring: 0x7f7f
+  __TEXT.__cstring: 0x7e9e
   __TEXT.__gcc_except_tab: 0x16bc
   __TEXT.__oslogstring: 0x1d3e
   __TEXT.__unwind_info: 0x2220
Functions:
~ -[NSData(HFSDataConversion) wrapperForAppleFileDataWithFileEncodingHint:] : 2860 -> 2848
~ -[MCMimePart _decodeMultipartAppledouble] : 1148 -> 1152
CStrings:
+ "!appleFileEntryIsInBounds(&thisEntry, length)"
+ "thisEntry.entryLength < sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt16)"
+ "thisEntry.entryLength < sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32)"
+ "thisEntry.entryLength > MAXPATHLEN"
- "thisEntry.entryLength > length || thisEntry.entryOffset > length || thisEntry.entryOffset > length - thisEntry.entryLength"
- "thisEntry.entryLength > length || thisEntry.entryOffset > length || thisEntry.entryOffset > length - thisEntry.entryLength || thisEntry.entryLength > MAXPATHLEN"
- "thisEntry.entryOffset > length - (sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt16))"
- "thisEntry.entryOffset > length - (sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32) + sizeof(UInt32))"
```
