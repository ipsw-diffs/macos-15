## syslogd

> `/usr/sbin/syslogd`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff

-402.0.0.0.0
-  __TEXT.__text: 0x12838
+402.0.0.700.1
+  __TEXT.__text: 0x1297c
   __TEXT.__auth_stubs: 0xeb0
-  __TEXT.__const: 0xc8
-  __TEXT.__cstring: 0x32cf
+  __TEXT.__const: 0xd8
+  __TEXT.__cstring: 0x33a9
   __TEXT.__unwind_info: 0x318
   __DATA_CONST.__auth_got: 0x758
   __DATA_CONST.__got: 0xc0

   - /usr/lib/libbsm.0.dylib
   Functions: 207
   Symbols:   262
-  CStrings:  554
+  CStrings:  556
 
Functions:
~ sub_100008bbc : 348 -> 672
CStrings:
+ "[Sender syslogd] [Level 3] [PID %u] [Facility syslog] [Message prepending uid %lu request for uid %lu]"
+ "[Sender syslogd] [Level 3] [PID %u] [Facility syslog] [Message prepending uid %lu's (gid %lu) request for gid %lu]"
```
