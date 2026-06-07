# Overview: prod
*Last updated: 2026-06-07 06:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T06:10 (1892 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,650 | avg: 12,937 | max: 84,644 | trend: INCREASING (+3.37/hr))
```
▃▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▂▁▁▁▇▇▄▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▃▄▃▂▂▂▂▃▁▁▁▁▁▁▁▁▁▃▃▄▂▅█▆▃▁▁▁▁▄▅▄
```

**Heap InUse** (current: 190.6MB | avg: 190.6MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▄▃▂▄▂▄▃▁▃▁▅▃▃▃▁▄▄▂▁▄▂▁▄▃▅▃▂▄▃▂▄▃▁▁▄▄▃▆▃▄▂▄▄▁▅▇▃▄▂▁▃▁▁▁▃▃▄▃▃▄▂▂▃▂▃▂▂▂▄▃▃▄▄▂▁▃▃▁▁▁▄▂▅█▂▅▄▆▃▂▂▂▄▆▄▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,650 | 14,919 | -269 | 12,937 | 84,644 | INCREASING (+3.37/hr) |
| Heap InUse | 190.6MB | 167.1MB | +23.5MB | 190.6MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 854.7MB | 855.5MB | -0.8MB | 2262.9MB | 6883.9MB | |
| Heap Objects | 998,140 | 424,676 | +573464 | 861,353 | 17,165,538 | |

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
| 2026-06-07 | 75 | 14,297 | 155.7MB | 247.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.58MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `bytes.growSlice` | 7.55MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `bufio.NewWriterSize` | 3.01MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_NewArray` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 23.2GB |
| 2 | `reflect.growslice` | 15.55GB |
| 3 | `jackskj/carta.getUniqueId` | 12.2GB |
| 4 | `reflect.unsafe_NewArray` | 11.83GB |
| 5 | `reflect.unsafe_New` | 11.42GB |
| 6 | `fmt.(*buffer).writeString` | 10.13GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.17GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 8.49GB |
| 9 | `carta/value.NewCell` | 7.94GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.5GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 570.83MB | 567.32MB | 517.66MB | 0B |
| `evaluation.mergeMetadata` | 299.07MB | 297.57MB | 270.33MB | 0B |
| `local.(*Client).EvaluateV2` | 876.12MB | 871.57MB | 791.89MB | 0B |
| `local.topologicalSort` | 122.46MB | 122.46MB | 110.22MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 882.33MB | 877.28MB | 797.39MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 79.22MB | 79.22MB | 72.75MB | 0B |
| `localEvaluation.getMapOfValue` | 882.33MB | 877.28MB | 797.39MB | 0B |
| `utils.ParseFeatureFlag` | 884.33MB | 879.28MB | 799.39MB | 0B |

**Total FF alloc (current snapshot):** 4.49GB  |  **24h avg:** 4.06GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1892 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1892 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1543/1892 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1892 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1892 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.72MB | 1543/1892 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.68MB | 1133/1892 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1892 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1892 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1892 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1892 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1892 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1892 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1892 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1892 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1892 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/1892 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1892 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.77GB | 409/1892 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1892 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
