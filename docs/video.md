# AI Video Security Pipeline · applied AI integration

**Problem:** detecting a person is not enough to explain a security event.

**Implemented:** closed-event ingestion from Frigate/MQTT, contextual gating, clip retrieval and temporal evidence, local model orchestration, decision artifacts, and threshold-based event annotation. Dor built the worker and operator UI during an R&D internship. Frigate, Ollama, vLLM, and Mosquitto remain credited upstream components.

![Architecture](../assets/video.svg)

The [public snapshot](https://github.com/doric2000/ai-video-security-portfolio) has independent Git history, a disabled synthetic camera, local lab setup, and clearly labeled illustrative payloads. It includes neither original footage nor deployment credentials/private keys.

Review the runner, evidence builder, MQTT ingest, model orchestration, and context administration. Direct video inference needs a compatible local model and hardware; the frame fallback is optional. Confidence is uncalibrated model output. No published latency/accuracy benchmark or autonomous physical-security guarantee is claimed.
