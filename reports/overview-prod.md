# Overview: prod
*Last updated: 2026-06-04 13:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T13:35 (1118 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,361 | avg: 10,974 | max: 84,644 | trend: decreasing (-17.95/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁
```

**Heap InUse** (current: 329.3MB | avg: 165.6MB | max: 2823.8MB | trend: stable (-0.24MB/hr))
```
▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,361 | 17,382 | +979 | 10,974 | 84,644 | decreasing (-17.95/hr) |
| Heap InUse | 329.3MB | 279.6MB | +49.7MB | 165.6MB | 2823.8MB | stable (-0.24MB/hr) |
| Heap Sys | 3408.0MB | 3408.7MB | -0.7MB | 2620.3MB | 6883.9MB | |
| Heap Objects | 1,461,260 | 1,219,234 | +242026 | 712,264 | 14,090,816 | |

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
| 2026-06-04 | 164 | 16,941 | 275.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 22.74MB |
| 3 | `bufio.NewReaderSize` | 13.55MB |
| 4 | `runtime.mallocgc` | 11.01MB |
| 5 | `bufio.NewWriterSize` | 10.54MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.05MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 9 | `compress/flate.NewWriter` | 3.53MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 10.06GB |
| 2 | `reflect.growslice` | 5.44GB |
| 3 | `jackskj/carta.getUniqueId` | 4.98GB |
| 4 | `fmt.Sprintf` | 4.44GB |
| 5 | `reflect.unsafe_New` | 4.36GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 4.0GB |
| 7 | `fmt.(*buffer).writeString` | 3.19GB |
| 8 | `carta/value.NewCell` | 3.12GB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.88GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.6GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 255.11MB | 247.92MB | 221.47MB | 0B |
| `evaluation.mergeMetadata` | 136.03MB | 133.03MB | 116.38MB | 0B |
| `local.(*Client).EvaluateV2` | 384.40MB | 374.05MB | 336.57MB | 0B |
| `local.topologicalSort` | 53.13MB | 52.62MB | 47.46MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 355.28MB | 343.42MB | 331.24MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 63.41MB | 63.41MB | 36.83MB | 0B |
| `localEvaluation.getMapOfValue` | 355.28MB | 343.42MB | 331.24MB | 0B |
| `utils.ParseFeatureFlag` | 355.28MB | 343.42MB | 331.52MB | 0B |

**Total FF alloc (current snapshot):** 1.91GB  |  **24h avg:** 1.71GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1118 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1118 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 769/1118 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1118 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.43MB | 769/1118 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1118 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.28MB | 556/1118 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1118 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1118 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.51MB | 355/1118 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1118 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1118 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1118 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1118 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1118 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.62GB | 742/1118 | `████░░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1118 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.97GB | 666/1118 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 12.86GB | 361/1118 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.45GB | 503/1118 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
