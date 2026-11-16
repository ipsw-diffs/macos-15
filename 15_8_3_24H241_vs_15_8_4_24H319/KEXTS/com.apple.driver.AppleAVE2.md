## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

```diff

-803.73.5.0.0
+803.73.6.0.0
   __TEXT.__const: 0x2ef60
-  __TEXT.__cstring: 0x364b2
-  __TEXT.__os_log: 0x41534
-  __TEXT_EXEC.__text: 0x14c96c
+  __TEXT.__cstring: 0x36937
+  __TEXT.__os_log: 0x41847
+  __TEXT_EXEC.__text: 0x14d4ac
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x290
   __DATA.__common: 0x130
   __DATA.__bss: 0x568
-  __DATA_CONST.__auth_got: 0x3e0
+  __DATA_CONST.__auth_got: 0x3e8
   __DATA_CONST.__got: 0xc0
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__mod_init_func: 0x38

   __DATA_CONST.__kalloc_type: 0x3f80
   __DATA_CONST.__kalloc_var: 0x1b80
   Functions: 2451
-  Symbols:   8453
-  CStrings:  7059
+  Symbols:   8465
+  CStrings:  7086
 
Symbols:
+ __ZZ22AVE_CalcBufSizeOfRecon14_E_AVE_DevType16_E_AVE_CodecTypeiiii12_E_ChromaFmtbPiS2_S2_S2_E11_os_log_fmt
+ __ZZ25AVE_CHM_SetDataInfo_FrameP10_S_AVE_CHMP16_S_AVE_FrameInfoP18AVE_PICMGMT_PARAMSE11_os_log_fmt_2
+ __ZZ25AVE_Client_CheckFrameInfoP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_5
+ __ZZ25AVE_Client_CheckFrameInfoP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_6
+ __ZZ25AVE_Client_CheckFrameInfoP13_S_AVE_ClientP16_S_AVE_FrameInfoE11_os_log_fmt_7
+ __ZZ26AVE_UCCmd_CheckParam_Start12_E_AVE_DevID17_E_AVE_ClientTypeP21S_AVE_UCInParam_StartE11_os_log_fmt_3
+ __ZZ27AVE_CalcBufSizeOfMCTFOutput14_E_AVE_DevTypebiii12_E_ChromaFmtbPiS1_S1_S1_E11_os_log_fmt_0
+ __ZZ28AVE_UCCmd_CheckParam_Prepare12_E_AVE_DevID17_E_AVE_ClientTypeP23S_AVE_UCInParam_PrepareE11_os_log_fmt_3
+ __ZZN7AVE_HwC15ProcessIntr_CmdEmijE11_os_log_fmt__19_
+ __ZZN7AVE_HwC15ProcessIntr_CmdEmijE11_os_log_fmt__20_
+ __ZZN9AVE_SVERC11UpdateStatsExixi14IMG_FRAME_TYPEiiiP25_S_AVE_DistributedRCStatsE11_os_log_fmt_3
+ _strnlen
Functions:
~ __ZN9AVE_FwLog5ResetEP11AVE_Surfacejj : 628 -> 636
~ __ZN9AVE_FwLog5PrintEjiPKci : 988 -> 1020
~ __ZN9AVE_FwLog10PrintEntryExx : 1612 -> 1680
~ __ZN9AVE_FwLog7ProcessEv : 1208 -> 1196
~ __Z22AVE_CalcBufSizeOfRecon14_E_AVE_DevType16_E_AVE_CodecTypeiiii12_E_ChromaFmtbPiS2_S2_S2_ : 1544 -> 1952
~ __Z27AVE_CalcBufSizeOfMCTFOutput14_E_AVE_DevTypebiii12_E_ChromaFmtbPiS1_S1_S1_ : 932 -> 1232
~ __Z25AVE_CHM_SetDataInfo_FrameP10_S_AVE_CHMP16_S_AVE_FrameInfoP18AVE_PICMGMT_PARAMS : 1472 -> 1692
~ __Z25AVE_Client_CheckFrameInfoP13_S_AVE_ClientP16_S_AVE_FrameInfo : 1396 -> 2136
~ __Z16AVE_Client_StartP13_S_AVE_ClientP14_S_AVE_TimeOutiP21_S_AVE_SurfaceIDInSetP35AVE_SessionSettings_UserKernel_DataPKc : 6544 -> 6552
~ __Z18AVE_Client_ProcessP13_S_AVE_ClientP14_S_AVE_TimeOuti : 2044 -> 2060
~ __Z16AVE_Client_ResetP13_S_AVE_ClientP14_S_AVE_TimeOuti : 1716 -> 1720
~ __ZN7AVE_HwC15ProcessIntr_CmdEmij : 6620 -> 7136
~ __Z19AVE_Pipeline_FindMDP15_S_AVE_Pipeliney : 60 -> 56
~ __ZN9AVE_SVERC11UpdateStatsExixi14IMG_FRAME_TYPEiiiP25_S_AVE_DistributedRCStats : 1376 -> 1520
~ __Z28AVE_UCCmd_CheckParam_Prepare12_E_AVE_DevID17_E_AVE_ClientTypeP23S_AVE_UCInParam_Prepare : 976 -> 1192
~ __Z26AVE_UCCmd_CheckParam_Start12_E_AVE_DevID17_E_AVE_ClientTypeP21S_AVE_UCInParam_Start : 976 -> 1192
CStrings:
+ "%lld %d AVE %s: %s DPB size overflow %d %d %d %d %lld %lld %lld %lld %lld"
+ "%lld %d AVE %s: %s DPB size overflow %d %d %d %d %lld %lld %lld %lld %lld\n"
+ "%lld %d AVE %s: %s MCTFOutput size overflow %d %d %d %lld %lld %lld %lld %lld"
+ "%lld %d AVE %s: %s MCTFOutput size overflow %d %d %d %lld %lld %lld %lld %lld\n"
+ "%lld %d AVE %s: %s:%d %s | client name not NUL-terminated %d %d %p %lld"
+ "%lld %d AVE %s: %s:%d %s | client name not NUL-terminated %d %d %p %lld\n"
+ "%lld %d AVE %s: %s:%d %s | frame number out of range %p %d %u (range: [0,%d])"
+ "%lld %d AVE %s: %s:%d %s | frame number out of range %p %d %u (range: [0,%d])\n"
+ "%lld %d AVE %s: %s:%d %s | invalid ANFD entry %d %p %d %d (%d %d %d %d %d)"
+ "%lld %d AVE %s: %s:%d %s | invalid ANFD entry %d %p %d %d (%d %d %d %d %d)\n"
+ "%lld %d AVE %s: %s:%d %s | layer ID out of range %p %d %u %u"
+ "%lld %d AVE %s: %s:%d %s | layer ID out of range %p %d %u %u\n"
+ "%lld %d AVE %s: %s:%d %s | non-contiguous frame number %p %d %p %u %lld"
+ "%lld %d AVE %s: %s:%d %s | non-contiguous frame number %p %d %p %u %lld\n"
+ "%lld %d AVE %s: %s::%s CBP0 flag size out of range %p %d | %u %u"
+ "%lld %d AVE %s: %s::%s CBP0 flag size out of range %p %d | %u %u\n"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %p"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %p\n"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %d %d"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %d %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %d %d"
+ "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %d %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | invalid slice index %p %d %d %d %p %d %d"
+ "%lld %d AVE %s: %s::%s:%d %s | invalid slice index %p %d %d %d %p %d %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | wrong process done size %p %d 0x%lx %d %ld"
+ "%lld %d AVE %s: %s::%s:%d %s | wrong process done size %p %d 0x%lx %d %ld\n"
+ "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %p %d | %d | %p %d"
+ "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %p %d | %d | %p %d\n"
+ "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %d | %d | %d-%d %d %d %d | %p %d %d"
+ "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %d | %d | %d-%d %d %d %d | %p %d %d\n"
+ "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %lld %d %d-%d %d"
+ "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %lld %d %d-%d %d\n"
+ "%lld %d AVE %s: FwLog %p %d | Phy %p Kernel %p DART %p | %d %d %d | %d %d"
+ "%lld %d AVE %s: FwLog %p %d | Phy %p Kernel %p DART %p | %d %d %d | %d %d\n"
+ "0 <= iSliceIdx && iSliceIdx < pClient->VideoParams.sSliceMap.iNum"
+ "20:15:29"
+ "21112"
+ "803.73.6"
+ "AVE_CalcBufSizeOfRecon"
+ "FwLog %p %d | Phy %p Kernel %p DART %p | %d %d %d | %d %d"
+ "FwLog %p %d | Phy %p Kernel %p DART %p | %d %d %d | %d %d\n"
+ "Nov 12 2026"
+ "pEntry->iBase > 0 && pEntry->sRect.iX >= 0 && pEntry->sRect.iY >= 0 && pEntry->sRect.iWidth >= 0 && pEntry->sRect.iHeight >= 0"
+ "pFrameData->FrameNumberFromDriver <= 2147483647"
+ "pFrameInfo->frameNumber == (uint32_t)(pClient->iLastFrameNumber + 1)"
+ "pFrameInfo->iLayerID < pClient->VideoParams.iLayerNum"
+ "size >= (int32_t)sizeof(sCAveCmdEncodeDone)"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %d %p"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find CHM %p %d %lld %d %d %p\n"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %d %d %d"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find MD %p %d %lld %d %d %d\n"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %d %d %d"
- "%lld %d AVE %s: %s::%s:%d %s | failed to find client %p %d %lld %d %d %d\n"
- "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %p %d | %d 0x%x | %p %d"
- "%lld %d AVE %s: %s::%s:%d command after client die %p %d %p %p %d | %d 0x%x | %p %d\n"
- "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %d | %d 0x%x | %d-%d %d %d %d | %p %d %d"
- "%lld %d AVE %s: %s::%s:%d discard frame command due to client die %p %d %p %p %d | %d 0x%x | %d-%d %d %d %d | %p %d %d\n"
- "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %d %lld %d %d-%d %d"
- "%lld %d AVE %s: %s::%s:%d receive firmware command %p %d %p %p %p %d %d %lld %d %d-%d %d\n"
- "%lld %d AVE %s: FwLog %p %d | Phy %p Kernel %p DART %p | %d %d %d"
- "%lld %d AVE %s: FwLog %p %d | Phy %p Kernel %p DART %p | %d %d %d\n"
- "00:58:53"
- "2111"
- "803.73.5"
- "FwLog %p %d | Phy %p Kernel %p DART %p | %d %d %d"
- "FwLog %p %d | Phy %p Kernel %p DART %p | %d %d %d\n"
- "Oct 12 2026"
```
