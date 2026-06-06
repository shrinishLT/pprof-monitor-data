# Overview: prod
*Last updated: 2026-06-06 10:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T10:05 (1651 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,436 | avg: 12,569 | max: 84,644 | trend: INCREASING (+2.18/hr))
```
▃▂█▄▁▁▂▁▁▁▇▄▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▃▂▁▁▁▁▁▁▂▃▃▁▁▁▁▁▁▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃
```

**Heap InUse** (current: 252.0MB | avg: 189.4MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▃▂█▆▃▂▂▃▁▂▆▅▃▂▃▁▂▂▃▂▁▁▁▂▂▁▂▁▁▄▄▁▁▁▁▂▃▂▄▅▁▂▁▁▁▁▂▃▂▂▂▂▃▁▁▂▃▁▁▁▁▂▁▂▂▁▁▁▃▁▂▂▁▂▁▁▁▁▂▁▂▁▂▂▂▁▁▁▁▁▂▂▂▁▂▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,436 | 15,708 | +1728 | 12,569 | 84,644 | INCREASING (+2.18/hr) |
| Heap InUse | 252.0MB | 207.8MB | +44.2MB | 189.4MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 1049.0MB | 1048.9MB | +0.1MB | 2433.1MB | 6883.9MB | |
| Heap Objects | 1,275,519 | 1,028,085 | +247434 | 837,917 | 17,165,538 | |

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
| 2026-06-06 | 122 | 15,655 | 225.9MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `bytes.growSlice` | 13.06MB |
| 4 | `reflect.growslice` | 12.46MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewWriterSize` | 9.04MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 8 | `bufio.NewReaderSize` | 6.02MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 10 | `reflect.unsafe_New` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 31.48GB |
| 2 | `fmt.Sprintf` | 31.34GB |
| 3 | `segmentio/kafka-go.makePartitions` | 30.96GB |
| 4 | `jackskj/carta.getUniqueId` | 29.19GB |
| 5 | `reflect.unsafe_New` | 25.42GB |
| 6 | `fmt.(*buffer).writeString` | 20.98GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 20.26GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 19.81GB |
| 9 | `carta/value.NewCell` | 17.98GB |
| 10 | `reflect.unsafe_NewArray` | 15.79GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.61GB | 1.61GB | 1.52GB | 0B |
| `evaluation.mergeMetadata` | 849.71MB | 847.71MB | 807.74MB | 0B |
| `local.(*Client).EvaluateV2` | 2.47GB | 2.46GB | 2.34GB | 0B |
| `local.topologicalSort` | 354.76MB | 354.25MB | 337.94MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.38GB | 2.38GB | 2.24GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 318.93MB | 318.93MB | 315.63MB | 0B |
| `localEvaluation.getMapOfValue` | 2.38GB | 2.38GB | 2.24GB | 0B |
| `utils.ParseFeatureFlag` | 2.39GB | 2.38GB | 2.25GB | 0B |

**Total FF alloc (current snapshot):** 12.72GB  |  **24h avg:** 12.03GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1651 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1651 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1651 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1302/1651 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1651 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.01MB | 1302/1651 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.59MB | 1020/1651 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1651 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1651 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1651 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1651 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1651 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1651 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1651 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1651 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1651 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1651 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1651 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 11.9GB | 835/1651 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 11.51GB | 362/1651 | `█░░░░░░░░░░░░░░ 9%` |

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
