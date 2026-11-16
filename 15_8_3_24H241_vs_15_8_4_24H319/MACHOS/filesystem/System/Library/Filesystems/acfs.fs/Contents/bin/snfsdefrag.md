## snfsdefrag

> `/System/Library/Filesystems/acfs.fs/Contents/bin/snfsdefrag`

### Sections with Same Size but Changed Content

- `__DATA.__data`

```diff

-782.140.2.0.0
+782.140.2.700.5
   __TEXT.__text: 0x91e0
   __TEXT.__auth_stubs: 0x5d0
   __TEXT.__const: 0x50
-  __TEXT.__cstring: 0x2352
+  __TEXT.__cstring: 0x23a0
   __TEXT.__unwind_info: 0x268
   __DATA_CONST.__auth_got: 0x2e8
   __DATA_CONST.__got: 0x30
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../authlib/libcvfsauth.a(auth_connection.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../authlib/libcvfsauth.a(auth_globals.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../authlib/libcvfsauth.a(md5.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../authlib/libcvfsauth.a(utilities.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../extapi/libcvextapi.a(cvapi.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../fsmlib/libfsmlib-static.a(program_init.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../fsmlib/libfsmlib-static.a(subr_nomad.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../fsmlib/libglobals-static.a(globals.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(alloc.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(cvras.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(dopanic.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(getroot.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(list.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(logger.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(priv_check.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(resolvshim.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(snprintf.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(thread_common.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(thrpri.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(util_track.c.o)
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/CMakeFiles/snfsdefrag.dir/snfsdefrag.c.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/authlib/
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/extapi/
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/fsmlib/
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/include/common/
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/libutil/
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/snfsdefrag/
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../authlib/libcvfsauth.a(auth_connection.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../authlib/libcvfsauth.a(auth_globals.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../authlib/libcvfsauth.a(md5.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../authlib/libcvfsauth.a(utilities.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../extapi/libcvextapi.a(cvapi.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../fsmlib/libfsmlib-static.a(program_init.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../fsmlib/libfsmlib-static.a(subr_nomad.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../fsmlib/libglobals-static.a(globals.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(alloc.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(cvras.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(dopanic.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(getroot.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(list.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(logger.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(priv_check.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(resolvshim.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(snprintf.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(thread_common.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(thrpri.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/../libutil/libsnutil-static.a(util_track.c.o)
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/XsanFS/install/TempContent/Objects/snfs/snfsdefrag/CMakeFiles/snfsdefrag.dir/snfsdefrag.c.o
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/authlib/
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/extapi/
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/fsmlib/
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/include/common/
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/libutil/
- /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/snfsdefrag/
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/libutil/alloc.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/libutil/cvras.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/snfsdefrag/snfsdefrag.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/libutil/alloc.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/libutil/cvras.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/snfsdefrag/snfsdefrag.c"
```
