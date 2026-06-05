# Overview: prod
*Last updated: 2026-06-05 20:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T20:21 (1487 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,150 | avg: 12,240 | max: 84,644 | trend: stable (+0.06/hr))
```
▁▁▁▃▃▃▂▂▄▃▃▃▂▂▂▂▂▂▃▂▂▁▂▂▁▂▂▂▂▃▃▃▂▂▁▂▁▁▂▁▂▂▁▂▆▅▅▄▆█▂▂▁▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▂▁▁▁▁▁▂▃▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂
```

**Heap InUse** (current: 174.8MB | avg: 185.8MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▃▁▂▃▅▅▃▃▆▅▄▄▄▃▃▄▄▅▄▄▄▂▂▄▁▂▄▅▃▅▃▃▃▄▁▄▂▃▁▂▃▃▁▂▆▇▇▅▇█▇▆▂▄▂▂▂▁▂▂▃▂▂▃▁▁▁▃▄▃▂▃▂▂▂▁▃▃▄▂▂▁▂▁▂▃▂▂▃▃▃▅▆▂▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,150 | 15,561 | -411 | 12,240 | 84,644 | stable (+0.06/hr) |
| Heap InUse | 174.8MB | 192.0MB | -17.2MB | 185.8MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1047.5MB | 1047.4MB | +0.1MB | 2586.9MB | 6883.9MB | |
| Heap Objects | 613,289 | 495,191 | +118098 | 825,451 | 17,165,538 | |

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
| 2026-06-05 | 245 | 16,092 | 244.4MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 12.82MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 4.53MB |
| 7 | `bufio.NewWriterSize` | 4.03MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 12.16GB |
| 2 | `fmt.Sprintf` | 10.53GB |
| 3 | `jackskj/carta.getUniqueId` | 9.72GB |
| 4 | `reflect.growslice` | 9.54GB |
| 5 | `reflect.unsafe_New` | 8.08GB |
| 6 | `fmt.(*buffer).writeString` | 6.45GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.37GB |
| 8 | `reflect.unsafe_NewArray` | 6.28GB |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 6.23GB |
| 10 | `carta/value.NewCell` | 5.76GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 875.35MB | 863.81MB | 683.75MB | 0B |
| `evaluation.mergeMetadata` | 450.61MB | 443.11MB | 350.38MB | 0B |
| `local.(*Client).EvaluateV2` | 1.32GB | 1.30GB | 1.04GB | 0B |
| `local.topologicalSort` | 191.70MB | 188.66MB | 150.88MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.23GB | 1.22GB | 1000.41MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 209.38MB | 207.38MB | 159.09MB | 0B |
| `localEvaluation.getMapOfValue` | 1.23GB | 1.22GB | 1000.41MB | 0B |
| `utils.ParseFeatureFlag` | 1.24GB | 1.22GB | 1002.68MB | 0B |

**Total FF alloc (current snapshot):** 6.71GB  |  **24h avg:** 5.28GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1487 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1487 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1487 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1138/1487 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1487 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.41MB | 1138/1487 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.84MB | 891/1487 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1487 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprint` | 11.68MB | 4/1487 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1487 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1487 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1487 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1487 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1487 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1487 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1487 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1487 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1487 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.49GB | 203/1487 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 8.78GB | 671/1487 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.9x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.6x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
