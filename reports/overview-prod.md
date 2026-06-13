# Overview: prod
*Last updated: 2026-06-14 02:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-14T02:45 (3866 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,751 | avg: 14,622 | max: 84,644 | trend: INCREASING (+2.97/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▆█▅▃▄▃▄▅▅▃▃▃▃▄▄▃▄▃▄▃▃▂▂▂▃▃▂▂▃▃▃▃▄▃▃▃▃▃▃▃▄▄▃▄▃▄▄▄▄▄▃▄▃▃▃▃▃▃
```

**Heap InUse** (current: 235.2MB | avg: 241.0MB | max: 3154.1MB | trend: stable (+0.08MB/hr))
```
▁▂▁▃▃▁▂▄▂▁▁▂▂▁▂▂▂▁▁▂▂▁▃▂▃▁▁▃▁▂▃▂▂▃▁▁▁▁▆█▄▃▄▃▄▃▄▄▃▄▃▄▅▃▄▃▄▃▃▂▂▃▃▅▂▂▃▃▄▃▅▄▂▅▄▃▃▅▃▄▄▅▅▃▄▄▃▄▄▄▅▃▃▃▃▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,751 | 15,840 | -89 | 14,622 | 84,644 | INCREASING (+2.97/hr) |
| Heap InUse | 235.2MB | 281.2MB | -46.0MB | 241.0MB | 3154.1MB | stable (+0.08MB/hr) |
| Heap Sys | 2299.1MB | 2297.0MB | +2.1MB | 2542.8MB | 6883.9MB | |
| Heap Objects | 392,547 | 1,310,666 | -918119 | 1,036,639 | 17,165,538 | |

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
| 2026-06-14 | 34 | 16,158 | 289.3MB | 371.7MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.86MB |
| 3 | `bytes.growSlice` | 15.19MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `bufio.NewWriterSize` | 7.03MB |
| 7 | `compress/flate.NewWriter` | 5.29MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.02MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.53MB |
| 10 | `bufio.NewReaderSize` | 3.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 53.07GB |
| 2 | `reflect.growslice` | 46.49GB |
| 3 | `jackskj/carta.getUniqueId` | 43.81GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 39.89GB |
| 5 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 38.97GB |
| 6 | `reflect.unsafe_New` | 38.05GB |
| 7 | `fmt.Sprintf` | 37.64GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 32.07GB |
| 9 | `fmt.(*buffer).writeString` | 28.78GB |
| 10 | `dotlapse-event-service/project.ApplyPagination` | 27.82GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.27GB | 2.26GB | 2.16GB | 0B |
| `evaluation.mergeMetadata` | 1.17GB | 1.16GB | 1.11GB | 0B |
| `local.(*Client).EvaluateV2` | 3.49GB | 3.48GB | 3.32GB | 0B |
| `local.topologicalSort` | 507.35MB | 505.84MB | 480.00MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.40GB | 3.40GB | 3.24GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 423.73MB | 423.73MB | 413.95MB | 0B |
| `localEvaluation.getMapOfValue` | 3.40GB | 3.40GB | 3.24GB | 0B |
| `utils.ParseFeatureFlag` | 3.41GB | 3.40GB | 3.24GB | 0B |

**Total FF alloc (current snapshot):** 18.05GB  |  **24h avg:** 17.19GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.23MB | 75/3866 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 42.26MB | 106/3866 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3517/3866 | `███████████░░░░ 75%` |
| 4 | `runtime.mallocgc` | 31.23MB | 3517/3866 | `█████████░░░░░░ 64%` |
| 5 | `database/sql.convertAssignRows` | 23.55MB | 126/3866 | `███████░░░░░░░░ 48%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/3866 | `█████░░░░░░░░░░ 37%` |
| 7 | `bytes.growSlice` | 15.78MB | 2772/3866 | `████░░░░░░░░░░░ 32%` |
| 8 | `net/http.(*Transport).dialConn` | 13.23MB | 101/3866 | `████░░░░░░░░░░░ 27%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/3866 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/3866 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/3866 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/3866 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/3866 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 69.9GB | 2055/3866 | `████████░░░░░░░ 55%` |
| 5 | `segmentio/kafka-go.makePartitions` | 59.07GB | 3240/3866 | `███████░░░░░░░░ 47%` |
| 6 | `reflect.growslice` | 59.01GB | 3078/3866 | `███████░░░░░░░░ 47%` |
| 7 | `jackskj/carta.getUniqueId` | 52.4GB | 3094/3866 | `██████░░░░░░░░░ 41%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/3866 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 49.88GB | 2858/3866 | `█████░░░░░░░░░░ 39%` |
| 10 | `fmt.(*buffer).writeString` | 46.02GB | 2412/3866 | `█████░░░░░░░░░░ 36%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.8x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.3x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.6x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.2x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
