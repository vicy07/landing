# Mentoring: outcome and fit boundaries

## Scope and evidence

- **Business goal:** set clear expectations before intro or payment.
- **User need:** decide whether mentoring can help with a live leadership situation, understand the expected outcome, and know what to do if it cannot.
- **Observed evidence (2026-08-07):** `mentoring.html` is a static English page. Its only booking entry point is a pre-filled `mailto:` link; there is no on-site booking or confirmation screen.
- **Research status:** Evidence not available beyond accepted HOME-25 decision. No research, metrics, or usability results are asserted.

## Design decision and flow

The aim of mentoring is to clarify the visitor’s decision and leave with one concrete next step; it does not guarantee a life or career result. Mentoring is not therapy, recruiting, legal or employment advice, or urgent incident response.

1. Landing says Mentoring clarifies a live decision and chooses a concrete next step.
2. Before the intro CTA, the mentoring page states outcome and fit boundaries.
3. The email template requests situation, decision, intended next step, and language.
4. During intro, explain the outcome and assess fit before a paid session.
5. If unfit, offer no paid mentoring; explain plainly and direct to a qualified specialist, organisational process, or urgent-support route where possible.

Alternative of publishing an outcome without boundaries was rejected by HOME-25 because it allows avoidable mismatched expectations.

## Accessibility, states, and validation

- Fit content has labelled headings, visible link text, keyboard reachability, and stacks in source order below `lg`.
- This static site has no form/loading/empty/validation/error/retry/confirmation states. `mailto:` hands off to the email client; the visible email address is the recovery path.
