## bluetoothd

> `/usr/sbin/bluetoothd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-186.4.0.8.0
-  __TEXT.__text: 0x7ad0ec
+186.4.0.9.0
+  __TEXT.__text: 0x7ad380
   __TEXT.__auth_stubs: 0x4040
   __TEXT.__objc_stubs: 0x102c0
   __TEXT.__init_offsets: 0x54
   __TEXT.__objc_methlist: 0x5a3c
-  __TEXT.__gcc_except_tab: 0x5daa0
+  __TEXT.__gcc_except_tab: 0x5daa4
   __TEXT.__const: 0x7ecc
-  __TEXT.__cstring: 0xa0121
+  __TEXT.__cstring: 0xa0812
   __TEXT.__oslogstring: 0xa3c32
   __TEXT.__objc_methname: 0x13128
   __TEXT.__objc_classname: 0x60a

   - /usr/lib/libsqlite3.dylib
   Functions: 29874
   Symbols:   1303
-  CStrings:  34294
+  CStrings:  34299
 
Functions:
~ sub_1000d6ca0 : 908 -> 1192
~ sub_10011bcf8 -> sub_10011be14 : 280 -> 284
~ sub_10011c4e8 -> sub_10011c608 : 1020 -> 1380
~ sub_1004c73b8 -> sub_1004c7640 : 852 -> 864
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Daemon/Server/XpcClassicConnection.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/Chipsets/LEHardwareModel.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/Platforms/Darwin/BT_DataElements.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/Platforms/Darwin/DeviceSettings.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/Platforms/Darwin/VirtualController/BTVirtualHciCommandChannel.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/Platforms/Darwin/VirtualController/BTVirtualHciPacket.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/Platforms/Darwin/VirtualController/include/BTVirtualHciPacket.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/a2dp/A2DPClient.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/aacp/AACPClient.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/core/Device.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/core/FastConnectManager.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Server/core/LocalDevice.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/Platforms/Darwin/bm3_uart.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/Platforms/Darwin/hcilite_filter.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/Platforms/Darwin/pcie_mempool.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/cl/BT_CL_Signaling.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/cl/BT_TS_Switching.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/dataelem/marshaller.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/hci/hcicmdapi.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/hci/hcievents.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/hci/hciflow.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/hci/hciparmcache.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/l2cap/chanman.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/l2cap/group.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/l2cap/signalman.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/le/LEA.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/le/LE_Events.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/magicPairing/BT_MagicPairing.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/sdp/sdp.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/sdp/sdpdb.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/sdp/sdpserver.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/support/oi_bytestream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/support/oi_mbuf.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/corestack/support/oi_varstring.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/aacp/aacp_client.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/aap/aap_client.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/av/avctp/avctp.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/av/avdtp/avdtp.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/av/avdtp/avdtp_signal.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/av/avrcp/avrcp_helper.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/av/avrcp/avrcp_metadata.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/bip/oi_bip_private.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/obex/obexcommon.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/profiles/obex/obexsrv_common.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/vsc/aci/aci_vsc.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/vsc/bcm/bcm_vsc.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/vsc/srs/srs_vsc.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/vsc/vsc.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/MobileBluetooth/Stack/vsc/vse.c"
+ "20:39:14"
+ "Nov 12 2026"
+ "Rejected malformed AAP SDP Protocol Descriptor List -- l2capSeq element type validation failed, ElemSeq[1].ElemType:%d\n"
+ "Rejected malformed AAP SDP Protocol Descriptor List -- l2capSeq type validation failed, ElemType:%d\n Size:%d \n"
+ "Rejected malformed AAP SDP Protocol Descriptor List -- seq type/size validation failed, ElemType:%d Size:%d \n"
+ "Rejecting HID GET_REPORT %s response, expectingContinuation=%d (transParam 0x%x len %d)"
+ "Rejecting HID GET_REPORT response - exceeded %d fragments for one request"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Daemon/Server/XpcClassicConnection.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/Chipsets/LEHardwareModel.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/Platforms/Darwin/BT_DataElements.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/Platforms/Darwin/DeviceSettings.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/Platforms/Darwin/VirtualController/BTVirtualHciCommandChannel.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/Platforms/Darwin/VirtualController/BTVirtualHciPacket.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/Platforms/Darwin/VirtualController/include/BTVirtualHciPacket.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/a2dp/A2DPClient.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/aacp/AACPClient.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/core/Device.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/core/FastConnectManager.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Server/core/LocalDevice.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/Platforms/Darwin/bm3_uart.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/Platforms/Darwin/hcilite_filter.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/Platforms/Darwin/pcie_mempool.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/cl/BT_CL_Signaling.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/cl/BT_TS_Switching.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/dataelem/marshaller.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/hci/hcicmdapi.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/hci/hcievents.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/hci/hciflow.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/hci/hciparmcache.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/l2cap/chanman.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/l2cap/group.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/l2cap/signalman.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/le/LEA.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/le/LE_Events.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/magicPairing/BT_MagicPairing.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/sdp/sdp.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/sdp/sdpdb.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/sdp/sdpserver.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/support/oi_bytestream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/support/oi_mbuf.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/corestack/support/oi_varstring.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/aacp/aacp_client.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/aap/aap_client.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/av/avctp/avctp.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/av/avdtp/avdtp.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/av/avdtp/avdtp_signal.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/av/avrcp/avrcp_helper.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/av/avrcp/avrcp_metadata.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/bip/oi_bip_private.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/obex/obexcommon.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/profiles/obex/obexsrv_common.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/vsc/aci/aci_vsc.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/vsc/bcm/bcm_vsc.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/vsc/srs/srs_vsc.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/vsc/vsc.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/MobileBluetooth/Stack/vsc/vse.c"
- "21:37:21"
- "Nov  2 2026"
```
