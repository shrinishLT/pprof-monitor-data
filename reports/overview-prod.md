# Overview: prod
*Last updated: 2026-05-16 02:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T02:31 (18 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,221 | avg: 18,316 | max: 84,644 | trend: INCREASING (+2208.79/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁
```

**Heap InUse** (current: 232.8MB | avg: 307.5MB | max: 1896.6MB | trend: INCREASING (+42.11MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 16%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,221 | 84,644 | -70423 | 18,316 | 84,644 | INCREASING (+2208.79/hr) |
| Heap InUse | 232.8MB | 1896.6MB | -1663.8MB | 307.5MB | 1896.6MB | INCREASING (+42.11MB/hr) |
| Heap Sys | 4751.9MB | 3461.2MB | +1290.7MB | 4540.4MB | 5825.3MB | |
| Heap Objects | 916,537 | 8,100,802 | -7184265 | 1,210,199 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 8 | 23,322 | 392.6MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 5 | `reflect.mapassign_faststr0` | 3.0MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.52MB |
| 7 | `dotlapse-event-service/workerpool.NewWorker` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `kafka-go/protocol.newPage` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 33.22GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 20.17GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 20.09GB |
| 4 | `experiment/local.topologicalSort` | 13.37GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 11.06GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.4GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 6.25GB |
| 8 | `fmt.Sprintf` | 5.9GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.67GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 5.01GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 82.13MB | 2/18 | `███████████████ 100%` |
| 2 | `bytes.growSlice` | 48.25MB | 7/18 | `████████░░░░░░░ 58%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 16/18 | `██████░░░░░░░░░ 44%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/18 | `█████░░░░░░░░░░ 37%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/18 | `█████░░░░░░░░░░ 36%` |
| 6 | `crypto/tls.Client` | 28.52MB | 1/18 | `█████░░░░░░░░░░ 34%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 19.52MB | 3/18 | `███░░░░░░░░░░░░ 23%` |
| 8 | `bufio.NewReaderSize` | 16.91MB | 8/18 | `███░░░░░░░░░░░░ 20%` |
| 9 | `bufio.NewWriterSize` | 14.13MB | 10/18 | `██░░░░░░░░░░░░░ 17%` |
| 10 | `runtime.mallocgc` | 11.85MB | 16/18 | `██░░░░░░░░░░░░░ 14%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 95.79GB | 13/18 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/18 | `██████░░░░░░░░░ 46%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/18 | `████░░░░░░░░░░░ 32%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 24.15GB | 12/18 | `███░░░░░░░░░░░░ 25%` |
| 5 | `internal/evaluation.mergeMetadata` | 16.57GB | 7/18 | `██░░░░░░░░░░░░░ 17%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 12.16GB | 13/18 | `█░░░░░░░░░░░░░░ 12%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 12.13GB | 13/18 | `█░░░░░░░░░░░░░░ 12%` |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/18 | `█░░░░░░░░░░░░░░ 9%` |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.28GB | 9/18 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 7.62GB | 10/18 | `█░░░░░░░░░░░░░░ 7%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.6x avg)
