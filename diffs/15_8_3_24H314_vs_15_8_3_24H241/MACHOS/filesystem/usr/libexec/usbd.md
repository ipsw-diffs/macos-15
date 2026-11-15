## usbd

> `/usr/libexec/usbd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

   __TEXT.__auth_stubs: 0x410
   __TEXT.__objc_stubs: 0x6e0
   __TEXT.__objc_methlist: 0x26c
-  __TEXT.__cstring: 0xd4c
+  __TEXT.__cstring: 0xd18
   __TEXT.__const: 0x20
   __TEXT.__objc_classname: 0x19
   __TEXT.__objc_methname: 0x825
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOUSBFamily_executables/USBAgentAndDaemon/Daemon/Classes/USBDaemon.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOUSBFamily_executables/USBAgentAndDaemon/Daemon/Classes/USBDevice.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOUSBFamily_executables/USBAgentAndDaemon/Daemon/Classes/USBDaemon.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOUSBFamily_executables/USBAgentAndDaemon/Daemon/Classes/USBDevice.m"
```
