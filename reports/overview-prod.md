# Overview: prod
*Last updated: 2026-06-11 02:11 IST*
*Data range: 2026-05-15T16:03 to 2026-06-11T02:10 (2995 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,127 | avg: 14,132 | max: 84,644 | trend: INCREASING (+3.88/hr))
```
▂▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▂▂▂▂▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▅█▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 266.2MB | avg: 229.5MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▃▂▃▃▂▂▁▂▂▃▃▂▃▃▂▁▂▃▂▃▂▁▄▂▂▃▃▃▄▃▁▁▂▄▂▃▂▄▃▂▁▁▁▁▂▃▂▁▁▂▃▂▁▁▂▃▃▂▁▁▅█▆▂▃▂▃▁▂▂▂▂▁▂▁▁▂▂▂▂▂▃▂▂▂▂▂▂▁▁▁▁▃▃▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,127 | 15,011 | +116 | 14,132 | 84,644 | INCREASING (+3.88/hr) |
| Heap InUse | 266.2MB | 317.8MB | -51.6MB | 229.5MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3335.3MB | 3333.8MB | +1.5MB | 2600.4MB | 6883.9MB | |
| Heap Objects | 1,011,641 | 1,418,380 | -406739 | 991,473 | 17,165,538 | |

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
| 2026-06-11 | 27 | 14,886 | 269.7MB | 317.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 9.55MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 6.04MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 8 | `bufio.NewReaderSize` | 4.04MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 149.16GB |
| 2 | `reflect.growslice` | 141.92GB |
| 3 | `jackskj/carta.getUniqueId` | 128.08GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 114.38GB |
| 5 | `reflect.unsafe_New` | 113.21GB |
| 6 | `fmt.Sprintf` | 103.05GB |
| 7 | `fmt.(*buffer).writeString` | 88.83GB |
| 8 | `carta/value.NewCell` | 80.95GB |
| 9 | `reflect.unsafe_NewArray` | 76.21GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 62.05GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.86GB | 7.85GB | 7.71GB | 0B |
| `evaluation.mergeMetadata` | 4.11GB | 4.11GB | 4.04GB | 0B |
| `local.(*Client).EvaluateV2` | 11.99GB | 11.98GB | 11.75GB | 0B |
| `local.topologicalSort` | 1.66GB | 1.66GB | 1.63GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 11.41GB | 11.39GB | 11.17GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.67GB | 1.67GB | 1.65GB | 0B |
| `localEvaluation.getMapOfValue` | 11.41GB | 11.39GB | 11.17GB | 0B |
| `utils.ParseFeatureFlag` | 11.42GB | 11.41GB | 11.19GB | 0B |

**Total FF alloc (current snapshot):** 61.52GB  |  **24h avg:** 60.31GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 62.39MB | 56/2995 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 52.73MB | 83/2995 | `████████████░░░ 84%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2646/2995 | `████████░░░░░░░ 58%` |
| 4 | `runtime.mallocgc` | 29.98MB | 2646/2995 | `███████░░░░░░░░ 48%` |
| 5 | `database/sql.convertAssignRows` | 27.44MB | 105/2995 | `██████░░░░░░░░░ 43%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2995 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.47MB | 2049/2995 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2995 | `███░░░░░░░░░░░░ 23%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2995 | `███░░░░░░░░░░░░ 22%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2995 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2995 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2995 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2995 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 55.26GB | 1512/2995 | `██████░░░░░░░░░ 44%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2995 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 46.15GB | 2369/2995 | `█████░░░░░░░░░░ 36%` |
| 7 | `reflect.growslice` | 45.33GB | 2207/2995 | `█████░░░░░░░░░░ 36%` |
| 8 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2995 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 39.65GB | 2223/2995 | `████░░░░░░░░░░░ 31%` |
| 10 | `reflect.unsafe_New` | 38.87GB | 1987/2995 | `████░░░░░░░░░░░ 31%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.2x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.4x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.4x avg)
