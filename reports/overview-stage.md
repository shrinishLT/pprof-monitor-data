# Overview: stage
*Last updated: 2026-05-21 19:31 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T19:31 (316 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,161 | avg: 14,328 | max: 28,205 | trend: INCREASING (+1.34/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 155.6MB | avg: 169.4MB | max: 732.9MB | trend: stable (+0.29MB/hr))
```
▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,161 | 14,222 | -61 | 14,328 | 28,205 | INCREASING (+1.34/hr) |
| Heap InUse | 155.6MB | 197.2MB | -41.6MB | 169.4MB | 732.9MB | stable (+0.29MB/hr) |
| Heap Sys | 1343.5MB | 1343.4MB | +0.1MB | 1308.6MB | 1793.6MB | |
| Heap Objects | 567,006 | 1,033,656 | -466650 | 869,692 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 60 | 14,400 | 179.7MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `bufio.NewReaderSize` | 3.57MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `reflect.mapassign_faststr0` | 3.5MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `bufio.NewWriterSize` | 2.02MB |
| 10 | `bytes.growSlice` | 2.01MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 8.64GB |
| 2 | `reflect.unsafe_NewArray` | 3.76GB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 2.62GB |
| 4 | `reflect.MakeSlice` | 2.11GB |
| 5 | `fmt.Sprintf` | 1.55GB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 1.14GB |
| 7 | `segmentio/kafka-go.makeLayout` | 950.28MB |
| 8 | `strconv.appendQuotedWith` | 725.7MB |
| 9 | `fmt.Sprint` | 704.03MB |
| 10 | `v3/newrelic.newAnalyticsEvents` | 514.83MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 314/316 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/316 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.54MB | 310/316 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/316 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.18MB | 16/316 | `████░░░░░░░░░░░ 33%` |
| 6 | `bytes.growSlice` | 11.31MB | 50/316 | `████░░░░░░░░░░░ 30%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/316 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/316 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/316 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/316 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 111.6GB | 307/316 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/316 | `█████████░░░░░░ 64%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/316 | `█████████░░░░░░ 63%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/316 | `█████████░░░░░░ 63%` |
| 5 | `reflect.unsafe_NewArray` | 48.21GB | 307/316 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 46.2GB | 292/316 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/316 | `████░░░░░░░░░░░ 32%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/316 | `████░░░░░░░░░░░ 32%` |
| 9 | `reflect.MakeSlice` | 27.02GB | 305/316 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.12GB | 292/316 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
