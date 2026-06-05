# Overview: prod
*Last updated: 2026-06-06 01:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T01:36 (1549 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 24,712 | avg: 12,398 | max: 84,644 | trend: INCREASING (+1.24/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▄▄▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▃▁▁▁▁▁▁▃▄▃▂▁▁▃▁▂▄▄▁▄█▄▁▁▁▄▇
```

**Heap InUse** (current: 565.8MB | avg: 188.2MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▁▂▁▁▁▁▂▁▁▂▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▂▃▁▁▁▂▂▂▁▃▃▂▂▁▁▁▁▂▄▅▁▄▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▅▄▁▂▁▁▂▁▃▅▃▄▁▁▄▂▂▅▅▂▅▇▅▁▁▂▅█
```

## Current Status

Goroutines: `█████░░░░░░░░░░░░░░░ 29%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 24,712 | 21,075 | +3637 | 12,398 | 84,644 | INCREASING (+1.24/hr) |
| Heap InUse | 565.8MB | 424.5MB | +141.3MB | 188.2MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 1017.5MB | 1021.8MB | -4.3MB | 2524.9MB | 6883.9MB | |
| Heap Objects | 2,397,905 | 1,882,448 | +515457 | 833,797 | 17,165,538 | |

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
| 2026-06-06 | 20 | 18,168 | 325.2MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 53.77MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 27.63MB |
| 4 | `bufio.NewReaderSize` | 27.12MB |
| 5 | `bufio.NewWriterSize` | 23.61MB |
| 6 | `runtime.mallocgc` | 15.63MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 13.01MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 10 | `net/http.(*Transport).dialConn` | 6.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 23.03GB |
| 2 | `segmentio/kafka-go.makePartitions` | 19.41GB |
| 3 | `jackskj/carta.getUniqueId` | 15.28GB |
| 4 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 15.09GB |
| 5 | `reflect.growslice` | 14.31GB |
| 6 | `reflect.unsafe_New` | 12.58GB |
| 7 | `strconv.appendQuotedWith` | 11.1GB |
| 8 | `fmt.Sprint` | 11.08GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.96GB |
| 10 | `fmt.(*buffer).writeString` | 10.02GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.25GB | 1.24GB | 1.12GB | 0B |
| `evaluation.mergeMetadata` | 663.66MB | 660.66MB | 590.29MB | 0B |
| `local.(*Client).EvaluateV2` | 1.91GB | 1.91GB | 1.72GB | 0B |
| `local.topologicalSort` | 280.37MB | 279.36MB | 251.96MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.82GB | 1.81GB | 1.62GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 282.58MB | 281.06MB | 263.07MB | 0B |
| `localEvaluation.getMapOfValue` | 1.82GB | 1.81GB | 1.62GB | 0B |
| `utils.ParseFeatureFlag` | 1.82GB | 1.81GB | 1.63GB | 0B |

**Total FF alloc (current snapshot):** 9.82GB  |  **24h avg:** 8.78GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 92.92MB | 34/1549 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 74.58MB | 54/1549 | `████████████░░░ 80%` |
| 3 | `database/sql.convertAssignRows` | 39.57MB | 67/1549 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1200/1549 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1549 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.13MB | 1200/1549 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.0MB | 942/1549 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1549 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1549 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1549 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1549 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1549 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1549 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1549 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1549 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1549 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1549 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1549 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.79GB | 261/1549 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.61GB | 733/1549 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
