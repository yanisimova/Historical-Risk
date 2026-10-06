# Version 2.0 — Historical risk lens

## Comparison
| Dimension | Primary | Contrast |
|---|---|---|
| Same technology and organization | Instruction-tuned transformer LLM; small consulting firm | Unchanged |
| Input | Public reports | Confidential client interviews and strategy documents |
| Review and permissions | Analyst approval, no connectors | No approval, proposed shared retrieval and email connector |
| General conclusion | Same creation lineage and historical mechanisms | Unchanged; posture does not change evidence |
| Main red flags | Fidelity, untrusted document instructions, unspecified service configuration | Confidential data handling, cross-client isolation, injection with tool access, unreviewed delivery |
| Bounded recommendation | Evaluate public-data drafts with checking | Resolve privacy/security and permission gaps before testing confidential automated workflow |

Both cases are synthetic. Multiple context variables change together; this tests qualitative context sensitivity, not isolated causal effects or risk probabilities. Safeguards are proposals, not demonstrated defenses.

## Boundary challenge
cases/boundary_privacy.json asks whether GPT-2 extraction proves an unnamed vendor trains on and leaks uploads. The saved response rejects that inference, separates training memorization, input retention and retrieval exposure, and requests current product/configuration evidence. No provider policy was invented.

## Preserved weakness and revision
history/version_1_0 preserves the prior specialist, inputs, outputs and prompts. Its initial response had a generic monitoring trigger and no named readiness handoff. Its final version improved those issues but still lacked a systematic historical mechanism -> exposure -> consequence -> safeguard chain and dedicated privacy/security evidence. Version 2.0 adds those requirements and two original research sources. Current cases intentionally differ from the earlier retailer contrast to match the user's requested consulting scenario; this is a scope revision, not a claim of improvement on an unchanged benchmark. Current primary, contrast and boundary outputs provide the new evidence.

## Run and review provenance
The same ChatGPT/Codex assistant generated and evaluated these three outputs from the current instructions and cases. Python builds packets and checks JSON; no separate model/API call, blinded evaluator or real deployment was used. The unchanged general finding was intentionally reused following inspection of the common evidence. Equality is an integration check, not independent proof of robustness. Human judgment confirmation remains pending.

## Verification checklist
- Completed: three saved response records; supplied validator and full JSON schema checks.
- Completed: seven frozen-core file checks against supplied manifest.
- Completed: original abstracts and publication histories for five sources inspected; full-paper methods not reviewed.
- Pending: student review of proposed judgment and case selection.
- Pending: current vendor/product/configuration documentation if making deployment claims.
- Pending: representative fidelity, isolation and adversarial-document tests on the actual application; not simulated as successes here.
- Pending: GitHub publication/version record and Brightspace submission.
