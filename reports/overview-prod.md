# Overview: prod
*Last updated: 2026-06-07 07:01 IST*
*Data range: 2026-05-15T16:03 to 2026-06-07T07:01 (1902 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,663 | avg: 12,946 | max: 84,644 | trend: INCREASING (+3.37/hr))
```
▂▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▄▁▁▂▁▁▁▆▆▄▁▂▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▃▃▂▂▂▂▂▃▁▁▁▁▁▁▁▁▁▂▃▃▁▄▆▅▂▁▁▁▁▃▄▃▃▃▄▅▅▁▁▁█▃
```

**Heap InUse** (current: 205.9MB | avg: 190.5MB | max: 3154.1MB | trend: stable (+0.02MB/hr))
```
▅▃▃▃▁▄▄▂▁▄▂▁▄▃▅▃▂▄▃▂▄▃▁▁▄▄▃▆▃▄▂▄▄▁▅▇▃▄▂▁▃▁▁▁▃▃▄▃▃▄▂▂▃▂▃▂▂▂▄▃▃▄▄▂▁▃▃▁▁▁▄▂▅█▂▅▄▆▃▂▂▂▄▆▄▅▅▅▄▆▄▃▄▄▄▅
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 2%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,663 | 15,550 | -887 | 12,946 | 84,644 | INCREASING (+3.37/hr) |
| Heap InUse | 205.9MB | 165.9MB | +40.0MB | 190.5MB | 3154.1MB | stable (+0.02MB/hr) |
| Heap Sys | 854.4MB | 854.3MB | +0.1MB | 2255.5MB | 6883.9MB | |
| Heap Objects | 1,226,929 | 529,235 | +697694 | 862,081 | 17,165,538 | |

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
| 2026-06-07 | 85 | 14,344 | 159.2MB | 247.2MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 14.57MB |
| 3 | `runtime.mallocgc` | 11.58MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 8.0MB |
| 6 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 7.49MB |
| 7 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 7.49MB |
| 8 | `bufio.NewReaderSize` | 3.53MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 3.01MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 24.36GB |
| 2 | `reflect.growslice` | 15.62GB |
| 3 | `reflect.unsafe_NewArray` | 12.4GB |
| 4 | `jackskj/carta.getUniqueId` | 12.27GB |
| 5 | `reflect.unsafe_New` | 11.49GB |
| 6 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 10.54GB |
| 7 | `fmt.(*buffer).writeString` | 10.15GB |
| 8 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 8.63GB |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 8.49GB |
| 10 | `carta/value.NewCell` | 7.98GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 622.75MB | 617.67MB | 543.33MB | 0B |
| `evaluation.mergeMetadata` | 324.08MB | 321.58MB | 283.79MB | 0B |
| `local.(*Client).EvaluateV2` | 948.68MB | 941.56MB | 831.43MB | 0B |
| `local.topologicalSort` | 131.56MB | 130.55MB | 115.93MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 953.31MB | 945.17MB | 837.37MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 88.98MB | 88.98MB | 76.28MB | 0B |
| `localEvaluation.getMapOfValue` | 953.31MB | 945.17MB | 837.37MB | 0B |
| `utils.ParseFeatureFlag` | 955.31MB | 947.17MB | 839.37MB | 0B |

**Total FF alloc (current snapshot):** 4.86GB  |  **24h avg:** 4.26GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 85.72MB | 37/1902 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 66.16MB | 62/1902 | `███████████░░░░ 77%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 1553/1902 | `██████░░░░░░░░░ 42%` |
| 4 | `database/sql.convertAssignRows` | 34.56MB | 78/1902 | `██████░░░░░░░░░ 40%` |
| 5 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1902 | `███░░░░░░░░░░░░ 20%` |
| 6 | `runtime.mallocgc` | 16.69MB | 1553/1902 | `██░░░░░░░░░░░░░ 19%` |
| 7 | `bytes.growSlice` | 14.61MB | 1143/1902 | `██░░░░░░░░░░░░░ 17%` |
| 8 | `net/http.(*Transport).dialConn` | 12.61MB | 32/1902 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1902 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/1902 | `█░░░░░░░░░░░░░░ 12%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.06GB | 388/1902 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1902 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1902 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1902 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1902 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1902 | `███░░░░░░░░░░░░ 22%` |
| 7 | `dotlapse-event-service/project.ApplyPagination` | 26.78GB | 1296/1902 | `███░░░░░░░░░░░░ 21%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 14.23GB | 969/1902 | `█░░░░░░░░░░░░░░ 11%` |
| 9 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 12.67GB | 419/1902 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `dotlapse-event-service/BackendComparison.CompareScreenshots` | 12.52GB | 301/1902 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (10.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (6.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.5x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.2x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.6x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.5x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.5x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.1x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (4.1x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (5.0x avg)
