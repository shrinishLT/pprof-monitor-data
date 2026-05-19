# Overview: stage
*Last updated: 2026-05-19 16:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T16:00 (193 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,113 | avg: 14,368 | max: 28,205 | trend: INCREASING (+7.51/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 193.8MB | avg: 163.9MB | max: 732.9MB | trend: INCREASING (+0.69MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,113 | 14,392 | -279 | 14,368 | 28,205 | INCREASING (+7.51/hr) |
| Heap InUse | 193.8MB | 227.9MB | -34.1MB | 163.9MB | 732.9MB | INCREASING (+0.69MB/hr) |
| Heap Sys | 1773.8MB | 1773.2MB | +0.6MB | 1098.4MB | 1773.8MB | |
| Heap Objects | 1,070,399 | 1,236,106 | -165707 | 853,140 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 33 | 14,121 | 177.7MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `reflect.mapassign_faststr0` | 3.0MB |
| 8 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 156.35GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 108.68GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 107.9GB |
| 4 | `internal/evaluation.mergeMetadata` | 105.04GB |
| 5 | `reflect.unsafe_NewArray` | 67.58GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 62.88GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 54.87GB |
| 8 | `experiment/local.topologicalSort` | 53.75GB |
| 9 | `reflect.MakeSlice` | 37.59GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.38GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 191/193 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/193 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/193 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.02MB | 187/193 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/193 | `████░░░░░░░░░░░ 32%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/193 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/193 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.33MB | 18/193 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 190/193 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 182/193 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 77.93GB | 184/193 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 43.2GB | 186/193 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 43.02GB | 180/193 | `████████░░░░░░░ 55%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 42.99GB | 185/193 | `████████░░░░░░░ 55%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 34.6GB | 169/193 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 33.69GB | 184/193 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.05GB | 182/193 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 21.88GB | 181/193 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 18.92GB | 182/193 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.06GB | 169/193 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
