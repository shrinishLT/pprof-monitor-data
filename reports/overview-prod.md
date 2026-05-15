# Overview: prod
*Last updated: 2026-05-16 03:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-16T03:02 (19 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,312 | avg: 18,158 | max: 84,644 | trend: INCREASING (+1782.61/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁
```

**Heap InUse** (current: 303.4MB | avg: 307.3MB | max: 1896.6MB | trend: INCREASING (+35.67MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 5%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,312 | 14,221 | +1091 | 18,158 | 84,644 | INCREASING (+1782.61/hr) |
| Heap InUse | 303.4MB | 232.8MB | +70.6MB | 307.3MB | 1896.6MB | INCREASING (+35.67MB/hr) |
| Heap Sys | 4755.1MB | 4751.9MB | +3.2MB | 4551.7MB | 5825.3MB | |
| Heap Objects | 1,253,730 | 916,537 | +337193 | 1,212,490 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 9 | 22,432 | 382.7MB | 1896.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 60.12MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `bytes.growSlice` | 9.55MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 7.03MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `segmentio/kafka-go.makePartitions` | 4.01MB |
| 8 | `compress/flate.NewWriter` | 3.53MB |
| 9 | `bufio.NewWriterSize` | 3.02MB |
| 10 | `reflect.unsafe_NewArray` | 2.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/evaluation.mergeMetadata` | 35.01GB |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 21.29GB |
| 3 | `experiment/local.(*Client).EvaluateV2` | 21.2GB |
| 4 | `experiment/local.topologicalSort` | 14.1GB |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 11.1GB |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 10.98GB |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 6.58GB |
| 8 | `fmt.Sprintf` | 6.18GB |
| 9 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 5.67GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 5.03GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 57.1MB | 3/19 | `███████████████ 100%` |
| 2 | `bytes.growSlice` | 43.41MB | 8/19 | `███████████░░░░ 76%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 17/19 | `█████████░░░░░░ 64%` |
| 4 | `net/http.(*Transport).tryPutIdleConn` | 30.52MB | 1/19 | `████████░░░░░░░ 53%` |
| 5 | `net/http.(*Transport).dialConn` | 30.0MB | 1/19 | `███████░░░░░░░░ 52%` |
| 6 | `crypto/tls.Client` | 28.52MB | 1/19 | `███████░░░░░░░░ 49%` |
| 7 | `aes/gcm.NewGCMForTLS13` | 19.52MB | 3/19 | `█████░░░░░░░░░░ 34%` |
| 8 | `bufio.NewReaderSize` | 16.91MB | 8/19 | `████░░░░░░░░░░░ 29%` |
| 9 | `runtime.mallocgc` | 14.69MB | 17/19 | `███░░░░░░░░░░░░ 25%` |
| 10 | `bufio.NewWriterSize` | 13.12MB | 11/19 | `███░░░░░░░░░░░░ 22%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 89.74GB | 14/19 | `███████████████ 100%` |
| 2 | `reflect.growslice` | 44.11GB | 6/19 | `███████░░░░░░░░ 49%` |
| 3 | `fmt.(*buffer).writeString` | 31.53GB | 6/19 | `█████░░░░░░░░░░ 35%` |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 22.68GB | 13/19 | `███░░░░░░░░░░░░ 25%` |
| 5 | `internal/evaluation.mergeMetadata` | 18.88GB | 8/19 | `███░░░░░░░░░░░░ 21%` |
| 6 | `internal/evaluation.(*Engine).Evaluate` | 12.81GB | 14/19 | `██░░░░░░░░░░░░░ 14%` |
| 7 | `experiment/local.(*Client).EvaluateV2` | 12.77GB | 14/19 | `██░░░░░░░░░░░░░ 14%` |
| 8 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.31GB | 9/19 | `█░░░░░░░░░░░░░░ 10%` |
| 9 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 9.28GB | 9/19 | `█░░░░░░░░░░░░░░ 10%` |
| 10 | `experiment/local.topologicalSort` | 7.59GB | 8/19 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (6.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (4.7x avg)
