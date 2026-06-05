# Overview: prod
*Last updated: 2026-06-06 03:05 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T03:05 (1567 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,823 | avg: 12,455 | max: 84,644 | trend: INCREASING (+1.62/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▄▄▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▃▁▁▁▁▁▁▃▄▃▂▁▁▃▁▂▄▄▁▄█▄▁▁▁▄▇▅▂▁▂▃▁▂▁▆▃▁▁▁▁▁▁▆▃
```

**Heap InUse** (current: 372.4MB | avg: 189.5MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▂▃▁▁▁▂▂▂▁▃▃▁▂▁▁▁▁▂▄▅▁▄▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▅▄▁▂▁▁▂▁▃▅▃▄▁▁▄▂▂▅▅▂▅▇▅▁▁▂▅█▇▃▁▃▄▂▃▂▆▅▂▁▂▃▁▁▅▄
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 22%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,823 | 23,051 | -4228 | 12,455 | 84,644 | INCREASING (+1.62/hr) |
| Heap InUse | 372.4MB | 429.6MB | -57.2MB | 189.5MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 1027.3MB | 1027.8MB | -0.5MB | 2507.7MB | 6883.9MB | |
| Heap Objects | 1,005,587 | 1,211,768 | -206181 | 836,711 | 17,165,538 | |

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
| 2026-06-06 | 38 | 17,754 | 310.9MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 35.68MB |
| 3 | `bufio.NewReaderSize` | 17.07MB |
| 4 | `bufio.NewWriterSize` | 16.59MB |
| 5 | `runtime.mallocgc` | 15.63MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.55MB |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `compress/flate.NewWriter` | 4.41MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 4.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 26.66GB |
| 2 | `segmentio/kafka-go.makePartitions` | 21.47GB |
| 3 | `jackskj/carta.getUniqueId` | 17.43GB |
| 4 | `reflect.growslice` | 16.61GB |
| 5 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 16.32GB |
| 6 | `reflect.unsafe_New` | 14.61GB |
| 7 | `strconv.appendQuotedWith` | 12.87GB |
| 8 | `fmt.Sprint` | 12.87GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.04GB |
| 10 | `fmt.(*buffer).writeString` | 11.23GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.31GB | 1.31GB | 1.21GB | 0B |
| `evaluation.mergeMetadata` | 698.67MB | 697.17MB | 644.67MB | 0B |
| `local.(*Client).EvaluateV2` | 2.02GB | 2.02GB | 1.86GB | 0B |
| `local.topologicalSort` | 294.06MB | 294.06MB | 272.32MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.93GB | 1.92GB | 1.77GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 291.84MB | 291.84MB | 277.43MB | 0B |
| `localEvaluation.getMapOfValue` | 1.93GB | 1.92GB | 1.77GB | 0B |
| `utils.ParseFeatureFlag` | 1.93GB | 1.92GB | 1.77GB | 0B |

**Total FF alloc (current snapshot):** 10.37GB  |  **24h avg:** 9.55GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 92.92MB | 34/1567 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 74.58MB | 54/1567 | `████████████░░░ 80%` |
| 3 | `database/sql.convertAssignRows` | 39.57MB | 67/1567 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1218/1567 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1567 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.11MB | 1218/1567 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.1MB | 960/1567 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1567 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1567 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1567 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1567 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1567 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1567 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1567 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1567 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1567 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1567 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1567 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 9.98GB | 751/1567 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.91GB | 279/1567 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
