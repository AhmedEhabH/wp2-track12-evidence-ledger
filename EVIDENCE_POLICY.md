# Evidence storage policy

Local originals: D:\WP2\audit_results\<milestone>.
Second locally verified copies: %USERPROFILE%\WP2_EVIDENCE_BACKUP_20261027\<milestone>.
Each member is SHA-256 indexed in EVIDENCE_INDEX.csv. No original evidence is rewritten.

The separate GitHub ledger is PRIVATE by design, but privacy does not eliminate the
need to screen raw logs, request/response bodies, historical data, third-party material,
API keys, bearer tokens, private addresses and large binaries. Therefore this initial
commit contains ONLY reviewed authored summaries and file hashes, not 32 raw payloads.
Raw evidence publication is a separate decision after classification and redaction.

Do not commit or reset dirty frozen source worktrees. Do not modify .git/lost-found.
No git push to source remotes `origin` or `opws-private` is authorized by this script.
