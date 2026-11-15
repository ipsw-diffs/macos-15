## AppleProResHWDecoder

> `/System/Library/Video/Plug-Ins/AppleProResHWDecoder.bundle/Contents/MacOS/AppleProResHWDecoder`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff

-477.0.0.0.0
-  __TEXT.__text: 0x21824
+475.11.0.0.0
+  __TEXT.__text: 0x21818
   __TEXT.__auth_stubs: 0xa30
   __TEXT.__const: 0x74120
   __TEXT.__gcc_except_tab: 0x454
   __TEXT.__cstring: 0x1100
-  __TEXT.__oslogstring: 0x3b8e
+  __TEXT.__oslogstring: 0x3b83
   __TEXT.__unwind_info: 0x400
   __DATA_CONST.__auth_got: 0x520
   __DATA_CONST.__got: 0x1e0
Functions:
~ sub_16524 : 484 -> 492
~ sub_16dfc -> sub_16e04 : 1192 -> 1172
CStrings:
+ "AppleProResHW (0x%x): %s(): Inconsistent subrame slices pSubFrameInfo->fr[%d].subFrameSize=%d subFrOffs=%d\n"
- "ERROR AppleProResHW (0x%x): %d: %s(): Inconsistent subrame slices pSubFrameInfo->fr[%d].subFrameSize=%d subFrOffs=%d\n\n"
```
