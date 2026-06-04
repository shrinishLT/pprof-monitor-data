# Overview: prod
*Last updated: 2026-06-04 11:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T11:30 (1093 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,931 | avg: 10,846 | max: 84,644 | trend: decreasing (-20.65/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁
```

**Heap InUse** (current: 214.2MB | avg: 163.5MB | max: 2823.8MB | trend: stable (-0.28MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▄▂▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,931 | 14,604 | +327 | 10,846 | 84,644 | decreasing (-20.65/hr) |
| Heap InUse | 214.2MB | 224.2MB | -10.0MB | 163.5MB | 2823.8MB | stable (-0.28MB/hr) |
| Heap Sys | 1196.1MB | 5106.9MB | -3910.8MB | 2649.1MB | 6883.9MB | |
| Heap Objects | 1,272,151 | 1,102,105 | +170046 | 702,224 | 14,090,816 | |

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
| 2026-06-04 | 139 | 17,009 | 279.1MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 8.58MB |
| 4 | `bufio.NewReaderSize` | 5.02MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `bytes.growSlice` | 4.53MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.02MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `http2/hpack.(*headerFieldTable).addEntry` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 1.66GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 688.12MB |
| 3 | `reflect.growslice` | 410.12MB |
| 4 | `jackskj/carta.getUniqueId` | 333.55MB |
| 5 | `reflect.unsafe_New` | 281.13MB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 261.01MB |
| 7 | `fmt.(*buffer).writeString` | 221.32MB |
| 8 | `carta/value.NewCell` | 210.02MB |
| 9 | `database/sql.convertAssignRows` | 194.01MB |
| 10 | `segmentio/kafka-go.makePartitions` | 77.93MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 8.54MB | 412.57MB | 248.06MB | 0B |
| `evaluation.mergeMetadata` | 5.50MB | 214.05MB | 128.45MB | 0B |
| `local.(*Client).EvaluateV2` | 13.69MB | 640.66MB | 380.22MB | 0B |
| `local.topologicalSort` | 2.53MB | 91.11MB | 54.10MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 13.72MB | 643.16MB | 381.44MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.00MB | 58.82MB | 35.59MB | 0B |
| `localEvaluation.getMapOfValue` | 13.72MB | 643.16MB | 381.44MB | 0B |
| `utils.ParseFeatureFlag` | 13.72MB | 644.16MB | 381.98MB | 0B |

**Total FF alloc (current snapshot):** 72.42MB  |  **24h avg:** 1.94GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1093 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1093 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 744/1093 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1093 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.78MB | 744/1093 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1093 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.19MB | 532/1093 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.77MB | 15/1093 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1093 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.53MB | 339/1093 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1093 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1093 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1093 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1093 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1093 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.96GB | 717/1093 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1093 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.46GB | 648/1093 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.19GB | 349/1093 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.9GB | 481/1093 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.6x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.8x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.9x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.1x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (4.0x avg)
