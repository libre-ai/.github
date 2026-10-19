<!-- SPDX-FileCopyrightText: 2026 Libre AI contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!--
Fleet pull request template (libre-ai/.github, default for every repository
that carries no template of its own). Comments like this one are guidance:
they are not rendered, and gates reading the description ignore them.

The declaration lines below (Door, Second-instrument, Owner-arbitration) are
read by gates, so their form is exact: the key at the start of its own line,
outside a code block. Where a repository runs the Door gate
(project-governance: tools/quality/check-pr-door.ts), a description without
a valid Door line does not pass.
-->

## Summary

<!--
The smallest visual that carries the change: a before/after table, a list of
the files that move, or one diagram. Prefer a table over a paragraph.
-->

## Evidence

<!--
Before and after: the red output of each added test on the unfixed code, then
the green one; the raw output of the repository's aggregated check (for
example `bun run check`), run after `git add`; for a change of behaviour, the
command that shows it at its real surface.
-->

## Work package

<!--
Work-package — exactly one declaration line in this description: the issue that
projects the work package, and the row of the PRD table it implements. Both
must agree with the body of that issue (### PRD-ref, ### WP). Replace the line
below with `Work-package: <owner>/<repo>#<n> WP-<k>` filled in; the placeholder
is refused on purpose, choosing is the point.

A pull request that implements no work package declares an exemption instead,
on a line of its own, copied out of this comment:

Exempt: <class>

where <class> is one of dependabot, docs-only or revert. The gate verifies the
predicate of the class on the pull request itself (its author, the paths it
changes, or its title); it never believes the claim. Never both lines.
-->
Work-package: <owner>/<repo>#<n> WP-<k>

## Reversibility and blast radius

<!--
Door — exactly one line, one value:
  two-way: reverting the merge restores the previous state;
  one-way: it does not (repository deletion, a published release or package,
  a ruleset change, a data migration, a force push, an external message).
Replace the line below with `Door: two-way` or `Door: one-way`.
-->
Door: one-way | two-way

Blast radius: <!-- which repositories, consumers, branches or users this reaches -->

<!--
One-way door only — the independent measurement taken before the act, by an
instrument different from the one that produced the green (gate-integrity
§3). Copy this line out of the comment and fill it:

Second-instrument: <instrument, what it measured, and its result>
-->

<!--
Guarded path only — when the change touches a path that the repository's
review-evidence gate protects (project-governance: GATED_PATH_PATTERNS in
tools/quality/check-review-evidence.ts), cite the owner arbitration with its
ISO date. Copy this line out of the comment and fill it:

Owner-arbitration: YYYY-MM-DD <where the arbitration was given>
-->
