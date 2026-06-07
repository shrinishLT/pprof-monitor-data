# Overview: prod
*Last updated: 2026-06-07 10:20 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T10:20 (1942 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 83,591 | avg: 13,054 | max: 84,644 | trend: INCREASING (+3.83/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█
```

**Heap InUse** (current: 1942.9MB | avg: 191.9MB | max: 3154.1MB | trend: stable (+0.03MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█
```

## Current Status

Goroutines: `███████████████████░ 98%`
Heap InUse: `█████░░░░░░░░░░░░░░░ 28%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 83,591 | 57,155 | +26436 | 13,054 | 84,644 | INCREASING (+3.83/hr) |
| Heap InUse | 1942.9MB | 1342.8MB | +600.1MB | 191.9MB | 3154.1MB | stable (+0.03MB/hr) |
| Heap Sys | 2396.5MB | 1643.8MB | +752.7MB | 2228.0MB | 6883.9MB | |
| Heap Objects | 8,199,828 | 5,985,618 | +2214210 | 869,203 | 17,165,538 | |

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
| 2026-06-06 | 288 | 15,841 | 221.6MB | 1932.8MB |
| 2026-06-07 | 125 | 15,580 | 190.2MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 333.15MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 157.73MB |
| 3 | `bufio.NewWriterSize` | 146.06MB |
| 4 | `bufio.NewReaderSize` | 143.05MB |
| 5 | `aes/gcm.NewGCMForTLS13` | 58.05MB |
| 6 | `runtime.mallocgc` | 45.97MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `crypto/tls.Client` | 32.03MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 28.53MB |
| 10 | `net/http.(*Transport).dialConn` | 28.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 28.89GB |
| 2 | `reflect.growslice` | 23.67GB |
| 3 | `jackskj/carta.getUniqueId` | 19.46GB |
| 4 | `reflect.unsafe_New` | 18.13GB |
| 5 | `fmt.(*buffer).writeString` | 14.79GB |
| 6 | `reflect.unsafe_NewArray` | 14.69GB |
| 7 | `carta/value.NewCell` | 12.85GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.84GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 11.08GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 784.60MB | 779.50MB | 684.42MB | 0B |
| `evaluation.mergeMetadata` | 405.10MB | 402.60MB | 355.94MB | 0B |
| `local.(*Client).EvaluateV2` | 1.16GB | 1.15GB | 1.02GB | 0B |
| `local.topologicalSort` | 160.44MB | 158.39MB | 142.92MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.19GB | 1.18GB | 1.03GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 93.52MB | 93.52MB | 90.85MB | 0B |
| `localEvaluation.getMapOfValue` | 1.19GB | 1.18GB | 1.03GB | 0B |
| `utils.ParseFeatureFlag` | 1.20GB | 1.18GB | 1.03GB | 0B |

**Total FF alloc (current snapshot):** 6.15GB  |  **24h avg:** 5.35GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1942 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1942 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1593/1942 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1942 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1942 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.61MB | 1593/1942 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.94MB | 1172/1942 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.31MB | 34/1942 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1942 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/1942 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1942 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1942 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1942 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1942 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1942 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1942 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/1942 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1942 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1942 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.35GB | 459/1942 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
