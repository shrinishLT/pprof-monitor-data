# Overview: prod
*Last updated: 2026-06-04 10:45 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:45 (1084 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 59,354 | avg: 10,763 | max: 84,644 | trend: decreasing (-22.10/hr))
```
▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▄▆▇█
```

**Heap InUse** (current: 1253.0MB | avg: 161.7MB | max: 2823.8MB | trend: stable (-0.30MB/hr))
```
▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▂▃▄▃
```

## Current Status

Goroutines: `██████████████░░░░░░ 70%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 18%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 59,354 | 55,625 | +3729 | 10,763 | 84,644 | decreasing (-22.10/hr) |
| Heap InUse | 1253.0MB | 1375.2MB | -122.2MB | 161.7MB | 2823.8MB | stable (-0.30MB/hr) |
| Heap Sys | 4954.0MB | 4978.3MB | -24.3MB | 2632.5MB | 6883.9MB | |
| Heap Objects | 4,440,397 | 6,634,489 | -2194092 | 696,090 | 14,090,816 | |

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
| 2026-06-04 | 130 | 16,740 | 271.6MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 239.25MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 112.52MB |
| 3 | `bufio.NewReaderSize` | 86.85MB |
| 4 | `bufio.NewWriterSize` | 82.83MB |
| 5 | `aes/gcm.NewGCMForTLS13` | 43.04MB |
| 6 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 7 | `runtime.mallocgc` | 34.36MB |
| 8 | `net/http.(*Transport).queueForIdleConn` | 29.03MB |
| 9 | `crypto/tls.Client` | 27.02MB |
| 10 | `net/http.(*Transport).dialConn` | 25.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 17.34GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 16.35GB |
| 5 | `jackskj/carta.getUniqueId` | 15.26GB |
| 6 | `reflect.unsafe_New` | 13.75GB |
| 7 | `fmt.(*buffer).writeString` | 10.29GB |
| 8 | `carta/value.NewCell` | 9.79GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.63GB |
| 10 | `segmentio/kafka-go.makePartitions` | 7.12GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 348.50MB | 343.79MB | 204.80MB | 0B |
| `evaluation.mergeMetadata` | 177.54MB | 176.54MB | 107.23MB | 0B |
| `local.(*Client).EvaluateV2` | 544.03MB | 537.20MB | 311.81MB | 0B |
| `local.topologicalSort` | 81.00MB | 81.00MB | 43.89MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 546.08MB | 540.29MB | 312.37MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 49.61MB | 48.57MB | 30.16MB | 0B |
| `localEvaluation.getMapOfValue` | 546.08MB | 540.29MB | 312.37MB | 0B |
| `utils.ParseFeatureFlag` | 546.58MB | 540.79MB | 312.86MB | 0B |

**Total FF alloc (current snapshot):** 2.77GB  |  **24h avg:** 1.60GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1084 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1084 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 735/1084 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1084 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.65MB | 735/1084 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1084 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 14.76MB | 524/1084 | `███░░░░░░░░░░░░ 23%` |
| 8 | `net/http.(*Transport).dialConn` | 11.96MB | 13/1084 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1084 | `██░░░░░░░░░░░░░ 16%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1084 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1084 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1084 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1084 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1084 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1084 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.96GB | 708/1084 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1084 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 639/1084 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1084 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 11.98GB | 474/1084 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.9x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.0x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.0x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.0x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.5x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.6x avg)
