# Overview: prod
*Last updated: 2026-06-04 13:19 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T13:19 (1114 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,442 | avg: 10,954 | max: 84,644 | trend: decreasing (-18.37/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁
```

**Heap InUse** (current: 325.9MB | avg: 165.2MB | max: 2823.8MB | trend: stable (-0.24MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,442 | 16,278 | +164 | 10,954 | 84,644 | decreasing (-18.37/hr) |
| Heap InUse | 325.9MB | 311.7MB | +14.2MB | 165.2MB | 2823.8MB | stable (-0.24MB/hr) |
| Heap Sys | 1204.6MB | 1203.9MB | +0.7MB | 2621.4MB | 6883.9MB | |
| Heap Objects | 1,836,348 | 1,626,838 | +209510 | 710,362 | 14,090,816 | |

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
| 2026-06-04 | 160 | 16,948 | 275.9MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 17.73MB |
| 3 | `reflect.growslice` | 11.44MB |
| 4 | `runtime.mallocgc` | 11.01MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 6.02MB |
| 7 | `reflect.unsafe_New` | 5.5MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 4.88GB |
| 2 | `jackskj/carta.getUniqueId` | 4.53GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 4.12GB |
| 4 | `fmt.Sprintf` | 3.93GB |
| 5 | `reflect.unsafe_New` | 3.91GB |
| 6 | `fmt.(*buffer).writeString` | 2.87GB |
| 7 | `carta/value.NewCell` | 2.82GB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 2.3GB |
| 10 | `fmt.Sprint` | 1.89GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 221.95MB | 210.73MB | 221.01MB | 0B |
| `evaluation.mergeMetadata` | 119.53MB | 114.03MB | 115.54MB | 0B |
| `local.(*Client).EvaluateV2` | 330.99MB | 310.52MB | 336.55MB | 0B |
| `local.topologicalSort` | 45.51MB | 41.97MB | 47.55MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 308.60MB | 288.12MB | 333.60MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 52.10MB | 50.56MB | 34.69MB | 0B |
| `localEvaluation.getMapOfValue` | 308.60MB | 288.12MB | 333.60MB | 0B |
| `utils.ParseFeatureFlag` | 308.60MB | 288.12MB | 333.92MB | 0B |

**Total FF alloc (current snapshot):** 1.66GB  |  **24h avg:** 1.72GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1114 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1114 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 765/1114 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1114 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.48MB | 765/1114 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1114 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.28MB | 552/1114 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1114 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1114 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.56MB | 351/1114 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1114 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1114 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1114 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1114 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1114 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.81GB | 738/1114 | `█████░░░░░░░░░░ 33%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1114 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.01GB | 664/1114 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 12.95GB | 357/1114 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.52GB | 499/1114 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
