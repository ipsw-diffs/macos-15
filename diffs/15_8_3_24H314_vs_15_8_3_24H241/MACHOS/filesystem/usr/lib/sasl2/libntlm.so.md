## libntlm.so

> `/usr/lib/sasl2/libntlm.so`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

 215.0.0.0.0
   __TEXT.__text: 0x3dd4
   __TEXT.__auth_stubs: 0x200
-  __TEXT.__cstring: 0xc11
+  __TEXT.__cstring: 0xbc3
   __TEXT.__unwind_info: 0xf0
   __DATA_CONST.__auth_got: 0x100
   __DATA_CONST.__got: 0x10
CStrings:
+ "Out of Memory in /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/passwordserver_sasl/cyrus_sasl/plugins/ntlm.c near line %d"
+ "Out of Memory in /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/passwordserver_sasl/cyrus_sasl/plugins/plugin_common.c near line %d"
+ "Parameter Error in /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/passwordserver_sasl/cyrus_sasl/plugins/plugin_common.c near line %d"
- "Out of Memory in /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/passwordserver_sasl/cyrus_sasl/plugins/ntlm.c near line %d"
- "Out of Memory in /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/passwordserver_sasl/cyrus_sasl/plugins/plugin_common.c near line %d"
- "Parameter Error in /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/passwordserver_sasl/cyrus_sasl/plugins/plugin_common.c near line %d"
```
