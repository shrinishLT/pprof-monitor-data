# Overview: prod
*Last updated: 2026-06-04 01:30 IST*
*Data range: 2026-05-15T16:03 to 2026-06-04T01:30 (973 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 18,393 | avg: 10,058 | max: 84,644 | trend: decreasing (-40.50/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▄▁▅▅▅▅▅▅▄▅▅▅▅▄▄▄▄▄▅▅▅▅▅▅▄█▆
```

**Heap InUse** (current: 338.6MB | avg: 147.9MB | max: 1896.6MB | trend: decreasing (-0.61MB/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▃▁▅▄▃▃▄▃▃▄▂▅▄▂▂▂▃▂▃▃▃▃▃▃▂█▅
```

## Current Status

Goroutines: `████░░░░░░░░░░░░░░░░ 21%`
Heap InUse: `░░░░░░░░░░░░░░░░░░░░ 4%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 18,393 | 25,305 | -6912 | 10,058 | 84,644 | decreasing (-40.50/hr) |
| Heap InUse | 338.6MB | 519.6MB | -181.0MB | 147.9MB | 1896.6MB | decreasing (-0.61MB/hr) |
| Heap Sys | 846.1MB | 842.0MB | +4.1MB | 2569.9MB | 6883.9MB | |
| Heap Objects | 691,090 | 1,821,042 | -1129952 | 631,543 | 8,100,802 | |

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
| 2026-06-04 | 19 | 15,560 | 207.2MB | 519.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `bytes.growSlice` | 30.21MB |
| 3 | `bufio.NewWriterSize` | 16.56MB |
| 4 | `runtime.mallocgc` | 14.13MB |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 14.07MB |
| 6 | `bufio.NewReaderSize` | 11.04MB |
| 7 | `sirupsen/logrus.(*Entry).WithFields` | 9.5MB |
| 8 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 9 | `aes/gcm.NewGCMForTLS13` | 8.01MB |
| 10 | `http2/hpack.(*headerFieldTable).addEntry` | 3.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `dotlapse-event-service/project.ApplyPagination` | 2.14GB |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 854.83MB |
| 3 | `fmt.Sprintf` | 784.91MB |
| 4 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 732.6MB |
| 5 | `dotlapse-event-service/Build.FilterByGivenBuildStatus` | 615.11MB |
| 6 | `strconv.appendQuotedWith` | 387.7MB |
| 7 | `fmt.Sprint` | 373.62MB |
| 8 | `go-sql-driver/mysql.(*binaryRows).readRow` | 368.01MB |
| 9 | `segmentio/kafka-go.makePartitions` | 367.25MB |
| 10 | `database/sql.convertAssignRows` | 328.02MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 30.60MB | 25.54MB | 73.81MB | 0B |
| `evaluation.mergeMetadata` | 15.00MB | 11.50MB | 38.24MB | 0B |
| `local.(*Client).EvaluateV2` | 49.09MB | 39.92MB | 111.30MB | 0B |
| `local.topologicalSort` | 9.11MB | 6.58MB | 18.68MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 44.07MB | 36.95MB | 96.93MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 7.08MB | 5.03MB | 23.05MB | 0B |
| `localEvaluation.getMapOfValue` | 44.07MB | 36.95MB | 96.93MB | 0B |
| `utils.ParseFeatureFlag` | 44.07MB | 36.95MB | 97.25MB | 0B |

**Total FF alloc (current snapshot):** 243.11MB  |  **24h avg:** 556.18MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `dotlapse-event-service/project.FetchProjectFilter` | 49.06MB | 26/973 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.ApplyPagination` | 43.74MB | 16/973 | `█████████████░░ 89%` |
| 3 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 624/973 | `███████████░░░░ 74%` |
| 4 | `database/sql.convertAssignRows` | 26.03MB | 34/973 | `███████░░░░░░░░ 53%` |
| 5 | `runtime.mallocgc` | 21.86MB | 624/973 | `██████░░░░░░░░░ 44%` |
| 6 | `bytes.growSlice` | 13.4MB | 433/973 | `████░░░░░░░░░░░ 27%` |
| 7 | `net/http.(*Transport).dialConn` | 11.31MB | 8/973 | `███░░░░░░░░░░░░ 23%` |
| 8 | `internal/evaluation.mergeMetadata` | 10.58MB | 64/973 | `███░░░░░░░░░░░░ 21%` |
| 9 | `dotlapse-event-service/Build.FetchBuildsWithFilter` | 9.32MB | 5/973 | `██░░░░░░░░░░░░░ 18%` |
| 10 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.2MB | 617/973 | `██░░░░░░░░░░░░░ 18%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/evaluation.mergeMetadata` | 125.38GB | 387/973 | `███████████████ 100%` |
| 2 | `internal/evaluation.(*Engine).Evaluate` | 74.55GB | 393/973 | `████████░░░░░░░ 59%` |
| 3 | `experiment/local.(*Client).EvaluateV2` | 74.52GB | 393/973 | `████████░░░░░░░ 59%` |
| 4 | `experiment/local.topologicalSort` | 51.23GB | 375/973 | `██████░░░░░░░░░ 40%` |
| 5 | `dotlapse-event-service/project.ApplyPagination` | 46.31GB | 601/973 | `█████░░░░░░░░░░ 36%` |
| 6 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 43.59GB | 343/973 | `█████░░░░░░░░░░ 34%` |
| 7 | `internal/evaluation.(*Engine).evaluateFlag` | 28.09GB | 316/973 | `███░░░░░░░░░░░░ 22%` |
| 8 | `dotlapse-event-service/project.FetchProjectFilter` | 20.67GB | 554/973 | `██░░░░░░░░░░░░░ 16%` |
| 9 | `fmt.Sprintf` | 15.24GB | 291/973 | `█░░░░░░░░░░░░░░ 12%` |
| 10 | `segmentio/kafka-go.makePartitions` | 13.37GB | 406/973 | `█░░░░░░░░░░░░░░ 10%` |

## Alerts

- Heap spike to 1896.6MB at 2026-05-16T02:03 (12.8x avg)
- Goroutine spike to 84,644 at 2026-05-16T02:03 (8.4x avg)
- Heap spike to 433.8MB at 2026-05-16T03:31 (2.9x avg)
- Goroutine spike to 20,552 at 2026-05-16T03:31 (2.0x avg)
- Heap spike to 478.7MB at 2026-05-16T06:02 (3.2x avg)
- Heap spike to 391.4MB at 2026-05-17T10:03 (2.6x avg)
- Goroutine spike to 27,990 at 2026-05-17T10:03 (2.8x avg)
- Heap spike to 404.6MB at 2026-05-18T06:03 (2.7x avg)
- Heap spike to 373.5MB at 2026-05-18T10:01 (2.5x avg)
- Goroutine spike to 21,569 at 2026-05-18T10:01 (2.1x avg)
