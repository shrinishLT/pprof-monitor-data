# Overview: prod
*Last updated: 2026-06-07 10:25 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T10:25 (1943 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 68,680 | avg: 13,083 | max: 84,644 | trend: INCREASING (+4.00/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█▆
```

**Heap InUse** (current: 1912.0MB | avg: 192.8MB | max: 3154.1MB | trend: stable (+0.04MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▅█▇
```

## Current Status

Goroutines: `████████████████░░░░ 81%`
Heap InUse: `█████░░░░░░░░░░░░░░░ 27%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 68,680 | 83,591 | -14911 | 13,083 | 84,644 | INCREASING (+4.00/hr) |
| Heap InUse | 1912.0MB | 1942.9MB | -30.9MB | 192.8MB | 3154.1MB | stable (+0.04MB/hr) |
| Heap Sys | 2653.7MB | 2396.5MB | +257.2MB | 2228.2MB | 6883.9MB | |
| Heap Objects | 8,231,486 | 8,199,828 | +31658 | 872,992 | 17,165,538 | |

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
| 2026-06-07 | 126 | 16,002 | 203.9MB | 1942.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 279.38MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 128.59MB |
| 3 | `bufio.NewWriterSize` | 119.96MB |
| 4 | `bufio.NewReaderSize` | 108.91MB |
| 5 | `runtime.mallocgc` | 49.47MB |
| 6 | `aes/gcm.NewGCMForTLS13` | 47.54MB |
| 7 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 30.03MB |
| 9 | `crypto/tls.Client` | 21.52MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 21.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 29.0GB |
| 2 | `reflect.growslice` | 24.71GB |
| 3 | `jackskj/carta.getUniqueId` | 20.39GB |
| 4 | `reflect.unsafe_New` | 18.99GB |
| 5 | `fmt.(*buffer).writeString` | 15.41GB |
| 6 | `reflect.unsafe_NewArray` | 14.75GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 14.27GB |
| 8 | `carta/value.NewCell` | 13.47GB |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 11.08GB |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.07GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 785.61MB | 784.60MB | 688.54MB | 0B |
| `evaluation.mergeMetadata` | 405.60MB | 405.10MB | 357.98MB | 0B |
| `local.(*Client).EvaluateV2` | 1.16GB | 1.16GB | 1.02GB | 0B |
| `local.topologicalSort` | 161.45MB | 160.44MB | 143.70MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 1.20GB | 1.19GB | 1.04GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 93.52MB | 93.52MB | 91.08MB | 0B |
| `localEvaluation.getMapOfValue` | 1.20GB | 1.19GB | 1.04GB | 0B |
| `utils.ParseFeatureFlag` | 1.20GB | 1.20GB | 1.04GB | 0B |

**Total FF alloc (current snapshot):** 6.18GB  |  **24h avg:** 5.38GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1943 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1943 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1594/1943 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1943 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1943 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.63MB | 1594/1943 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 15.16MB | 1173/1943 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 13.31MB | 34/1943 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1943 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 10.48MB | 38/1943 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1943 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1943 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1943 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1943 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1943 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1943 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/1943 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1943 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1943 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.35GB | 460/1943 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (9.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.1x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.4x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.6x avg)
