<!-- SPDX-FileCopyrightText: 2026 Libre AI contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->
Door: one-way | two-way
Origin: observed YYYY-MM-DD <source> | inspection | synthetic | proposal

<!--
Fleet pull request template (libre-ai/.github, default for every repository
that carries no template of its own). Comments like this one are guidance:
they are not rendered, and gates reading the description ignore them.

The declaration block is the two lines above, and it must stay where it is:
the first lines of the description, right after the SPDX comment lines,
ended by one blank line. Each line is `Key: value`, the key at the start of
the line; a value carries no HTML and closes on its own line every backtick
code span, bracket, parenthesis, `~~` and double quote it opens. Where a
repository runs the Door gate (project-governance:
tools/quality/check-pr-door.ts), a description whose first lines are not
this block, with a valid Door line and a valid Origin line, does not pass;
a key line written anywhere else in the description is refused.

Replace each placeholder line, and add any optional line below to the same
block, directly under the others, never elsewhere.

Door — exactly one line, one value:
  two-way: reverting the merge restores the previous state;
  one-way: it does not (repository deletion, a published release or package,
  a ruleset change, a data migration, a force push, an external message).

Origin — exactly one line, one value (project-governance ADR-0056 D1): where
the problem this pull request treats comes from.
  observed: a failure that happened in real use, or a dated and cited stale
    fact; it carries its ISO date and its source (pull request, issue,
    `path:line`, session note): `Origin: observed 2026-10-07 #123`;
  inspection: a defect found by reading code, doctrine or a tool;
  synthetic: a case built for the occasion (probe, fixture, vector,
    mutation) — a probe that turns red is synthetic, even when it reproduces
    a real defect;
  proposal: an improvement with no defect found.
Nothing follows a value other than observed. A problem with several origins
declares the one that triggered it and cites the others in the body.

Second-instrument — one-way door only: the independent measurement taken
before the act, by an instrument different from the one that produced the
green (gate-integrity §3).
  Second-instrument: <instrument, what it measured, and its result>

Owner-arbitration — guarded path only: when the change touches a path that
the repository's review-evidence gate protects (project-governance:
GATED_PATH_PATTERNS in tools/quality/check-review-evidence.ts), the owner
arbitration with its ISO date.
  Owner-arbitration: YYYY-MM-DD <where the arbitration was given>

Not-added — optional (project-governance ADR-0056 D5): what a pull request
that adds a capability does not add, from the closed vocabulary dependency,
schema, workflow, hosted-service, telemetry, public-surface, comma-separated,
each once, on one line. Where the gate runs, dependency, schema and workflow
are checked against the diff, and a declaration the diff cannot confirm
fails; the other three are read in review.
  Not-added: dependency, schema, workflow, hosted-service, telemetry, public-surface
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
Work package — declared in a commit, not in this description. This description
is not read for it, so nothing written here declares a work package.

On at least one commit of the pull request, set a git trailer:

  git commit --trailer "Work-package: <owner>/<repo>#<n> WP-<k>"

where <owner>/<repo>#<n> is the issue that projects the work package and
WP-<k> the row of the PRD table it implements; both must agree with the body
of that issue (### PRD-ref, ### WP). The same value may be repeated on several
commits; two distinct values are refused.

A pull request that implements no work package declares an exemption instead:

  git commit --trailer "Exempt: <class>"

where <class> is one of dependabot, docs-only or revert. The gate verifies the
predicate of the class on the pull request itself (its author, the paths it
changes, or its title); it never believes the claim. Never both.
-->

## Blast radius

<!-- which repositories, consumers, branches or users this reaches -->
