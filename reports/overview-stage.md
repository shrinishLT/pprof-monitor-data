# Overview: stage
*Last updated: 2026-05-21 06:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T06:33 (270 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,435 | avg: 14,302 | max: 28,205 | trend: INCREASING (+0.68/hr))
```
▂▁▁▁▁▁▁▁▁▁▁▃▁▃▁▃▁▅▁▁▁▁▃▂▄▅▁▁▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁█▁▂▁▂▁▃▁▁▁▁▁▂▅▂▄▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▄▁▅▆
```

**Heap InUse** (current: 211.3MB | avg: 167.5MB | max: 732.9MB | trend: stable (+0.37MB/hr))
```
▂▁▃▁▁▂▁▃▁▂▂▂▂▂▂▂▂▃▂▂▁▂▂▃▂▂▂▂▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 11%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,435 | 14,392 | +43 | 14,302 | 28,205 | INCREASING (+0.68/hr) |
| Heap InUse | 211.3MB | 252.1MB | -40.8MB | 167.5MB | 732.9MB | stable (+0.37MB/hr) |
| Heap Sys | 1792.6MB | 1792.5MB | +0.1MB | 1293.7MB | 1793.5MB | |
| Heap Objects | 756,361 | 799,681 | -43320 | 863,371 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 14 | 14,141 | 176.5MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 18.01MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 9.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `bufio.NewWriterSize` | 3.04MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 2.02MB |
| 9 | `bytes.growSlice` | 2.01MB |
| 10 | `aws/endpoints.init` | 2.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 225.74GB |
| 2 | `experiment/local.(*Client).EvaluateV2` | 137.18GB |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 136.46GB |
| 4 | `internal/evaluation.mergeMetadata` | 132.81GB |
| 5 | `reflect.unsafe_NewArray` | 97.44GB |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 91.07GB |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 69.15GB |
| 8 | `experiment/local.topologicalSort` | 67.86GB |
| 9 | `reflect.MakeSlice` | 54.36GB |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 39.7GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 268/270 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 18.48MB | 5/270 | `███████░░░░░░░░ 50%` |
| 3 | `runtime.mallocgc` | 14.47MB | 264/270 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 11.17MB | 13/270 | `████░░░░░░░░░░░ 30%` |
| 5 | `bytes.growSlice` | 11.0MB | 36/270 | `████░░░░░░░░░░░ 30%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/270 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 267/270 | `███░░░░░░░░░░░░ 25%` |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 8.97MB | 259/270 | `███░░░░░░░░░░░░ 24%` |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.59MB | 6/270 | `███░░░░░░░░░░░░ 23%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.43MB | 7/270 | `███░░░░░░░░░░░░ 23%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 111.39GB | 261/270 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 65.99GB | 263/270 | `████████░░░░░░░ 59%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 65.71GB | 262/270 | `████████░░░░░░░ 58%` |
| 4 | `internal/evaluation.mergeMetadata` | 65.22GB | 257/270 | `████████░░░░░░░ 58%` |
| 5 | `reflect.unsafe_NewArray` | 48.13GB | 261/270 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.55GB | 246/270 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 33.66GB | 259/270 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 33.23GB | 258/270 | `████░░░░░░░░░░░ 29%` |
| 9 | `reflect.MakeSlice` | 27.0GB | 259/270 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.27GB | 246/270 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
