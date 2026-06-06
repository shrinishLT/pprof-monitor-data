# Overview: prod
*Last updated: 2026-06-06 10:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-06T10:20 (1654 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 72,810 | avg: 12,634 | max: 84,644 | trend: INCREASING (+2.64/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄█
```

**Heap InUse** (current: 1650.1MB | avg: 190.9MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▅█
```

## Current Status

Goroutines: `█████████████████░░░ 86%`
Heap InUse: `████░░░░░░░░░░░░░░░░ 23%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 72,810 | 44,111 | +28699 | 12,634 | 84,644 | INCREASING (+2.64/hr) |
| Heap InUse | 1650.1MB | 1034.2MB | +615.9MB | 190.9MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 1985.3MB | 1106.6MB | +878.7MB | 2431.2MB | 6883.9MB | |
| Heap Objects | 7,299,068 | 5,417,174 | +1881894 | 845,331 | 17,165,538 | |

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
| 2026-06-06 | 125 | 16,442 | 245.8MB | 1650.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 280.09MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 136.63MB |
| 3 | `bufio.NewReaderSize` | 126.98MB |
| 4 | `bufio.NewWriterSize` | 118.95MB |
| 5 | `aes/gcm.NewGCMForTLS13` | 44.04MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `runtime.mallocgc` | 34.36MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 30.53MB |
| 9 | `crypto/tls.Client` | 29.02MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 18.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 35.08GB |
| 2 | `jackskj/carta.getUniqueId` | 32.3GB |
| 3 | `fmt.Sprintf` | 32.01GB |
| 4 | `segmentio/kafka-go.makePartitions` | 31.3GB |
| 5 | `reflect.unsafe_New` | 28.39GB |
| 6 | `fmt.(*buffer).writeString` | 23.15GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 22.61GB |
| 8 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 20.5GB |
| 9 | `carta/value.NewCell` | 20.05GB |
| 10 | `reflect.unsafe_NewArray` | 15.98GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.62GB | 1.62GB | 1.54GB | 0B |
| `evaluation.mergeMetadata` | 856.21MB | 854.21MB | 813.68MB | 0B |
| `local.(*Client).EvaluateV2` | 2.48GB | 2.47GB | 2.35GB | 0B |
| `local.topologicalSort` | 355.78MB | 355.27MB | 340.15MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.40GB | 2.39GB | 2.26GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 318.93MB | 318.93MB | 316.31MB | 0B |
| `localEvaluation.getMapOfValue` | 2.40GB | 2.39GB | 2.26GB | 0B |
| `utils.ParseFeatureFlag` | 2.40GB | 2.40GB | 2.27GB | 0B |

**Total FF alloc (current snapshot):** 12.80GB  |  **24h avg:** 12.12GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 90.47MB | 35/1654 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 73.3MB | 55/1654 | `████████████░░░ 81%` |
| 3 | `database/sql.convertAssignRows` | 39.03MB | 68/1654 | `██████░░░░░░░░░ 43%` |
| 4 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1305/1654 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1654 | `██░░░░░░░░░░░░░ 19%` |
| 6 | `runtime.mallocgc` | 17.03MB | 1305/1654 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `bytes.growSlice` | 15.01MB | 1023/1654 | `██░░░░░░░░░░░░░ 16%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1654 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `net/http.(*Transport).dialConn` | 11.41MB | 28/1654 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.66MB | 37/1654 | `█░░░░░░░░░░░░░░ 11%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1654 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1654 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1654 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1654 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1654 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 30.87GB | 1105/1654 | `███░░░░░░░░░░░░ 24%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1654 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.82GB | 928/1654 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `fmt.Sprintf` | 11.97GB | 838/1654 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 11.59GB | 365/1654 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
