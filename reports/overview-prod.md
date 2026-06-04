# Overview: prod
*Last updated: 2026-06-04 15:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T15:10 (1137 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 20,047 | avg: 11,078 | max: 84,644 | trend: decreasing (-15.99/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 451.7MB | avg: 168.2MB | max: 2823.8MB | trend: stable (-0.20MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▂▂▁▁▁▂▂▂▁▁▁▁▂▁▁▁▁▃▁▂▂▁▂▂▂
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 23%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 6%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 20,047 | 18,685 | +1362 | 11,078 | 84,644 | decreasing (-15.99/hr) |
| Heap InUse | 451.7MB | 364.6MB | +87.1MB | 168.2MB | 2823.8MB | stable (-0.20MB/hr) |
| Heap Sys | 4148.0MB | 3413.7MB | +734.3MB | 2634.2MB | 6883.9MB | |
| Heap Objects | 2,076,834 | 1,844,112 | +232722 | 724,915 | 14,090,816 | |

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
| 2026-06-04 | 183 | 16,968 | 280.2MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 34.2MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 17.08MB |
| 4 | `bufio.NewWriterSize` | 11.54MB |
| 5 | `bufio.NewReaderSize` | 11.04MB |
| 6 | `runtime.mallocgc` | 11.01MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 4.5MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.5MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 20.09GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 7.94GB |
| 3 | `fmt.Sprintf` | 7.58GB |
| 4 | `reflect.growslice` | 6.02GB |
| 5 | `jackskj/carta.getUniqueId` | 5.8GB |
| 6 | `segmentio/kafka-go.makePartitions` | 5.0GB |
| 7 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 4.99GB |
| 8 | `reflect.unsafe_New` | 4.95GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.22GB |
| 10 | `database/sql.convertAssignRows` | 3.74GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 464.73MB | 450.56MB | 235.25MB | 0B |
| `evaluation.mergeMetadata` | 238.56MB | 229.56MB | 124.50MB | 0B |
| `local.(*Client).EvaluateV2` | 715.55MB | 693.07MB | 355.05MB | 0B |
| `local.topologicalSort` | 101.18MB | 98.65MB | 48.83MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 666.51MB | 648.15MB | 334.87MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 113.50MB | 107.85MB | 52.76MB | 0B |
| `localEvaluation.getMapOfValue` | 666.51MB | 648.15MB | 334.87MB | 0B |
| `utils.ParseFeatureFlag` | 666.51MB | 648.15MB | 334.93MB | 0B |

**Total FF alloc (current snapshot):** 3.55GB  |  **24h avg:** 1.78GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 63.4MB | 39/1137 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1137 | `█████████████░░ 91%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 788/1137 | `████████░░░░░░░ 57%` |
| 4 | `database/sql.convertAssignRows` | 31.76MB | 49/1137 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.2MB | 788/1137 | `████░░░░░░░░░░░ 31%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1137 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.46MB | 575/1137 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1137 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1137 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.47MB | 373/1137 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1137 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1137 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1137 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1137 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1137 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 40.91GB | 761/1137 | `████░░░░░░░░░░░ 32%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1137 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 18.58GB | 685/1137 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 12.51GB | 380/1137 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.18GB | 522/1137 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.6x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.6x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.5x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (4.0x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
