## afscexpand

> `/usr/bin/afscexpand`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-170.0.0.700.1
-  __TEXT.__text: 0x12864
+170.0.0.701.1
+  __TEXT.__text: 0x12888
   __TEXT.__auth_stubs: 0x320
   __TEXT.__const: 0x23640
-  __TEXT.__cstring: 0xb7c
+  __TEXT.__cstring: 0xbca
   __TEXT.__unwind_info: 0x200
   __TEXT.__eh_frame: 0x50
   __DATA_CONST.__auth_got: 0x190
Functions:
~ sub_10000d564 : 2796 -> 2828
~ sub_100010b88 -> sub_100010ba8 : 1516 -> 1520
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleFSCompression_executables/Common/ChunkCompression.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleFSCompression_executables/Common/commonUtilsUser.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleFSCompression_executables/Libraries/CompressData/CompressData.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleFSCompression_executables/Common/ChunkCompression.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleFSCompression_executables/Common/commonUtilsUser.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleFSCompression_executables/Libraries/CompressData/CompressData.c"
```
