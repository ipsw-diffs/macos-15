## avbanalyse

> `/usr/bin/avbanalyse`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`

```diff

-1350.2.0.0.0
+1320.3.0.0.0
   __TEXT.__text: 0x18f70
   __TEXT.__auth_stubs: 0x210
   __TEXT.__objc_stubs: 0x2760
   __TEXT.__objc_methlist: 0x23f4
   __TEXT.__gcc_except_tab: 0x1098
   __TEXT.__objc_methname: 0x3f89
-  __TEXT.__cstring: 0x55ea
+  __TEXT.__cstring: 0x55b6
   __TEXT.__objc_classname: 0x6fe
   __TEXT.__objc_methtype: 0x320
   __TEXT.__const: 0x78
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbanalyse/PCAPAnalysis/AAAnalysePCAP.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/IOAVBFamily_executables/avbanalyse/Trace/AAAnalyseTrace.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbanalyse/PCAPAnalysis/AAAnalysePCAP.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/IOAVBFamily_executables/avbanalyse/Trace/AAAnalyseTrace.m"
```
