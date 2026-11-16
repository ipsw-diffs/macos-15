## AppleMIDIUSBDriver

> `/System/Library/Extensions/AppleMIDIUSBDriver.plugin/Contents/MacOS/AppleMIDIUSBDriver`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-315.501.0.0.0
-  __TEXT.__text: 0x1f790
+315.503.0.0.0
+  __TEXT.__text: 0x1f984
   __TEXT.__auth_stubs: 0x8e0
-  __TEXT.__gcc_except_tab: 0xeb0
-  __TEXT.__cstring: 0x90f
-  __TEXT.__const: 0x272
-  __TEXT.__oslogstring: 0x4306
+  __TEXT.__gcc_except_tab: 0xeac
+  __TEXT.__cstring: 0x978
+  __TEXT.__const: 0x27a
+  __TEXT.__oslogstring: 0x4466
   __TEXT.__unwind_info: 0xad0
   __DATA_CONST.__auth_got: 0x478
   __DATA_CONST.__got: 0x100
-  __DATA_CONST.__const: 0xce0
+  __DATA_CONST.__const: 0xcf8
   __DATA_CONST.__cfstring: 0x400
   __DATA.__data: 0xb0
   __DATA.__bss: 0x138

   - /usr/lib/libc++.1.dylib
   Functions: 553
   Symbols:   183
-  CStrings:  393
+  CStrings:  398
 
Functions:
~ sub_51bc : 492 -> 652
~ sub_589c -> sub_593c : 2128 -> 2276
~ sub_1761c -> sub_17750 : 3316 -> 3508
CStrings:
+ "%25s:%-5d USBDevice::LoadDescriptor - Refusing string descriptor bLength %d into a %zu byte buffer"
+ "%25s:%-5d [!]  FATAL: Could not retrieve Group Terminal Descriptors for USB MIDI interface %d alternate setting %d (error 0x%x)"
+ "%25s:%-5d [!]  FATAL: Expected %u byte(s) of group terminal block descriptors but got %u (error 0x%x)"
+ "%25s:%-5d [!]  FATAL: Rejecting Group Terminal Block descriptor header for USB MIDI interface %d alternate setting %d: %s (headerLength %u, buffer capacity %u): %s"
+ "%25s:%-5d [+] USBDevice::LoadGroupTerminalDescriptors(interface: %d, altSettingNumber: %d, buf:%p, bufCapacity:%zu, len:%d)"
+ "%25s:%-5d [-] USBDevice::LoadGroupTerminalDescriptors() - Refusing to request %u byte(s) into a %zu byte buffer"
+ "incomplete descriptor header"
+ "wTotalLength is not a whole number of descriptors"
+ "wTotalLength out of range"
- "%25s:%-5d      Unexpected group terminal descriptor length: %u"
- "%25s:%-5d      Unexpected total descriptor length: %u"
- "%25s:%-5d [!]  FATAL: Could not retrieve Group Terminal Descriptors for USB MIDI interface %d alternate setting %d. Expected header length %u but got %u"
- "%25s:%-5d [+] USBDevice::LoadGroupTerminalDescriptors(interface: %d, altSettingNumber: %d, buf:%p, len:%d)"
```
