# NousResearch/hermes-agent

Generated: 2026-10-05T11:13:54.472669+00:00

- Unassigned: 39+
- [View all unassigned issues](https://github.com/NousResearch/hermes-agent/issues?q=is%3Aissue%20is%3Aopen%20no%3Aassignee)

Most recently opened:

| Issue | Comments |
|---|---|
| [#133272 [Bug]: macOS — an unparseable LaunchAgent plist is silently skipped, so `hermes update` books a supervised dashboard as `manual-serve` and respawns it into the job's own port (exit 1)](https://github.com/NousResearch/hermes-agent/issues/133272) | 1 |
| [#133266 Docker/s6: a restart during an in-flight turn ends unclean — the supervised start command is `hermes gateway run --replace`](https://github.com/NousResearch/hermes-agent/issues/133266) | 0 |
| [#133265 Matrix: messages that arrive while the gateway is down are silently discarded on startup (5 s startup grace, no log line)](https://github.com/NousResearch/hermes-agent/issues/133265) | 0 |
| [#133262 Sessions tied to a removed/erroring local-model provider cannot be deleted from the Desktop UI (CLI works)](https://github.com/NousResearch/hermes-agent/issues/133262) | 0 |
| [#133261 Local model launch: auto-generated preset (ctx-size 262144) OOMs a 16GB machine; please allow editing/importing llama.cpp launch args](https://github.com/NousResearch/hermes-agent/issues/133261) | 4 |
| [#133259 [Bug]: Pinned llama.cpp Vulkan build is ~4x slower than LM Studio's Vulkan build on the same Windows AMD GPU (RX 9070 XT) — -ngl 99 buys nothing over -ngl 0](https://github.com/NousResearch/hermes-agent/issues/133259) | 0 |
| [#133258 fix(tui): exact skill commands are redirected to longer aliases because catalog canon omits skills](https://github.com/NousResearch/hermes-agent/issues/133258) | 1 |
| [#133256 Dashboard Chat tab: WebSocket reconnect storm from synchronous onState replay + shared generation counter](https://github.com/NousResearch/hermes-agent/issues/133256) | 0 |
| [#133254 [Bug] `hermes pm update --uv` fails building spaCy 2.0.17 on Python 3.14](https://github.com/NousResearch/hermes-agent/issues/133254) | 0 |
| [#133253 [Bug]: Desktop update blocked - state.db pre-flight has a hard 30s timeout that a ~1GB state.db cannot meet](https://github.com/NousResearch/hermes-agent/issues/133253) | 1 |
| [#133249 Windows: creating a profile deadlocks the multiplexed host gateway (reconcile_served_profiles blocks on own control pipe, watchdog exit 75)](https://github.com/NousResearch/hermes-agent/issues/133249) | 1 |
| [#133247 Signal: keep @mentions in raw_message so pre_gateway_dispatch plugins can tell the bot was addressed](https://github.com/NousResearch/hermes-agent/issues/133247) | 0 |
| [#133244 [Bug] Multiplexed gateway: plugin slash command from profile A runs in profile B's chat and fails with "could not read this profile's ANTHROPIC_TOKEN (internal profile-scoping bug)"](https://github.com/NousResearch/hermes-agent/issues/133244) | 1 |
| [#133243 PR #121054: feat(estop): keep an allowlisted identity working through a pause, and bound the pause itself](https://github.com/NousResearch/hermes-agent/issues/133243) | 0 |
| [#133242 PR #120084: fix(profiles): a served session's child can name the profile it acts for](https://github.com/NousResearch/hermes-agent/issues/133242) | 0 |
| [#133241 PR #118700: fix(skills): restore a symlinked skill as a symlink on batch rollback](https://github.com/NousResearch/hermes-agent/issues/133241) | 0 |
| [#133240 PR #118692: fix(skills): park a batch rollback outside the skills root](https://github.com/NousResearch/hermes-agent/issues/133240) | 0 |
| [#133239 PR #118631: fix(skills_sync): leave symlinked skill entries alone on sync](https://github.com/NousResearch/hermes-agent/issues/133239) | 0 |
| [#133238 PR #118550: fix(skills): resolve skill_manage targets through the symlink-following index walk](https://github.com/NousResearch/hermes-agent/issues/133238) | 0 |
| [#133226 [Bug]: mirrored subagent tool.complete payload carries undeclared preview field, violates wire contract](https://github.com/NousResearch/hermes-agent/issues/133226) | 0 |
| [#133223 hermes tools ▸ Speech-to-Text never lists plugin transcription providers](https://github.com/NousResearch/hermes-agent/issues/133223) | 1 |
| [#133220 [Bug] macOS: every in-app update reports failure — post-update dashboard refresh kills the Desktop backend on a fixed port and cannot respawn it (exit 1 / receipt partial)](https://github.com/NousResearch/hermes-agent/issues/133220) | 2 |
| [#133219 [Bug]: read_file and search_files fail on infinite offset/limit (OverflowError in _coerce_int)](https://github.com/NousResearch/hermes-agent/issues/133219) | 0 |
| [#133217 Desktop Files pane resolves listings via backend filesystem (docker terminal backend), not local FS - project folder node unexpandable](https://github.com/NousResearch/hermes-agent/issues/133217) | 0 |
| [#133216 [Bug]: CDP supervisor crashes with empty exception text on every browser_exec call (attach timeout); supervisor never survives between calls](https://github.com/NousResearch/hermes-agent/issues/133216) | 0 |
| [#133215 Signal: partial group delivery treated as total failure → reachable members get 3–4 duplicate replies](https://github.com/NousResearch/hermes-agent/issues/133215) | 0 |
| [#133212 [Feature]: subagent_lifecycle v1.1 for plugin orchestrators: steer, host-isolation transport, then effort/route/follow-up on the facade](https://github.com/NousResearch/hermes-agent/issues/133212) | 0 |
| [#133211 Consolidate local skill set: treat local ~/.agents/skills/ as definitive, freeze upstream tpl-light sync](https://github.com/NousResearch/hermes-agent/issues/133211) | 0 |
| [#133208 [Bug]: Dashboard /api/model/info context-length probe omits api_key — keyless /models 401s on auth-gated providers (LiteLLM)](https://github.com/NousResearch/hermes-agent/issues/133208) | 0 |
| [#133206 tests: the env-isolation allowlist misses kanban worker-shell variables (ambient ask turns a green suite red)](https://github.com/NousResearch/hermes-agent/issues/133206) | 1 |
| [#133205 Feature request: ghost-text prompt suggestions in the desktop composer](https://github.com/NousResearch/hermes-agent/issues/133205) | 0 |
| [#133196 Auxiliary unhealthy-provider cache is honoured by the main route, so a background helper can disable fallback_providers](https://github.com/NousResearch/hermes-agent/issues/133196) | 0 |
| [#133193 [Bug]: a 403 matching no _FALLBACK_REASONS predicate hard-fails every auxiliary task — no fallback, no health mark, silently dropped](https://github.com/NousResearch/hermes-agent/issues/133193) | 0 |
| [#133192 [Bug/Feature Request]: ACP session/load fails for unpersisted empty sessions after client reconnect / restart](https://github.com/NousResearch/hermes-agent/issues/133192) | 0 |
| [#133184 [Bug]: source changes are invisible to the PM environment stamp, so a generation-snapshot unit serves stale code silently; and update reclaims generations without rewriting units that reference them](https://github.com/NousResearch/hermes-agent/issues/133184) | 1 |
| [#133183 [Bug]: provider "custom:<name>" whose base_url IS a vendor host loses context-length resolution entirely — 1M models compact at ~142-192K (3x early)](https://github.com/NousResearch/hermes-agent/issues/133183) | 0 |
| [#133181 [Bug]: OpenCode Zen/Go default_aux_model point at retired relay ids — harmless for 'auto' aux, dead the moment a provider is pinned](https://github.com/NousResearch/hermes-agent/issues/133181) | 1 |
| [#133179 [Security]: a leftover model.base_url redirects a named vendor provider's credential to a third-party host (opencode-zen/gemini/openrouter)](https://github.com/NousResearch/hermes-agent/issues/133179) | 0 |
| [#133164 [Bug]: standalone Telegram send (hermes send) uses PTB default read_timeout=5s — media sends report 'Timed out' although delivered (duplicates on retry)](https://github.com/NousResearch/hermes-agent/issues/133164) | 2 |
