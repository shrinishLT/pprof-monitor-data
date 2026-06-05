# Overview: prod
*Last updated: 2026-06-05 21:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-05T21:45 (1503 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,392 | avg: 12,277 | max: 84,644 | trend: stable (+0.35/hr))
```
▂▂▂▂▂▁▂▁▁▁▂▂▂▂▃▃▂▂▁▂▁▁▁▁▂▁▁▂▅▅▄▃▅▆▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▂▂▂▁▁▁▁▂▃▂▂▂▁▂▁▃█▆▁
```

**Heap InUse** (current: 168.8MB | avg: 186.3MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▃▃▃▃▂▁▂▂▁▁▃▃▂▃▂▂▂▃▁▃▁▂▁▁▂▂▁▁▄▅▄▃▅▅▅▄▁▃▁▂▁▁▁▁▂▂▁▂▁▁▁▂▃▂▂▂▂▁▂▁▂▂▃▁▁▁▁▁▁▂▂▂▂▂▂▃▄▂▂▁▂▃▂▁▄▄▂▃▁▂▂▁▃▆█▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,392 | 19,547 | -5155 | 12,277 | 84,644 | stable (+0.35/hr) |
| Heap InUse | 168.8MB | 439.3MB | -270.5MB | 186.3MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1036.3MB | 1026.4MB | +9.9MB | 2570.5MB | 6883.9MB | |
| Heap Objects | 675,134 | 1,997,063 | -1321929 | 826,228 | 17,165,538 | |

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
| 2026-06-05 | 261 | 16,068 | 243.5MB | 3154.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.04MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `compress/flate.NewWriter` | 4.41MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.52MB |
| 8 | `bufio.NewWriterSize` | 3.04MB |
| 9 | `segmentio/kafka-go.makePartitions` | 2.53MB |
| 10 | `bufio.NewReaderSize` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 17.91GB |
| 2 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 14.84GB |
| 3 | `jackskj/carta.getUniqueId` | 14.55GB |
| 4 | `segmentio/kafka-go.makePartitions` | 14.03GB |
| 5 | `reflect.growslice` | 13.89GB |
| 6 | `reflect.unsafe_New` | 12.09GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.94GB |
| 8 | `fmt.(*buffer).writeString` | 9.89GB |
| 9 | `strconv.appendQuotedWith` | 8.65GB |
| 10 | `carta/value.NewCell` | 8.61GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1010.04MB | 1004.99MB | 815.03MB | 0B |
| `evaluation.mergeMetadata` | 516.13MB | 514.63MB | 417.27MB | 0B |
| `local.(*Client).EvaluateV2` | 1.52GB | 1.52GB | 1.23GB | 0B |
| `local.topologicalSort` | 224.09MB | 224.09MB | 180.07MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.43GB | 1.42GB | 1.16GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 240.73MB | 240.73MB | 194.85MB | 0B |
| `localEvaluation.getMapOfValue` | 1.43GB | 1.42GB | 1.16GB | 0B |
| `utils.ParseFeatureFlag` | 1.43GB | 1.43GB | 1.16GB | 0B |

**Total FF alloc (current snapshot):** 7.76GB  |  **24h avg:** 6.27GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1503 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1503 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1503 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1154/1503 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1503 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.33MB | 1154/1503 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.85MB | 906/1503 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1503 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1503 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1503 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1503 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1503 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1503 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1503 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1503 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1503 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1503 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1503 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.54GB | 215/1503 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 8.94GB | 687/1503 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.9x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.1x avg)
