# Meshtail issue tracker

Report bugs and suggest improvements for Meshtail, a companion app for MeshCore. This repository contains reporting forms and support documents, not the application source.

See the [Meshtail privacy policy](https://meshtailapp.github.io/meshtail-issues/privacy/) for details about local data, optional online features, and support reports.

- [Report a bug](https://github.com/meshtailapp/meshtail-issues/issues/new?template=bug_report.yml)
- [Suggest an improvement](https://github.com/meshtailapp/meshtail-issues/issues/new?template=feature_request.yml)
- [Browse existing reports](https://github.com/meshtailapp/meshtail-issues/issues)

Search existing reports before opening a new one. Include your app version, phone and radio models, and clear steps to reproduce the problem. A GitHub account is required to submit a report.

## Reporting by platform

Browse open reports by platform:

- [Android reports](https://github.com/meshtailapp/meshtail-issues/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22platform%3A%20android%22)
- [iOS reports](https://github.com/meshtailapp/meshtail-issues/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22platform%3A%20ios%22)
- [Shared reports](https://github.com/meshtailapp/meshtail-issues/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22platform%3A%20shared%22)
- [Reports needing platform triage](https://github.com/meshtailapp/meshtail-issues/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22platform%3A%20needs-triage%22)

Include:

- Meshtail version and build number, plus the install channel: Google Play, TestFlight, App Store or a source build.
- Android or iOS version and device model, plus relevant radio model, firmware and connection type.
- Steps to reproduce, expected behavior and what happened.
- For a source build, the exact commit SHA and branch.

I use `platform: android` or `platform: ios` when the report establishes that platform. `platform: shared` requires evidence for both platforms; shared Flutter code alone does not establish that. Reports without enough platform information use `platform: needs-triage`.

You can submit a report using the platform you have; you do not need to test both. During triage, I check Android and iOS applicability and record reproduction results or why a platform is not affected. Each issue tracks the fix commit, test results and release status for each platform. Checks or releases that have not happened stay marked as pending; an issue is not fully resolved until both platforms are accounted for.

Corresponding Android and iOS releases use the same marketing version and build number. A change implemented in source is separate from release availability. I identify the exact version, build and channel when it is available through Google Play, TestFlight or the App Store. Matching version and build numbers alone do not establish identical source or behavior across platforms.

## Protect your privacy

Issues and attachments are public. Do not post passwords, radio/channel keys, private messages, precise locations, full backups, or unreviewed diagnostics. Redact screenshots before uploading them.

## Private support

For private diagnostics or security concerns, email [support@meshtail.app](mailto:support@meshtail.app?subject=Meshtail%20support). Mention the issue number if your email relates to an existing report. The app's email support option can attach diagnostics with your permission.
