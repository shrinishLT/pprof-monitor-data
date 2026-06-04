# Overview: prod
*Last updated: 2026-06-04 22:10 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T22:10 (1221 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,093 | avg: 11,420 | max: 84,644 | trend: decreasing (-9.78/hr))
```
▃▃▂▁▂▃▅▆▄▄▅▆▄▃▂▄▅▂▂▁▂▃▂▁▁▃▄▄▄▄▇▃▁▂▃▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▃▂▂▂▃▄▅▄▂▂▃▁▂▁▁▁▁▁▁▃▅█▇▅▆▁▂▂▁
```

**Heap InUse** (current: 219.6MB | avg: 173.4MB | max: 2823.8MB | trend: stable (-0.11MB/hr))
```
▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂▂▂▂▁▂▁▁▁▁▁▂▃▄▄▃▄▂▁▁▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,093 | 15,316 | -223 | 11,420 | 84,644 | decreasing (-9.78/hr) |
| Heap InUse | 219.6MB | 209.6MB | +10.0MB | 173.4MB | 2823.8MB | stable (-0.11MB/hr) |
| Heap Sys | 3845.2MB | 3844.8MB | +0.4MB | 2663.2MB | 6883.9MB | |
| Heap Objects | 1,018,481 | 843,628 | +174853 | 749,806 | 14,090,816 | |

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
| 2026-06-04 | 267 | 16,677 | 269.1MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 12.12MB |
| 3 | `runtime.mallocgc` | 12.01MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `segmentio/kafka-go.makePartitions` | 6.01MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `bufio.NewReaderSize` | 5.03MB |
| 8 | `bufio.NewWriterSize` | 4.03MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 15.15GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 12.38GB |
| 3 | `fmt.Sprintf` | 7.62GB |
| 4 | `segmentio/kafka-go.makePartitions` | 6.99GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 6.03GB |
| 6 | `database/sql.convertAssignRows` | 4.5GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 4.28GB |
| 8 | `strconv.appendQuotedWith` | 3.82GB |
| 9 | `fmt.Sprint` | 3.72GB |
| 10 | `jackskj/carta.getUniqueId` | 3.68GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 591.61MB | 584.48MB | 383.09MB | 0B |
| `evaluation.mergeMetadata` | 306.57MB | 304.07MB | 197.57MB | 0B |
| `local.(*Client).EvaluateV2` | 919.16MB | 908.42MB | 600.26MB | 0B |
| `local.topologicalSort` | 125.44MB | 122.91MB | 84.11MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 807.23MB | 798.56MB | 531.21MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 193.42MB | 190.32MB | 123.68MB | 0B |
| `localEvaluation.getMapOfValue` | 807.23MB | 798.56MB | 531.21MB | 0B |
| `utils.ParseFeatureFlag` | 807.73MB | 799.06MB | 531.37MB | 0B |

**Total FF alloc (current snapshot):** 4.45GB  |  **24h avg:** 2.91GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1221 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1221 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 872/1221 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1221 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.34MB | 872/1221 | `████░░░░░░░░░░░ 29%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1221 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.34MB | 658/1221 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1221 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1221 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1221 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1221 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1221 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1221 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1221 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1221 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 37.99GB | 844/1221 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1221 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.08GB | 767/1221 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.12GB | 463/1221 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.22GB | 605/1221 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.8x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
