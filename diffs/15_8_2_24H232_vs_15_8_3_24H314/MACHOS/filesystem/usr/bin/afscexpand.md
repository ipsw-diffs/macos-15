## afscexpand

> `/usr/bin/afscexpand`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-170.0.0.700.1
-  __TEXT.__text: 0x127d4
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
~ sub_10000af0c : 2460 -> 2540
~ sub_10000b8a8 -> sub_10000b8f8 : 2792 -> 2784
~ sub_10000c5cc -> sub_10000c614 : 792 -> 804
~ sub_10000c8e4 -> sub_10000c938 : 432 -> 444
~ sub_10000ca94 -> sub_10000caf4 : 864 -> 876
~ sub_10000cdf4 -> sub_10000ce60 : 496 -> 508
~ sub_10000cfe4 -> sub_10000d05c : 812 -> 824
~ sub_10000d310 -> sub_10000d394 : 452 -> 464
~ sub_10000d4d4 -> sub_10000d564 : 2796 -> 2828
~ sub_100010af8 -> sub_100010ba8 : 1516 -> 1520
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleFSCompression_executables/Common/ChunkCompression.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleFSCompression_executables/Common/commonUtilsUser.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AppleFSCompression_executables/Libraries/CompressData/CompressData.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleFSCompression_executables/Common/ChunkCompression.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleFSCompression_executables/Common/commonUtilsUser.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AppleFSCompression_executables/Libraries/CompressData/CompressData.c"
```
