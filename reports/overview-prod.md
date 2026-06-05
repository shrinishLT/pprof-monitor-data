# Overview: prod
*Last updated: 2026-06-06 00:35 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T00:35 (1537 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,607 | avg: 12,348 | max: 84,644 | trend: INCREASING (+0.87/hr))
```
▁▂▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▁▁▁▁▁▂▂▂▁▁▁▂▁▃▇▆▁▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▄▁▁▁▁▁▁▄▆▅▃▁▁▅▂
```

**Heap InUse** (current: 224.8MB | avg: 186.9MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▅▄▁▃▁▂▁▁▁▁▂▂▁▂▁▁▁▂▃▂▂▂▂▁▂▁▂▂▃▁▁▁▁▁▁▂▂▂▂▂▂▃▄▂▂▁▂▃▂▁▄▄▂▃▁▂▂▁▃▆█▁▆▁▁▁▂▂▁▁▁▁▂▂▂▂▁▁▂▁▇▅▁▂▁▁▂▁▅▆▅▅▂▁▅▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,607 | 18,698 | -3091 | 12,348 | 84,644 | INCREASING (+0.87/hr) |
| Heap InUse | 224.8MB | 328.7MB | -103.9MB | 186.9MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 1041.9MB | 1040.8MB | +1.1MB | 2536.6MB | 6883.9MB | |
| Heap Objects | 776,707 | 1,315,848 | -539141 | 829,266 | 17,165,538 | |

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
| 2026-06-06 | 8 | 17,078 | 278.6MB | 390.5MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 17.08MB |
| 3 | `runtime.mallocgc` | 11.51MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 5.53MB |
| 7 | `bufio.NewWriterSize` | 4.56MB |
| 8 | `bufio.NewReaderSize` | 3.03MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 3.0MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `fmt.Sprintf` | 20.3GB |
| 2 | `segmentio/kafka-go.makePartitions` | 17.96GB |
| 3 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 15.08GB |
| 4 | `jackskj/carta.getUniqueId` | 14.95GB |
| 5 | `reflect.growslice` | 14.16GB |
| 6 | `reflect.unsafe_New` | 12.4GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 10.96GB |
| 8 | `fmt.(*buffer).writeString` | 9.94GB |
| 9 | `strconv.appendQuotedWith` | 9.81GB |
| 10 | `fmt.Sprint` | 9.77GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.19GB | 1.18GB | 1.04GB | 0B |
| `evaluation.mergeMetadata` | 631.16MB | 627.15MB | 549.86MB | 0B |
| `local.(*Client).EvaluateV2` | 1.82GB | 1.81GB | 1.61GB | 0B |
| `local.topologicalSort` | 263.12MB | 262.10MB | 236.93MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.72GB | 1.71GB | 1.51GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 272.92MB | 272.38MB | 251.49MB | 0B |
| `localEvaluation.getMapOfValue` | 1.72GB | 1.71GB | 1.51GB | 0B |
| `utils.ParseFeatureFlag` | 1.73GB | 1.72GB | 1.52GB | 0B |

**Total FF alloc (current snapshot):** 9.32GB  |  **24h avg:** 8.22GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.46MB | 33/1537 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 75.91MB | 53/1537 | `███████████░░░░ 79%` |
| 3 | `database/sql.convertAssignRows` | 40.13MB | 66/1537 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1188/1537 | `█████░░░░░░░░░░ 38%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1537 | `██░░░░░░░░░░░░░ 18%` |
| 6 | `runtime.mallocgc` | 17.16MB | 1188/1537 | `██░░░░░░░░░░░░░ 17%` |
| 7 | `bytes.growSlice` | 14.79MB | 931/1537 | `██░░░░░░░░░░░░░ 15%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1537 | `█░░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.4MB | 26/1537 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1537 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1537 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1537 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1537 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1537 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1537 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1537 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1537 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1537 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 9.73GB | 249/1537 | `█░░░░░░░░░░░░░░ 7%` |
| 10 | `fmt.Sprintf` | 9.41GB | 721/1537 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.9x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.3x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.6x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.2x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.2x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
