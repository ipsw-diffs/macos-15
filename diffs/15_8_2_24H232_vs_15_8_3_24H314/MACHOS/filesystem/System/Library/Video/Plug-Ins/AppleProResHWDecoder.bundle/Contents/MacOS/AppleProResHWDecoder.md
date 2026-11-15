## AppleProResHWDecoder

> `/System/Library/Video/Plug-Ins/AppleProResHWDecoder.bundle/Contents/MacOS/AppleProResHWDecoder`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff

-475.11.0.0.0
-  __TEXT.__text: 0x21818
+477.0.0.0.0
+  __TEXT.__text: 0x21824
   __TEXT.__auth_stubs: 0xa30
   __TEXT.__const: 0x74120
   __TEXT.__gcc_except_tab: 0x454
   __TEXT.__cstring: 0x1100
-  __TEXT.__oslogstring: 0x3b83
+  __TEXT.__oslogstring: 0x3b8e
   __TEXT.__unwind_info: 0x400
   __DATA_CONST.__auth_got: 0x520
   __DATA_CONST.__got: 0x1e0
Functions:
~ sub_16524 : 492 -> 484
~ sub_16e04 -> sub_16dfc : 1172 -> 1192
CStrings:
+ "ERROR AppleProResHW (0x%x): %d: %s(): Inconsistent subrame slices pSubFrameInfo->fr[%d].subFrameSize=%d subFrOffs=%d\n\n"
- "AppleProResHW (0x%x): %s(): Inconsistent subrame slices pSubFrameInfo->fr[%d].subFrameSize=%d subFrOffs=%d\n"
```
