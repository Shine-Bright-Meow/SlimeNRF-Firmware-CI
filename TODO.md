# TODO: Fix SHA blank retry in Generate Lookups

## Plan
- [x] Edit `.github/workflows/workflow.yml` — fix `resolve_sha` to fail on blank SHA after retries
- [x] Add exponential backoff to `resolve_sha` retry delays
- [x] Increase retry attempts from 5 to 10
- [x] Add post-generation validation to check for blank SHAs in `lookups.json`

