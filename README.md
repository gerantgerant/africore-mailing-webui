# Africore Mailing WebUI

Customized Stalwart WebUI for **Africore Mailing**.

## Production bundle

- `release/webui.zip` — deployable Stalwart Web Application bundle.
- `release/webui-africore-mailing-v1.0.11-stalwart-0.16.24.zip` — versioned copy of the same bundle.
- `source/africore-mailing-source-b7044ce.zip` — corresponding source for the customized WebUI.
- `release/SHA256SUMS` — integrity hashes.

This customization changes the WebUI branding, uses an Africore burgundy palette, removes Enterprise trial/activation promotions, and adds a Community dashboard that only queries management/JMAP data available to the current account. It does **not** unlock or bypass Enterprise-only server features.

## Stalwart integration

The target server is Stalwart 0.16.24. Keep `/admin` and `/account` as URL prefixes and point the Stalwart Web Application Resource URL to the immutable raw GitHub URL documented in the deployment commit.

Rollback URL:

`https://github.com/stalwartlabs/webui/releases/latest/download/webui.zip`

## Licensing

This project is derived from the Stalwart WebUI project. Original copyright and SPDX notices are retained in the corresponding source archive. The upstream WebUI licensing terms (AGPL-3.0-only OR LicenseRef-SEL, as applicable) continue to apply to the derived code.
