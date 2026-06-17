# Overview: prod
*Last updated: 2026-06-17 19:06 IST*
*Data range: 2026-05-15T16:03 to 2026-06-17T19:06 (4922 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,181 | avg: 14,954 | max: 84,644 | trend: INCREASING (+2.09/hr))
```
▁▁▁▂▂▂▂▁▁▁▁▁▁▁▁▁▂▂▂▂▂▂▁▁▁▁▂▂▂▂▂█▃▃▂▁▄▃▂▂▂▂▃▂▂▂▂▂▂▂▁▁▄▂▂▁▁▁▁▂▂▁▁▁▁▂▂▁▃▄▅▄▃▃▃▂▁▂▂▆▆▅▅▅▅▂▂▁▁▁▂▁▁▂▁▅
```

**Heap InUse** (current: 308.3MB | avg: 246.2MB | max: 3154.1MB | trend: stable (+0.05MB/hr))
```
▂▂▁▂▂▃▂▁▁▁▁▁▁▁▁▂▂▃▃▁▂▂▁▁▁▂▃▂▃▂▃█▄▃▂▂▃▂▂▂▂▄▃▃▂▂▂▁▂▂▂▁▃▂▃▁▂▄▁▁▂▁▁▂▁▂▂▃▃▃▅▃▂▃▃▂▃▁▂▅▅▄▄▅▅▂▃▁▁▁▁▁▁▂▁▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,181 | 14,877 | +3304 | 14,954 | 84,644 | INCREASING (+2.09/hr) |
| Heap InUse | 308.3MB | 193.5MB | +114.8MB | 246.2MB | 3154.1MB | stable (+0.05MB/hr) |
| Heap Sys | 2231.4MB | 2233.4MB | -2.0MB | 2420.1MB | 6883.9MB | |
| Heap Objects | 909,299 | 643,869 | +265430 | 1,055,589 | 17,165,538 | |

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
| 2026-06-17 | 230 | 16,603 | 263.7MB | 1186.4MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 30.51MB |
| 3 | `bytes.growSlice` | 21.61MB |
| 4 | `bufio.NewReaderSize` | 10.55MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewWriterSize` | 7.54MB |
| 7 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.53MB |
| 8 | `http2/hpack.(*headerFieldTable).addEntry` | 5.5MB |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 4.0MB |
| 10 | `aes/gcm.NewGCMForTLS13` | 3.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 43.46GB |
| 2 | `reflect.growslice` | 41.01GB |
| 3 | `jackskj/carta.getUniqueId` | 38.49GB |
| 4 | `fmt.Sprintf` | 33.58GB |
| 5 | `reflect.unsafe_New` | 33.51GB |
| 6 | `fmt.(*buffer).writeString` | 25.33GB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 25.28GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 24.63GB |
| 9 | `carta/value.NewCell` | 23.62GB |
| 10 | `reflect.unsafe_NewArray` | 22.42GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 2.93GB | 2.92GB | 2.69GB | 0B |
| `evaluation.mergeMetadata` | 1.50GB | 1.50GB | 1.38GB | 0B |
| `local.(*Client).EvaluateV2` | 4.45GB | 4.44GB | 4.09GB | 0B |
| `local.topologicalSort` | 625.03MB | 622.52MB | 573.43MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 4.27GB | 4.25GB | 3.93GB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 624.19MB | 622.63MB | 561.72MB | 0B |
| `localEvaluation.getMapOfValue` | 4.27GB | 4.25GB | 3.93GB | 0B |
| `utils.ParseFeatureFlag` | 4.28GB | 4.26GB | 3.94GB | 0B |

**Total FF alloc (current snapshot):** 22.93GB  |  **24h avg:** 21.08GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 37.54MB | 104/4922 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 4573/4922 | `██████████████░ 97%` |
| 3 | `dotlapse-event-service/project.FetchProjectFilter` | 34.61MB | 139/4922 | `█████████████░░ 92%` |
| 4 | `runtime.mallocgc` | 30.29MB | 4573/4922 | `████████████░░░ 80%` |
| 5 | `database/sql.convertAssignRows` | 19.76MB | 163/4922 | `███████░░░░░░░░ 52%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/4922 | `███████░░░░░░░░ 47%` |
| 7 | `bytes.growSlice` | 15.79MB | 3640/4922 | `██████░░░░░░░░░ 42%` |
| 8 | `net/http.(*Transport).dialConn` | 13.27MB | 138/4922 | `█████░░░░░░░░░░ 35%` |
| 9 | `dotlapse-event-service/utils.CheckImageExists` | 10.86MB | 7/4922 | `████░░░░░░░░░░░ 28%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/4922 | `████░░░░░░░░░░░ 28%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/4922 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/4922 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/4922 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 73.91GB | 2839/4922 | `████████░░░░░░░ 59%` |
| 5 | `segmentio/kafka-go.makePartitions` | 60.92GB | 4296/4922 | `███████░░░░░░░░ 48%` |
| 6 | `reflect.growslice` | 60.65GB | 4134/4922 | `███████░░░░░░░░ 48%` |
| 7 | `jackskj/carta.getUniqueId` | 54.27GB | 4150/4922 | `██████░░░░░░░░░ 43%` |
| 8 | `experiment/local.topologicalSort` | 51.23GB | 375/4922 | `██████░░░░░░░░░ 40%` |
| 9 | `reflect.unsafe_New` | 50.49GB | 3914/4922 | `██████░░░░░░░░░ 40%` |
| 10 | `fmt.(*buffer).writeString` | 46.03GB | 3325/4922 | `█████░░░░░░░░░░ 36%` |

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
