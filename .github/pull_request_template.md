## Change summary

Describe the problem, resulting behavior, and any linked issue or task.

## Affected modules

- Paths/modules changed:
- Module leads consulted and any shared interface/CBOM changes:
- Dependencies, Docker, or generated files changed (explain, or write "None"):

## Testing performed

- Commands and results (include `git diff --check`):
- Relevant regression/manual checks:
- Checks not run, missing tools, and remaining risks:

## Screenshots if applicable

Attach before/after screenshots for dashboard or report presentation changes,
or write "Not applicable". Remove private scan/target information first.

## Reviewer checklist

- [ ] The branch targets `main` and contains one focused change.
- [ ] The affected module lead reviewed the paths and shared interfaces.
- [ ] Existing VECTOR behavior is preserved, or explicitly scoped behavior changes
      have regression coverage and agreement from the affected leads.
- [ ] CLI and CycloneDX CBOM compatibility, evidence, and `pqcmat:` fields remain valid.
- [ ] Testing evidence is sufficient; skipped checks and limitations are stated.
- [ ] No secrets, private scan results, accidental generated files, or unrelated formatting.
- [ ] AGPL-3.0, original source notices, `AUTHORS`, and upstream attribution are preserved.
- [ ] At least one teammate other than the author approved the current revision;
      cross-module changes were reviewed by the relevant leads.
