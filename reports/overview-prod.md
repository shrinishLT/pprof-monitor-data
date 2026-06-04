# Overview: prod
*Last updated: 2026-06-04 10:40 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:40 (1083 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 55,625 | avg: 10,718 | max: 84,644 | trend: decreasing (-22.66/hr))
```
▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▄▂▄▆█
```

**Heap InUse** (current: 1375.2MB | avg: 160.7MB | max: 2823.8MB | trend: stable (-0.32MB/hr))
```
▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▂▃▄
```

## Current Status

Goroutines: `█████████████░░░░░░░ 65%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 19%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 55,625 | 49,577 | +6048 | 10,718 | 84,644 | decreasing (-22.66/hr) |
| Heap InUse | 1375.2MB | 1231.0MB | +144.2MB | 160.7MB | 2823.8MB | stable (-0.32MB/hr) |
| Heap Sys | 4978.3MB | 4999.3MB | -21.0MB | 2630.4MB | 6883.9MB | |
| Heap Objects | 6,634,489 | 5,916,215 | +718274 | 692,632 | 14,090,816 | |

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
| 2026-06-04 | 129 | 16,410 | 264.0MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 186.49MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 90.42MB |
| 3 | `bufio.NewWriterSize` | 84.83MB |
| 4 | `bufio.NewReaderSize` | 78.31MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 35.03MB |
| 7 | `runtime.mallocgc` | 27.28MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 22.02MB |
| 9 | `net/http.(*Transport).dialConn` | 20.5MB |
| 10 | `crypto/tls.Client` | 17.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 16.5GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 15.2GB |
| 5 | `jackskj/carta.getUniqueId` | 14.57GB |
| 6 | `reflect.unsafe_New` | 13.08GB |
| 7 | `fmt.(*buffer).writeString` | 9.78GB |
| 8 | `carta/value.NewCell` | 9.33GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.5GB |
| 10 | `segmentio/kafka-go.makePartitions` | 7.0GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 343.79MB | 336.73MB | 199.33MB | 0B |
| `evaluation.mergeMetadata` | 176.54MB | 173.04MB | 104.52MB | 0B |
| `local.(*Client).EvaluateV2` | 537.20MB | 523.92MB | 303.14MB | 0B |
| `local.topologicalSort` | 81.00MB | 78.99MB | 42.56MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 540.29MB | 525.99MB | 303.63MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 48.57MB | 48.57MB | 29.48MB | 0B |
| `localEvaluation.getMapOfValue` | 540.29MB | 525.99MB | 303.63MB | 0B |
| `utils.ParseFeatureFlag` | 540.79MB | 526.49MB | 304.11MB | 0B |

**Total FF alloc (current snapshot):** 2.74GB  |  **24h avg:** 1.55GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1083 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1083 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 734/1083 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1083 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.63MB | 734/1083 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1083 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 14.33MB | 523/1083 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).dialConn` | 10.83MB | 12/1083 | `██░░░░░░░░░░░░░ 17%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1083 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1083 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1083 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1083 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1083 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1083 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1083 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.95GB | 707/1083 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1083 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 638/1083 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1083 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.99GB | 473/1083 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.9x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.0x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.0x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.1x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.5x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
