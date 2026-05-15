# Overview: prod
*Last updated: 2026-05-16 04:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T04:31 (22 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,217 | avg: 17,914 | max: 84,644 | trend: INCREASING (+1018.11/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁
```

**Heap InUse** (current: 259.1MB | avg: 305.7MB | max: 1896.6MB | trend: INCREASING (+21.83MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,217 | 14,342 | -125 | 17,914 | 84,644 | INCREASING (+1018.11/hr) |
| Heap InUse | 259.1MB | 194.6MB | +64.5MB | 305.7MB | 1896.6MB | INCREASING (+21.83MB/hr) |
| Heap Sys | 5828.9MB | 5829.9MB | -1.0MB | 4722.0MB | 5829.9MB | |
| Heap Objects | 1,292,099 | 380,797 | +911302 | 1,190,108 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 12 | 20,916 | 361.0MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `bufio.NewWriterSize` | 3.07MB |
| 6 | `bufio.NewReaderSize` | 3.04MB |
| 7 | `compress/flate.NewWriter` | 2.64MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bytes.growSlice` | 2.04MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 49.14GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 29.94GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 29.74GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 20.98GB |
| 5 | `experiment/local.topologicalSort` | 19.7GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.5GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 9.53GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 9.32GB |
| 9 | `fmt.Sprintf` | 8.45GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.28GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 46.97MB | 4/22 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 20/22 | `███████████░░░░ 77%` |
| 3 | `bytes.growSlice` | 35.28MB | 11/22 | `███████████░░░░ 75%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/22 | `█████████░░░░░░ 64%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/22 | `█████████░░░░░░ 63%` |
| 6 | `runtime.mallocgc` | 21.5MB | 20/22 | `██████░░░░░░░░░ 45%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/22 | `█████░░░░░░░░░░ 35%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/22 | `█████░░░░░░░░░░ 35%` |
| 9 | `bufio.NewReaderSize` | 14.99MB | 10/22 | `████░░░░░░░░░░░ 31%` |
| 10 | `bufio.NewWriterSize` | 11.86MB | 14/22 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 77.32GB | 17/22 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/22 | `████████░░░░░░░ 57%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/22 | `██████░░░░░░░░░ 40%` |
| 4 | `internal/evaluation.mergeMetadata` | 26.44GB | 11/22 | `█████░░░░░░░░░░ 34%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.07GB | 16/22 | `███░░░░░░░░░░░░ 25%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 15.56GB | 17/22 | `███░░░░░░░░░░░░ 20%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 15.5GB | 17/22 | `███░░░░░░░░░░░░ 20%` |
| 8 | `experiment/local.topologicalSort` | 10.62GB | 11/22 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/22 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.28GB | 9/22 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.7x avg)
