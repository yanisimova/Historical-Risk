# Assignment 2 — Emerging Technology Creation Agent
Yulia Anisimova | Emerging Technologies, Section 103 | Prepared October 6, 2026 (UTC)

## Package status
Working interactive ChatGPT specialist and test evidence prepared. Student judgment confirmation, publication in the student's GitHub working repository and Brightspace submission remain pending. No external GitHub records were changed.

The user supplied unpacked scaffold files. All seven FROZEN CORE entries match the supplied checksum manifest. The original agents/_template folder, example files and some other baseline entries were not supplied. Therefore the new student-editable agents/creation_agent folder was authored directly against the intact schemas; tools/new_agent.py was not run. This is a functional working subset, not a claim that the entire original ZIP was reconstructed or its package-wide manifest passed. Original uploaded files remain untouched. The original PACKAGE_SHA256.txt describes the course baseline, not the modified package.

## Use
Run commands from this folder:

    python tools/check_frozen_core.py
    python tools/build_prompt.py --agent agents/creation_agent --case agents/creation_agent/cases/primary.json

Paste work/creation_agent_primary_prompt.txt into ChatGPT. Save its JSON response, then run:

    python tools/validate_response.py agents/creation_agent/responses/primary_response.json

Repeat with cases/contrast_1.json. The checked-in responses are actual assistant-generated outputs from this preparation session, not organization deployment tests. No API key is needed. The supplied validator is a basic structure check; a supplemental full-schema check using jsonschema was also performed during preparation without changing course tools.

## Evidence
- agents/creation_agent/specialist_instructions.md: final instructions and verified source register.
- core/input_schema.json and core/output_schema.json: unchanged common interfaces.
- agents/creation_agent/cases/: synthetic primary and contrast contexts.
- agents/creation_agent/responses/: initial weakness and revised responses.
- agents/creation_agent/records/comparison.md: comparison, revision and provenance.
- agents/creation_agent/records/validation_log.txt: actual checks performed.
- docs/: completed Word record, once packaged.

## Before submission
1. Review the proposed independent judgment in the Word record and confirm the case choice fits instructor guidance.
2. Add this working package to your own GitHub repository; record its URL, branch and final remote commit in the Word record. The local checkpoint is not proof of GitHub publication.
3. Upload the requested artifacts to the correct Brightspace assignment and retain the submission receipt. No Brightspace destination was provided in this conversation.

## Handoff
Preserve all common field names and the distinction between evidence and inference. This expert can explain creation and capability lineage. Refer diffusion, significance and organizational readiness decisions to the appropriate specialists; retain accountable human deployment authority.
