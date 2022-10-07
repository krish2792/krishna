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
- 2022-04-16: oops
- 2022-04-21: better wording
- 2022-04-24: oops typo
- 2022-05-04: wip(rl): partial fail open
- 2022-06-25: feat(rl): first pass at sliding window
- 2022-07-13: docs(rl): document redis cluster
- 2022-07-31: test(rl): snapshot redis cluster
- 2022-08-03: feat: introduce lua script
- 2022-08-13: style(rl): rename for clarity
- 2022-08-26: fix: avoid lua script
- 2022-09-15: chore(rl): reformat
- 2022-10-01: refactor: collapse lua script
- 2022-10-04: tidy notes
- 2022-10-07: fix(rl): avoid sliding window
