# Overview: prod
*Last updated: 2026-06-17 04:26 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T04:26 (4746 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 32,175 | avg: 14,881 | max: 84,644 | trend: INCREASING (+2.14/hr))
```
▂▃▂▂▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▄▂▁▁▁▁▁▁▁▁▁▂▁▄▁▁▁▁▁▂▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▄█
```

**Heap InUse** (current: 638.6MB | avg: 244.9MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▃▄▃▃▁▂▁▂▁▂▃▃▂▂▁▂▁▁▁▁▁▁▁▅▃▁▁▁▂▁▂▁▁▁▃▂▆▃▂▂▂▁▃▂▁▂▁▁▁▂▃▁▁▁▁▁▁▂▁▁▁▁▁▂▁▂▃▁▂▁▁▁▁▂▁▁▄▂▁▁▁▁▁▁▁▁▁▂▁▁▁▁▂▂▄█
```

## Current Status

Goroutines: `███████░░░░░░░░░░░░░ 38%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 32,175 | 23,928 | +8247 | 14,881 | 84,644 | INCREASING (+2.14/hr) |
| Heap InUse | 638.6MB | 384.8MB | +253.8MB | 244.9MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 958.3MB | 982.9MB | -24.6MB | 2448.6MB | 6883.9MB | |
| Heap Objects | 2,774,632 | 850,604 | +1924028 | 1,051,230 | 17,165,538 | |

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
| 2026-06-07 | 288 | 15,421 | 234.3MB | 1942.9MB |
| 2026-06-08 | 288 | 16,327 | 305.6MB | 2130.6MB |
| 2026-06-09 | 288 | 16,163 | 304.7MB | 1487.7MB |
| 2026-06-10 | 287 | 16,453 | 305.9MB | 1442.9MB |
| 2026-06-11 | 288 | 16,393 | 314.0MB | 1403.5MB |
| 2026-06-12 | 288 | 16,142 | 260.8MB | 1418.7MB |
| 2026-06-13 | 288 | 16,274 | 264.7MB | 1566.3MB |
| 2026-06-14 | 288 | 15,854 | 265.3MB | 1419.6MB |
| 2026-06-15 | 286 | 16,144 | 281.9MB | 1342.8MB |
| 2026-06-16 | 286 | 16,159 | 253.2MB | 1286.4MB |
| 2026-06-17 | 54 | 15,580 | 209.9MB | 638.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `bytes.growSlice` | 91.96MB |
| 2 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 45.21MB |
| 3 | `bufio.NewWriterSize` | 43.17MB |
| 4 | `bufio.NewReaderSize` | 38.64MB |
| 5 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 6 | `runtime.mallocgc` | 17.51MB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 15.98MB |
| 8 | `aes/gcm.NewGCMForTLS13` | 15.51MB |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 10 | `crypto/tls.Client` | 8.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 23.26GB |
| 2 | `fmt.Sprintf` | 16.87GB |
| 3 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 13.12GB |
| 4 | `reflect.unsafe_NewArray` | 12.14GB |
| 5 | `jackskj/carta.getUniqueId` | 10.92GB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 10.77GB |
| 7 | `reflect.growslice` | 10.44GB |
| 8 | `reflect.unsafe_New` | 9.21GB |
| 9 | `fmt.Sprint` | 8.29GB |
| 10 | `strconv.appendQuotedWith` | 8.21GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 1.55GB | 1.54GB | 1.44GB | 0B |
| `evaluation.mergeMetadata` | 813.70MB | 810.20MB | 758.36MB | 0B |
| `local.(*Client).EvaluateV2` | 2.38GB | 2.37GB | 2.21GB | 0B |
| `local.topologicalSort` | 334.01MB | 332.50MB | 307.09MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 2.28GB | 2.27GB | 2.11GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 329.96MB | 329.96MB | 321.80MB | 0B |
| `localEvaluation.getMapOfValue` | 2.28GB | 2.27GB | 2.11GB | 0B |
| `utils.ParseFeatureFlag` | 2.29GB | 2.28GB | 2.12GB | 0B |

**Total FF alloc (current snapshot):** 12.22GB  |  **24h avg:** 11.35GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 38.54MB | 101/4746 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4397/4746 | `██████████████░ 95%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 35.39MB | 134/4746 | `█████████████░░ 91%` |
| 4 | `runtime.mallocgc` | 30.49MB | 4397/4746 | `███████████░░░░ 79%` |
| 5 | `database/sql.convertAssignRows` | 20.24MB | 157/4746 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4746 | `███████░░░░░░░░ 46%` |
| 7 | `bytes.growSlice` | 15.61MB | 3484/4746 | `██████░░░░░░░░░ 40%` |
| 8 | `net/http.(*Transport).dialConn` | 13.18MB | 129/4746 | `█████░░░░░░░░░░ 34%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4746 | `████░░░░░░░░░░░ 30%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4746 | `████░░░░░░░░░░░ 27%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4746 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 75.85GB | 2734/4746 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4746 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4746 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 62.09GB | 4120/4746 | `███████░░░░░░░░ 49%` |
| 6 | `reflect.growslice` | 61.95GB | 3958/4746 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 55.39GB | 3974/4746 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 51.68GB | 3738/4746 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4746 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 47.4GB | 3159/4746 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.7x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
