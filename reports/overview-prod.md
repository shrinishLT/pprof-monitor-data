# Overview: prod
*Last updated: 2026-06-11 19:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T19:05 (3198 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,250 | avg: 14,273 | max: 84,644 | trend: INCREASING (+3.68/hr))
```
▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▃▃▃▂▁▁▁▁▁▂▁▂▂▂▂▂▃▂▁▁▁▂▁▁▁▁▁▁▁▁▁▃▁▂▂▂▂▂▂▂▁▁▁▁▁▄▂▂▁▁▁▁▂▂▃▂▂▃▄▄▄▂▃▃▂▁▁▂▅▇▆▅▄█▂▃
```

**Heap InUse** (current: 359.6MB | avg: 234.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▁▂▄▁▂▁▁▁▁▂▂▃▂▃▂▁▁▃▅▃▃▂▄▂▃▁▂▂▄▃▂▃▂▃▂▃▄▃▂▁▄▁▂▃▂▃▁▁▃▁▃▁▄▂▃▂▂▄▂▃▂▁▁▁▆▃▂▂▂▁▂▂▂▄▃▂▄▄▄▄▄▂▃▃▁▂▃▄█▆▆▅▇▃▄
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,250 | 15,233 | +1017 | 14,273 | 84,644 | INCREASING (+3.68/hr) |
| Heap InUse | 359.6MB | 300.4MB | +59.2MB | 234.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3330.2MB | 3330.7MB | -0.5MB | 2646.7MB | 6883.9MB | |
| Heap Objects | 1,575,262 | 1,289,584 | +285678 | 1,010,486 | 17,165,538 | |

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
| 2026-06-11 | 230 | 16,177 | 306.5MB | 1403.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 32.92MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 7.04MB |
| 7 | `bufio.NewReaderSize` | 6.04MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 9 | `http2/hpack.(*headerFieldTable).addEntry` | 3.5MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 178.13GB |
| 2 | `segmentio/kafka-go.makePartitions` | 172.56GB |
| 3 | `jackskj/carta.getUniqueId` | 161.51GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 142.85GB |
| 5 | `reflect.unsafe_New` | 142.31GB |
| 6 | `fmt.Sprintf` | 127.78GB |
| 7 | `fmt.(*buffer).writeString` | 112.09GB |
| 8 | `carta/value.NewCell` | 101.67GB |
| 9 | `reflect.unsafe_NewArray` | 88.04GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 81.61GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 9.44GB | 9.43GB | 9.19GB | 0B |
| `evaluation.mergeMetadata` | 4.93GB | 4.93GB | 4.80GB | 0B |
| `local.(*Client).EvaluateV2` | 14.38GB | 14.36GB | 13.99GB | 0B |
| `local.topologicalSort` | 1.99GB | 1.99GB | 1.94GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 13.72GB | 13.71GB | 13.37GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.98GB | 1.98GB | 1.91GB | 0B |
| `localEvaluation.getMapOfValue` | 13.72GB | 13.71GB | 13.37GB | 0B |
| `utils.ParseFeatureFlag` | 13.74GB | 13.73GB | 13.39GB | 0B |

**Total FF alloc (current snapshot):** 73.91GB  |  **24h avg:** 71.95GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 59.59MB | 59/3198 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.56MB | 87/3198 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2849/3198 | `█████████░░░░░░ 61%` |
| 4 | `runtime.mallocgc` | 31.44MB | 2849/3198 | `███████░░░░░░░░ 52%` |
| 5 | `database/sql.convertAssignRows` | 27.21MB | 106/3198 | `██████░░░░░░░░░ 45%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3198 | `████░░░░░░░░░░░ 30%` |
| 7 | `bytes.growSlice` | 15.6MB | 2224/3198 | `███░░░░░░░░░░░░ 26%` |
| 8 | `net/http.(*Transport).dialConn` | 14.43MB | 69/3198 | `███░░░░░░░░░░░░ 24%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/3198 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3198 | `██░░░░░░░░░░░░░ 17%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3198 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3198 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3198 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 64.48GB | 1715/3198 | `███████░░░░░░░░ 51%` |
| 5 | `reflect.growslice` | 55.42GB | 2410/3198 | `██████░░░░░░░░░ 44%` |
| 6 | `segmentio/kafka-go.makePartitions` | 55.21GB | 2572/3198 | `██████░░░░░░░░░ 44%` |
| 7 | `experiment/local.topologicalSort` | 51.23GB | 375/3198 | `██████░░░░░░░░░ 40%` |
| 8 | `jackskj/carta.getUniqueId` | 48.81GB | 2426/3198 | `█████░░░░░░░░░░ 39%` |
| 9 | `reflect.unsafe_New` | 47.46GB | 2190/3198 | `█████░░░░░░░░░░ 37%` |
| 10 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/3198 | `█████░░░░░░░░░░ 34%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.8x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
