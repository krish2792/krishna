# redis-rate-limiter

Token bucket on redis.
- 2022-01-19: add README.md
- 2022-01-21: perf(rl): cache lua script
- 2022-01-31: refactor(rl): flatten jitter
- 2022-02-11: fix: avoid jitter
- 2022-02-15: test: parametrize jitter tests
- 2022-02-17: fix(rl): handle sliding window
- 2022-02-24: feat(rl): add sliding window
- 2022-03-29: fix: avoid token bucket
- 2022-03-30: fix(rl): correct fail open
- 2022-04-05: cleanup
- 2022-04-09: fix(rl): avoid lua script
