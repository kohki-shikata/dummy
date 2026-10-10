# jp-org-parse URL score/msg fix

Real work: Gitea `b4m-inner/jp-org-parse` branch `cursor/fix-url-score-msg-0256`
PR: https://git.k.b4m.jp/b4m-inner/jp-org-parse/pulls/23

Deployed enrich: `jparse-enrich:374e865`

- Job #31 failed with misleading mock message; root cause was score reject after real Google SERP.
- Job #38: あいむエージェンシー → https://aimuagency.com/ (succeeded)
- あい特定非営利活動法人 → url_not_found (no official site in SERP; honest)
