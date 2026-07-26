# ELECHECK Extension Releases

Public host for the signed `.crx` + `update.xml` that Chrome's enterprise
`ExtensionSettings` policy (pushed via Mosyle/Intune) checks to force-install and
auto-update the **ELECHECK: HELPDESK AUTOMATION BRIDGE** extension on
CompoSecure-managed machines.

This repo intentionally contains only the built release artifacts — no source.
Chrome's `update_url` fetch is unauthenticated, which is why this has to be public
rather than living in the private
[`elecheck_extension`](https://github.com/derondecamp/elecheck_extension) source
repo.

Current extension ID: `nikjinminlpdihagpehholnlofjbillc`
