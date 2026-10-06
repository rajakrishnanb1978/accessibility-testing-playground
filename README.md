# UCS Accessibility Testing Playground

**Accessibility tools test websites. But who tests the accessibility tools?**

The **UCS Accessibility Testing Playground** is a free WCAG 2.2 testing resource from **Ultra Content Services LLP (UCS)**. It contains deliberate accessibility failures and corresponding PASS controls so developers, QA teams, accessibility specialists, and tool makers can challenge the tools and workflows they rely on.

## Take the WCAG 2.2 Challenge

1. Open the live Accessibility Testing Playground.
2. Choose the accessibility testing tool you normally use.
3. Run it against the scenarios.
4. See what it finds — and what it misses.
5. Continue with keyboard, guided, manual, and assistive-technology evaluation where automation is not enough.

**Live Playground:** https://www.ultracontentservices.com/accessibility-testing-playground/

## What the Playground covers

The published Playground is based on a frozen WCAG 2.2 Level A and AA benchmark developed while building and testing UCS A11yAllies.

The frozen benchmark includes:

- **612 deliberate failures** in the comprehensive test surface
- Coverage across **55 WCAG 2.2 Level A and AA success criteria**
- Corresponding PASS controls used to help distinguish expected findings from false positives
- Scenarios intended for automated, guided, manual, focus-sequence, temporal, transient-capture, and page-set evaluation

The Playground is deliberately inaccessible. Do **not** use it as an example of an accessible website.

## Why this exists

Automated accessibility testing is valuable, but accessibility conformance cannot be established by an automated scanner alone.

The Playground is intended to help teams ask better questions:

- What can our automated checker detect reliably?
- Which issues require keyboard interaction or human judgement?
- Where do guided testing workflows help?
- Does a tool report problems on known PASS controls?
- What should happen after a finding is discovered?

The goal is not to create a leaderboard. It is to encourage transparent, repeatable accessibility testing and stronger end-to-end workflows.

## Try it with your tools

Use the Playground with the accessibility tools you already rely on. Compare automated results with human evaluation rather than assuming that a clean automated scan means the page is accessible.

If you find something interesting, unexpected, or potentially incorrect in the public Playground, GitHub Issues can be used to discuss it.

## UCS A11yAllies

The benchmark was developed while building **UCS A11yAllies**, a Chrome-based accessibility audit and evidence workspace.

A11yAllies brings together automated WCAG auditing, guided manual testing, evidence capture, remediation workflows, retesting, and audit-ready reporting.

**Explore A11yAllies:** https://www.ultracontentservices.com/a11yallies/

## Learn how to test website accessibility

For a practical workflow covering automated checks, keyboard testing, manual evaluation, evidence, remediation, and retesting:

**Website Accessibility Testing Guide:** https://www.ultracontentservices.com/how-to-test-website-accessibility/

## Important limitations

This repository documents and links to the public testing resource. It does **not** publish UCS's internal regression oracle, proprietary rule logic, internal expected-result mappings, benchmark-generation infrastructure, or A11yAllies source code.

The benchmark is a controlled testing resource, not an independent certification of any accessibility product. Results from it should be described in the context of the benchmark and the testing method used.

## About UCS

**Ultra Content Services LLP** works in digital accessibility and accessible publishing, including WCAG testing, accessibility remediation, accessible EPUB, and accessibility technology.

**UCS:** https://www.ultracontentservices.com/

---

If this resource is useful, **star this repository** and share the Playground with accessibility, QA, development, and testing teams.

**Let's test the testers. ♿**
