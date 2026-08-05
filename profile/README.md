# quaestor-ledger-test

Independent acceptance organization for **quaestor-ledger**.

Accounting invariants, API/SDK, billing adapters, idempotency, migrations, reconciliation, and authenticated UI acceptance.

## Portfolio

| Repository | Class | Readiness | Primary dependency path |
|---|---|---|---|
| `double-entry-invariants` | protocol conformance | `ready` | `matrix` |
| `api-contract` | API contract | `ready` | `matrix` |
| `clients-consumer-matrix` | SDK consumer | `ready` | `matrix` |
| `billing-provider-adapters` | provider adapter | `ready` | `matrix` |
| `idempotency-retry` | chaos/fault injection | `ready` | `matrix` |
| `postgres-cockroach-migrations` | database conformance | `ready` | `matrix` |
| `reconciliation-currency-rounding` | protocol conformance | `ready` | `matrix` |
| `flutter-web-auth-e2e` | UI/accessibility | `ready` | `matrix` |

Pull requests run deterministic harness checks. Emulators, desktop matrices, live APIs/providers, databases, chaos, scale, and soaks are scheduled/manual. Missing upstreams or credentials are blocked readiness—not false passes or product regressions.
