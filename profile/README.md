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

<!-- org-project-routing:start -->
## Planning and delivery

- [GitHub Project: quaestor-ledger-test-project](https://github.com/orgs/quaestor-ledger-test/projects/1)
- [Linear planning project](https://linear.app/denman/project/githubcomquaestor-ledger-test-5bbe2a7b92a1)
- [Detailed project-routing contract](../docs/PROJECTS.md)

GitHub owns code and delivery evidence; Linear owns planning and dependencies. The linked organization Project provides the cross-repository execution view.
<!-- org-project-routing:end -->


<!-- ore-org-baseline:begin -->
## Planning and governance

- Canonical Linear project: https://linear.app/denman/project/githubcomquaestor-ledger-test-5bbe2a7b92a1
- Organization defaults: https://github.com/quaestor-ledger-test/.github
- Canonical agent policy: https://github.com/quaestor-ledger-test/.github/blob/main/agents.md
- Security policy: https://github.com/quaestor-ledger-test/.github/security/policy

Repositories in this organization use semantic conflict resolution with 3–10 relevant prior commits when useful, full cross-repository context, pull-request delivery, and a hard automated-agent denylist for destructive or history-rewriting operations.
<!-- ore-org-baseline:end -->
