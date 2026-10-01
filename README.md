# Flex GUI Pro Releases

Official public download repository for signed Flex GUI Pro ZXP packages.

> This repository contains release packages only. The private source code, signing certificate, license credentials, and backend secrets are never published here.

## Download

Use the **Releases** page to download the latest signed package:

https://github.com/raselmuntasir/Flex-Releases/releases

The permanent latest-download URL is:

https://github.com/raselmuntasir/Flex-Releases/releases/latest/download/Flex_GUI_Pro.zxp

The permanent URL works after the first production release is published. Every release must attach the signed package using the exact asset name `Flex_GUI_Pro.zxp`.

## Publishing a new version

1. Complete local and clean-machine testing.
2. Build and sign the production ZXP.
3. Create a GitHub release with a version tag such as `v9.2.3`.
4. Upload the signed package with the exact name `Flex_GUI_Pro.zxp`.
5. Publish the release only after verifying its checksum and installation.
6. In the Flex Apps Script `Settings` sheet set `B1` to the new version. Keep `B2` set to the permanent latest-download URL above.

No production package has been published yet.