# Overview: prod
*Last updated: 2026-06-04 20:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T20:30 (1201 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 15,640 | avg: 11,336 | max: 84,644 | trend: decreasing (-11.13/hr))
```
▃▅█▇▇▇▄▂▂▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃▂▂▂▂▂▃▄▄▃▂
```

**Heap InUse** (current: 253.0MB | avg: 172.1MB | max: 2823.8MB | trend: stable (-0.13MB/hr))
```
▂▃▅▅▅▄▅▃▃▂▁▂▃▃▄▁▂▁▂▃▂▂▂▂█▂▃▄▂▃▄▅▄▃▂▃▄▂▂▁▁▃▃▁▁▂▂▃▃▅▄▃▁▂▃▁▁▁▁▁▁▁▂▁▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▁▂▂▂▂▂▁▁▂▃▃▄▂▂
```

## Current Status

Goroutines: `███░░░░░░░░░░░░░░░░░ 18%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 3%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 15,640 | 17,526 | -1886 | 11,336 | 84,644 | decreasing (-11.13/hr) |
| Heap InUse | 253.0MB | 273.2MB | -20.2MB | 172.1MB | 2823.8MB | stable (-0.13MB/hr) |
| Heap Sys | 3852.8MB | 3853.7MB | -0.9MB | 2643.4MB | 6883.9MB | |
| Heap Objects | 1,249,805 | 625,255 | +624550 | 744,506 | 14,090,816 | |

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
| 2026-05-24 | 48 | 14,694 | 189.5MB | 689.3MB |
| 2026-05-25 | 48 | 15,445 | 248.9MB | 478.8MB |
| 2026-05-26 | 46 | 15,843 | 216.2MB | 639.8MB |
| 2026-05-27 | 47 | 11,771 | 179.8MB | 615.8MB |
| 2026-05-28 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-29 | 49 | 370 | 6.8MB | 333.9MB |
| 2026-05-30 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-05-31 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-01 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-02 | 48 | 0 | 0.0MB | 0.0MB |
| 2026-06-03 | 54 | 2,097 | 29.7MB | 299.4MB |
| 2026-06-04 | 247 | 16,696 | 270.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 11.51MB |
| 3 | `bytes.growSlice` | 10.07MB |
| 4 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 5 | `bufio.NewReaderSize` | 6.55MB |
| 6 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 7 | `bufio.NewWriterSize` | 5.52MB |
| 8 | `compress/flate.NewWriter` | 5.29MB |
| 9 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 4.52MB |
| 10 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 11.0GB |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 9.11GB |
| 3 | `fmt.Sprintf` | 4.79GB |
| 4 | `segmentio/kafka-go.makePartitions` | 4.73GB |
| 5 | `dotlapse-event-service/project.FetchProjectFilter` | 3.62GB |
| 6 | `database/sql.convertAssignRows` | 3.38GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 3.15GB |
| 8 | `jackskj/carta.getUniqueId` | 2.88GB |
| 9 | `reflect.unsafe_NewArray` | 2.44GB |
| 10 | `strconv.appendQuotedWith` | 2.37GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 411.34MB | 402.71MB | 251.82MB | 0B |
| `evaluation.mergeMetadata` | 210.55MB | 207.05MB | 131.33MB | 0B |
| `local.(*Client).EvaluateV2` | 645.58MB | 633.81MB | 392.12MB | 0B |
| `local.topologicalSort` | 89.02MB | 88.02MB | 57.11MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 575.50MB | 564.79MB | 353.45MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 129.57MB | 127.49MB | 75.51MB | 0B |
| `localEvaluation.getMapOfValue` | 575.50MB | 564.79MB | 353.45MB | 0B |
| `utils.ParseFeatureFlag` | 575.50MB | 564.79MB | 353.45MB | 0B |

**Total FF alloc (current snapshot):** 3.14GB  |  **24h avg:** 1.92GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1201 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1201 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 852/1201 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1201 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.52MB | 852/1201 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1201 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.31MB | 638/1201 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1201 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1201 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1201 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1201 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1201 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1201 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1201 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1201 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.59GB | 824/1201 | `████░░░░░░░░░░░ 30%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1201 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.39GB | 747/1201 | `██░░░░░░░░░░░░░ 13%` |
| 9 | `fmt.Sprintf` | 11.34GB | 443/1201 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.36GB | 585/1201 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.0x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.0x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.8x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
