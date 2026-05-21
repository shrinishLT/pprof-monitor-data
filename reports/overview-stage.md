# Overview: stage
*Last updated: 2026-05-21 15:12 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T15:12 (301 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,108 | avg: 14,331 | max: 28,205 | trend: INCREASING (+1.68/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁
```

**Heap InUse** (current: 160.1MB | avg: 168.5MB | max: 732.9MB | trend: stable (+0.30MB/hr))
```
▁▁▂▁▁▁▁▁▂▂▁▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 50%`
Heap InUse: `█░░░░░░░░░░░░░░░░░░░ 8%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,108 | 27,410 | -13302 | 14,331 | 28,205 | INCREASING (+1.68/hr) |
| Heap InUse | 160.1MB | 556.9MB | -396.8MB | 168.5MB | 732.9MB | stable (+0.30MB/hr) |
| Heap Sys | 1208.7MB | 1149.1MB | +59.6MB | 1308.2MB | 1793.6MB | |
| Heap Objects | 783,157 | 1,135,034 | -351877 | 865,515 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 45 | 14,442 | 177.1MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 13.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `segmentio/kafka-go.makePartitions` | 4.0MB |
| 6 | `compress/flate.NewWriter` | 3.53MB |
| 7 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 8 | `reflect.mapassign_faststr0` | 2.0MB |
| 9 | `bufio.NewReaderSize` | 1.55MB |
| 10 | `aws/endpoints.init` | 1.0MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 1.82GB |
| 2 | `reflect.unsafe_NewArray` | 830.85MB |
| 3 | `dotlapse-event-service/project.ApplyPagination` | 752.47MB |
| 4 | `fmt.Sprintf` | 648.91MB |
| 5 | `reflect.MakeSlice` | 509.51MB |
| 6 | `dotlapse-event-service/project.FetchProjectFilter` | 341.73MB |
| 7 | `strconv.appendQuotedWith` | 308.95MB |
| 8 | `fmt.Sprint` | 281.37MB |
| 9 | `segmentio/kafka-go.makeLayout` | 216.67MB |
| 10 | `bytes.growSlice` | 203.55MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 15.37MB | 0B | 15.37MB | 0B |
| `evaluation.mergeMetadata` | 9.00MB | 0B | 9.00MB | 0B |
| `local.(*Client).EvaluateV2` | 27.94MB | 0B | 27.94MB | 0B |
| `local.topologicalSort` | 4.04MB | 0B | 4.04MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 31.55MB | 0B | 31.55MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 1.54MB | 0B | 1.54MB | 0B |
| `localEvaluation.getMapOfValue` | 31.55MB | 0B | 31.55MB | 0B |
| `utils.ParseFeatureFlag` | 31.55MB | 0B | 31.55MB | 0B |

**Total FF alloc (current snapshot):** 152.53MB  |  **24h avg:** 152.53MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 299/301 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/301 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 295/301 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/301 | `█████░░░░░░░░░░ 38%` |
| 5 | `bytes.growSlice` | 13.17MB | 41/301 | `█████░░░░░░░░░░ 35%` |
| 6 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/301 | `█████░░░░░░░░░░ 35%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/301 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/301 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/301 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/301 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 117.05GB | 292/301 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/301 | `█████████░░░░░░ 61%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/301 | `█████████░░░░░░ 60%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/301 | `█████████░░░░░░ 60%` |
| 5 | `reflect.unsafe_NewArray` | 50.56GB | 292/301 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 48.6GB | 277/301 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/301 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/301 | `████░░░░░░░░░░░ 30%` |
| 9 | `reflect.MakeSlice` | 28.35GB | 290/301 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 21.16GB | 277/301 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
