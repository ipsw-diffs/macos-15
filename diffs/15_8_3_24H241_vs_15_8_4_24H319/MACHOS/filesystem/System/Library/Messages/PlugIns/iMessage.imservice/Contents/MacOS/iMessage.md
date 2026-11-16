## iMessage

> `/System/Library/Messages/PlugIns/iMessage.imservice/Contents/MacOS/iMessage`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1402.700.63.1.43
-  __TEXT.__text: 0x9fc20
+1402.700.63.1.46
+  __TEXT.__text: 0x9fc70
   __TEXT.__auth_stubs: 0x1120
   __TEXT.__objc_stubs: 0xb020
-  __TEXT.__objc_methlist: 0x26cc
+  __TEXT.__objc_methlist: 0x26dc
   __TEXT.__const: 0x38a
-  __TEXT.__gcc_except_tab: 0xa96c
+  __TEXT.__gcc_except_tab: 0xa978
   __TEXT.__cstring: 0x2d4d
-  __TEXT.__oslogstring: 0x14088
+  __TEXT.__oslogstring: 0x13ff8
   __TEXT.__objc_classname: 0x4e1
-  __TEXT.__objc_methname: 0x10249
+  __TEXT.__objc_methname: 0x10257
   __TEXT.__objc_methtype: 0x278e
   __TEXT.__ustring: 0x4
   __TEXT.__constg_swiftt: 0x178

   __TEXT.__swift_as_ret: 0x14
   __TEXT.__swift5_capture: 0xa0
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x1e50
+  __TEXT.__unwind_info: 0x1e60
   __TEXT.__eh_frame: 0x2c0
   __DATA_CONST.__auth_got: 0x8a0
   __DATA_CONST.__got: 0xd70

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1323
+  Functions: 1324
   Symbols:   736
-  CStrings:  4093
+  CStrings:  4092
 
CStrings:
+ "_setReplyToGUIDForMessage:messageDictionary:"
+ "setReplyToMessageGUID: %@ for message: %@"
- "Dropping group message payload of type %@ because its sender %@ is not in its from participants: %@"
- "Dropping message because its sender %@ is not in its participant list. participants: %@"
- "isSender:listedInParticipants:"
```
