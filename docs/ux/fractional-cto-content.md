# Fractional CTO page: first-month and engagement-choice content

**Decision date:** 2026-08-07  
**Status:** approved direction from HOME-31 (HOME-26 variant 1)

## Traceability

| Link | Definition |
| --- | --- |
| Business goal | Help prospective clients understand the nature of the Fractional CTO engagement before requesting an introduction. |
| User need | See what the team can expect to work on in the first month and decide whether fractional leadership matches the current need. |
| User flow | Arrive on the Fractional CTO page → understand fit and problems → review first-30-days baseline → compare engagement types → request a 15-minute introduction. |
| Content decision | Present four first-month working outputs and distinguish fractional CTO from a full-time CTO hire and a specialist consultant. |
| Acceptance | The page names the retained first-month artifacts, explains the fit without claiming a guaranteed outcome, and remains readable and operable on small screens and with a keyboard. |

## Content and interaction rules

- **First 30 days:** describe a delivery baseline, ownership map, 90-day plan and weekly operating cadence as working artifacts. Scope is explicitly tailored; no outcome, speed or performance guarantee is made.
- **Choose this when / not when:** use parallel cards for Fractional CTO, Full-time CTO hire and Specialist consultant. The supporting intro states the boundaries: fractional work is not a replacement for either a permanent executive or a narrowly scoped specialist assignment.
- **Responsive behavior:** first-month cards stack to one column below the `sm` breakpoint; comparison cards stack below `md`. No horizontal scrolling is required.
- **Accessibility:** each section has a programmatic heading; first-month steps use an ordered list; cards use descriptive headings and ordinary readable text. Existing visible focus styles, reduced-motion preference, color contrast and semantic mailto CTA remain in effect.

## Evidence and uncertainty

- **Observed evidence:** the existing page targets software teams and software departments in non-IT companies, typically 5–25 people; it already frames a minimum 20-hour monthly engagement and a short introductory email flow.
- **Evidence not available:** visitor research, analytics, conversion baseline and usability-session results.
- **Assumption:** visitors need a decision aid before contacting the advisor. Validate this assumption with qualitative feedback from prospective clients or a measured CTA/content test before treating it as a conversion result.

## Handoffs and validation

- **Implementation:** static HTML only; reuse the existing Tailwind grid/card and brand CSS patterns.
- **QA:** verify heading hierarchy, ordered-list semantics, keyboard focus visibility, mobile stacking at 320px, and readable comparison-card wrapping.
- **BA/PO:** no new pricing, scope guarantee or business rule is introduced; confirm any future changes to engagement minimums or commercial language.
- **SRE/DevOps:** no runtime or degraded-state impact for this static content change.
- **Validation result:** not yet validated with users. Owner: Vicy. Follow-up: review qualitative feedback or page metrics after publication.
