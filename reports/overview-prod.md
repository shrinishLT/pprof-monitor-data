# Overview: prod
*Last updated: 2026-06-08 01:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-08T01:45 (2126 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,335 | avg: 13,240 | max: 84,644 | trend: INCREASING (+3.84/hr))
```
▁▁▁▁▄▁▁▁▃▁▁▂▁▁▁▁▄▁▁▁▁▁▂▁▁▁▁▁▂▁▁▂▁▂▁▁▂▃▂▁▃▂▂▅▂▂▂▂▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▂▁▁▁▁▄▆▂▁▁▁▁▇█▄▆▁▁▁▁▁▁▁▂▃▂▂▆▂▃▆▂
```

**Heap InUse** (current: 202.1MB | avg: 198.0MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▄▃▄▅▂▁▄▁▂▂▃▄▄▃▁▁▅▆▅▁▆▂▁▆▅▂▃▂▂▅▅▂▅▂▃▃▂▃▃▅▇▆▃▃▆▂▆▂▃▂▃▃▅▅▄▄▄▅▅▅▄▁▂▂▂▂▇▅▄▅█▅▄▅▃▄▆▄▆▇▃▃▂▂▁▁▂▄▂▃▁▅▃▂▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,335 | 14,786 | -451 | 13,240 | 84,644 | INCREASING (+3.84/hr) |
| Heap InUse | 202.1MB | 221.1MB | -19.0MB | 198.0MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 3222.8MB | 3222.1MB | +0.7MB | 2311.9MB | 6883.9MB | |
| Heap Objects | 637,849 | 711,840 | -73991 | 892,100 | 17,165,538 | |

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
| 2026-06-08 | 21 | 14,405 | 222.6MB | 295.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 49.47MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.01MB |
| 7 | `bufio.NewReaderSize` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 49.82GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 40.05GB |
| 3 | `reflect.growslice` | 34.68GB |
| 4 | `jackskj/carta.getUniqueId` | 29.73GB |
| 5 | `reflect.unsafe_New` | 26.78GB |
| 6 | `reflect.unsafe_NewArray` | 25.49GB |
| 7 | `fmt.(*buffer).writeString` | 21.45GB |
| 8 | `carta/value.NewCell` | 19.13GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 17.83GB |
| 10 | `fmt.Sprintf` | 17.46GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.34GB | 1.33GB | 1.29GB | 0B |
| `evaluation.mergeMetadata` | 708.17MB | 706.67MB | 678.82MB | 0B |
| `local.(*Client).EvaluateV2` | 2.03GB | 2.02GB | 1.94GB | 0B |
| `local.topologicalSort` | 269.80MB | 268.27MB | 260.22MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.01GB | 2.00GB | 1.93GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 222.89MB | 221.37MB | 214.26MB | 0B |
| `localEvaluation.getMapOfValue` | 2.01GB | 2.00GB | 1.93GB | 0B |
| `utils.ParseFeatureFlag` | 2.02GB | 2.01GB | 1.94GB | 0B |

**Total FF alloc (current snapshot):** 10.58GB  |  **24h avg:** 10.15GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/2126 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 64.17MB | 64/2126 | `███████████░░░░ 74%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1777/2126 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 32.28MB | 84/2126 | `█████░░░░░░░░░░ 37%` |
| 5 | `runtime.mallocgc` | 20.01MB | 1777/2126 | `███░░░░░░░░░░░░ 23%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2126 | `███░░░░░░░░░░░░ 20%` |
| 7 | `bytes.growSlice` | 14.69MB | 1289/2126 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.47MB | 37/2126 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2126 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/2126 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2126 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2126 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2126 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2126 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2126 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/2126 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/2126 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 19.52GB | 643/2126 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `segmentio/kafka-go.makePartitions` | 15.31GB | 1500/2126 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/2126 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.4x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.4x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.3x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.0x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.0x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.8x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.5x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (3.1x avg)
