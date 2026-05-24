# Overview: prod
*Last updated: 2026-05-24 10:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-24T10:31 (444 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,047 | avg: 15,677 | max: 84,644 | trend: INCREASING (+0.66/hr))
```
▁▁▁▁▁▁▁▁▁▁▂▁▂▁▂▂▁▁▂▁▁▁▂▃▁▅▄▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▅▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁
```

**Heap InUse** (current: 293.0MB | avg: 231.3MB | max: 1896.6MB | trend: stable (-0.10MB/hr))
```
▂▁▁▂▁▂▁▂▂▂▃▁▃▁▂▃▁▂▁▁▁▁▃▃▁▃▄▂▂▂▂▂▁▁▁▁▁▁▄▁▁▁▁▁▁▂▃▂▂▃▁▁▂▁▁▂▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁▁▁▁▁▂▁▂▁▁▁▁▂▂▂▁▁▂▁▁▁▂█▃
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 17%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,047 | 27,994 | -12947 | 15,677 | 84,644 | INCREASING (+0.66/hr) |
| Heap InUse | 293.0MB | 622.0MB | -329.0MB | 231.3MB | 1896.6MB | stable (-0.10MB/hr) |
| Heap Sys | 4444.5MB | 4438.2MB | +6.3MB | 4209.7MB | 6883.9MB | |
| Heap Objects | 1,017,550 | 3,573,261 | -2555711 | 985,768 | 8,100,802 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,311 | 239.5MB | 280.1MB |
| 2026-05-16 | 49 | 15,985 | 246.0MB | 1896.6MB |
| 2026-05-17 | 48 | 14,799 | 174.8MB | 391.4MB |
| 2026-05-18 | 53 | 15,650 | 264.5MB | 670.7MB |
| 2026-05-19 | 48 | 15,324 | 230.9MB | 661.0MB |
| 2026-05-20 | 48 | 17,037 | 257.2MB | 1004.2MB |
| 2026-05-21 | 68 | 16,073 | 267.1MB | 501.2MB |
| 2026-05-22 | 50 | 16,200 | 234.4MB | 962.7MB |
| 2026-05-23 | 48 | 14,757 | 174.9MB | 359.1MB |
| 2026-05-24 | 22 | 14,984 | 187.8MB | 622.0MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `runtime.mallocgc` | 48.11MB |
| 2 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `bytes.growSlice` | 6.53MB |
| 5 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 7 | `compress/flate.NewWriter` | 4.41MB |
| 8 | `segmentio/kafka-go.makePartitions` | 2.51MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `reflect.unsafe_NewArray` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 132.89GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 50.67GB |
| 3 | `segmentio/kafka-go.makePartitions` | 27.3GB |
| 4 | `reflect.growslice` | 24.64GB |
| 5 | `jackskj/carta.getUniqueId` | 20.3GB |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 19.66GB |
| 7 | `reflect.unsafe_New` | 18.88GB |
| 8 | `dotlapse-event-service/BackendComparison.convertToImagePointers` | 18.52GB |
| 9 | `database/sql.convertAssignRows` | 15.08GB |
| 10 | `fmt.(*buffer).writeString` | 14.04GB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 54.33MB | 10/444 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 43.59MB | 17/444 | `████████████░░░ 80%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 442/444 | `██████████░░░░░ 67%` |
| 4 | `database/sql.convertAssignRows` | 28.62MB | 21/444 | `███████░░░░░░░░ 52%` |
| 5 | `runtime.mallocgc` | 22.41MB | 442/444 | `██████░░░░░░░░░ 41%` |
| 6 | `bytes.growSlice` | 13.72MB | 300/444 | `███░░░░░░░░░░░░ 25%` |
| 7 | `net/http.(*Transport).dialConn` | 12.08MB | 6/444 | `███░░░░░░░░░░░░ 22%` |
| 8 | `net/http.(*Transport).tryPutIdleConn` | 11.08MB | 7/444 | `███░░░░░░░░░░░░ 20%` |
| 9 | `dotlapse-event-service/Build.prepareImageComparisonArr` | 10.7MB | 1/444 | `██░░░░░░░░░░░░░ 19%` |
| 10 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/444 | `██░░░░░░░░░░░░░ 19%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/444 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/444 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/444 | `████████░░░░░░░ 59%` |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 52.07GB | 419/444 | `██████░░░░░░░░░ 41%` |
| 5 | `experiment/local.topologicalSort` | 51.23GB | 375/444 | `██████░░░░░░░░░ 40%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/444 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/444 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 24.34GB | 376/444 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `fmt.(*buffer).writeString` | 18.38GB | 22/444 | `██░░░░░░░░░░░░░ 14%` |
| 10 | `fmt.Sprintf` | 18.14GB | 201/444 | `██░░░░░░░░░░░░░ 14%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (8.2x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (5.4x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (2.9x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (2.9x avg)
- Heap spike to 786.9MB at 2026-05-20T02:02 (3.4x avg)
- Heap spike to 958.1MB at 2026-05-20T10:30 (4.1x avg)
- Goroutine spike to 33,655 at 2026-05-20T10:30 (2.1x avg)
- Heap spike to 621.3MB at 2026-05-20T20:30 (2.7x avg)
- Heap spike to 1004.2MB at 2026-05-20T22:02 (4.3x avg)
- Goroutine spike to 48,719 at 2026-05-20T22:02 (3.1x avg)
