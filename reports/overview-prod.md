# Overview: prod
*Last updated: 2026-06-16 23:47 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T23:47 (4690 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,369 | avg: 14,874 | max: 84,644 | trend: INCREASING (+2.20/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▂▁▁▂▁▁▁▂▂▁▁▁▁▂▆█▅▂▂▃▅▄▃▁▂▂▂▁▁▃▃▁▂▁▁▁▁▁▁▁▁▁▆▃▁▁▁▁▂▁▁▁▁▄▁▇▂▁▁
```

**Heap InUse** (current: 254.9MB | avg: 245.4MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▂▂▁▁▁▂▂▁▁▁▁▂▂▂▂▂▂▂▁▁▂▁▁▂▁▂▂▂▃▂▂▁▁▁▁▂▂▁▂▂▁▁▂▂▂▁▁▁▂▃▇▆▆▄▃▄▅▄▄▂▃▂▃▂▂▄▃▂▂▁▂▁▂▂▂▁▂▁▆▄▂▂▂▂▂▂▁▁▁▄▂█▃▂▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,369 | 14,899 | +470 | 14,874 | 84,644 | INCREASING (+2.20/hr) |
| Heap InUse | 254.9MB | 223.5MB | +31.4MB | 245.4MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 991.2MB | 991.2MB | +0.0MB | 2465.9MB | 6883.9MB | |
| Heap Objects | 1,312,216 | 906,031 | +406185 | 1,052,531 | 17,165,538 | |

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
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 284 | 16,171 | 253.6MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.04MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 6 | `bufio.NewReaderSize` | 4.52MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `reflect.unsafe_NewArray` | 3.52MB |
| 10 | `bufio.NewWriterSize` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 16.92GB |
| 2 | `fmt.Sprintf` | 13.17GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 8.92GB |
| 4 | `reflect.unsafe_NewArray` | 8.87GB |
| 5 | `jackskj/carta.getUniqueId` | 8.35GB |
| 6 | `reflect.growslice` | 7.71GB |
| 7 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.3GB |
| 8 | `reflect.unsafe_New` | 6.79GB |
| 9 | `fmt.Sprint` | 6.58GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.55GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.29GB | 1.29GB | 1.13GB | 0B |
| `evaluation.mergeMetadata` | 674.66MB | 673.66MB | 594.34MB | 0B |
| `local.(*Client).EvaluateV2` | 1.97GB | 1.96GB | 1.72GB | 0B |
| `local.topologicalSort` | 270.79MB | 269.78MB | 234.79MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.86GB | 1.86GB | 1.62GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 300.77MB | 300.77MB | 278.08MB | 0B |
| `localEvaluation.getMapOfValue` | 1.86GB | 1.86GB | 1.62GB | 0B |
| `utils.ParseFeatureFlag` | 1.87GB | 1.86GB | 1.62GB | 0B |

**Total FF alloc (current snapshot):** 10.07GB  |  **24h avg:** 8.80GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4690 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4341/4690 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.39MB | 134/4690 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 30.7MB | 4341/4690 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.24MB | 157/4690 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4690 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.67MB | 3440/4690 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.18MB | 129/4690 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4690 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4690 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4690 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4690 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4690 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4690 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 62.71GB | 3902/4690 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.67GB | 4064/4690 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.04GB | 3918/4690 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 52.34GB | 3682/4690 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4690 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4690 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
