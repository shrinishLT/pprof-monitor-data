# Overview: stage
*Last updated: 2026-05-21 12:32 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T12:32 (290 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,532 | avg: 14,291 | max: 28,205 | trend: stable (+0.10/hr))
```
▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▁▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▇
```

**Heap InUse** (current: 187.9MB | avg: 167.5MB | max: 732.9MB | trend: stable (+0.30MB/hr))
```
▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,532 | 14,328 | +204 | 14,291 | 28,205 | stable (+0.10/hr) |
| Heap InUse | 187.9MB | 162.2MB | +25.7MB | 167.5MB | 732.9MB | stable (+0.30MB/hr) |
| Heap Sys | 1793.1MB | 1793.2MB | -0.1MB | 1328.2MB | 1793.5MB | |
| Heap Objects | 715,167 | 529,309 | +185858 | 862,692 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 34 | 14,137 | 171.3MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 3.51MB |
| 6 | `bufio.NewWriterSize` | 3.04MB |
| 7 | `bufio.NewReaderSize` | 2.52MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `aws/endpoints.init` | 2.0MB |
| 10 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 1.51MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 236.61GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 138.0GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 137.29GB |
| 4 | `internal/evaluation.mergeMetadata` | 133.66GB |
| 5 | `reflect.unsafe_NewArray` | 102.08GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 91.15GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 69.58GB |
| 8 | `experiment/local.topologicalSort` | 68.27GB |
| 9 | `reflect.MakeSlice` | 56.99GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 39.73GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 288/290 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/290 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.72MB | 284/290 | `██████░░░░░░░░░ 40%` |
| 4 | `bytes.growSlice` | 10.81MB | 37/290 | `████░░░░░░░░░░░ 29%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.48MB | 14/290 | `████░░░░░░░░░░░ 28%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/290 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 287/290 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 279/290 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/290 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.43MB | 7/290 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 119.91GB | 281/290 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.05GB | 283/290 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 70.76GB | 282/290 | `████████░░░░░░░ 59%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.13GB | 277/290 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 51.8GB | 281/290 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 49.91GB | 266/290 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.21GB | 279/290 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.73GB | 278/290 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 29.05GB | 279/290 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.73GB | 266/290 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
