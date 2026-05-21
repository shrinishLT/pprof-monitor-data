# Overview: stage
*Last updated: 2026-05-21 15:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T15:00 (298 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,082 | avg: 14,288 | max: 28,205 | trend: stable (-0.01/hr))
```
▁▂▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▆▅▁▁▁▁▁▁▁▁▁▁▁▇▁▂▁▂▁▃▂▁▁▁▁▂▅▂▃▄▁▃▁▂▁▁▁▁▂▁▁▁▁▁▁▁▃▁▅▆█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▇▂▃▁▁▃▃▅▁
```

**Heap InUse** (current: 163.9MB | avg: 167.3MB | max: 732.9MB | trend: stable (+0.26MB/hr))
```
▁▂▁▁▁▂▂▁▁▂▂▃▂▁▃▃▂▂█▃▂▁▁▁▁▂▁▁▁▁▃▃▂▂▃▂▂▃▃▂▂▃▂▁▂▃▁▂▁▂▁▂▁▂▂▃▂▂▂▂▁▂▂▁▂▁▄▃▂▁▃▁▁▃▃▂▁▂▁▁▂▁▂▁▁▁▂▂▁▃▁▁▁▂▁▂
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,082 | 14,389 | -307 | 14,288 | 28,205 | stable (-0.01/hr) |
| Heap InUse | 163.9MB | 133.0MB | +30.9MB | 167.3MB | 732.9MB | stable (+0.26MB/hr) |
| Heap Sys | 443.8MB | 443.5MB | +0.3MB | 1311.9MB | 1793.6MB | |
| Heap Objects | 1,118,779 | 700,704 | +418075 | 864,973 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 42 | 14,146 | 169.1MB | 252.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 3 | `runtime.mallocgc` | 6.01MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 3.53MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `reflect.unsafe_NewArray` | 1.5MB |
| 8 | `reflect.mapassign_faststr0` | 1.5MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.52GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 750.75MB |
| 3 | `reflect.unsafe_NewArray` | 689.29MB |
| 4 | `reflect.MakeSlice` | 423.01MB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 340.73MB |
| 6 | `segmentio/kafka-go.makeLayout` | 179.56MB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 117.0MB |
| 8 | `database/sql.convertAssignRows` | 110.0MB |
| 9 | `v3/newrelic.newAnalyticsEvents` | 100.92MB |
| 10 | `compress/flate.NewWriter` | 79.33MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 296/298 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/298 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.56MB | 292/298 | `█████░░░░░░░░░░ 39%` |
| 4 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 10.48MB | 14/298 | `████░░░░░░░░░░░ 28%` |
| 5 | `bytes.growSlice` | 10.17MB | 40/298 | `████░░░░░░░░░░░ 27%` |
| 6 | `net/http.(*Transport).dialConn` | 10.0MB | 2/298 | `████░░░░░░░░░░░ 27%` |
| 7 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB | 295/298 | `███░░░░░░░░░░░░ 25%` |
| 8 | `database/sql.convertAssignRows` | 9.21MB | 7/298 | `███░░░░░░░░░░░░ 25%` |
| 9 | `sirupsen/logrus.(*Entry).WithFields` | 8.89MB | 287/298 | `███░░░░░░░░░░░░ 24%` |
| 10 | `internal/evaluation.mergeMetadata` | 8.0MB | 8/298 | `███░░░░░░░░░░░░ 21%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 118.25GB | 289/298 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/298 | `█████████░░░░░░ 60%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/298 | `█████████░░░░░░ 60%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/298 | `████████░░░░░░░ 59%` |
| 5 | `reflect.unsafe_NewArray` | 51.08GB | 289/298 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 49.13GB | 274/298 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/298 | `████░░░░░░░░░░░ 30%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/298 | `████░░░░░░░░░░░ 30%` |
| 9 | `reflect.MakeSlice` | 28.64GB | 287/298 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.39GB | 274/298 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.4x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
