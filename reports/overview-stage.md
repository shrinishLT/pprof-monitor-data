# Overview: stage
*Last updated: 2026-05-22 02:00 IST*
*Data range: 2026-05-15T16:03 to 2026-05-22T02:00 (334 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,063 | avg: 14,318 | max: 28,205 | trend: INCREASING (+0.79/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
```

**Heap InUse** (current: 176.1MB | avg: 170.2MB | max: 732.9MB | trend: stable (+0.28MB/hr))
```
▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂▂▂▁▂▁▂▂▂▁▁▂▁▂▁▁▁▁▁▂▁▁▂▂▂▁▂▂▁▂▁
```

## Current Status

Goroutines: `█████████░░░░░░░░░░░ 49%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 9%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,063 | 14,061 | +2 | 14,318 | 28,205 | INCREASING (+0.79/hr) |
| Heap InUse | 176.1MB | 212.5MB | -36.4MB | 170.2MB | 732.9MB | stable (+0.28MB/hr) |
| Heap Sys | 1344.2MB | 1344.2MB | +0.0MB | 1310.5MB | 1793.6MB | |
| Heap Objects | 953,548 | 1,397,980 | -444432 | 877,646 | 2,432,873 | |

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
| 2026-05-22 | 6 | 14,067 | 189.2MB | 218.1MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.51MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `bufio.NewReaderSize` | 1.55MB |
| 9 | `bufio.NewWriterSize` | 1.02MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 18.85GB |
| 2 | `reflect.unsafe_NewArray` | 8.25GB |
| 3 | `reflect.MakeSlice` | 4.59GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 2.62GB |
| 5 | `segmentio/kafka-go.makeLayout` | 2.03GB |
| 6 | `fmt.Sprintf` | 1.73GB |
| 7 | `dotlapse-event-service/project.FetchProjectFilter` | 1.14GB |
| 8 | `v3/newrelic.newAnalyticsEvents` | 1.09GB |
| 9 | `internal/reflectlite.unsafe_New` | 921.58MB |
| 10 | `strconv.appendQuotedWith` | 815.98MB |

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 332/334 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/334 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.54MB | 328/334 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/334 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.18MB | 16/334 | `████░░░░░░░░░░░ 33%` |
| 6 | `bytes.growSlice` | 10.64MB | 54/334 | `████░░░░░░░░░░░ 29%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/334 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/334 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/334 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/334 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 106.18GB | 325/334 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/334 | `██████████░░░░░ 67%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/334 | `██████████░░░░░ 67%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/334 | `█████████░░░░░░ 66%` |
| 5 | `reflect.unsafe_NewArray` | 45.88GB | 325/334 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 43.67GB | 310/334 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/334 | `█████░░░░░░░░░░ 34%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/334 | `█████░░░░░░░░░░ 33%` |
| 9 | `reflect.MakeSlice` | 25.71GB | 323/334 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 19.01GB | 310/334 | `██░░░░░░░░░░░░░ 17%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.7x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.1x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
