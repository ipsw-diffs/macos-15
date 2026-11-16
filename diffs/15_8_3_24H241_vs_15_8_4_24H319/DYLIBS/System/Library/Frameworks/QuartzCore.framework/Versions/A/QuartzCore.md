## QuartzCore

> `/System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1156.18.3.0.0
-  __TEXT.__text: 0x345200
+1156.18.5.0.0
+  __TEXT.__text: 0x345220
   __TEXT.__auth_stubs: 0x5230
   __TEXT.__objc_methlist: 0xa944
   __TEXT.__const: 0x14184
Symbols:
+ __ZN12_GLOBAL__N_118retain_slot_bufferEjRj
- __ZN12_GLOBAL__N_118retain_slot_bufferEj
Functions:
~ _CASCaptureDisplayLayer : 428 -> 440
~ __ZN12_GLOBAL__N_118retain_slot_bufferEj -> __ZN12_GLOBAL__N_118retain_slot_bufferEjRj : 660 -> 672
~ _CASCaptureDisplayContextList : 476 -> 484
CStrings:
+ "24H315"
- "24H225"
```
