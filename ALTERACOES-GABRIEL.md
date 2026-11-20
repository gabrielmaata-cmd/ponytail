# Alterações do Gabriel (fork)

- Remoção anterior do hook `UserPromptSubmit` em `hooks/claude-codex-hooks.json` (motivo: atraso a cada mensagem no Windows).
- 5 skills marcadas como manuais (`disable-model-invocation: true`): `ponytail-review`, `ponytail-audit`, `ponytail-debt`, `ponytail-gain`, `ponytail-help`. A skill `ponytail` segue automática.
- Versão em `.claude-plugin/plugin.json`: `5.3.3` -> `5.3.3-gabriel.1`.

> Ao sincronizar com o original (Sync fork), verificar se estas alterações continuam aplicadas.
