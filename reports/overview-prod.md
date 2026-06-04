# Overview: prod
*Last updated: 2026-06-04 09:51 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T09:51 (1073 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,361 | avg: 10,528 | max: 84,644 | trend: decreasing (-25.45/hr))
```
▂▂▁▄▁▄▂▁▂▂▁▁▁▁▁▁▁▂▇▂▁▁▁▁▁▁▁▁▁▁▄▂▄█▂▁▁▂▄▁▂▂▂▃▁▃▃▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂
```

**Heap InUse** (current: 187.8MB | avg: 156.3MB | max: 2823.8MB | trend: stable (-0.37MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,361 | 15,359 | +2 | 10,528 | 84,644 | decreasing (-25.45/hr) |
| Heap InUse | 187.8MB | 210.0MB | -22.2MB | 156.3MB | 2823.8MB | stable (-0.37MB/hr) |
| Heap Sys | 5126.6MB | 5127.1MB | -0.5MB | 2607.7MB | 6883.9MB | |
| Heap Objects | 862,401 | 1,083,576 | -221175 | 673,495 | 14,090,816 | |

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
| 2026-06-04 | 119 | 15,173 | 233.1MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 12.6MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 7.04MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 7 | `bufio.NewReaderSize` | 3.04MB |
| 8 | `bufio.NewWriterSize` | 3.03MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 9.57GB |
| 4 | `jackskj/carta.getUniqueId` | 8.28GB |
| 5 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 7.53GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 7.5GB |
| 7 | `reflect.unsafe_New` | 7.43GB |
| 8 | `database/sql.convertAssignRows` | 5.99GB |
| 9 | `segmentio/kafka-go.makePartitions` | 5.94GB |
| 10 | `fmt.(*buffer).writeString` | 5.66GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 269.91MB | 259.71MB | 146.16MB | 0B |
| `evaluation.mergeMetadata` | 138.53MB | 134.53MB | 77.74MB | 0B |
| `local.(*Client).EvaluateV2` | 415.19MB | 401.86MB | 219.73MB | 0B |
| `local.topologicalSort` | 59.77MB | 58.76MB | 29.70MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 418.72MB | 405.39MB | 219.53MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 38.92MB | 37.92MB | 22.68MB | 0B |
| `localEvaluation.getMapOfValue` | 418.72MB | 405.39MB | 219.53MB | 0B |
| `utils.ParseFeatureFlag` | 419.22MB | 405.89MB | 219.90MB | 0B |

**Total FF alloc (current snapshot):** 2.13GB  |  **24h avg:** 1.13GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1073 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1073 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 724/1073 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1073 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.66MB | 724/1073 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1073 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 12.9MB | 513/1073 | `███░░░░░░░░░░░░ 20%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1073 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1073 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1073 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1073 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1073 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1073 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1073 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1073 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.87GB | 697/1073 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1073 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.5GB | 628/1073 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1073 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.11GB | 463/1073 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.0x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.0x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.1x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
