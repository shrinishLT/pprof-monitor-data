# Overview: prod
*Last updated: 2026-06-06 04:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T04:01 (1578 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,361 | avg: 12,470 | max: 84,644 | trend: INCREASING (+1.71/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▄▄▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▃▁▁▁▁▁▁▃▄▃▂▁▁▃▁▂▄▄▁▄█▄▁▁▁▄▇▅▂▁▂▃▁▂▁▆▃▁▁▁▁▁▁▆▃▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 147.2MB | avg: 189.5MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▂▃▁▁▁▂▂▂▁▃▃▁▂▁▁▁▁▂▄▅▁▄▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▅▄▁▂▁▁▂▁▃▅▃▄▁▁▄▂▂▅▅▂▅▇▅▁▁▂▅█▇▃▁▃▄▂▃▂▆▅▂▁▂▃▁▁▅▄▂▂▂▁▂▁▂▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,361 | 14,381 | -20 | 12,470 | 84,644 | INCREASING (+1.71/hr) |
| Heap InUse | 147.2MB | 165.8MB | -18.6MB | 189.5MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 1036.2MB | 1036.0MB | +0.2MB | 2497.4MB | 6883.9MB | |
| Heap Objects | 474,705 | 780,797 | -306092 | 837,804 | 17,165,538 | |

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
| 2026-06-06 | 49 | 17,077 | 286.2MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 5 | `compress/flate.NewWriter` | 5.29MB |
| 6 | `reflect.unsafe_NewArray` | 3.02MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.0MB |
| 9 | `bufio.NewWriterSize` | 1.53MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 27.03GB |
| 2 | `segmentio/kafka-go.makePartitions` | 22.69GB |
| 3 | `jackskj/carta.getUniqueId` | 17.51GB |
| 4 | `reflect.growslice` | 16.68GB |
| 5 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 16.35GB |
| 6 | `reflect.unsafe_New` | 14.68GB |
| 7 | `fmt.Sprint` | 13.05GB |
| 8 | `strconv.appendQuotedWith` | 13.05GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.04GB |
| 10 | `reflect.unsafe_NewArray` | 11.6GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.36GB | 1.36GB | 1.26GB | 0B |
| `evaluation.mergeMetadata` | 722.18MB | 719.18MB | 671.85MB | 0B |
| `local.(*Client).EvaluateV2` | 2.09GB | 2.09GB | 1.94GB | 0B |
| `local.topologicalSort` | 305.19MB | 303.67MB | 283.18MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.00GB | 1.99GB | 1.85GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 298.52MB | 297.98MB | 284.73MB | 0B |
| `localEvaluation.getMapOfValue` | 2.00GB | 1.99GB | 1.85GB | 0B |
| `utils.ParseFeatureFlag` | 2.00GB | 1.99GB | 1.85GB | 0B |

**Total FF alloc (current snapshot):** 10.74GB  |  **24h avg:** 9.96GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 92.92MB | 34/1578 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 74.58MB | 54/1578 | `████████████░░░ 80%` |
| 3 | `database/sql.convertAssignRows` | 39.57MB | 67/1578 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1229/1578 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1578 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.09MB | 1229/1578 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.01MB | 970/1578 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1578 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1578 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1578 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1578 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1578 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1578 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1578 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1578 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1578 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1578 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1578 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 10.22GB | 762/1578 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.99GB | 290/1578 | `█░░░░░░░░░░░░░░ 7%` |

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
