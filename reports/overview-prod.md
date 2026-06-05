# Overview: prod
*Last updated: 2026-06-06 00:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T00:15 (1533 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,939 | avg: 12,338 | max: 84,644 | trend: INCREASING (+0.81/hr))
```
▄▃▄▆▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▁▁▁▂▂▂▁▁▁▂▁▃▇▆▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▁▁▁▁▁▁▄▆▅▃
```

**Heap InUse** (current: 320.6MB | avg: 186.8MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▄▃▅▅▅▄▁▃▁▂▁▁▁▁▂▂▁▂▁▁▁▂▃▂▂▂▂▁▂▁▂▂▃▁▁▁▁▁▁▂▂▂▂▂▂▃▄▂▂▁▂▃▂▁▄▄▂▃▁▂▂▁▃▆█▁▆▁▁▁▂▂▁▁▁▁▂▂▂▂▁▁▂▁▇▅▁▂▁▁▂▁▅▆▅▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,939 | 18,538 | -1599 | 12,338 | 84,644 | INCREASING (+0.81/hr) |
| Heap InUse | 320.6MB | 308.8MB | +11.8MB | 186.8MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1037.8MB | 1036.6MB | +1.2MB | 2540.5MB | 6883.9MB | |
| Heap Objects | 1,461,478 | 1,069,214 | +392264 | 829,037 | 17,165,538 | |

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
| 2026-06-06 | 4 | 18,316 | 333.3MB | 390.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 23.21MB |
| 3 | `bufio.NewWriterSize` | 12.09MB |
| 4 | `runtime.mallocgc` | 11.51MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 9.54MB |
| 6 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 7 | `bufio.NewReaderSize` | 8.04MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 9 | `compress/flate.NewWriter` | 5.29MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 4.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 19.93GB |
| 2 | `segmentio/kafka-go.makePartitions` | 17.51GB |
| 3 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 15.08GB |
| 4 | `jackskj/carta.getUniqueId` | 14.91GB |
| 5 | `reflect.growslice` | 14.14GB |
| 6 | `reflect.unsafe_New` | 12.38GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.96GB |
| 8 | `fmt.(*buffer).writeString` | 9.94GB |
| 9 | `strconv.appendQuotedWith` | 9.63GB |
| 10 | `fmt.Sprint` | 9.61GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.16GB | 1.16GB | 1.02GB | 0B |
| `evaluation.mergeMetadata` | 617.15MB | 616.15MB | 535.38MB | 0B |
| `local.(*Client).EvaluateV2` | 1.79GB | 1.78GB | 1.57GB | 0B |
| `local.topologicalSort` | 260.06MB | 258.56MB | 231.16MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.69GB | 1.68GB | 1.48GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 270.30MB | 268.79MB | 246.35MB | 0B |
| `localEvaluation.getMapOfValue` | 1.69GB | 1.68GB | 1.48GB | 0B |
| `utils.ParseFeatureFlag` | 1.69GB | 1.69GB | 1.48GB | 0B |

**Total FF alloc (current snapshot):** 9.13GB  |  **24h avg:** 8.01GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1533 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1533 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1533 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1184/1533 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1533 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.18MB | 1184/1533 | `██░░░░░░░░░░░░░ 17%` |
| 7 | `bytes.growSlice` | 14.77MB | 929/1533 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1533 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1533 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1533 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1533 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1533 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1533 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1533 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1533 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1533 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1533 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1533 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.71GB | 245/1533 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.35GB | 717/1533 | `█░░░░░░░░░░░░░░ 7%` |

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
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
