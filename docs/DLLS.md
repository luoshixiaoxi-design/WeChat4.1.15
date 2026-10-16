# DLL 导出与依赖

以下清单直接读取发布 DLL 的 PE 导出表和导入表。所有模块均为 x64。导出名称不是 HTTP API；传参需使用对应模块的二进制协议，不能把普通字符串作为请求结构传入。仅有 DLL 和导出名称不足以替代调用端。

## sender_session_v2_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-locale-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## image_session_v2_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-locale-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## video_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## voice_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## file_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## sticker_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## webcard_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## music_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## namecard_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## forward_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## favorite_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`, `api-ms-win-crt-utility-l1-1-0.dll`

## emoji_session_v1_41553.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## quote_session_service_v3.dll

导出：`QueueProbeRead`, `QueueProbeSnapshotThread`, `QueueProbeThread`, `SendSnapshotThread`, `ServiceSnapshotThread`, `TextProbeSnapshotThread`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-locale-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## recall_network_generation_v2.dll

导出：`NetworkSnapshotThread`, `QueueProbeThread`, `ResetNetworkThread`, `ResponseSnapshotThread`, `ServiceSnapshotThread`

依赖：`KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-locale-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## recall_local_generation_v2.dll

导出：`LocalObserveThread`, `QueueProbeThread`, `ResetLocalThread`, `ServiceSnapshotThread`

依赖：`KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-locale-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## receive_host_session_v2.dll

导出：`ReceiverBind`, `ReceiverCommand`, `ReceiverControlRead`, `ReceiverDisable`, `ReceiverEnable`, `ReceiverPause`, `ReceiverRead`, `ReceiverResume`, `ReceiverServiceRead`, `ReceiverSessionRead`, `ReceiverShutdown`, `ReceiverShutdownJoin`, `ReceiverStart`

依赖：`bcrypt.dll`, `KERNEL32.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`, `ntdll.dll`

## receive_payload_session_v2.dll

导出：`PayloadDispatch`

依赖：`KERNEL32.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## brief_contact_session_v2.dll

导出：`QuerySnapshotThread`, `QuerySubmitThread`

依赖：`KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`

## label_mutation_session_v2.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-locale-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`, `api-ms-win-crt-utility-l1-1-0.dll`

## label_sync_session_v2.dll

导出：`QueueProbeThread`, `ServiceSnapshotThread`

依赖：`KERNEL32.dll`, `api-ms-win-crt-convert-l1-1-0.dll`, `api-ms-win-crt-environment-l1-1-0.dll`, `api-ms-win-crt-heap-l1-1-0.dll`, `api-ms-win-crt-private-l1-1-0.dll`, `api-ms-win-crt-runtime-l1-1-0.dll`, `api-ms-win-crt-stdio-l1-1-0.dll`, `api-ms-win-crt-string-l1-1-0.dll`, `api-ms-win-crt-utility-l1-1-0.dll`
