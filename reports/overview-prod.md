# Overview: prod
*Last updated: 2026-06-15 17:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-15T17:01 (4325 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,258 | avg: 14,769 | max: 84,644 | trend: INCREASING (+2.49/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▂▃▅▆▇█▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 252.4MB | avg: 244.0MB | max: 3154.1MB | trend: stable (+0.06MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▂▂▃▃▃▄▄▆▆█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▁▁▁▁▁▁▁▁▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,258 | 16,479 | -1221 | 14,769 | 84,644 | INCREASING (+2.49/hr) |
| Heap InUse | 252.4MB | 299.8MB | -47.4MB | 244.0MB | 3154.1MB | stable (+0.06MB/hr) |
| Heap Sys | 2425.3MB | 2425.7MB | -0.4MB | 2524.4MB | 6883.9MB | |
| Heap Objects | 1,046,837 | 1,131,699 | -84862 | 1,046,715 | 17,165,538 | |

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
| 2026-06-15 | 205 | 16,229 | 278.3MB | 1342.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 32.36MB |
| 3 | `bytes.growSlice` | 9.71MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.5MB |
| 6 | `bufio.NewWriterSize` | 5.55MB |
| 7 | `compress/flate.NewWriter` | 5.29MB |
| 8 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 9 | `segmentio/kafka-go.makePartitions` | 3.03MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 109.74GB |
| 2 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 109.62GB |
| 3 | `segmentio/kafka-go.makePartitions` | 105.4GB |
| 4 | `jackskj/carta.getUniqueId` | 99.54GB |
| 5 | `reflect.unsafe_New` | 87.07GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 79.27GB |
| 7 | `fmt.Sprintf` | 71.93GB |
| 8 | `fmt.(*buffer).writeString` | 67.75GB |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 65.25GB |
| 10 | `carta/value.NewCell` | 63.03GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 4.28GB | 4.27GB | 4.04GB | 0B |
| `evaluation.mergeMetadata` | 2.22GB | 2.21GB | 2.09GB | 0B |
| `local.(*Client).EvaluateV2` | 6.58GB | 6.56GB | 6.22GB | 0B |
| `local.topologicalSort` | 949.11MB | 949.11MB | 900.23MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 6.43GB | 6.41GB | 6.10GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 810.33MB | 808.23MB | 744.76MB | 0B |
| `localEvaluation.getMapOfValue` | 6.43GB | 6.41GB | 6.10GB | 0B |
| `utils.ParseFeatureFlag` | 6.44GB | 6.43GB | 6.11GB | 0B |

**Total FF alloc (current snapshot):** 34.09GB  |  **24h avg:** 32.28GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 43.12MB | 88/4325 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 38.23MB | 122/4325 | `█████████████░░ 88%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 3976/4325 | `████████████░░░ 84%` |
| 4 | `runtime.mallocgc` | 31.33MB | 3976/4325 | `██████████░░░░░ 72%` |
| 5 | `database/sql.convertAssignRows` | 21.72MB | 143/4325 | `███████░░░░░░░░ 50%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4325 | `██████░░░░░░░░░ 41%` |
| 7 | `bytes.growSlice` | 15.83MB | 3098/4325 | `█████░░░░░░░░░░ 36%` |
| 8 | `net/http.(*Transport).dialConn` | 13.35MB | 117/4325 | `████░░░░░░░░░░░ 30%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 11.84MB | 6/4325 | `████░░░░░░░░░░░ 27%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4325 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4325 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4325 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4325 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 72.7GB | 2514/4325 | `████████░░░░░░░ 58%` |
| 5 | `reflect.growslice` | 61.79GB | 3537/4325 | `███████░░░░░░░░ 49%` |
| 6 | `segmentio/kafka-go.makePartitions` | 61.59GB | 3699/4325 | `███████░░░░░░░░ 49%` |
| 7 | `jackskj/carta.getUniqueId` | 55.11GB | 3553/4325 | `██████░░░░░░░░░ 44%` |
| 8 | `reflect.unsafe_New` | 51.83GB | 3317/4325 | `██████░░░░░░░░░ 41%` |
| 9 | `experiment/local.topologicalSort` | 51.23GB | 375/4325 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.65GB | 2871/4325 | `█████░░░░░░░░░░ 37%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (7.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.7x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.7x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.7x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.2x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (3.9x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.3x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.5x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.1x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.3x avg)
