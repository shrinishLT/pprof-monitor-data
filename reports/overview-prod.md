# Overview: prod
*Last updated: 2026-06-07 05:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T05:30 (1884 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,008 | avg: 12,930 | max: 84,644 | trend: INCREASING (+3.37/hr))
```
▂▁▂▁▁▁▂▁▃▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▂▁▁▁▇▇▄▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▃▄▃▂▂▂▂▃▁▁▁▁▁▁▁▁▁▃▃▄▂▅█▆
```

**Heap InUse** (current: 218.6MB | avg: 190.7MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▄▁▃▂▁▂▄▄▄▃▂▄▂▄▃▁▃▁▅▃▃▃▁▄▄▂▁▄▂▁▄▃▅▃▂▄▃▂▄▃▁▁▄▄▃▆▃▄▂▄▄▁▅▇▃▄▂▁▃▁▁▁▃▃▄▃▃▄▂▂▃▂▃▂▂▂▄▃▃▄▄▂▁▃▃▁▁▁▄▂▅█▂▅▄▆
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,008 | 15,265 | -257 | 12,930 | 84,644 | INCREASING (+3.37/hr) |
| Heap InUse | 218.6MB | 184.3MB | +34.3MB | 190.7MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 854.3MB | 855.2MB | -0.9MB | 2268.9MB | 6883.9MB | |
| Heap Objects | 1,103,613 | 765,249 | +338364 | 861,395 | 17,165,538 | |

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
| 2026-06-07 | 67 | 14,284 | 154.9MB | 247.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `bytes.growSlice` | 10.56MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `reflect.growslice` | 5.59MB |
| 7 | `bufio.NewWriterSize` | 4.02MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.53MB |
| 9 | `bufio.NewReaderSize` | 3.51MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 22.3GB |
| 2 | `reflect.growslice` | 13.66GB |
| 3 | `reflect.unsafe_NewArray` | 11.37GB |
| 4 | `jackskj/carta.getUniqueId` | 10.76GB |
| 5 | `reflect.unsafe_New` | 10.11GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.04GB |
| 7 | `fmt.(*buffer).writeString` | 8.76GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.41GB |
| 9 | `carta/value.NewCell` | 7.01GB |
| 10 | `reflect.MakeSlice` | 6.44GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 554.02MB | 550.92MB | 500.28MB | 0B |
| `evaluation.mergeMetadata` | 291.57MB | 290.57MB | 261.03MB | 0B |
| `local.(*Client).EvaluateV2` | 848.44MB | 844.26MB | 764.67MB | 0B |
| `local.topologicalSort` | 118.41MB | 118.41MB | 106.12MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 856.20MB | 852.02MB | 769.55MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 76.14MB | 76.14MB | 70.73MB | 0B |
| `localEvaluation.getMapOfValue` | 856.20MB | 852.02MB | 769.55MB | 0B |
| `utils.ParseFeatureFlag` | 858.20MB | 854.02MB | 771.56MB | 0B |

**Total FF alloc (current snapshot):** 4.35GB  |  **24h avg:** 3.92GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1884 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1884 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1535/1884 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1884 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1884 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.75MB | 1535/1884 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.71MB | 1128/1884 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1884 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1884 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1884 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1884 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1884 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1884 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1884 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1884 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1884 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/1884 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1884 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.86GB | 401/1884 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1884 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
