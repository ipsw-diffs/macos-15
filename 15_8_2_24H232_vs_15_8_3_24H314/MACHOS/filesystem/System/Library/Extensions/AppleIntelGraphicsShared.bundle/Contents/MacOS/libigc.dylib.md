## libigc.dylib

> `/System/Library/Extensions/AppleIntelGraphicsShared.bundle/Contents/MacOS/libigc.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__la_symbol_ptr`
- `__DATA.__data`

```diff

 23.7.10.0.0
-  __TEXT.__text: 0xd5375f
+  __TEXT.__text: 0xd5374f
   __TEXT.__stubs: 0x5a0
   __TEXT.__stub_helper: 0x92a
   __TEXT.__init_offsets: 0x5f8
   __TEXT.__const: 0x5d730
-  __TEXT.__cstring: 0x8a8cd
+  __TEXT.__cstring: 0x8a8e7
   __TEXT.__gcc_except_tab: 0x25b98
   __TEXT.__unwind_info: 0xd200
   __TEXT.__eh_frame: 0x58
Functions:
~ __ZL13getAttributesRN4llvm11LLVMContextENS_15GenISAIntrinsic2IDE : 400 -> 384
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/GPUDriversIntel/igc/gfx-driver/Source/visa/iga/GEDLibrary/GED_internal/Source/ged/xcoder/ged_ins.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/GPUDriversIntel/igc/gfx-driver/Source/visa/iga/GEDLibrary/GED_internal/Source/ged/xcoder/ged_ins.cpp"
```
