# Overview: stage
*Last updated: 2026-05-21 13:02 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T13:01 (291 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,185 | avg: 14,290 | max: 28,205 | trend: stable (+0.09/hr))
```
▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▁▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▇▂
```

**Heap InUse** (current: 158.4MB | avg: 167.5MB | max: 732.9MB | trend: stable (+0.29MB/hr))
```
▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁▂▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,185 | 14,532 | -347 | 14,290 | 28,205 | stable (+0.09/hr) |
| Heap InUse | 158.4MB | 187.9MB | -29.5MB | 167.5MB | 732.9MB | stable (+0.29MB/hr) |
| Heap Sys | 1793.5MB | 1793.1MB | +0.4MB | 1329.8MB | 1793.5MB | |
| Heap Objects | 713,253 | 715,167 | -1914 | 862,179 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 35 | 14,138 | 170.9MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `reflect.unsafe_NewArray` | 3.01MB |
| 6 | `segmentio/kafka-go.makePartitions` | 2.5MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `aws/endpoints.init` | 2.0MB |
| 9 | `compress/flate.NewWriter` | 1.76MB |
| 10 | `bufio.NewWriterSize` | 1.53MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 237.47GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 138.23GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 137.56GB |
| 4 | `internal/evaluation.mergeMetadata` | 133.89GB |
| 5 | `reflect.unsafe_NewArray` | 102.45GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 91.73GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 69.7GB |
| 8 | `experiment/local.topologicalSort` | 68.41GB |
| 9 | `reflect.MakeSlice` | 57.18GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 39.99GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 289/291 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/291 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.73MB | 285/291 | `██████░░░░░░░░░ 40%` |
| 4 | `bytes.growSlice` | 10.81MB | 37/291 | `████░░░░░░░░░░░ 29%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.48MB | 14/291 | `████░░░░░░░░░░░ 28%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/291 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 288/291 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 280/291 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/291 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.43MB | 7/291 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 120.32GB | 282/291 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.29GB | 284/291 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.99GB | 283/291 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.36GB | 278/291 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 51.98GB | 282/291 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 50.06GB | 267/291 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.33GB | 280/291 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.85GB | 279/291 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 29.15GB | 280/291 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.8GB | 267/291 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
