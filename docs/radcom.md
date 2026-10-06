# RADCOM Cyber Classifier · asynchronous ML serving

**Problem:** traffic classification needs feature processing and model inference without tying the UI to one long-running request.

**Implemented:** CSV upload to FastAPI, Redis-backed Celery tasks, model inference, task-status polling, and Streamlit download of predictions. Application classification and attribution classification have separate training and feature pipelines.

![Architecture](../assets/radcom.svg)

Co-built by **Dor Cohen and Baruh Ifraimov**, as credited in the application. The portfolio claims collaborative ownership; it does not assign unverified sole authorship of individual algorithms.

Inspect [API and worker](https://github.com/doric2000/RadcomProject/tree/main/app), training modules, Docker service boundaries, and the documented artifact requirements. Training data and fitted models are excluded, so a clone alone is not a complete trained demo. No accuracy figure is claimed without its dataset and evaluation protocol.
