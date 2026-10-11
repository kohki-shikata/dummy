# Screenshot 404 fix (2026-10-11)

Gitea: https://git.k.b4m.jp/b4m-inner/jp-org-parse/pulls/28
Deployed API: jparse-api:6706b8d

Root cause: s3 driver left Storage nil → relative redirect → 404.
