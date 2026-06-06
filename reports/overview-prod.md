# Overview: prod
*Last updated: 2026-06-06 10:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T10:10 (1652 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 28,409 | avg: 12,579 | max: 84,644 | trend: INCREASING (+2.24/hr))
```
▁▅▂▁▁▁▁▁▁▅▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂█
```

**Heap InUse** (current: 478.7MB | avg: 189.5MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▂█▆▃▂▂▃▁▂▆▅▃▂▃▁▂▂▃▂▁▁▁▂▂▁▂▁▁▄▄▁▁▁▁▂▃▂▄▅▁▂▁▁▁▁▂▃▂▂▂▂▃▁▁▂▃▁▁▁▁▂▁▂▂▁▁▁▃▁▂▂▁▂▁▁▁▁▂▁▂▁▂▂▂▁▁▁▁▁▂▂▂▁▂▃▇
```

## Current Status

Goroutines: `██████░░░░░░░░░░░░░░ 33%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 28,409 | 17,436 | +10973 | 12,579 | 84,644 | INCREASING (+2.24/hr) |
| Heap InUse | 478.7MB | 252.0MB | +226.7MB | 189.5MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 1008.5MB | 1049.0MB | -40.5MB | 2432.2MB | 6883.9MB | |
| Heap Objects | 2,059,540 | 1,275,519 | +784021 | 838,656 | 17,165,538 | |

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
| 2026-06-06 | 123 | 15,759 | 227.9MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 71.88MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 41.69MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `bufio.NewWriterSize` | 30.62MB |
| 5 | `bufio.NewReaderSize` | 29.62MB |
| 6 | `runtime.mallocgc` | 15.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 15.51MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 10 | `crypto/tls.Client` | 6.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 32.55GB |
| 2 | `fmt.Sprintf` | 31.47GB |
| 3 | `segmentio/kafka-go.makePartitions` | 31.09GB |
| 4 | `jackskj/carta.getUniqueId` | 30.11GB |
| 5 | `reflect.unsafe_New` | 26.27GB |
| 6 | `fmt.(*buffer).writeString` | 21.61GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 20.63GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 19.91GB |
| 9 | `carta/value.NewCell` | 18.59GB |
| 10 | `reflect.unsafe_NewArray` | 15.86GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.61GB | 1.61GB | 1.53GB | 0B |
| `evaluation.mergeMetadata` | 851.21MB | 849.71MB | 809.73MB | 0B |
| `local.(*Client).EvaluateV2` | 2.47GB | 2.47GB | 2.34GB | 0B |
| `local.topologicalSort` | 354.76MB | 354.76MB | 338.70MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.39GB | 2.38GB | 2.25GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 318.93MB | 318.93MB | 315.87MB | 0B |
| `localEvaluation.getMapOfValue` | 2.39GB | 2.38GB | 2.25GB | 0B |
| `utils.ParseFeatureFlag` | 2.39GB | 2.39GB | 2.26GB | 0B |

**Total FF alloc (current snapshot):** 12.74GB  |  **24h avg:** 12.06GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1652 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1652 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1652 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1303/1652 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1652 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.01MB | 1303/1652 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.65MB | 1021/1652 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1652 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1652 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1652 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1652 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1652 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1652 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1652 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1652 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1652 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1652 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1652 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 11.92GB | 836/1652 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 11.54GB | 363/1652 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
