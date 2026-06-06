# Overview: prod
*Last updated: 2026-06-06 06:50 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T06:50 (1612 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,864 | avg: 12,522 | max: 84,644 | trend: INCREASING (+1.98/hr))
```
▁▁▁▁▁▅▃▁▁▁▁▁▁▃▄▃▂▁▁▃▁▂▄▄▁▄█▄▁▁▁▄▇▅▂▁▂▃▁▂▂▆▃▁▁▁▁▁▁▆▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁
```

**Heap InUse** (current: 249.2MB | avg: 189.7MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▂▁▁▂▁▅▄▁▂▁▁▂▁▃▅▃▄▁▁▄▂▂▅▅▂▆▇▅▁▁▂▅█▇▃▁▃▄▂▃▂▆▅▃▁▂▃▁▂▅▄▂▂▂▁▂▂▂▂▁▁▁▂▁▁▁▁▁▃▃▁▁▁▁▂▃▁▄▄▁▂▁▁▁▁▂▂▂▂▂▂▂▁▁▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,864 | 14,147 | +717 | 12,522 | 84,644 | INCREASING (+1.98/hr) |
| Heap InUse | 249.2MB | 193.3MB | +55.9MB | 189.7MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 1043.1MB | 1042.8MB | +0.3MB | 2466.7MB | 6883.9MB | |
| Heap Objects | 974,688 | 1,257,650 | -282962 | 838,457 | 17,165,538 | |

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
| 2026-06-06 | 83 | 16,188 | 249.4MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 15.63MB |
| 3 | `bytes.growSlice` | 12.56MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 7 | `bufio.NewReaderSize` | 3.01MB |
| 8 | `reflect.unsafe_NewArray` | 2.51MB |
| 9 | `bufio.NewWriterSize` | 2.51MB |
| 10 | `segmentio/kafka-go.makePartitions` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 29.7GB |
| 2 | `reflect.growslice` | 27.61GB |
| 3 | `segmentio/kafka-go.makePartitions` | 26.56GB |
| 4 | `jackskj/carta.getUniqueId` | 25.67GB |
| 5 | `reflect.unsafe_New` | 22.16GB |
| 6 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 19.03GB |
| 7 | `fmt.(*buffer).writeString` | 18.93GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 18.41GB |
| 9 | `carta/value.NewCell` | 15.74GB |
| 10 | `strconv.appendQuotedWith` | 14.37GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.46GB | 1.46GB | 1.38GB | 0B |
| `evaluation.mergeMetadata` | 773.19MB | 769.69MB | 734.11MB | 0B |
| `local.(*Client).EvaluateV2` | 2.25GB | 2.24GB | 2.13GB | 0B |
| `local.topologicalSort` | 328.99MB | 326.47MB | 309.88MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.16GB | 2.14GB | 2.03GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 313.29MB | 312.77MB | 302.06MB | 0B |
| `localEvaluation.getMapOfValue` | 2.16GB | 2.14GB | 2.03GB | 0B |
| `utils.ParseFeatureFlag` | 2.16GB | 2.15GB | 2.03GB | 0B |

**Total FF alloc (current snapshot):** 11.57GB  |  **24h avg:** 10.92GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1612 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1612 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1612 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1263/1612 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1612 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.05MB | 1263/1612 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.9MB | 991/1612 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1612 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1612 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1612 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1612 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1612 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1612 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1612 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1612 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1612 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1612 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1612 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 11.0GB | 796/1612 | `█░░░░░░░░░░░░░░ 8%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.57GB | 323/1612 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
