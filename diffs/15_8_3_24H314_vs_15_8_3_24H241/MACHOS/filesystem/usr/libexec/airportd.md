## airportd

> `/usr/libexec/airportd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-19075.40.0.0.0
-  __TEXT.__text: 0xf44a8
-  __TEXT.__auth_stubs: 0x2110
-  __TEXT.__objc_stubs: 0x11780
+19075.39.0.0.0
+  __TEXT.__text: 0xf3e54
+  __TEXT.__auth_stubs: 0x20d0
+  __TEXT.__objc_stubs: 0x117a0
   __TEXT.__objc_methlist: 0x6330
   __TEXT.__const: 0xf48
-  __TEXT.__objc_methname: 0x163ac
+  __TEXT.__objc_methname: 0x163c9
   __TEXT.__objc_classname: 0x414
   __TEXT.__objc_methtype: 0x3d66
   __TEXT.__gcc_except_tab: 0x1fd8
-  __TEXT.__cstring: 0x2e079
-  __TEXT.__oslogstring: 0x14e6
+  __TEXT.__cstring: 0x2dfaf
+  __TEXT.__oslogstring: 0x1326
   __TEXT.__unwind_info: 0x2920
   __TEXT.__eh_frame: 0xf8
-  __DATA_CONST.__auth_got: 0x1098
+  __DATA_CONST.__auth_got: 0x1078
   __DATA_CONST.__got: 0xa18
   __DATA_CONST.__auth_ptr: 0x20
   __DATA_CONST.__const: 0x34d8

   __DATA_CONST.__objc_arrayobj: 0x90
   __DATA_CONST.__objc_dictobj: 0x168
   __DATA.__objc_const: 0x8580
-  __DATA.__objc_selrefs: 0x4fb0
+  __DATA.__objc_selrefs: 0x4fb8
   __DATA.__objc_ivar: 0x95c
   __DATA.__objc_data: 0xcd0
   __DATA.__data: 0x4b8

   - /usr/lib/libpcap.A.dylib
   - /usr/lib/libz.1.dylib
   Functions: 3202
-  Symbols:   882
-  CStrings:  8222
+  Symbols:   878
+  CStrings:  8215
 
Symbols:
- _fdopen
- _fstat
- _rename
- _unlink
Functions:
~ sub_1000736c0 : 4108 -> 2488
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AirPort_executables/Tools/airportd/CWXPCSubsystem.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AirPort_executables/Tools/airportd/airportProcessCommand.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AirPort_executables/Tools/airportd/airportdAutoJoin.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AirPort_executables/Tools/airportd/airportdCommandLine.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AirPort_executables/Tools/airportd/airportdMain.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AirPort_executables/Tools/airportd/airportdPreferences.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AirPort_executables/Tools/airportd/configdIODriverInterface.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/AirPort_executables/Tools/airportd/configdSCInterface.m"
+ "/private/var/tmp/%@"
+ "<%{public}s:%u> Unable to open read file '%{public}s'"
+ "moveItemAtPath:toPath:error:"
- "%@/.%@.XXXXXX"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AirPort_executables/Tools/airportd/CWXPCSubsystem.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AirPort_executables/Tools/airportd/airportProcessCommand.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AirPort_executables/Tools/airportd/airportdAutoJoin.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AirPort_executables/Tools/airportd/airportdCommandLine.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AirPort_executables/Tools/airportd/airportdMain.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AirPort_executables/Tools/airportd/airportdPreferences.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AirPort_executables/Tools/airportd/configdIODriverInterface.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AirPort_executables/Tools/airportd/configdSCInterface.m"
- "<%{public}s:%u> Not a regular file '%{public}s'"
- "<%{public}s:%u> Path too long '%{public}s'"
- "<%{public}s:%u> Unable to close '%{public}s'"
- "<%{public}s:%u> Unable to create temporary file '%{public}s', errno[%d]"
- "<%{public}s:%u> Unable to flush '%{public}s'"
- "<%{public}s:%u> Unable to move '%{public}s' to '%{public}s', errno[%d]"
- "<%{public}s:%u> Unable to open read file '%{public}s', errno[%d]"
- "<%{public}s:%u> Unable to open read stream '%{public}s'"
- "<%{public}s:%u> Unable to open write stream '%{public}s'"
```
