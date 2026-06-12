# Overview: prod
*Last updated: 2026-06-12 09:32 IST*
*Data range: 2026-05-15T16:03 to 2026-06-12T09:31 (3371 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,184 | avg: 14,345 | max: 84,644 | trend: INCREASING (+3.39/hr))
```
▂▁▁▁▂▂▂▂▁▁▁▁▂▂▂▁▁▁▁▁▁▅▂▁▂▂▂▂▂▂▂▁▁▂▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▂▄▂▁▁▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▃█▁▁▁▁▁▁▁▁▁▁▁▃▅
```

**Heap InUse** (current: 338.2MB | avg: 237.5MB | max: 3154.1MB | trend: stable (+0.10MB/hr))
```
▃▂▃▁▁▂▂▃▁▃▁▁▁▃▃▁▃▂▁▂▂▄▂▃▂▂▂▄▂▁▄▂▁▃▃▂▁▂▂▃▂▃▂▂▃▂▁▂▁▁▃▃▂▂▁▂▃▃▄▄▂▂▃▁▂▃▂▁▃▂▁▃▁▂▄▂▁▁▁▃▁▄█▃▂▃▁▃▂▃▃▃▂▂▃▄
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,184 | 16,125 | +2059 | 14,345 | 84,644 | INCREASING (+3.39/hr) |
| Heap InUse | 338.2MB | 284.6MB | +53.6MB | 237.5MB | 3154.1MB | stable (+0.10MB/hr) |
| Heap Sys | 3331.4MB | 3331.8MB | -0.4MB | 2681.7MB | 6883.9MB | |
| Heap Objects | 864,320 | 752,939 | +111381 | 1,019,610 | 17,165,538 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 288 | 16,555 | 265.7MB | 2823.8MB |
| 2026-06-05 | 287 | 15,969 | 239.1MB | 3154.1MB |
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 115 | 14,893 | 263.2MB | 490.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 26.65MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 14.07MB |
| 5 | `bufio.NewWriterSize` | 11.07MB |
| 6 | `bufio.NewReaderSize` | 10.57MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 6.51MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 195.22GB |
| 2 | `segmentio/kafka-go.makePartitions` | 192.47GB |
| 3 | `jackskj/carta.getUniqueId` | 176.31GB |
| 4 | `reflect.unsafe_New` | 155.63GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 152.51GB |
| 6 | `fmt.Sprintf` | 141.85GB |
| 7 | `fmt.(*buffer).writeString` | 121.96GB |
| 8 | `carta/value.NewCell` | 111.26GB |
| 9 | `reflect.unsafe_NewArray` | 98.17GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 87.53GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 10.55GB | 10.54GB | 10.43GB | 0B |
| `evaluation.mergeMetadata` | 5.51GB | 5.50GB | 5.44GB | 0B |
| `local.(*Client).EvaluateV2` | 16.07GB | 16.05GB | 15.89GB | 0B |
| `local.topologicalSort` | 2.24GB | 2.23GB | 2.21GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 15.36GB | 15.35GB | 15.18GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.19GB | 2.19GB | 2.18GB | 0B |
| `localEvaluation.getMapOfValue` | 15.36GB | 15.35GB | 15.18GB | 0B |
| `utils.ParseFeatureFlag` | 15.39GB | 15.37GB | 15.20GB | 0B |

**Total FF alloc (current snapshot):** 82.66GB  |  **24h avg:** 81.70GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.78MB | 65/3371 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 48.07MB | 92/3371 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3022/3371 | `██████████░░░░░ 66%` |
| 4 | `runtime.mallocgc` | 32.53MB | 3022/3371 | `████████░░░░░░░ 59%` |
| 5 | `database/sql.convertAssignRows` | 25.59MB | 114/3371 | `███████░░░░░░░░ 46%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3371 | `████░░░░░░░░░░░ 32%` |
| 7 | `bytes.growSlice` | 15.41MB | 2373/3371 | `████░░░░░░░░░░░ 28%` |
| 8 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3371 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*Transport).dialConn` | 13.81MB | 75/3371 | `███░░░░░░░░░░░░ 25%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3371 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3371 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3371 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3371 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 71.93GB | 1888/3371 | `████████░░░░░░░ 57%` |
| 5 | `reflect.growslice` | 63.98GB | 2583/3371 | `███████░░░░░░░░ 51%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.23GB | 2745/3371 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.64GB | 2599/3371 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 54.73GB | 2363/3371 | `██████░░░░░░░░░ 43%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/3371 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 48.61GB | 2110/3371 | `█████░░░░░░░░░░ 38%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
