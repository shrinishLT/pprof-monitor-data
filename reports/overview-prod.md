# Overview: prod
*Last updated: 2026-06-07 01:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T01:20 (1834 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,746 | avg: 12,892 | max: 84,644 | trend: INCREASING (+3.39/hr))
```
▃▄▄▂▃▃▁▁▇▄▃▇▂▁▂▂▂▂▂▂▇▃▁▂▅▃▄▁▁▁▂▂▅▂▁▁▅▁▁▁▂▂▂▃▄▁▂▄▃▂▃▂▃▁▁▁▃▁▅▁▁▁▁▁▁▁▁▁▃▁▄▁▁▁▁▁▁▁▁▁▁▁▄▁▁▁▁▁▁▁▁▁▁▁▁█
```

**Heap InUse** (current: 207.4MB | avg: 191.7MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▂▄▃▁▄▃▂▅▅▅▃▃▄▃▃▄▃▂▂▄▅▄▄▁▄▄▆▅▄▄▄▃▅▂▅▁▄▁▂▂▆▂▂▄▄▄▁▃▅▁▅▁▄▃▁▃▆▅▅▄▂▅▃▅▄▁▄▁▆▄▄▄▂▅▅▃▁▅▃▁▅▄▆▄▂▅▄▂▆▄▁▁▆▅▄█
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,746 | 14,099 | +647 | 12,892 | 84,644 | INCREASING (+3.39/hr) |
| Heap InUse | 207.4MB | 161.9MB | +45.5MB | 191.7MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 853.6MB | 853.7MB | -0.1MB | 2307.5MB | 6883.9MB | |
| Heap Objects | 797,407 | 1,088,456 | -291049 | 862,181 | 17,165,538 | |

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
| 2026-06-07 | 17 | 14,148 | 155.9MB | 207.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 7.54MB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 4.89MB |
| 7 | `bufio.NewWriterSize` | 4.52MB |
| 8 | `bufio.NewReaderSize` | 3.01MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 16.6GB |
| 2 | `reflect.unsafe_NewArray` | 8.48GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.06GB |
| 4 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.76GB |
| 5 | `reflect.MakeSlice` | 4.75GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 3.75GB |
| 7 | `reflect.growslice` | 2.24GB |
| 8 | `fmt.Sprintf` | 2.16GB |
| 9 | `segmentio/kafka-go.makeLayout` | 2.1GB |
| 10 | `jackskj/carta.getUniqueId` | 2.0GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 442.46MB | 441.96MB | 407.01MB | 0B |
| `evaluation.mergeMetadata` | 232.06MB | 232.06MB | 213.05MB | 0B |
| `local.(*Client).EvaluateV2` | 672.81MB | 670.76MB | 613.06MB | 0B |
| `local.topologicalSort` | 93.64MB | 92.62MB | 83.21MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 677.52MB | 674.94MB | 613.69MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 62.80MB | 62.80MB | 59.57MB | 0B |
| `localEvaluation.getMapOfValue` | 677.52MB | 674.94MB | 613.69MB | 0B |
| `utils.ParseFeatureFlag` | 679.52MB | 676.94MB | 615.13MB | 0B |

**Total FF alloc (current snapshot):** 3.46GB  |  **24h avg:** 3.14GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 88.01MB | 36/1834 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 67.18MB | 61/1834 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1485/1834 | `██████░░░░░░░░░ 41%` |
| 4 | `database/sql.convertAssignRows` | 34.98MB | 77/1834 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1834 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.92MB | 1485/1834 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.89MB | 1109/1834 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1834 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1834 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1834 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1834 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1834 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1834 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1834 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1834 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1834 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 27.66GB | 1248/1834 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1834 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1834 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1834 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
