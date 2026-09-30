Backend and systems engineer. Go and Python in production, low-latency services, and the unusual part: an electronics and instrumentation background, so I am just as comfortable with a CAD assembly, an ESP32 board or a neural network as with a Kafka pipeline.

- **Backend:** Go (Middle, 2+ years commercial), Python, gRPC, REST, Kafka, PostgreSQL, Redis
- **Infra:** Docker, Kubernetes, GitLab CI / GitHub Actions, Prometheus, Grafana, Linux
- **ML:** machine and deep learning, PyTorch, signal processing (Innopolis University, retraining program)
- **Frontend:** React, TypeScript, Tailwind, Three.js / WebGL
- **Engineering:** SolidWorks, KOMPAS-3D, AutoCAD, CadQuery, circuit design, embedded C++ on ESP32
- **Education:** Saint Petersburg Electrotechnical University "LETI", electronics, instrument engineering (MSc in progress)

---

#### Featured

| Project | What it shows | Numbers |
|---|---|---|
| [**orderbook-engine**](https://github.com/YoungOver/orderbook-engine) | Matching engine in Go: single-writer loops, group-commit journal with crash recovery, SSE market data | 3.6M orders/s core, 95k HTTP req/s, 433k records replayed in 96 ms |
| [**logbroker**](https://github.com/YoungOver/logbroker) | Kafka-style broker: segmented commit log, sparse index, sendfile fetch with long polling, group-commit fsync, consumer groups | 1.22M msg/s, 559 MB/s, restart over 9.4 GB in 2.4 s |
| [**tsdb-gorilla**](https://github.com/YoungOver/tsdb-gorilla) | Time-series DB: Gorilla compression, sharded store, group-commit WAL, zero-alloc line protocol parser | 10M samples/s ingest, 0.4 to 3 bytes/sample, 53k queries/s |
| [**geo-dispatch**](https://github.com/YoungOver/geo-dispatch) | Real-time courier location index: 17-byte UDP pings, sharded grid, ring-based nearest search | 467k pings/s while serving 25k dispatch queries/s |
| [**web-studio**](https://github.com/YoungOver/web-studio) | 10 production-style sites: React 19, Tailwind 4, shadcn/ui, GSAP, React Three Fiber | Lighthouse-friendly, mobile first |
| [**cad-engineering**](https://github.com/YoungOver/cad-engineering) | Mechanical design as code: CadQuery assemblies, ESKD drawings, sheet metal flat patterns, DXF plans | STEP / STL / DXF from one script |
| [**esp32-greenhouse**](https://github.com/YoungOver/esp32-greenhouse) | ESP32 firmware with web UI and MQTT, schematic generated from code | |
| [**python-automation**](https://github.com/YoungOver/python-automation) | aiogram booking bot, async scraper to Excel, Google Sheets automation | |
| [**threejs-viz**](https://github.com/YoungOver/threejs-viz) | Three.js product animation and interior 3D with a deterministic video recorder | |
| [**data-analytics**](https://github.com/YoungOver/data-analytics) | Excel financial model with live formulas, pandas sales report | |

<p>
<img src="https://raw.githubusercontent.com/YoungOver/logbroker/main/docs/bench.png" width="49%">
<img src="https://raw.githubusercontent.com/YoungOver/tsdb-gorilla/main/docs/bench.png" width="49%">
<img src="https://raw.githubusercontent.com/YoungOver/orderbook-engine/main/docs/bench.png" width="49%">
<img src="https://raw.githubusercontent.com/YoungOver/geo-dispatch/main/docs/demo.png" width="49%">
</p>

