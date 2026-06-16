# Overview: prod
*Last updated: 2026-06-16 20:42 IST*
*Data range: 2026-05-15T16:03 to 2026-06-16T20:42 (4653 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 19,220 | avg: 14,866 | max: 84,644 | trend: INCREASING (+2.23/hr))
```
▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▃▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▂▁▁▂▁▁▁▂▂▁▁▁▁▂▆█▅▂▂▃▅▄
```

**Heap InUse** (current: 328.6MB | avg: 245.4MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▃▂▁▂▃▂▂▁▁▂▂▃▂▃▂▁▁▁▁▁▁▂▂▁▂▁▂▁▂▂▁▁▁▃▂▃▂▂▂▁▁▁▂▂▁▁▁▁▂▂▂▂▂▂▂▁▂▂▁▂▂▁▂▂▂▄▂▂▁▁▁▂▂▂▂▂▂▂▁▂▂▂▁▁▂▂▃█▇▆▄▃▅▅▄
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 19,220 | 19,600 | -380 | 14,866 | 84,644 | INCREASING (+2.23/hr) |
| Heap InUse | 328.6MB | 383.2MB | -54.6MB | 245.4MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 988.3MB | 987.8MB | +0.5MB | 2477.6MB | 6883.9MB | |
| Heap Objects | 1,032,750 | 1,122,073 | -89323 | 1,052,278 | 17,165,538 | |

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
| 2026-06-16 | 247 | 16,223 | 255.8MB | 1286.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 31.07MB |
| 3 | `runtime.mallocgc` | 14.01MB |
| 4 | `bufio.NewWriterSize` | 10.54MB |
| 5 | `bufio.NewReaderSize` | 10.04MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.54MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 5.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 4.5MB |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 12.69GB |
| 2 | `fmt.Sprintf` | 9.84GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.26GB |
| 4 | `jackskj/carta.getUniqueId` | 7.21GB |
| 5 | `reflect.growslice` | 6.96GB |
| 6 | `reflect.unsafe_NewArray` | 6.69GB |
| 7 | `reflect.unsafe_New` | 6.02GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 5.95GB |
| 9 | `dotlapse-event-service/project.ApplyPagination` | 5.68GB |
| 10 | `fmt.Sprint` | 4.95GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.03GB | 1.02GB | 806.38MB | 0B |
| `evaluation.mergeMetadata` | 543.63MB | 535.63MB | 413.28MB | 0B |
| `local.(*Client).EvaluateV2` | 1.57GB | 1.55GB | 1.20GB | 0B |
| `local.topologicalSort` | 210.00MB | 207.49MB | 162.50MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.46GB | 1.45GB | 1.13GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 262.57MB | 261.52MB | 197.39MB | 0B |
| `localEvaluation.getMapOfValue` | 1.46GB | 1.45GB | 1.13GB | 0B |
| `utils.ParseFeatureFlag` | 1.47GB | 1.45GB | 1.13GB | 0B |

**Total FF alloc (current snapshot):** 7.99GB  |  **24h avg:** 6.12GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4653 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4304/4653 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.6MB | 133/4653 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.85MB | 4304/4653 | `████████████░░░ 80%` |
| 5 | `database/sql.convertAssignRows` | 20.45MB | 155/4653 | `███████░░░░░░░░ 53%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4653 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.72MB | 3403/4653 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.25MB | 128/4653 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4653 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4653 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4653 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4653 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4653 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4653 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 63.24GB | 3865/4653 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 63.11GB | 4027/4653 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 56.5GB | 3881/4653 | `██████░░░░░░░░░ 45%` |
| 8 | `reflect.unsafe_New` | 52.81GB | 3645/4653 | `██████░░░░░░░░░ 42%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4653 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4653 | `█████░░░░░░░░░░ 37%` |

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
