# Overview: prod
*Last updated: 2026-05-16 04:27 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T04:27 (21 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,342 | avg: 18,090 | max: 84,644 | trend: INCREASING (+1276.45/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁
```

**Heap InUse** (current: 194.6MB | avg: 307.9MB | max: 1896.6MB | trend: INCREASING (+26.43MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,342 | 20,552 | -6210 | 18,090 | 84,644 | INCREASING (+1276.45/hr) |
| Heap InUse | 194.6MB | 433.8MB | -239.2MB | 307.9MB | 1896.6MB | INCREASING (+26.43MB/hr) |
| Heap Sys | 5829.9MB | 5742.2MB | +87.7MB | 4669.3MB | 5829.9MB | |
| Heap Objects | 380,797 | 1,472,178 | -1091381 | 1,185,252 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 11 | 21,525 | 370.2MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bufio.NewWriterSize` | 3.07MB |
| 7 | `bytes.growSlice` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 49.1GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 29.93GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 29.72GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 20.98GB |
| 5 | `experiment/local.topologicalSort` | 19.69GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.49GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 9.53GB |
| 8 | `internal/evaluation.(*Engine).evaluateFlag` | 9.31GB |
| 9 | `fmt.Sprintf` | 8.44GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.05GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 46.97MB | 4/21 | `███████████████ 100%` |
| 2 | `bytes.growSlice` | 38.61MB | 10/21 | `████████████░░░ 82%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 19/21 | `███████████░░░░ 77%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/21 | `█████████░░░░░░ 64%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/21 | `█████████░░░░░░ 63%` |
| 6 | `runtime.mallocgc` | 19.47MB | 19/21 | `██████░░░░░░░░░ 41%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/21 | `█████░░░░░░░░░░ 35%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/21 | `█████░░░░░░░░░░ 35%` |
| 9 | `bufio.NewReaderSize` | 16.32MB | 9/21 | `█████░░░░░░░░░░ 34%` |
| 10 | `bufio.NewWriterSize` | 12.54MB | 13/21 | `████░░░░░░░░░░░ 26%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 80.84GB | 16/21 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/21 | `████████░░░░░░░ 54%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/21 | `█████░░░░░░░░░░ 39%` |
| 4 | `internal/evaluation.mergeMetadata` | 24.16GB | 10/21 | `████░░░░░░░░░░░ 29%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 20.77GB | 15/21 | `███░░░░░░░░░░░░ 25%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 14.66GB | 16/21 | `██░░░░░░░░░░░░░ 18%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 14.61GB | 16/21 | `██░░░░░░░░░░░░░ 18%` |
| 8 | `experiment/local.topologicalSort` | 9.71GB | 10/21 | `█░░░░░░░░░░░░░░ 12%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/21 | `█░░░░░░░░░░░░░░ 11%` |
| 10 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.28GB | 9/21 | `█░░░░░░░░░░░░░░ 11%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.7x avg)
