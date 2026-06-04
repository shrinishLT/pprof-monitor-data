# Overview: prod
*Last updated: 2026-06-04 10:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:30 (1081 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 34,990 | avg: 10,641 | max: 84,644 | trend: decreasing (-23.65/hr))
```
▁▁▁▁▁▁▁▁▁▁▃▁▁▁▁▁▁▁▁▁▁▁▂▁▂▃▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▆█▄▇
```

**Heap InUse** (current: 836.8MB | avg: 158.5MB | max: 2823.8MB | trend: stable (-0.34MB/hr))
```
▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▂
```

## Current Status

Goroutines: `████████░░░░░░░░░░░░ 41%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 12%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 34,990 | 25,817 | +9173 | 10,641 | 84,644 | decreasing (-23.65/hr) |
| Heap InUse | 836.8MB | 491.7MB | +345.1MB | 158.5MB | 2823.8MB | stable (-0.34MB/hr) |
| Heap Sys | 5046.6MB | 5071.0MB | -24.4MB | 2626.0MB | 6883.9MB | |
| Heap Objects | 4,031,459 | 1,876,366 | +2155093 | 682,304 | 14,090,816 | |

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
| 2026-06-04 | 127 | 15,840 | 247.6MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 136.17MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 55.76MB |
| 3 | `bufio.NewReaderSize` | 48.7MB |
| 4 | `bufio.NewWriterSize` | 47.2MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 22.22MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 19.02MB |
| 8 | `reflect.growslice` | 13.79MB |
| 9 | `net/http.(*Transport).queueForIdleConn` | 11.01MB |
| 10 | `net/http.(*Transport).tryPutIdleConn` | 11.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 14.98GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 13.4GB |
| 5 | `jackskj/carta.getUniqueId` | 13.24GB |
| 6 | `reflect.unsafe_New` | 11.8GB |
| 7 | `fmt.(*buffer).writeString` | 8.82GB |
| 8 | `carta/value.NewCell` | 8.44GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.28GB |
| 10 | `segmentio/kafka-go.makePartitions` | 6.81GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 328.14MB | 322.98MB | 188.52MB | 0B |
| `evaluation.mergeMetadata` | 168.54MB | 167.54MB | 99.06MB | 0B |
| `local.(*Client).EvaluateV2` | 509.65MB | 498.82MB | 285.95MB | 0B |
| `local.topologicalSort` | 75.45MB | 72.92MB | 39.86MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 514.75MB | 504.43MB | 286.29MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 44.52MB | 43.50MB | 28.10MB | 0B |
| `localEvaluation.getMapOfValue` | 514.75MB | 504.43MB | 286.29MB | 0B |
| `utils.ParseFeatureFlag` | 515.25MB | 504.93MB | 286.75MB | 0B |

**Total FF alloc (current snapshot):** 2.61GB  |  **24h avg:** 1.47GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1081 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1081 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 732/1081 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1081 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.62MB | 732/1081 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1081 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 13.7MB | 521/1081 | `███░░░░░░░░░░░░ 21%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1081 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 9.95MB | 11/1081 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1081 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1081 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1081 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1081 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1081 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1081 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.93GB | 705/1081 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1081 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 636/1081 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1081 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.01GB | 471/1081 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.0x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.0x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.6x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.0x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.1x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.7x avg)
