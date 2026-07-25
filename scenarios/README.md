# Scenarios

Each folder is a defanged, deliberately vulnerable artifact. Read it, predict the
findings, then run `uncloak scan scenarios/<name>` and compare.


| # | Scenario | Maps to |
|---|----------|---------|
| 01 | [Direct prompt injection in the skill body](scenarios/01-direct-injection/) | LLM01 · UC201 |
| 02 | [Invisible Unicode instruction (Tags block)](scenarios/02-hidden-unicode/) | LLM01 · UC101 |
| 03 | [MCP tool-description poisoning](scenarios/03-tool-poisoning/) | LLM01 · UC204 |
| 04 | [Secret read + outbound channel (lethal trifecta)](scenarios/04-data-exfiltration/) | LLM06 · UC301/UC303/UC501 |
| 05 | [Privilege / permission bypass](scenarios/05-rbac-bypass/) | LLM06 · UC201 |
| 06 | [KVKK / PII extraction](scenarios/06-pii-leak/) | LLM02/LLM06 · UC301 |
| 07 | [Trigger-conditioned (rug-pull) behavior](scenarios/07-rug-pull/) | LLM01 · UC205 |
| 08 | [Bundled fetch-and-run script](scenarios/08-bundled-script-rce/) | LLM05 · UC402 |
