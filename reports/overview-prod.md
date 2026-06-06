# Overview: prod
*Last updated: 2026-06-06 10:15 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T10:15 (1653 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 44,111 | avg: 12,598 | max: 84,644 | trend: INCREASING (+2.38/hr))
```
▃▁▁▁▁▁▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄█
```

**Heap InUse** (current: 1034.2MB | avg: 190.0MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▃▃▂▁▁▂▁▁▃▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▂▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃█
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 52%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 15%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 44,111 | 28,409 | +15702 | 12,598 | 84,644 | INCREASING (+2.38/hr) |
| Heap InUse | 1034.2MB | 478.7MB | +555.5MB | 190.0MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 1106.6MB | 1008.5MB | +98.1MB | 2431.4MB | 6883.9MB | |
| Heap Objects | 5,417,174 | 2,059,540 | +3357634 | 841,426 | 17,165,538 | |

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
| 2026-06-06 | 124 | 15,988 | 234.4MB | 1034.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 120.6MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 63.79MB |
| 3 | `bufio.NewWriterSize` | 53.71MB |
| 4 | `bufio.NewReaderSize` | 46.17MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 19.51MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 18.52MB |
| 8 | `net/http.(*Transport).dialConn` | 17.0MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 16.01MB |
| 10 | `crypto/tls.Client` | 11.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 33.62GB |
| 2 | `fmt.Sprintf` | 31.64GB |
| 3 | `segmentio/kafka-go.makePartitions` | 31.2GB |
| 4 | `jackskj/carta.getUniqueId` | 31.04GB |
| 5 | `reflect.unsafe_New` | 27.18GB |
| 6 | `fmt.(*buffer).writeString` | 22.27GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 21.27GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 20.09GB |
| 9 | `carta/value.NewCell` | 19.22GB |
| 10 | `reflect.unsafe_NewArray` | 15.92GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.62GB | 1.61GB | 1.53GB | 0B |
| `evaluation.mergeMetadata` | 854.21MB | 851.21MB | 811.69MB | 0B |
| `local.(*Client).EvaluateV2` | 2.47GB | 2.47GB | 2.35GB | 0B |
| `local.topologicalSort` | 355.27MB | 354.76MB | 339.43MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.39GB | 2.39GB | 2.26GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 318.93MB | 318.93MB | 316.09MB | 0B |
| `localEvaluation.getMapOfValue` | 2.39GB | 2.39GB | 2.26GB | 0B |
| `utils.ParseFeatureFlag` | 2.40GB | 2.39GB | 2.26GB | 0B |

**Total FF alloc (current snapshot):** 12.77GB  |  **24h avg:** 12.09GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1653 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1653 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1653 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1304/1653 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1653 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.01MB | 1304/1653 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 14.75MB | 1022/1653 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1653 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.41MB | 28/1653 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1653 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1653 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1653 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1653 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1653 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1653 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1653 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1653 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1653 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 11.94GB | 837/1653 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 11.56GB | 364/1653 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Goroutine spike to 25,220 at 2026-05-20T02:02 (2.0x avg)
