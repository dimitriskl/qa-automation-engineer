# Changelog

All notable changes to this agent are tracked here.

## [1.1.0] - 2026-11-10

- Added a Clear communication rule to the Claude Code and Codex definitions. User-facing explanations use clear, simple English, or the language the user requests, with short sentences and familiar words. Terms and acronyms are explained on first use. The explanation says what a change does and why in terms a non-programmer can follow, and still keeps exact file paths, class and method names, evidence, risks and technical detail. Do not invent code locations or claim a check ran when it did not.
- Renamed the read-only QA workflow from Engineering Judgment to MyDevFactory in the Claude Code and Codex definitions and the README. The skill link is [dimitriskl/mydevfactory](https://github.com/dimitriskl/mydevfactory).

## [1.0.0] - 2026-11-04

- Initial public, platform-specific Claude Code + Codex distribution.
- MIT license and step-by-step project/personal installation instructions.
- Version declarations and immutable versioned release snapshots.
- Generalized the original private definition: test frameworks follow the project (xUnit/NUnit/MSTest, Jasmine/Karma/Jest, Playwright/Cypress), build/test commands are discovered instead of hard-coded, and a private task-tool dependency was removed. Added an Engineering Judgment read-only QA mode that writes its own verdict into the slice file.
