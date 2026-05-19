# Overview: stage
*Last updated: 2026-05-19 07:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T07:00 (175 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,164 | avg: 14,393 | max: 28,205 | trend: INCREASING (+11.98/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 175.6MB | avg: 162.5MB | max: 732.9MB | trend: INCREASING (+0.81MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,164 | 14,367 | -203 | 14,393 | 28,205 | INCREASING (+11.98/hr) |
| Heap InUse | 175.6MB | 269.0MB | -93.4MB | 162.5MB | 732.9MB | INCREASING (+0.81MB/hr) |
| Heap Sys | 1771.3MB | 1771.2MB | +0.1MB | 1029.1MB | 1771.3MB | |
| Heap Objects | 1,016,236 | 1,305,855 | -289619 | 843,129 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 15 | 14,122 | 177.5MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 5.01MB |
| 6 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bufio.NewReaderSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 140.23GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 104.93GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 104.07GB |
| 4 | `internal/evaluation.mergeMetadata` | 101.39GB |
| 5 | `reflect.unsafe_NewArray` | 60.65GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 60.35GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 52.96GB |
| 8 | `experiment/local.topologicalSort` | 51.83GB |
| 9 | `reflect.MakeSlice` | 33.67GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 26.26GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 173/175 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/175 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.73MB | 27/175 | `█████░░░░░░░░░░ 37%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.83MB | 11/175 | `█████░░░░░░░░░░ 35%` |
| 5 | `runtime.mallocgc` | 12.48MB | 169/175 | `█████░░░░░░░░░░ 34%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/175 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/175 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.7MB | 17/175 | `███░░░░░░░░░░░░ 26%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 172/175 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 164/175 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 70.25GB | 166/175 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 36.47GB | 168/175 | `███████░░░░░░░░ 51%` |
| 3 | `internal/evaluation.mergeMetadata` | 36.42GB | 162/175 | `███████░░░░░░░░ 51%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 36.28GB | 167/175 | `███████░░░░░░░░ 51%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 31.46GB | 151/175 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 30.37GB | 166/175 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 18.59GB | 164/175 | `███░░░░░░░░░░░░ 26%` |
| 8 | `experiment/local.topologicalSort` | 18.51GB | 163/175 | `███░░░░░░░░░░░░ 26%` |
| 9 | `reflect.MakeSlice` | 17.08GB | 164/175 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 13.7GB | 151/175 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
