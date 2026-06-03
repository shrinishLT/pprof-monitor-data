# Overview: prod
*Last updated: 2026-06-04 05:16 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T05:16 (1018 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,276 | avg: 10,302 | max: 84,644 | trend: decreasing (-32.60/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆▄▅▄▅▅▅▅▅▅▅▅▄▅▅▅▅▅▄▄▅▄▅▆▅▅▅▅▅▅▅▅▅▅▅▆▅▆▇▅▅▄▅▆▅▅
```

**Heap InUse** (current: 221.5MB | avg: 154.3MB | max: 2823.8MB | trend: stable (-0.46MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,276 | 14,809 | +467 | 10,302 | 84,644 | decreasing (-32.60/hr) |
| Heap InUse | 221.5MB | 201.2MB | +20.3MB | 154.3MB | 2823.8MB | stable (-0.46MB/hr) |
| Heap Sys | 940.5MB | 939.2MB | +1.3MB | 2563.4MB | 6883.9MB | |
| Heap Objects | 713,008 | 567,859 | +145149 | 660,322 | 14,090,816 | |

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
| 2026-06-04 | 64 | 15,576 | 267.8MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.51MB |
| 3 | `bytes.growSlice` | 13.26MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 7.5MB |
| 6 | `reflect.growslice` | 5.09MB |
| 7 | `carta/value.(*Cell).Scan` | 4.0MB |
| 8 | `bufio.NewReaderSize` | 3.51MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 2.51MB |
| 10 | `bufio.NewWriterSize` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 6.45GB |
| 2 | `fmt.Sprintf` | 5.92GB |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 4.79GB |
| 4 | `reflect.growslice` | 4.43GB |
| 5 | `jackskj/carta.getUniqueId` | 4.4GB |
| 6 | `reflect.unsafe_New` | 3.75GB |
| 7 | `fmt.(*buffer).writeString` | 3.52GB |
| 8 | `strconv.appendQuotedWith` | 2.87GB |
| 9 | `fmt.Sprint` | 2.76GB |
| 10 | `carta/value.NewCell` | 2.58GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 43.22MB | 39.18MB | 80.16MB | 0B |
| `evaluation.mergeMetadata` | 24.51MB | 21.50MB | 41.61MB | 0B |
| `local.(*Client).EvaluateV2` | 60.15MB | 55.57MB | 123.77MB | 0B |
| `local.topologicalSort` | 8.58MB | 8.58MB | 19.95MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 66.34MB | 60.73MB | 119.54MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.00MB | 512.14kB | 11.52MB | 0B |
| `localEvaluation.getMapOfValue` | 66.34MB | 60.73MB | 119.54MB | 0B |
| `utils.ParseFeatureFlag` | 66.34MB | 60.73MB | 119.54MB | 0B |

**Total FF alloc (current snapshot):** 336.47MB  |  **24h avg:** 635.65MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 69.34MB | 28/1018 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 62.95MB | 17/1018 | `█████████████░░ 90%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 669/1018 | `███████░░░░░░░░ 52%` |
| 4 | `database/sql.convertAssignRows` | 34.25MB | 36/1018 | `███████░░░░░░░░ 49%` |
| 5 | `runtime.mallocgc` | 21.32MB | 669/1018 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1018 | `███░░░░░░░░░░░░ 25%` |
| 7 | `bytes.growSlice` | 13.35MB | 476/1018 | `██░░░░░░░░░░░░░ 19%` |
| 8 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 11.12MB | 18/1018 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1018 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `net/http.(*Transport).dialConn` | 10.5MB | 9/1018 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1018 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1018 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1018 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1018 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1018 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.53GB | 644/1018 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1018 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.8GB | 582/1018 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.58GB | 336/1018 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.47GB | 441/1018 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.3x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.2x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.8x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.1x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.7x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.2x avg)
- Goroutine spike to 20,625 at 2026-05-18T12:33 (2.0x avg)
