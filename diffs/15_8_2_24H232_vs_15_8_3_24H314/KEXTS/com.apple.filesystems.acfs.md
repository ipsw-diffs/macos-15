## com.apple.filesystems.acfs

> `com.apple.filesystems.acfs`

```diff

-782.140.2.0.0
-  __TEXT.__cstring: 0x37212
-  __TEXT.__const: 0x36a0
-  __TEXT_EXEC.__text: 0xd7ea8
+782.140.2.700.5
+  __TEXT.__cstring: 0x37b11
+  __TEXT.__const: 0x36d2
+  __TEXT_EXEC.__text: 0xd8330
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x12498
   __DATA.__common: 0x613c
   __DATA.__bss: 0x10934
-  __DATA_CONST.__auth_got: 0x820
+  __DATA_CONST.__auth_got: 0x828
   __DATA_CONST.__got: 0x40
   __DATA_CONST.__const: 0x290
   __DATA_CONST.__kalloc_type: 0x2c0
-  Functions: 3882
-  Symbols:   2237
-  CStrings:  5146
+  Functions: 3885
+  Symbols:   2239
+  CStrings:  5156
 
Symbols:
+ _get_msgbuf_alloclen
+ _memchr
Functions:
~ _dmig_path_to_handle : 1384 -> 1392
~ _FsmDataToken : 1600 -> 1632
~ _FsmGetExtentList : 520 -> 564
~ _FsmStatVfs : 1164 -> 1264
~ _FsmLookup : 692 -> 872
~ _FsmGetFullPath : 628 -> 716
~ _FsmGetNTSecurityDescriptor : 324 -> 412
~ _FsmSetNTSecurityDescriptor : 340 -> 424
+ _get_msgbuf_alloclen
~ _snbt_scan : 1436 -> 1568
~ _ReadDirBlk3 : 2148 -> 2160
~ _LookupCvp : 1692 -> 1696
~ _cvrtqos_freeBucket : 456 -> 460
~ _cvrtqos_stopProcessing : 284 -> 288
~ _cvRtQos_createBucketFromReply : 636 -> 668
~ _xsanfs_getsecurity : 3180 -> 3344
+ _FsmDataToken.cold.3
~ _FsmGetExtentList.cold.3 : 76 -> 84
+ _FsmGetExtentList.cold.4
~ _CvShRename : 4060 -> 4064
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/dmiglib/dmig_attributes.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/dmiglib/dmig_events.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/dmiglib/dmig_handles.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/dmiglib/dmig_io.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/dmiglib/dmig_session.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/dmiglib/dmigfs.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/misclib/dmon.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/misclib/lock.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/misclib/memalloc.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/misclib/nomad/md_dmon.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/misclib/nomad/md_memalloc.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/misclib/slidingbucket.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/misclib/utf8.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/cvportmap.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/cvproxy_clnt.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/cvproxy_con.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/cvproxy_srv.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/cvproxy_subr.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/fsm_brlops.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/fsm_proxy.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/fsm_rtqos.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/fsm_token.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/fsm_vfsops.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/fsm_vnops.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/fsmcom.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/nomad/md_cvproxy.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/nomad/md_cvsock.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/nomad/md_fsmcom.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/recon.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/sockinput.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/net/socksubr.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/clntrtqos.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/cvdir.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/cvdisk.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/cvnc.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/cvpath.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/cvsock.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/cvsubr.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/debuglog.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/extapi.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/extent.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/iodesc.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/md_acl.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/md_cvdir.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/md_debuglog.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/md_rw.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/md_rwbuf.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/md_rwproxy.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/md_subr.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/md_vfsops.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/md_vnops.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/xsanfs_bulkaccess.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/nomad/xsanfs_spotproxy.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/quotas.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/rtio.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/rw.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/rwproxy.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/shared/sh_vnops.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/vfsops.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/vnops.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/client/vfs/xattr.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/darwinSupport/include/../../qustat/libqustat/libqustat.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/include/common/list.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/include/common/rbtree.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/XsanFS/snfs/include/common/splay.c"
+ "FsmDataToken: rejecting malformed extent count %d cookie 0x%llx"
+ "FsmGetExtentList: rejecting malformed extent count %d cookie 0x%llx"
+ "FsmGetFullPath: path truncated to fit target buffer"
+ "FsmGetNTSecurityDescriptor: bad nt_sd_key 0x%llx, rejecting"
+ "FsmLookup: rejecting malformed VopLkUpNmOffset 0x%x (maxNmOffset %u)"
+ "FsmLookup: server name truncated to fit %u byte buffer"
+ "FsmSetNTSecurityDescriptor: bad nt_sd_key 0x%llx, rejecting"
+ "FsmStatVfs: rejecting malformed domain sid off %d len %d"
+ "snbt_scan bad entry idx/%d offs/%d len/%d, rejecting block"
+ "xsanfs_getsecurity: cvp %p nt_sd_key 0x%llx bad SD length, rejecting"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/dmiglib/dmig_attributes.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/dmiglib/dmig_events.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/dmiglib/dmig_handles.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/dmiglib/dmig_io.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/dmiglib/dmig_session.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/dmiglib/dmigfs.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/misclib/dmon.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/misclib/lock.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/misclib/memalloc.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/misclib/nomad/md_dmon.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/misclib/nomad/md_memalloc.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/misclib/slidingbucket.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/misclib/utf8.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/cvportmap.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/cvproxy_clnt.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/cvproxy_con.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/cvproxy_srv.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/cvproxy_subr.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/fsm_brlops.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/fsm_proxy.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/fsm_rtqos.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/fsm_token.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/fsm_vfsops.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/fsm_vnops.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/fsmcom.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/nomad/md_cvproxy.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/nomad/md_cvsock.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/nomad/md_fsmcom.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/recon.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/sockinput.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/net/socksubr.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/clntrtqos.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/cvdir.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/cvdisk.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/cvnc.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/cvpath.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/cvsock.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/cvsubr.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/debuglog.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/extapi.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/extent.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/iodesc.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/md_acl.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/md_cvdir.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/md_debuglog.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/md_rw.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/md_rwbuf.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/md_rwproxy.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/md_subr.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/md_vfsops.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/md_vnops.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/xsanfs_bulkaccess.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/nomad/xsanfs_spotproxy.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/quotas.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/rtio.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/rw.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/rwproxy.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/shared/sh_vnops.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/vfsops.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/vnops.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/client/vfs/xattr.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/darwinSupport/include/../../qustat/libqustat/libqustat.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/include/common/list.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/include/common/rbtree.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/XsanFS/snfs/include/common/splay.c"
```
