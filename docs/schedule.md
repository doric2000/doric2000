# PlanLi Schedule · collaborative scheduling

**Problem:** staff availability, coverage requirements, and fairness compete when managers assemble shifts.

**Implemented:** a React application, Node/Express API, PostgreSQL persistence, and a Python OR-Tools CP-SAT solver, with editable and versioned plans. The repository has evolved beyond the original weekly prototype into monthly scheduling.

![Architecture](../assets/schedule.svg)

Co-built by Roy Naor, Dor Cohen, Ofek, and Baruh Ifraimov. Dor's identifiable contributions include [monthly scheduling and tests](https://github.com/RoyNaor/PlanLi-Schedule/commit/8c5e52a538a4aac400ee7951b2970a435ec20ff6), [eligibility/state handling](https://github.com/RoyNaor/PlanLi-Schedule/commit/8861d5efc53a3c5e063acb742aa3bd91dcf8aa0c), and [worker-type CRUD](https://github.com/RoyNaor/PlanLi-Schedule/commit/c7e8ad246d42b343faeae6cdd98e9b9cac551a38).

[Shared source](https://github.com/RoyNaor/PlanLi-Schedule) · [Contribution history](https://github.com/RoyNaor/PlanLi-Schedule/commits?author=doric2000)

Inspect the API route map, migrations, scheduling services, and solver contract for current behavior. Do not interpret the project as a measured fairness improvement or a production adoption claim; neither is quantified here.
