# cloudincsa org-default repo

Hosts reusable GitHub Actions workflows used across CloudInc repos.

## Reusable workflows

### `plane-sync.yml`
Syncs PR state to Plane tickets. Caller workflow in each project repo references it.
See [docs/TRACKER.md](https://github.com/cloudincsa/kilo-billing/blob/master/docs/TRACKER.md) (canonical convention).
