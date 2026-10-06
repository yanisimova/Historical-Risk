# Context comparison and revision evidence

| Dimension | Primary: consulting drafts | Contrast: retailer order changes |
|---|---|---|
| Technology and creation evidence | Same instruction-tuned transformer LLMs; same three historical sources | Unchanged |
| Application | Generate a reviewable summary | Interpret supplier messages and alter external commitments |
| Organizational conditions | Public documents, two reviewers, no model-training staff | Fragmented codes, inconsistent messages, no dedicated validation team |
| Bounded implication | Explore verified drafting with readiness/value review | Creation evidence does not justify automatic writes; consider buyer-reviewed proposals |
| Missing empirical evidence | Actual fidelity and net review effort | Identity mapping, authorization and transaction validation |

The stable conclusion is cumulative recombination of predecessor capabilities. The changed conclusion concerns permissible task scope and the evidence needed before assigning action authority. This is a qualitative demonstration on two synthetic cases, not a performance benchmark. The shared general finding was intentionally retained after inspecting the common evidence; exact string equality is an integration check, not independent proof of model robustness.

## Preserved weakness and revision
The initial primary response is preserved in responses/primary_response_v1.json with instructions in records/specialist_instructions_v1.md and its original packet in work/. Its trigger ('Reassess as technology improves or organizational needs change') gives no observable event or accountable handoff. The initial recommendation also fails to name who evaluates deployment readiness. Version 1.0 requires observable changes, a capability-to-task mapping, a limit on what history proves, and explicit handoffs. The revised primary identifies document/model availability, scope expansion and review-effort evidence; the contrast identifies product mapping, permission changes and validation evidence. Cases were not changed to make the revision pass.

## Test provenance and limitations
The assistant in this ChatGPT/Codex conversation generated and saved the initial primary, revised primary and revised contrast responses using the supplied scaffold instructions. No separate API/model session or blind evaluation was used. The first contrast packet was generated as a development artifact but not run; only the final contrast has a saved response. Python built packets and validated saved JSON; it did not execute an LLM. The same assistant produced and assessed the runs, so student review and an independent rerun remain valuable. No human verification or team approval is claimed.
