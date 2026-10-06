# Wireless Threat Detection · security tooling

**Problem:** security operators need persistent, interpretable signals beyond a single MAC address.

**Implemented:** a Python/Kismet observation pipeline, multi-signal fingerprinting, configurable presence and suspicious-SSID checks, SQLite state, and a REST/WebSocket browser dashboard.

![Architecture](../assets/wifi.svg)

Dor built the application during an R&D internship; Kismet supplies the upstream capture service. The [public repository](https://github.com/doric2000/wifi-threat-detection-portfolio) is an independent sanitized snapshot with new Git history, generic lab settings, synthetic data, setup instructions, and evidence limits.

Review `fingerprint.py`, `logic_engine.py`, `db.py`, and the live runner. Fingerprints and RSSI are heuristic signals, not guaranteed identity/proximity. No measured accuracy, false-positive rate, or BLE pipeline is claimed. The portfolio publication did not use company hardware.
