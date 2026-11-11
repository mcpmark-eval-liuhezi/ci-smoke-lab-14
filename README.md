# ci-smoke-lab-14
Throwaway sandbox to prove the contribution + CI loop works end to end

## Build artifact

The CI workflow (`.github/workflows/ci-smoke.yml`) runs on demand via
`workflow_dispatch`. It writes a short text file (`demo-file.txt`) and uploads it
as a build artifact named `demo-build`, which is available on every successful
run under the repository's Actions tab.
