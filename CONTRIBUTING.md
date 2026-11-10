# Contributing to ScreenQuiver

Bug reports, feature requests and documentation fixes are welcome. This is the
public downloads and feedback repository. The application source is private;
application code changes are developed in the private source repository.

## Report a problem

Check [existing issues](https://github.com/Xamother/ScreenQuiver-Releases/issues)
and identify the release you used. Stable C# releases use tags such as
`v1.3.0`; Rust previews use tags such as `rust-v2.0.0`.

Use the bug-report form and include:

- The edition, exact app version and Windows version/build.
- Clear reproduction steps, what you expected and what happened.
- Relevant GPU/driver, connection or docking information, if display switching
  is involved.

Screenshots and short, relevant log excerpts can help. Redact account names,
local paths, monitor serial numbers and other identifying information. Do not
attach access tokens, passwords or complete unredacted settings/diagnostic files.

Report suspected vulnerabilities using [SECURITY.md](SECURITY.md), rather than
putting exploit details in a public bug report.

## Suggest a feature

Describe the problem you are trying to solve and how the proposed behaviour
would help. Use the feature-request form and note whether the request concerns
stable C#, the Rust preview or both.

## Improve documentation

Open a pull request against this repository's default branch with a focused
documentation or community-guidance change. Check links, preserve copyright and
licence notices, and explain any changes to user instructions.

Do not commit application source, decompiled code, release binaries, tokens or
private logs here. Changes to the downloads README may also need to be reflected
in the private source repository's release workflow, which maintains that file.

## Expectations

Follow the [code of conduct](CODE_OF_CONDUCT.md). ScreenQuiver is a personal
project; reports and suggestions are reviewed as time permits, without a
guaranteed response or delivery date. CI uses simulated displays, so a passing
build does not establish that a change works with every GPU, dock or monitor.
