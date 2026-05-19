# Overview: stage
*Last updated: 2026-05-19 07:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T07:31 (176 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,083 | avg: 14,391 | max: 28,205 | trend: INCREASING (+11.65/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 152.4MB | avg: 162.4MB | max: 732.9MB | trend: INCREASING (+0.79MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,083 | 14,164 | -81 | 14,391 | 28,205 | INCREASING (+11.65/hr) |
| Heap InUse | 152.4MB | 175.6MB | -23.2MB | 162.4MB | 732.9MB | INCREASING (+0.79MB/hr) |
| Heap Sys | 1771.3MB | 1771.3MB | +0.0MB | 1033.3MB | 1771.3MB | |
| Heap Objects | 726,847 | 1,016,236 | -289389 | 842,468 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 16 | 14,120 | 175.9MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `reflect.unsafe_NewArray` | 2.5MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 141.15GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 104.96GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.1GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.42GB |
| 5 | `reflect.unsafe_NewArray` | 61.05GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 52.98GB |
| 8 | `experiment/local.topologicalSort` | 51.85GB |
| 9 | `reflect.MakeSlice` | 33.89GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 174/176 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/176 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/176 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/176 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.52MB | 170/176 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/176 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/176 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/176 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 173/176 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 165/176 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 70.67GB | 167/176 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 36.87GB | 169/176 | `███████░░░░░░░░ 52%` |
| 3 | `internal/evaluation.mergeMetadata` | 36.82GB | 163/176 | `███████░░░░░░░░ 52%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 36.68GB | 168/176 | `███████░░░░░░░░ 51%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 31.65GB | 152/176 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 30.56GB | 167/176 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.8GB | 165/176 | `███░░░░░░░░░░░░ 26%` |
| 8 | `experiment/local.topologicalSort` | 18.71GB | 164/176 | `███░░░░░░░░░░░░ 26%` |
| 9 | `reflect.MakeSlice` | 17.18GB | 165/176 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.78GB | 152/176 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
