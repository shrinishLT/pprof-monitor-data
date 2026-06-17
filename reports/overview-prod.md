# Overview: prod
*Last updated: 2026-06-17 16:08 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T16:08 (4886 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,192 | avg: 14,946 | max: 84,644 | trend: INCREASING (+2.12/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▃▄▄▃▅▆▆█▇▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 220.8MB | avg: 246.0MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▃▄▅▄▄▆█▇▇▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▂▃▂▂▁▁▁▁▁▁▁▂▁▂▁▁▁▁▁▁▁▁▂▁▂▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,192 | 14,800 | +392 | 14,946 | 84,644 | INCREASING (+2.12/hr) |
| Heap InUse | 220.8MB | 221.4MB | -0.6MB | 246.0MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 2233.3MB | 2234.1MB | -0.8MB | 2421.4MB | 6883.9MB | |
| Heap Objects | 530,399 | 907,399 | -377000 | 1,055,042 | 17,165,538 | |

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
| 2026-06-17 | 194 | 16,699 | 261.5MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.51MB |
| 3 | `bytes.growSlice` | 9.44MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 4.53MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.85MB |
| 10 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `reflect.growslice` | 40.39GB |
| 2 | `segmentio/kafka-go.makePartitions` | 39.38GB |
| 3 | `jackskj/carta.getUniqueId` | 37.38GB |
| 4 | `reflect.unsafe_New` | 32.79GB |
| 5 | `fmt.Sprintf` | 30.14GB |
| 6 | `fmt.(*buffer).writeString` | 24.8GB |
| 7 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 24.23GB |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 23.2GB |
| 9 | `carta/value.NewCell` | 23.1GB |
| 10 | `reflect.unsafe_NewArray` | 20.37GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.57GB | 2.56GB | 2.32GB | 0B |
| `evaluation.mergeMetadata` | 1.32GB | 1.31GB | 1.20GB | 0B |
| `local.(*Client).EvaluateV2` | 3.92GB | 3.90GB | 3.54GB | 0B |
| `local.topologicalSort` | 551.66MB | 551.16MB | 495.76MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 3.78GB | 3.76GB | 3.43GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 529.04MB | 526.46MB | 457.31MB | 0B |
| `localEvaluation.getMapOfValue` | 3.78GB | 3.76GB | 3.43GB | 0B |
| `utils.ParseFeatureFlag` | 3.79GB | 3.77GB | 3.44GB | 512.56kB |

**Total FF alloc (current snapshot):** 20.22GB  |  **24h avg:** 18.27GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.54MB | 104/4886 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4537/4886 | `██████████████░ 97%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.61MB | 139/4886 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.29MB | 4537/4886 | `████████████░░░ 80%` |
| 5 | `database/sql.convertAssignRows` | 19.76MB | 163/4886 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4886 | `███████░░░░░░░░ 47%` |
| 7 | `bytes.growSlice` | 15.8MB | 3607/4886 | `██████░░░░░░░░░ 42%` |
| 8 | `net/http.(*Transport).dialConn` | 13.27MB | 138/4886 | `█████░░░░░░░░░░ 35%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4886 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4886 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4886 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4886 | `████████░░░░░░░ 59%` |
| 3 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 74.55GB | 2803/4886 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4886 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 61.08GB | 4260/4886 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.growslice` | 60.82GB | 4098/4886 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.41GB | 4114/4886 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4886 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.66GB | 3878/4886 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.26GB | 3289/4886 | `█████░░░░░░░░░░ 36%` |

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
