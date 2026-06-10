# Overview: prod
*Last updated: 2026-06-10 10:12 IST*
*Data range: 2026-05-15T16:03 to 2026-06-10T10:12 (2804 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 25,287 | avg: 13,975 | max: 84,644 | trend: INCREASING (+4.03/hr))
```
▄▅▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▁▂▅█
```

**Heap InUse** (current: 507.6MB | avg: 224.1MB | max: 3154.1MB | trend: stable (+0.11MB/hr))
```
▆▆▄▂▂▃▂▂▂▁▃▃▁▂▁▂▂▂▄▃▂▃▃▃▁▁▁▁▂▂▂▂▂▂▁▂▁▂▂▃▃▁▁▃▃▁▂▂▃▃▄▁▃▂▁▁▂▁▂▁▂▁▂▂▁▂▁▂▂▂▂▂▂▁▂▁▃▂▃▁▁▁▁▃▁▂▂▂▃▃▃▄▃▄▄█
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 29%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 25,287 | 21,007 | +4280 | 13,975 | 84,644 | INCREASING (+4.03/hr) |
| Heap InUse | 507.6MB | 337.6MB | +170.0MB | 224.1MB | 3154.1MB | stable (+0.11MB/hr) |
| Heap Sys | 3310.9MB | 3329.7MB | -18.8MB | 2550.8MB | 6883.9MB | |
| Heap Objects | 2,256,716 | 857,700 | +1399016 | 975,908 | 17,165,538 | |

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
| 2026-06-10 | 123 | 16,126 | 294.1MB | 1004.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 58.53MB |
| 2 | `runtime.mallocgc` | 50.47MB |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 29.13MB |
| 5 | `bufio.NewWriterSize` | 26.63MB |
| 6 | `bufio.NewReaderSize` | 22.6MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 7.51MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 7.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 127.05GB |
| 2 | `reflect.growslice` | 125.67GB |
| 3 | `jackskj/carta.getUniqueId` | 111.69GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 102.83GB |
| 5 | `reflect.unsafe_New` | 99.08GB |
| 6 | `fmt.Sprintf` | 85.82GB |
| 7 | `fmt.(*buffer).writeString` | 79.58GB |
| 8 | `carta/value.NewCell` | 70.68GB |
| 9 | `reflect.unsafe_NewArray` | 64.94GB |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 53.93GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.27GB | 6.26GB | 6.14GB | 0B |
| `evaluation.mergeMetadata` | 3.29GB | 3.29GB | 3.23GB | 0B |
| `local.(*Client).EvaluateV2` | 9.56GB | 9.55GB | 9.36GB | 0B |
| `local.topologicalSort` | 1.33GB | 1.33GB | 1.30GB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 9.15GB | 9.14GB | 8.94GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.29GB | 1.29GB | 1.28GB | 0B |
| `localEvaluation.getMapOfValue` | 9.15GB | 9.14GB | 8.94GB | 0B |
| `utils.ParseFeatureFlag` | 9.17GB | 9.16GB | 8.95GB | 0B |

**Total FF alloc (current snapshot):** 49.22GB  |  **24h avg:** 48.13GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 71.38MB | 48/2804 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 56.12MB | 77/2804 | `███████████░░░░ 78%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 2455/2804 | `███████░░░░░░░░ 51%` |
| 4 | `database/sql.convertAssignRows` | 28.64MB | 99/2804 | `██████░░░░░░░░░ 40%` |
| 5 | `runtime.mallocgc` | 28.38MB | 2455/2804 | `█████░░░░░░░░░░ 39%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/2804 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 15.38MB | 1871/2804 | `███░░░░░░░░░░░░ 21%` |
| 8 | `net/http.(*Transport).dialConn` | 14.27MB | 55/2804 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 14.13MB | 4/2804 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/2804 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/2804 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/2804 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/2804 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/2804 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 47.01GB | 1321/2804 | `█████░░░░░░░░░░ 37%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/2804 | `█████░░░░░░░░░░ 34%` |
| 7 | `segmentio/kafka-go.makePartitions` | 38.08GB | 2178/2804 | `████░░░░░░░░░░░ 30%` |
| 8 | `reflect.growslice` | 36.6GB | 2016/2804 | `████░░░░░░░░░░░ 29%` |
| 9 | `jackskj/carta.getUniqueId` | 31.81GB | 2032/2804 | `███░░░░░░░░░░░░ 25%` |
| 10 | `reflect.unsafe_New` | 31.42GB | 1796/2804 | `███░░░░░░░░░░░░ 25%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.1x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.0x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.5x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.3x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.4x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.8x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.5x avg)
