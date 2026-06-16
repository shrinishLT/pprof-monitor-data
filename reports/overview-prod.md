# Overview: prod
*Last updated: 2026-06-17 00:46 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T00:46 (4702 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,827 | avg: 14,875 | max: 84,644 | trend: INCREASING (+2.19/hr))
```
▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▃▁▁▁▁▁▁▂▂▁▁▂▁▁▁▂▂▁▁▁▁▂▆█▅▂▂▃▅▄▃▁▂▂▂▁▁▃▃▁▂▁▁▁▁▁▁▁▁▁▆▃▁▁▁▁▂▁▁▁▁▄▁▇▂▁▁▁▁▄▂▁▂▁▁▁▂▃▁
```

**Heap InUse** (current: 203.1MB | avg: 245.3MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▂▂▂▂▂▂▁▁▂▁▁▂▁▂▂▂▃▂▂▁▁▁▁▂▂▁▂▂▁▁▂▂▂▁▁▁▂▃▇▆▆▄▃▄▅▄▄▂▃▂▃▂▂▄▃▂▂▁▂▁▂▂▂▁▂▁▆▄▂▂▂▂▂▂▁▁▁▄▂█▃▂▃▂▁▄▂▁▃▁▁▁▂▄▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,827 | 17,356 | -2529 | 14,875 | 84,644 | INCREASING (+2.19/hr) |
| Heap InUse | 203.1MB | 351.5MB | -148.4MB | 245.3MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 997.1MB | 995.3MB | +1.8MB | 2462.1MB | 6883.9MB | |
| Heap Objects | 883,196 | 1,790,759 | -907563 | 1,052,319 | 17,165,538 | |

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
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 10 | 15,797 | 227.0MB | 351.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.01MB |
| 3 | `bytes.growSlice` | 10.25MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 6.02MB |
| 6 | `bufio.NewWriterSize` | 4.03MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 18.21GB |
| 2 | `fmt.Sprintf` | 14.0GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 10.56GB |
| 4 | `reflect.unsafe_NewArray` | 9.56GB |
| 5 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 8.67GB |
| 6 | `jackskj/carta.getUniqueId` | 8.44GB |
| 7 | `reflect.growslice` | 7.77GB |
| 8 | `fmt.Sprint` | 6.97GB |
| 9 | `reflect.unsafe_New` | 6.87GB |
| 10 | `strconv.appendQuotedWith` | 6.84GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.35GB | 1.35GB | 1.22GB | 0B |
| `evaluation.mergeMetadata` | 710.17MB | 706.67MB | 637.81MB | 0B |
| `local.(*Client).EvaluateV2` | 2.07GB | 2.06GB | 1.85GB | 0B |
| `local.topologicalSort` | 285.96MB | 285.46MB | 253.85MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.96GB | 1.95GB | 1.75GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 311.07MB | 309.53MB | 292.23MB | 0B |
| `localEvaluation.getMapOfValue` | 1.96GB | 1.95GB | 1.75GB | 0B |
| `utils.ParseFeatureFlag` | 1.97GB | 1.96GB | 1.75GB | 512.56kB |

**Total FF alloc (current snapshot):** 10.59GB  |  **24h avg:** 9.47GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4702 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4353/4702 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.39MB | 134/4702 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 30.66MB | 4353/4702 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.24MB | 157/4702 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4702 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.66MB | 3451/4702 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.18MB | 129/4702 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4702 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4702 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4702 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4702 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4702 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4702 | `████████░░░░░░░ 59%` |
| 5 | `reflect.growslice` | 62.54GB | 3914/4702 | `███████░░░░░░░░ 50%` |
| 6 | `segmentio/kafka-go.makePartitions` | 62.54GB | 4076/4702 | `███████░░░░░░░░ 50%` |
| 7 | `jackskj/carta.getUniqueId` | 55.9GB | 3930/4702 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 52.19GB | 3694/4702 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4702 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4702 | `█████░░░░░░░░░░ 37%` |

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
