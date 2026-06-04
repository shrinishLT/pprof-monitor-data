# Overview: prod
*Last updated: 2026-06-04 19:42 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T19:42 (1191 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 16,979 | avg: 11,292 | max: 84,644 | trend: decreasing (-11.86/hr))
```
▁▁▁▁▁▁▁▁▁▁▃▅█▇▇▇▄▂▃▂▁▃▄▅▄▁▁▂▂▄▃▃▂▁▂▂▅▅▃▄▅▆▄▃▂▄▅▂▂▁▂▂▂▁▁▃▄▄▃▄▇▃▁▂▂▂▂▁▁▁▁▁▂▂▂▁▁▁▂▁▁▁▁▂▂▁▁▁▁▁▁▁▁▃▂▃
```

**Heap InUse** (current: 279.7MB | avg: 171.3MB | max: 2823.8MB | trend: stable (-0.14MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▃▃▅▅▅▄▅▃▃▃▂▃▃▄▄▂▂▂▂▃▃▃▂▂█▂▄▄▃▄▄▅▄▃▂▃▄▂▂▂▂▃▃▂▁▃▃▃▃▅▄▄▁▂▃▂▂▂▁▁▂▁▂▂▂▁▁▁▂▂▂▁▁▂▂▁▁▂▂▂▁▁▂▂▂▃
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 20%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 16,979 | 15,917 | +1062 | 11,292 | 84,644 | decreasing (-11.86/hr) |
| Heap InUse | 279.7MB | 255.9MB | +23.8MB | 171.3MB | 2823.8MB | stable (-0.14MB/hr) |
| Heap Sys | 3859.4MB | 3859.2MB | +0.2MB | 2633.3MB | 6883.9MB | |
| Heap Objects | 1,294,467 | 1,250,460 | +44007 | 741,115 | 14,090,816 | |

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
| 2026-06-04 | 237 | 16,700 | 270.3MB | 2823.8MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 19.81MB |
| 3 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.06MB |
| 4 | `runtime.mallocgc` | 11.01MB |
| 5 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 6 | `bufio.NewReaderSize` | 9.06MB |
| 7 | `bufio.NewWriterSize` | 8.03MB |
| 8 | `sirupsen/logrus.(*Entry).WithFields` | 6.0MB |
| 9 | `http2/hpack.(*headerFieldTable).addEntry` | 3.0MB |
| 10 | `compress/flate.NewWriter` | 2.64MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 9.07GB |
| 2 | `dotlapse-event-service/testinfo.scanImagesFromRows` | 7.59GB |
| 3 | `segmentio/kafka-go.makePartitions` | 3.63GB |
| 4 | `dotlapse-event-service/project.FetchProjectFilter` | 3.6GB |
| 5 | `fmt.Sprintf` | 2.72GB |
| 6 | `database/sql.convertAssignRows` | 2.65GB |
| 7 | `go-sql-driver/mysql.(*binaryRows).readRow` | 2.45GB |
| 8 | `reflect.unsafe_NewArray` | 1.87GB |
| 9 | `jackskj/carta.getUniqueId` | 1.68GB |
| 10 | `strconv.appendQuotedWith` | 1.37GB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 323.65MB | 313.42MB | 296.90MB | 0B |
| `evaluation.mergeMetadata` | 163.04MB | 160.04MB | 154.77MB | 0B |
| `local.(*Client).EvaluateV2` | 507.50MB | 493.13MB | 460.93MB | 0B |
| `local.topologicalSort` | 73.88MB | 71.85MB | 66.95MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 451.88MB | 440.12MB | 422.40MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 102.26MB | 99.14MB | 80.44MB | 0B |
| `localEvaluation.getMapOfValue` | 451.88MB | 440.12MB | 422.40MB | 0B |
| `utils.ParseFeatureFlag` | 451.88MB | 440.12MB | 422.40MB | 0B |

**Total FF alloc (current snapshot):** 2.47GB  |  **24h avg:** 2.27GB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 64.9MB | 40/1191 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 58.21MB | 24/1191 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 842/1191 | `████████░░░░░░░ 56%` |
| 4 | `database/sql.convertAssignRows` | 31.07MB | 52/1191 | `███████░░░░░░░░ 47%` |
| 5 | `runtime.mallocgc` | 19.62MB | 842/1191 | `████░░░░░░░░░░░ 30%` |
| 6 | `go-sql-driver/mysql.(*binaryRows).readRow` | 18.0MB | 1/1191 | `████░░░░░░░░░░░ 27%` |
| 7 | `bytes.growSlice` | 15.26MB | 628/1191 | `███░░░░░░░░░░░░ 23%` |
| 8 | `dotlapse-event-service/api.CompareScreenshots` | 12.55MB | 1/1191 | `██░░░░░░░░░░░░░ 19%` |
| 9 | `net/http.(*Transport).dialConn` | 12.28MB | 16/1191 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `fmt.Sprint` | 12.05MB | 2/1191 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/1191 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/1191 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/1191 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/1191 | `██████░░░░░░░░░ 40%` |
| 5 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/1191 | `█████░░░░░░░░░░ 34%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 38.95GB | 814/1191 | `████░░░░░░░░░░░ 31%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/1191 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 17.58GB | 737/1191 | `██░░░░░░░░░░░░░ 14%` |
| 9 | `fmt.Sprintf` | 11.52GB | 433/1191 | `█░░░░░░░░░░░░░░ 9%` |
| 10 | `segmentio/kafka-go.makePartitions` | 10.47GB | 575/1191 | `█░░░░░░░░░░░░░░ 8%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (11.1x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (7.5x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.5x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (2.8x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.5x avg)
- Heap spike to 491.8MB at 2026-05-18T12:33 (2.9x avg)
- Heap spike to 670.7MB at 2026-05-18T20:03 (3.9x avg)
- Goroutine spike to 23,165 at 2026-05-18T20:03 (2.1x avg)
- Heap spike to 661.0MB at 2026-05-19T10:02 (3.9x avg)
- Goroutine spike to 26,874 at 2026-05-19T10:02 (2.4x avg)
