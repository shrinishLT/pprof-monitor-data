# Overview: prod
*Last updated: 2026-06-06 01:55 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T01:55 (1553 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,376 | avg: 12,412 | max: 84,644 | trend: INCREASING (+1.33/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▄▄▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▃▁▁▁▁▁▁▃▄▃▂▁▁▃▁▂▄▄▁▄█▄▁▁▁▄▇▅▂▁▂
```

**Heap InUse** (current: 303.5MB | avg: 188.6MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▁▁▂▁▁▂▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▂▃▁▁▁▂▂▂▁▃▃▁▂▁▁▁▁▂▄▅▁▄▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▁▅▄▁▂▁▁▂▁▃▅▃▄▁▁▄▂▂▅▅▂▅▇▅▁▁▂▅█▇▃▁▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 19%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,376 | 14,485 | +1891 | 12,412 | 84,644 | INCREASING (+1.33/hr) |
| Heap InUse | 303.5MB | 163.3MB | +140.2MB | 188.6MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 1027.2MB | 1027.6MB | -0.4MB | 2521.0MB | 6883.9MB | |
| Heap Objects | 1,524,758 | 639,006 | +885752 | 834,880 | 17,165,538 | |

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
| 2026-06-06 | 24 | 18,074 | 325.3MB | 565.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 16.35MB |
| 3 | `runtime.mallocgc` | 15.63MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `bufio.NewReaderSize` | 6.54MB |
| 7 | `bufio.NewWriterSize` | 6.05MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 6.03MB |
| 9 | `reflect.mapassign_faststr0` | 3.5MB |
| 10 | `net/http.(*http2Framer).startWriteDataPadded` | 2.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 23.83GB |
| 2 | `segmentio/kafka-go.makePartitions` | 19.87GB |
| 3 | `jackskj/carta.getUniqueId` | 15.9GB |
| 4 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 15.29GB |
| 5 | `reflect.growslice` | 14.95GB |
| 6 | `reflect.unsafe_New` | 13.15GB |
| 7 | `strconv.appendQuotedWith` | 11.48GB |
| 8 | `fmt.Sprint` | 11.48GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 11.14GB |
| 10 | `fmt.(*buffer).writeString` | 10.35GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.26GB | 1.26GB | 1.14GB | 0B |
| `evaluation.mergeMetadata` | 671.67MB | 669.66MB | 602.88MB | 0B |
| `local.(*Client).EvaluateV2` | 1.94GB | 1.93GB | 1.75GB | 0B |
| `local.topologicalSort` | 283.42MB | 280.88MB | 256.69MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.84GB | 1.83GB | 1.65GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 285.16MB | 284.66MB | 266.66MB | 0B |
| `localEvaluation.getMapOfValue` | 1.84GB | 1.83GB | 1.65GB | 0B |
| `utils.ParseFeatureFlag` | 1.85GB | 1.84GB | 1.66GB | 0B |

**Total FF alloc (current snapshot):** 9.94GB  |  **24h avg:** 8.96GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 92.92MB | 34/1553 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 74.58MB | 54/1553 | `████████████░░░ 80%` |
| 3 | `database/sql.convertAssignRows` | 39.57MB | 67/1553 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1204/1553 | `█████░░░░░░░░░░ 39%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1553 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.12MB | 1204/1553 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.03MB | 946/1553 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1553 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.2MB | 27/1553 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1553 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1553 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1553 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1553 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1553 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1553 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1553 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1553 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1553 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.8GB | 265/1553 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.68GB | 737/1553 | `█░░░░░░░░░░░░░░ 7%` |

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
