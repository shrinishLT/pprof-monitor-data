# Overview: prod
*Last updated: 2026-06-10 22:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T22:25 (2950 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,957 | avg: 14,116 | max: 84,644 | trend: INCREASING (+3.99/hr))
```
▁▂▂▂▃▂▁▃▁▁▄▂▂▂▂▂▂▂▂▂▁▁▂▂▃▂▂▁▂▂▇▂▁▁▁▁▁▁▁▃▅▁▂▃▄▃▂▂▃▃▂▂▃▃▂▂▂▁▃▁▁▃▁▂▁▁▁█▂▄▅▄▄▅▃▂▁▄▅▃▁▁▃▁▁▁▁▁▁▂▂▂▁▂▂▄
```

**Heap InUse** (current: 318.8MB | avg: 228.7MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▄▂▃▂▃▄▂▆▂▂▃▃▄▃▃▂▄▂▂▃▁▃▅▄▅▂▄▂▄▅▅▄▂▁▃▁▃▁▁▃▅▂▃▅▆▆▄▅▄▃▃▂▃▂▅▆▄▄▅▃▂▃▅▄▄▄▁▇▃▄▅▄▄▇▄▂▁▄█▄▄▂▆▅▃▁▂▂▁▃▅▂▂▂▃▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,957 | 14,903 | +1054 | 14,116 | 84,644 | INCREASING (+3.99/hr) |
| Heap InUse | 318.8MB | 270.9MB | +47.9MB | 228.7MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3343.1MB | 3342.3MB | +0.8MB | 2589.2MB | 6883.9MB | |
| Heap Objects | 1,290,946 | 1,352,100 | -61154 | 988,544 | 17,165,538 | |

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
| 2026-06-10 | 269 | 16,503 | 306.4MB | 1442.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 50.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 12.31MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewWriterSize` | 7.54MB |
| 7 | `compress/flate.NewWriter` | 5.29MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 144.02GB |
| 2 | `reflect.growslice` | 139.09GB |
| 3 | `jackskj/carta.getUniqueId` | 124.81GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 112.88GB |
| 5 | `reflect.unsafe_New` | 110.34GB |
| 6 | `fmt.Sprintf` | 99.05GB |
| 7 | `fmt.(*buffer).writeString` | 87.5GB |
| 8 | `carta/value.NewCell` | 78.88GB |
| 9 | `reflect.unsafe_NewArray` | 73.6GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 59.74GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 7.57GB | 7.56GB | 7.35GB | 0B |
| `evaluation.mergeMetadata` | 3.97GB | 3.96GB | 3.86GB | 0B |
| `local.(*Client).EvaluateV2` | 11.54GB | 11.52GB | 11.21GB | 0B |
| `local.topologicalSort` | 1.60GB | 1.60GB | 1.56GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 10.97GB | 10.95GB | 10.68GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.62GB | 1.62GB | 1.55GB | 0B |
| `localEvaluation.getMapOfValue` | 10.97GB | 10.95GB | 10.68GB | 0B |
| `utils.ParseFeatureFlag` | 10.99GB | 10.97GB | 10.70GB | 0B |

**Total FF alloc (current snapshot):** 59.24GB  |  **24h avg:** 57.60GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 65.57MB | 53/2950 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 54.51MB | 80/2950 | `████████████░░░ 83%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2601/2950 | `████████░░░░░░░ 55%` |
| 4 | `runtime.mallocgc` | 29.62MB | 2601/2950 | `██████░░░░░░░░░ 45%` |
| 5 | `database/sql.convertAssignRows` | 28.12MB | 102/2950 | `██████░░░░░░░░░ 42%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2950 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.61MB | 2007/2950 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 14.56MB | 60/2950 | `███░░░░░░░░░░░░ 22%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2950 | `███░░░░░░░░░░░░ 21%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2950 | `██░░░░░░░░░░░░░ 16%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2950 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2950 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2950 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 53.48GB | 1467/2950 | `██████░░░░░░░░░ 42%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/2950 | `██████░░░░░░░░░ 40%` |
| 6 | `segmentio/kafka-go.makePartitions` | 44.21GB | 2324/2950 | `█████░░░░░░░░░░ 35%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2950 | `█████░░░░░░░░░░ 34%` |
| 8 | `reflect.growslice` | 43.37GB | 2162/2950 | `█████░░░░░░░░░░ 34%` |
| 9 | `jackskj/carta.getUniqueId` | 37.87GB | 2178/2950 | `████░░░░░░░░░░░ 30%` |
| 10 | `reflect.unsafe_New` | 37.19GB | 1942/2950 | `████░░░░░░░░░░░ 29%` |

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
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.5x avg)
