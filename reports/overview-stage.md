# Overview: stage
*Last updated: 2026-05-22 05:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T05:00 (341 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,063 | avg: 14,314 | max: 28,205 | trend: INCREASING (+0.61/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 143.2MB | avg: 170.6MB | max: 732.9MB | trend: stable (+0.27MB/hr))
```
▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▂▂▁▂▂▁▂▁▂▂▂▂▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 7%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,063 | 14,063 | +0 | 14,314 | 28,205 | INCREASING (+0.61/hr) |
| Heap InUse | 143.2MB | 197.0MB | -53.8MB | 170.6MB | 732.9MB | stable (+0.27MB/hr) |
| Heap Sys | 1344.8MB | 1344.8MB | +0.0MB | 1311.2MB | 1793.6MB | |
| Heap Objects | 558,325 | 1,205,357 | -647032 | 881,717 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 72 | 14,362 | 180.0MB | 556.9MB |
| 2026-05-22 | 13 | 14,101 | 189.6MB | 231.6MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 7 | `compress/flate.NewWriter` | 1.76MB |
| 8 | `bufio.NewReaderSize` | 1.55MB |
| 9 | `compress/flate.(*compressor).initDeflate` | 1.07MB |
| 10 | `bufio.NewWriterSize` | 1.02MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 23.64GB |
| 2 | `reflect.unsafe_NewArray` | 10.31GB |
| 3 | `reflect.MakeSlice` | 5.75GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.62GB |
| 5 | `segmentio/kafka-go.makeLayout` | 2.53GB |
| 6 | `fmt.Sprintf` | 1.96GB |
| 7 | `v3/newrelic.newAnalyticsEvents` | 1.38GB |
| 8 | `internal/reflectlite.unsafe_New` | 1.14GB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 1.14GB |
| 10 | `compress/flate.NewWriter` | 948.42MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 339/341 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/341 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.55MB | 335/341 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/341 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.18MB | 16/341 | `████░░░░░░░░░░░ 33%` |
| 6 | `bytes.growSlice` | 10.64MB | 54/341 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/341 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/341 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/341 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/341 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 104.4GB | 332/341 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/341 | `██████████░░░░░ 68%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/341 | `██████████░░░░░ 68%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/341 | `██████████░░░░░ 67%` |
| 5 | `reflect.unsafe_NewArray` | 45.11GB | 332/341 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 42.76GB | 317/341 | `██████░░░░░░░░░ 40%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/341 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/341 | `█████░░░░░░░░░░ 34%` |
| 9 | `reflect.MakeSlice` | 25.27GB | 330/341 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 18.62GB | 317/341 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
