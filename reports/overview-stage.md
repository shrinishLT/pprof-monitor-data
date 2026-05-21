# Overview: stage
*Last updated: 2026-05-21 23:30 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T23:30 (327 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,250 | avg: 14,323 | max: 28,205 | trend: INCREASING (+1.02/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 189.4MB | avg: 169.7MB | max: 732.9MB | trend: stable (+0.28MB/hr))
```
▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,250 | 14,063 | +187 | 14,323 | 28,205 | INCREASING (+1.02/hr) |
| Heap InUse | 189.4MB | 193.1MB | -3.7MB | 169.7MB | 732.9MB | stable (+0.28MB/hr) |
| Heap Sys | 1343.6MB | 1344.0MB | -0.4MB | 1309.8MB | 1793.6MB | |
| Heap Objects | 910,164 | 1,186,658 | -276494 | 871,569 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 71 | 14,364 | 179.5MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bufio.NewReaderSize` | 3.56MB |
| 7 | `bytes.growSlice` | 2.51MB |
| 8 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 9 | `reflect.unsafe_NewArray` | 2.0MB |
| 10 | `segmentio/kafka-go.makePartitions` | 1.5MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 14.88GB |
| 2 | `reflect.unsafe_NewArray` | 6.58GB |
| 3 | `reflect.MakeSlice` | 3.64GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.62GB |
| 5 | `fmt.Sprintf` | 1.71GB |
| 6 | `segmentio/kafka-go.makeLayout` | 1.6GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 1.14GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 881.56MB |
| 9 | `strconv.appendQuotedWith` | 809.47MB |
| 10 | `fmt.Sprint` | 783.28MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 325/327 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/327 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.54MB | 321/327 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/327 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.18MB | 16/327 | `████░░░░░░░░░░░ 33%` |
| 6 | `bytes.growSlice` | 10.79MB | 53/327 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/327 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/327 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/327 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/327 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 108.15GB | 318/327 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/327 | `█████████░░░░░░ 66%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/327 | `█████████░░░░░░ 65%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/327 | `█████████░░░░░░ 65%` |
| 5 | `reflect.unsafe_NewArray` | 46.72GB | 318/327 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 44.62GB | 303/327 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/327 | `█████░░░░░░░░░░ 33%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/327 | `████░░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 26.19GB | 316/327 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.43GB | 303/327 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
