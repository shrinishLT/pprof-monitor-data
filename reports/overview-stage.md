# Overview: stage
*Last updated: 2026-05-21 15:33 IST*
*Data range: 2026-05-15T16:03 to 2026-05-21T15:33 (304 snapshots)*

---

## All-Time Trend

**Goroutines** (current: 14,595 | avg: 14,335 | max: 28,205 | trend: INCREASING (+1.79/hr))
```
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁█▁▁▁▁
```

**Heap InUse** (current: 195.7MB | avg: 168.8MB | max: 732.9MB | trend: stable (+0.30MB/hr))
```
▁▁▁▁▁▂▂▁▂▂▁▂▄▂▁▁▁▁▁▁▁▁▁▁▂▂▂▁▂▁▁▂▂▁▁▂▁▁▁▂▁▁▁▁▁▂▁▁▁▂▁▁▁▂▁▁▁▁▂▁▃▂▂▁▂▁▁▂▂▂▁▂▁▁▂▁▁▁▁▁▁▁▁▂▁▁▁▁▁▁▁█▁▁▂▂
```

## Current Status

Goroutines: `██████████░░░░░░░░░░ 51%`
Heap InUse: `██░░░░░░░░░░░░░░░░░░ 10%`

## Metrics

| Metric | Current | Prev | Delta | All-Time Avg | All-Time Max | Trend |
|--------|---------|------|-------|-------------|-------------|-------|
| Goroutines | 14,595 | 14,816 | -221 | 14,335 | 28,205 | INCREASING (+1.79/hr) |
| Heap InUse | 195.7MB | 198.7MB | -3.0MB | 168.8MB | 732.9MB | stable (+0.30MB/hr) |
| Heap Sys | 1213.8MB | 1212.9MB | +0.9MB | 1307.2MB | 1793.6MB | |
| Heap Objects | 926,532 | 923,603 | +2929 | 864,556 | 2,432,873 | |

## Daily Summary

| Date | Snapshots | Avg Goroutines | Avg Heap InUse | Max Heap InUse |
|------|-----------|----------------|----------------|----------------|
| 2026-05-15 | 10 | 14,174 | 142.7MB | 181.5MB |
| 2026-05-16 | 49 | 14,153 | 142.4MB | 201.6MB |
| 2026-05-17 | 48 | 14,110 | 152.2MB | 213.6MB |
| 2026-05-18 | 53 | 14,989 | 189.7MB | 732.9MB |
| 2026-05-19 | 48 | 14,127 | 175.4MB | 293.9MB |
| 2026-05-20 | 48 | 14,138 | 178.7MB | 369.4MB |
| 2026-05-21 | 48 | 14,461 | 178.0MB | 556.9MB |

## Top Heap Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB |
| 2 | `runtime.mallocgc` | 14.67MB |
| 3 | `dotlapse-event-service/workerpool.InitWorkerPool.func1` | 9.25MB |
| 4 | `sirupsen/logrus.(*Entry).WithFields` | 5.0MB |
| 5 | `compress/flate.NewWriter` | 4.41MB |
| 6 | `bytes.growSlice` | 3.52MB |
| 7 | `bufio.NewReaderSize` | 3.05MB |
| 8 | `segmentio/kafka-go.makePartitions` | 3.0MB |
| 9 | `dotlapse-event-service/workerpool.NewRedisWorkerPool` | 2.31MB |
| 10 | `bufio.NewWriterSize` | 1.52MB |

## Top Alloc Consumers (latest snapshot)

| # | Function | Flat |
|---|----------|------|
| 1 | `segmentio/kafka-go.makePartitions` | 2.38GB |
| 2 | `fmt.Sprintf` | 1.31GB |
| 3 | `reflect.unsafe_NewArray` | 1.07GB |
| 4 | `dotlapse-event-service/project.ApplyPagination` | 752.47MB |
| 5 | `reflect.MakeSlice` | 633.51MB |
| 6 | `strconv.appendQuotedWith` | 617.92MB |
| 7 | `fmt.Sprint` | 595.76MB |
| 8 | `bytes.growSlice` | 403.41MB |
| 9 | `dotlapse-event-service/project.FetchProjectFilter` | 341.73MB |
| 10 | `segmentio/kafka-go.makeLayout` | 279.78MB |

## Feature Flag Function Tracking

_Always-monitored FF SDK + caller functions (regardless of top-N rank)._

| Function (substring) | Alloc (current) | Alloc (prev) | Alloc (24h avg) | Heap InUse (current) |
|----------------------|-----------------|--------------|-----------------|----------------------|
| `evaluation.(*Engine).Evaluate` | 26.14MB | 0B | 20.76MB | 0B |
| `evaluation.mergeMetadata` | 13.00MB | 0B | 11.00MB | 0B |
| `local.(*Client).EvaluateV2` | 45.48MB | 0B | 36.71MB | 0B |
| `local.topologicalSort` | 7.09MB | 0B | 5.56MB | 0B |
| `localEvaluation.GetFeatureFlagByOrg` | 48.59MB | 0B | 40.07MB | 0B |
| `localEvaluation.GetFeatureFlagPayload` | 3.08MB | 0B | 2.31MB | 0B |
| `localEvaluation.getMapOfValue` | 48.59MB | 0B | 40.07MB | 0B |
| `utils.ParseFeatureFlag` | 48.59MB | 0B | 40.07MB | 0B |

**Total FF alloc (current snapshot):** 240.59MB  |  **24h avg:** 196.56MB

## Top Heap Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `internal/audit.InitAuditLogWorkerPool.func1` | 36.63MB | 302/304 | `███████████████ 100%` |
| 2 | `dotlapse-event-service/project.FetchProjectFilter` | 17.43MB | 7/304 | `███████░░░░░░░░ 47%` |
| 3 | `runtime.mallocgc` | 14.53MB | 298/304 | `█████░░░░░░░░░░ 39%` |
| 4 | `http2/hpack.(*headerFieldTable).addEntry` | 14.01MB | 1/304 | `█████░░░░░░░░░░ 38%` |
| 5 | `crypto/tls.(*Conn).unmarshalHandshakeMessage` | 12.89MB | 15/304 | `█████░░░░░░░░░░ 35%` |
| 6 | `bytes.growSlice` | 12.55MB | 44/304 | `█████░░░░░░░░░░ 34%` |
| 7 | `net/http.(*Transport).dialConn` | 10.0MB | 2/304 | `████░░░░░░░░░░░ 27%` |
| 8 | `net/http.(*http2Transport).newClientConn.http2NewFramer.func2` | 9.52MB | 1/304 | `███░░░░░░░░░░░░ 25%` |
| 9 | `net/http.(*http2Framer).startWriteDataPadded` | 9.52MB | 1/304 | `███░░░░░░░░░░░░ 25%` |
| 10 | `aes/gcm.NewGCMForTLS13` | 9.32MB | 8/304 | `███░░░░░░░░░░░░ 25%` |

## Top Alloc Contributors (average across all snapshots)

| # | Function | Avg | Seen in | Bar |
|---|----------|-----|---------|-----|
| 1 | `segmentio/kafka-go.makePartitions` | 115.88GB | 295/304 | `███████████████ 100%` |
| 2 | `experiment/local.(*Client).EvaluateV2` | 71.52GB | 285/304 | `█████████░░░░░░ 61%` |
| 3 | `internal/evaluation.(*Engine).Evaluate` | 71.23GB | 284/304 | `█████████░░░░░░ 61%` |
| 4 | `internal/evaluation.mergeMetadata` | 70.59GB | 279/304 | `█████████░░░░░░ 60%` |
| 5 | `reflect.unsafe_NewArray` | 50.06GB | 295/304 | `██████░░░░░░░░░ 43%` |
| 6 | `dotlapse-event-service/project.ApplyPagination` | 48.09GB | 280/304 | `██████░░░░░░░░░ 41%` |
| 7 | `lambda-featureflag-go-sdk/localEvaluation.getMapOfValue` | 36.45GB | 281/304 | `████░░░░░░░░░░░ 31%` |
| 8 | `experiment/local.topologicalSort` | 35.97GB | 280/304 | `████░░░░░░░░░░░ 31%` |
| 9 | `reflect.MakeSlice` | 28.07GB | 293/304 | `███░░░░░░░░░░░░ 24%` |
| 10 | `dotlapse-event-service/project.FetchProjectFilter` | 20.94GB | 280/304 | `██░░░░░░░░░░░░░ 18%` |

## Alerts

- Heap spike to 633.5MB at 2026-05-18T18:53 (3.8x avg)
- Heap spike to 732.9MB at 2026-05-18T19:04 (4.3x avg)
- Heap spike to 536.1MB at 2026-05-18T19:04 (3.2x avg)
- Heap spike to 556.9MB at 2026-05-21T15:06 (3.3x avg)
