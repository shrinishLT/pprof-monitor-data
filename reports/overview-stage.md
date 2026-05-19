# Overview: stage
*Last updated: 2026-05-19 08:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T08:30 (178 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,097 | avg: 14,388 | max: 28,205 | trend: INCREASING (+11.03/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 148.3MB | avg: 162.6MB | max: 732.9MB | trend: INCREASING (+0.78MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,097 | 14,067 | +30 | 14,388 | 28,205 | INCREASING (+11.03/hr) |
| Heap InUse | 148.3MB | 208.1MB | -59.8MB | 162.6MB | 732.9MB | INCREASING (+0.78MB/hr) |
| Heap Sys | 1771.4MB | 1771.4MB | +0.0MB | 1041.6MB | 1771.4MB | |
| Heap Objects | 645,476 | 1,433,693 | -788217 | 844,683 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 18 | 14,116 | 176.2MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 6 | `compress/flate.NewWriter` | 2.64MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 142.88GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 105.16GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.31GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.6GB |
| 5 | `reflect.unsafe_NewArray` | 61.79GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 53.07GB |
| 8 | `experiment/local.topologicalSort` | 51.95GB |
| 9 | `reflect.MakeSlice` | 34.29GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 176/178 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/178 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/178 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/178 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.58MB | 172/178 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/178 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/178 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/178 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 175/178 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 167/178 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 71.52GB | 169/178 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 37.67GB | 171/178 | `███████░░░░░░░░ 52%` |
| 3 | `internal/evaluation.mergeMetadata` | 37.6GB | 165/178 | `███████░░░░░░░░ 52%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 37.48GB | 170/178 | `███████░░░░░░░░ 52%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 32.03GB | 154/178 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 30.92GB | 169/178 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 19.21GB | 167/178 | `████░░░░░░░░░░░ 26%` |
| 8 | `experiment/local.topologicalSort` | 19.12GB | 166/178 | `████░░░░░░░░░░░ 26%` |
| 9 | `reflect.MakeSlice` | 17.38GB | 167/178 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.94GB | 154/178 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
