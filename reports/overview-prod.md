# Overview: prod
*Last updated: 2026-05-16 05:01 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T05:01 (23 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,949 | avg: 17,785 | max: 84,644 | trend: INCREASING (+826.38/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁
```

**Heap InUse** (current: 296.9MB | avg: 305.3MB | max: 1896.6MB | trend: INCREASING (+18.91MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▂▁▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,949 | 14,217 | +732 | 17,785 | 84,644 | INCREASING (+826.38/hr) |
| Heap InUse | 296.9MB | 259.1MB | +37.8MB | 305.3MB | 1896.6MB | INCREASING (+18.91MB/hr) |
| Heap Sys | 5829.6MB | 5828.9MB | +0.7MB | 4770.1MB | 5829.9MB | |
| Heap Objects | 1,430,559 | 1,292,099 | +138460 | 1,200,563 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 13 | 20,457 | 356.0MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 8.54MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 6.5MB |
| 6 | `bufio.NewReaderSize` | 5.03MB |
| 7 | `reflect.mapassign_faststr0` | 4.0MB |
| 8 | `bufio.NewWriterSize` | 2.52MB |
| 9 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 50.37GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 30.73GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 30.48GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 21.01GB |
| 5 | `experiment/local.topologicalSort` | 20.19GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 15.88GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 9.56GB |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 9.55GB |
| 9 | `fmt.Sprintf` | 8.67GB |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 6.34GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 46.97MB | 4/23 | `███████████████ 100%` |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 21/23 | `███████████░░░░ 77%` |
| 3 | `bytes.growSlice` | 33.05MB | 12/23 | `██████████░░░░░ 70%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/23 | `█████████░░░░░░ 64%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/23 | `█████████░░░░░░ 63%` |
| 6 | `runtime.mallocgc` | 23.34MB | 21/23 | `███████░░░░░░░░ 49%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 16.52MB | 4/23 | `█████░░░░░░░░░░ 35%` |
| 8 | `crypto/tls.Client` | 16.51MB | 2/23 | `█████░░░░░░░░░░ 35%` |
| 9 | `bufio.NewReaderSize` | 14.09MB | 11/23 | `████░░░░░░░░░░░ 29%` |
| 10 | `bufio.NewWriterSize` | 11.24MB | 15/23 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 74.19GB | 18/23 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/23 | `████████░░░░░░░ 59%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/23 | `██████░░░░░░░░░ 42%` |
| 4 | `internal/evaluation.mergeMetadata` | 28.43GB | 12/23 | `█████░░░░░░░░░░ 38%` |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 19.45GB | 17/23 | `███░░░░░░░░░░░░ 26%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 16.4GB | 18/23 | `███░░░░░░░░░░░░ 22%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 16.33GB | 18/23 | `███░░░░░░░░░░░░ 22%` |
| 8 | `experiment/local.topologicalSort` | 11.41GB | 12/23 | `██░░░░░░░░░░░░░ 15%` |
| 9 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 9.73GB | 11/23 | `█░░░░░░░░░░░░░░ 13%` |
| 10 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/23 | `█░░░░░░░░░░░░░░ 12%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.8x avg)
