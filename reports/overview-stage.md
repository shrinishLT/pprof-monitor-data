# Overview: stage
*Last updated: 2026-05-19 17:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-19T17:30 (196 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,074 | avg: 14,363 | max: 28,205 | trend: INCREASING (+6.90/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁▁▁▇▁█▇▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 173.7MB | avg: 164.0MB | max: 732.9MB | trend: INCREASING (+0.67MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▂▂▁▁▆▁█▅▂▁▁▁▁▁▂▁▁▁▁▂▁▁▁▁▁▁▂▁▁▃▂▁▁▂▁▁▁▁▂▁▁▁▁▁▁▁▁▁▂▁▂▁▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,074 | 14,071 | +3 | 14,363 | 28,205 | INCREASING (+6.90/hr) |
| Heap InUse | 173.7MB | 153.1MB | +20.6MB | 164.0MB | 732.9MB | INCREASING (+0.67MB/hr) |
| Heap Sys | 1774.2MB | 1774.2MB | +0.0MB | 1108.7MB | 1774.2MB | |
| Heap Objects | 999,863 | 685,656 | +314207 | 855,266 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 36 | 14,117 | 177.4MB | 293.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `segmentio/kafka-go.makePartitions` | 3.5MB |
| 7 | `internal/sync.runtime_SemacquireMutex` | 2.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `compress/flate.(*compressor).initDeflate` | 1.6MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 159.05GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 108.92GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 108.13GB |
| 4 | `internal/evaluation.mergeMetadata` | 105.27GB |
| 5 | `reflect.unsafe_NewArray` | 68.72GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 63.39GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 54.97GB |
| 8 | `experiment/local.topologicalSort` | 53.86GB |
| 9 | `reflect.MakeSlice` | 38.2GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 27.6GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 194/196 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 15.39MB | 2/196 | `██████░░░░░░░░░ 42%` |
| 3 | `bytes.growSlice` | 13.35MB | 28/196 | `█████░░░░░░░░░░ 36%` |
| 4 | `runtime.mallocgc` | 13.09MB | 190/196 | `█████░░░░░░░░░░ 35%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.93MB | 12/196 | `████░░░░░░░░░░░ 32%` |
| 6 | `internal/evaluation.mergeMetadata` | 10.5MB | 5/196 | `████░░░░░░░░░░░ 28%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/196 | `████░░░░░░░░░░░ 27%` |
| 8 | `bufio.NewReaderSize` | 9.33MB | 18/196 | `███░░░░░░░░░░░░ 25%` |
| 9 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 193/196 | `███░░░░░░░░░░░░ 25%` |
| 10 | `sirupsen/logrus.(*Entry).WithFields` | 8.95MB | 185/196 | `███░░░░░░░░░░░░ 24%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 79.21GB | 187/196 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 44.24GB | 189/196 | `████████░░░░░░░ 55%` |
| 3 | `internal/evaluation.mergeMetadata` | 44.04GB | 183/196 | `████████░░░░░░░ 55%` |
| 4 | `internal/evaluation.(*Engine).Evaluate` | 44.03GB | 188/196 | `████████░░░░░░░ 55%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 35.1GB | 172/196 | `██████░░░░░░░░░ 44%` |
| 6 | `reflect.unsafe_NewArray` | 34.25GB | 187/196 | `██████░░░░░░░░░ 43%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 22.58GB | 185/196 | `████░░░░░░░░░░░ 28%` |
| 8 | `experiment/local.topologicalSort` | 22.4GB | 184/196 | `████░░░░░░░░░░░ 28%` |
| 9 | `reflect.MakeSlice` | 19.23GB | 185/196 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 15.28GB | 172/196 | `██░░░░░░░░░░░░░ 19%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.9x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.5x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.3x avg)
