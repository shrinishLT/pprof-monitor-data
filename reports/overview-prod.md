# Overview: prod
*Last updated: 2026-06-04 11:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T11:15 (1090 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,453 | avg: 10,836 | max: 84,644 | trend: decreasing (-20.94/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█▇▃▁▁▁▁
```

**Heap InUse** (current: 186.7MB | avg: 163.4MB | max: 2823.8MB | trend: stable (-0.28MB/hr))
```
▁▂▁▁▁▁▁▁▁▁▁▁▁▂▄▂▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▅▇█▇▆▅▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,453 | 14,348 | +105 | 10,836 | 84,644 | decreasing (-20.94/hr) |
| Heap InUse | 186.7MB | 242.2MB | -55.5MB | 163.4MB | 2823.8MB | stable (-0.28MB/hr) |
| Heap Sys | 5106.5MB | 5106.1MB | +0.4MB | 2645.9MB | 6883.9MB | |
| Heap Objects | 595,559 | 1,396,836 | -801277 | 701,215 | 14,090,816 | |

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
| 2026-06-04 | 136 | 17,060 | 280.4MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 34.36MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `reflect.unsafe_New` | 6.5MB |
| 5 | `jackskj/carta.loadRow` | 6.05MB |
| 6 | `jackskj/carta.getUniqueId` | 4.0MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 8 | `bufio.NewReaderSize` | 3.53MB |
| 9 | `bytes.growSlice` | 3.02MB |
| 10 | `segmentio/kafka-go.makePartitions` | 3.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.7GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.23GB |
| 3 | `reflect.growslice` | 18.47GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 17.95GB |
| 5 | `jackskj/carta.getUniqueId` | 16.43GB |
| 6 | `reflect.unsafe_New` | 14.75GB |
| 7 | `fmt.(*buffer).writeString` | 11.03GB |
| 8 | `carta/value.NewCell` | 10.57GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.83GB |
| 10 | `segmentio/kafka-go.makePartitions` | 7.8GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 395.83MB | 384.04MB | 238.63MB | 0B |
| `evaluation.mergeMetadata` | 204.55MB | 196.55MB | 123.76MB | 0B |
| `local.(*Client).EvaluateV2` | 617.65MB | 599.25MB | 365.03MB | 0B |
| `local.topologicalSort` | 90.60MB | 87.07MB | 51.86MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 618.62MB | 600.24MB | 366.02MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 56.80MB | 54.75MB | 34.44MB | 0B |
| `localEvaluation.getMapOfValue` | 618.62MB | 600.24MB | 366.02MB | 0B |
| `utils.ParseFeatureFlag` | 619.62MB | 601.24MB | 366.55MB | 0B |

**Total FF alloc (current snapshot):** 3.15GB  |  **24h avg:** 1.87GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1090 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1090 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 741/1090 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1090 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.76MB | 741/1090 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1090 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 15.25MB | 529/1090 | `███░░░░░░░░░░░░ 24%` |
| 8 | `net/http.(*Transport).dialConn` | 12.77MB | 15/1090 | `███░░░░░░░░░░░░ 20%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1090 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.55MB | 338/1090 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1090 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1090 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1090 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1090 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1090 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.0GB | 714/1090 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1090 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 645/1090 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.19GB | 349/1090 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.94GB | 478/1090 | `█░░░░░░░░░░░░░░ 9%` |

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
