# Overview: prod
*Last updated: 2026-06-05 06:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T06:55 (1326 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,622 | avg: 11,698 | max: 84,644 | trend: decreasing (-5.32/hr))
```
▁▂▂▂▃█▄▁▁▁▁▂▁▂▁▁▁▁▁▁▂▆▃▁▁▁▁▁▁▁▁▂▃▂▃▃▃▂▂▁▁▄▂▁▂▃▁▁▁▃▁▂▁▁▁▂▄▃▄▆▅▁▁▁▁▁▁▂▂▁▆▂▁▁▁▂▂▂▁▁▂▃▂▃▃▂▂▂▂▂▁▁▁▁▁▁
```

**Heap InUse** (current: 195.9MB | avg: 180.0MB | max: 3154.1MB | trend: stable (-0.03MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,622 | 14,555 | +67 | 11,698 | 84,644 | decreasing (-5.32/hr) |
| Heap InUse | 195.9MB | 149.2MB | +46.7MB | 180.0MB | 3154.1MB | stable (-0.03MB/hr) |
| Heap Sys | 199.1MB | 4534.9MB | -4335.8MB | 2709.0MB | 6883.9MB | |
| Heap Objects | 1,272,907 | 382,715 | +890192 | 800,472 | 17,165,538 | |

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
| 2026-06-05 | 84 | 14,916 | 265.3MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 9.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 2.64MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 2.02MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 10.06MB |
| 3 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `segmentio/kafka-go.makePartitions` | 6.01MB |
| 6 | `internal/evaluation.mergeMetadata` | 4.0MB |
| 7 | `compress/flate.NewWriter` | 3.53MB |
| 8 | `reflect.unsafe_NewArray` | 3.03MB |
| 9 | `strconv.appendQuotedWith` | 3.01MB |
| 10 | `dotlapse-event-service/kafka.StartKafka.func1` | 3.0MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 6.61MB | 320.55MB | 174.89MB | 0B |
| `evaluation.mergeMetadata` | 4.00MB | 161.54MB | 88.44MB | 0B |
| `local.(*Client).EvaluateV2` | 9.16MB | 486.43MB | 264.52MB | 0B |
| `local.topologicalSort` | 1.53MB | 72.35MB | 38.55MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 7.64MB | 482.51MB | 261.92MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 2.04MB | 53.03MB | 27.50MB | 0B |
| `localEvaluation.getMapOfValue` | 7.64MB | 482.51MB | 261.92MB | 0B |
| `utils.ParseFeatureFlag` | 7.64MB | 483.51MB | 262.73MB | 0B |

**Total FF alloc (current snapshot):** 46.25MB  |  **24h avg:** 1.35GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 94.56MB | 31/1326 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 76.85MB | 51/1326 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 40.34MB | 63/1326 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 977/1326 | `█████░░░░░░░░░░ 38%` |
| 5 | `runtime.mallocgc` | 18.22MB | 977/1326 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1326 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.37MB | 747/1326 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1326 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1326 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1326 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1326 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1326 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1326 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1326 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1326 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 35.33GB | 948/1326 | `████░░░░░░░░░░░ 28%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1326 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 15.69GB | 871/1326 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `fmt.Sprintf` | 9.77GB | 543/1326 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.58GB | 187/1326 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.5x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.2x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.7x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.4x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.7x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.3x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.4x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.2x avg)
