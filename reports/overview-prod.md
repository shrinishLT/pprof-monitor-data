# Overview: prod
*Last updated: 2026-06-04 10:36 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T10:35 (1082 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 49,577 | avg: 10,677 | max: 84,644 | trend: decreasing (-23.18/hr))
```
▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▄▅▃▅█
```

**Heap InUse** (current: 1231.0MB | avg: 159.5MB | max: 2823.8MB | trend: stable (-0.33MB/hr))
```
▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▂▃
```

## Current Status

Goroutines: `███████████░░░░░░░░░ 58%`
Heap InUse: `███░░░░░░░░░░░░░░░░░ 17%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 49,577 | 34,990 | +14587 | 10,677 | 84,644 | decreasing (-23.18/hr) |
| Heap InUse | 1231.0MB | 836.8MB | +394.2MB | 159.5MB | 2823.8MB | stable (-0.33MB/hr) |
| Heap Sys | 4999.3MB | 5046.6MB | -47.3MB | 2628.2MB | 6883.9MB | |
| Heap Objects | 5,916,215 | 4,031,459 | +1884756 | 687,141 | 14,090,816 | |

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
| 2026-06-04 | 128 | 16,103 | 255.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 171.85MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 82.88MB |
| 3 | `bufio.NewWriterSize` | 60.25MB |
| 4 | `bufio.NewReaderSize` | 60.24MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 26.28MB |
| 7 | `aes/gcm.NewGCMForTLS13` | 22.02MB |
| 8 | `crypto/tls.Client` | 19.52MB |
| 9 | `net/http.(*Transport).tryPutIdleConn` | 16.51MB |
| 10 | `net/http.(*Transport).queueForIdleConn` | 15.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 48.67GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 19.21GB |
| 3 | `reflect.growslice` | 15.77GB |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 14.27GB |
| 5 | `jackskj/carta.getUniqueId` | 13.93GB |
| 6 | `reflect.unsafe_New` | 12.47GB |
| 7 | `fmt.(*buffer).writeString` | 9.32GB |
| 8 | `carta/value.NewCell` | 8.89GB |
| 9 | `go-sql-driver/mysql.(*binaryRows).readRow` | 8.41GB |
| 10 | `segmentio/kafka-go.makePartitions` | 6.91GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 336.73MB | 328.14MB | 193.89MB | 0B |
| `evaluation.mergeMetadata` | 173.04MB | 168.54MB | 101.78MB | 0B |
| `local.(*Client).EvaluateV2` | 523.92MB | 509.65MB | 294.52MB | 0B |
| `local.topologicalSort` | 78.99MB | 75.45MB | 41.22MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 525.99MB | 514.75MB | 294.92MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 48.57MB | 44.52MB | 28.80MB | 0B |
| `localEvaluation.getMapOfValue` | 525.99MB | 514.75MB | 294.92MB | 0B |
| `utils.ParseFeatureFlag` | 526.49MB | 515.25MB | 295.39MB | 0B |

**Total FF alloc (current snapshot):** 2.68GB  |  **24h avg:** 1.51GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 62.4MB | 37/1082 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 54.44MB | 22/1082 | `█████████████░░ 87%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 733/1082 | `████████░░░░░░░ 58%` |
| 4 | `database/sql.convertAssignRows` | 31.23MB | 46/1082 | `███████░░░░░░░░ 50%` |
| 5 | `runtime.mallocgc` | 20.62MB | 733/1082 | `████░░░░░░░░░░░ 33%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1082 | `████░░░░░░░░░░░ 28%` |
| 7 | `bytes.growSlice` | 14.0MB | 522/1082 | `███░░░░░░░░░░░░ 22%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1082 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `net/http.(*Transport).dialConn` | 9.95MB | 11/1082 | `██░░░░░░░░░░░░░ 15%` |
| 10 | `dotlapse-event-service/project.ConsolidateTagsIntoProjects` | 9.43MB | 24/1082 | `██░░░░░░░░░░░░░ 15%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1082 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1082 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1082 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1082 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1082 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.94GB | 706/1082 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1082 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 19.49GB | 637/1082 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `fmt.Sprintf` | 13.22GB | 347/1082 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `segmentio/kafka-go.makePartitions` | 12.0GB | 472/1082 | `█░░░░░░░░░░░░░░ 9%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.9x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.9x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.7x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.0x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.6x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.0x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (3.1x avg)
- Heap spike to 408.3MB at 2026-05-18T16:02 (2.6x avg)
- Heap spike to 424.1MB at 2026-05-18T18:33 (2.7x avg)
