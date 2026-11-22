# SocketSweep

A zero-dependency, multi-threaded TCP port scanner, service fingerprinter, and passive/active HTTP banner grabber built from scratch in Python.

### [Launch Interactive Live Showcase & Documentation ->](https://github.io)

---

## Quick Start

```bash
git clone https://github.com
cd SocketSweep
python3 socketsweep.py -t scanme.nmap.org -p 1-1024 -o report.json
```

*Requires Python 3.8+ (uses only standard library modules: `socket`, `concurrent.futures`, `threading`, `argparse`, `json`).*

---

## Legal Notice

For authorized security auditing and educational lab testing only (Indian IT Act, 2000 — Sections 43 & 66).

**Engineered by [Madhan M (`27thEncoder`)](https://github.io)**
