# Security reporting

This policy covers ScreenQuiver's official stable C# releases, Rust previews and
their download/update process. Application source is maintained privately; this
public repository is the reporting and downloads entry point.

## Maintained releases

Please check the latest stable release or latest Rust preview for the edition
you use. Include the exact release tag in your report. Reports about older
versions are still useful when the problem may affect a maintained release.
The Rust edition remains a preview.

## Report a vulnerability privately

Use GitHub's **Security → Report a vulnerability** option when it is available:
[start a private report](https://github.com/Xamother/ScreenQuiver-Releases/security/advisories/new).

If GitHub does not offer private reporting, open an issue titled **Private
security contact requested**, without technical details, attachments or exploit
instructions. The maintainer can arrange a private reporting channel. GitHub
does not provide general private messages between user accounts.

Do not publish vulnerability details in an ordinary issue or pull request while
arranging a private report. Include these details in the private channel:

- Affected edition, release tag and Windows version.
- The problem, reproduction steps and expected security impact.
- A minimal example or proof of concept, if available.

Remove credentials, personal information, monitor serial numbers and unrelated
logs. Only test systems you own or are authorised to test.

Xamother reviews reports as time permits and can coordinate a fix and disclosure
with the reporter. No response deadline, fix deadline or bounty is promised.
Ordinary feature requests and non-security bugs belong in
[Issues](https://github.com/Xamother/ScreenQuiver-Releases/issues).
