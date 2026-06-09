# Overview: prod
*Last updated: 2026-06-10 00:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T00:40 (2690 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,218 | avg: 13,880 | max: 84,644 | trend: INCREASING (+4.13/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▂▁▁▁▂▂▃▁▂▆▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▃▄▃▂▁▁▇▃▁▅▃▂▁▅▄▁▃▂▁█▅▁▂▂▂▁▁▁▁▄▁▁▁▁▁▁▁
```

**Heap InUse** (current: 247.8MB | avg: 221.0MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▂▁▁▁▂▂▂▂▂▂▁▂▁▁▁▂▁▁▂▁▂▂▂▁▂▃▃▂▃▂▃▂▃▂▂▁▂▂▃▃▄▃▃▇▃▂▁▁▁▁▁▁▂▂▁▁▁▁▁▃▄▄▂▂▂▇▃▁▅▄▂▁▆▅▁▃▄▁█▅▁▁▂▃▁▁▁▁▄▂▁▁▂▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,218 | 14,711 | -493 | 13,880 | 84,644 | INCREASING (+4.13/hr) |
| Heap InUse | 247.8MB | 217.3MB | +30.5MB | 221.0MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3330.4MB | 3330.4MB | +0.0MB | 2518.0MB | 6883.9MB | |
| Heap Objects | 1,446,173 | 480,934 | +965239 | 964,419 | 17,165,538 | |

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
| 2026-06-10 | 9 | 14,921 | 258.9MB | 390.3MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 6.09MB |
| 6 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 114.06GB |
| 2 | `reflect.growslice` | 105.17GB |
| 3 | `jackskj/carta.getUniqueId` | 94.15GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 90.26GB |
| 5 | `reflect.unsafe_New` | 83.39GB |
| 6 | `fmt.Sprintf` | 76.45GB |
| 7 | `fmt.(*buffer).writeString` | 67.46GB |
| 8 | `carta/value.NewCell` | 59.47GB |
| 9 | `reflect.unsafe_NewArray` | 58.28GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 47.17GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 5.69GB | 5.69GB | 5.54GB | 0B |
| `evaluation.mergeMetadata` | 3.00GB | 2.99GB | 2.91GB | 0B |
| `local.(*Client).EvaluateV2` | 8.69GB | 8.68GB | 8.46GB | 0B |
| `local.topologicalSort` | 1.21GB | 1.21GB | 1.18GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 8.28GB | 8.27GB | 8.05GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.22GB | 1.21GB | 1.18GB | 0B |
| `localEvaluation.getMapOfValue` | 8.28GB | 8.27GB | 8.05GB | 0B |
| `utils.ParseFeatureFlag` | 8.29GB | 8.28GB | 8.06GB | 0B |

**Total FF alloc (current snapshot):** 44.65GB  |  **24h avg:** 43.42GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 79.04MB | 43/2690 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 59.71MB | 72/2690 | `███████████░░░░ 75%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2341/2690 | `██████░░░░░░░░░ 46%` |
| 4 | `database/sql.convertAssignRows` | 29.99MB | 94/2690 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 27.31MB | 2341/2690 | `█████░░░░░░░░░░ 34%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2690 | `███░░░░░░░░░░░░ 22%` |
| 7 | `bytes.growSlice` | 15.33MB | 1783/2690 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `net/http.(*Transport).dialConn` | 14.48MB | 53/2690 | `██░░░░░░░░░░░░░ 18%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2690 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2690 | `██░░░░░░░░░░░░░ 13%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2690 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2690 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2690 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2690 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2690 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 42.46GB | 1207/2690 | `█████░░░░░░░░░░ 33%` |
| 7 | `segmentio/kafka-go.makePartitions` | 33.52GB | 2064/2690 | `████░░░░░░░░░░░ 26%` |
| 8 | `reflect.growslice` | 31.97GB | 1902/2690 | `███░░░░░░░░░░░░ 25%` |
| 9 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2690 | `███░░░░░░░░░░░░ 22%` |
| 10 | `jackskj/carta.getUniqueId` | 27.67GB | 1918/2690 | `███░░░░░░░░░░░░ 22%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.6x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
