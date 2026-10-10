# jp-org-parse job verbose SSE

Gitea: https://git.k.b4m.jp/b4m-inner/jp-org-parse/pulls/25
Branch: cursor/job-verbose-sse-0256
Deployed: jparse-{api,enrich,spa}:439b459

Job #39 CAPTCHA fail lacked GUI stdout. Now enrich mirrors verbose lines to enrich_job_events and GUI uses EventSource.

## Follow-up bb99db6
- Gate URL+screenshot chain: require org.url before starting screenshot
- いーよる: SERP only had directories → url_not_found (expected)
