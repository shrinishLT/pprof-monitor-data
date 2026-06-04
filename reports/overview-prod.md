# Overview: prod
*Last updated: 2026-06-04 14:21 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T14:21 (1127 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 17,137 | avg: 11,020 | max: 84,644 | trend: decreasing (-17.05/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 284.1MB | avg: 166.5MB | max: 2823.8MB | trend: stable (-0.22MB/hr))
```
▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 17,137 | 17,049 | +88 | 11,020 | 84,644 | decreasing (-17.05/hr) |
| Heap InUse | 284.1MB | 279.6MB | +4.5MB | 166.5MB | 2823.8MB | stable (-0.22MB/hr) |
| Heap Sys | 3415.8MB | 3410.0MB | +5.8MB | 2626.6MB | 6883.9MB | |
| Heap Objects | 1,156,205 | 1,343,553 | -187348 | 716,471 | 14,090,816 | |

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
| 2026-06-04 | 173 | 16,926 | 275.7MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 19.2MB |
| 3 | `runtime.mallocgc` | 11.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 8.54MB |
| 6 | `bufio.NewWriterSize` | 7.53MB |
| 7 | `bufio.NewReaderSize` | 6.02MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 9 | `compress/flate.NewWriter` | 4.41MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 12.01GB |
| 2 | `fmt.Sprintf` | 5.69GB |
| 3 | `reflect.growslice` | 5.68GB |
| 4 | `jackskj/carta.getUniqueId` | 5.29GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 4.79GB |
| 6 | `reflect.unsafe_New` | 4.6GB |
| 7 | `segmentio/kafka-go.makePartitions` | 3.91GB |
| 8 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 3.78GB |
| 9 | `fmt.(*buffer).writeString` | 3.31GB |
| 10 | `carta/value.NewCell` | 3.28GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 336.76MB | 327.62MB | 223.47MB | 0B |
| `evaluation.mergeMetadata` | 177.04MB | 173.04MB | 118.39MB | 0B |
| `local.(*Client).EvaluateV2` | 517.87MB | 503.55MB | 338.73MB | 0B |
| `local.topologicalSort` | 72.36MB | 71.34MB | 47.26MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 488.78MB | 472.44MB | 327.15MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 80.31MB | 77.72MB | 42.71MB | 0B |
| `localEvaluation.getMapOfValue` | 488.78MB | 472.44MB | 327.15MB | 0B |
| `utils.ParseFeatureFlag` | 488.78MB | 472.44MB | 327.33MB | 0B |

**Total FF alloc (current snapshot):** 2.59GB  |  **24h avg:** 1.71GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.94MB | 38/1127 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.75MB | 23/1127 | `██████████████░ 93%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 778/1127 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.33MB | 48/1127 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 20.32MB | 778/1127 | `████░░░░░░░░░░░ 32%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1127 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.33MB | 565/1127 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1127 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1127 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.45MB | 363/1127 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1127 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1127 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1127 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1127 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1127 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 41.26GB | 751/1127 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1127 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.77GB | 675/1127 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.67GB | 370/1127 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.31GB | 512/1127 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.4x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.7x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
