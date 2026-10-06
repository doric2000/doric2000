# PlanLi Travels · product ownership

**Problem:** travelers need a coherent way to discover recommendations, organize destinations, and share trips.

**Delivered:** a photo-first, Hebrew/RTL travel product released on iOS and Android. Dor Cohen designed and built the application, backend, data model, security controls, release workflows, and operational tooling.

![Architecture](../assets/planli.svg)

## Evidence to inspect

- [Client](https://github.com/doric2000/PlanLi/tree/main/client) and [backend](https://github.com/doric2000/PlanLi/tree/main/functions).
- [Authorization rules](https://github.com/doric2000/PlanLi/blob/main/firestore.rules), [storage rules](https://github.com/doric2000/PlanLi/blob/main/storage.rules), and [CI workflows](https://github.com/doric2000/PlanLi/tree/main/.github/workflows).
- [Operations and release history](https://github.com/doric2000/PlanLi/blob/main/docs/OPERATIONS.md) records validation and deployment state.
- [App Store](https://apps.apple.com/il/app/planli-travels/id6801453067) and [Google Play](https://play.google.com/store/apps/details?id=com.planli.planlitravels).

The production record dated **30 September 2026** reports **1,004 client tests and 458 backend tests (three backend tests skipped)**, alongside Firebase Rules emulator validation. These are historical validation counts, not a new test run or a permanent current count. Release state and remaining checks belong in the current operations record.

The engineering signal is ownership of the whole delivery path: authenticated clients, server-side business writes, private/public data boundaries, media and moderation flows, and guarded release procedures. No user-growth or commercial-impact metric is asserted.
