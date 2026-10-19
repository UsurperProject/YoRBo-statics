# Source Code and Modification Information

This repository redistributes a modified filesystem image derived from **Ventoy 1.1.18**.

Ventoy is developed by the Ventoy project. This repository is not an official Ventoy distribution and is not affiliated with or endorsed by the Ventoy developers.

## Upstream project

- Project: https://www.ventoy.net/
- Source repository: https://github.com/ventoy/Ventoy
- Version: **1.1.18**
- Version-specific source: https://github.com/ventoy/Ventoy/tree/v1.1.18
- Release: https://github.com/ventoy/Ventoy/releases/tag/v1.1.18
- Licensing information: https://www.ventoy.net/en/doc_license.html

## Local modifications

The redistributed image contains changes to plaintext scripts. The repository documents the affected scripts in two directories:

- `modifications/original/` — unmodified upstream versions of affected scripts.
- `modifications/modified/` — corresponding versions included in the redistributed image.

Compare matching files in these directories to inspect the changes. No changes to compiled binaries are intended. Other files are intended to remain as supplied by upstream Ventoy 1.1.18.

The prebuilt image is supplied to preserve filesystem metadata such as Unix permissions and symbolic links, which may be lost when extracting and repacking the image using Windows tools.

## Corresponding source

The upstream source for Ventoy 1.1.18 is available from the version-specific source link above. The source of the locally modified scripts is provided under `modifications/modified/`, with original versions under `modifications/original/`.

The image also contains third-party components governed by their own licenses. Refer to the upstream Ventoy 1.1.18 `License/` directory for the component-specific notices and source information:

https://github.com/ventoy/Ventoy/tree/v1.1.18/License

**Distribution note:** These links and modification files are intended to help recipients obtain the corresponding source, but a link alone does not guarantee license compliance. Before publishing the image, verify that the referenced sources correspond to *all* GPL/LGPL-covered binaries in the distributed image (including bundled third-party components), that any required build and installation scripts are available, and that equivalent access to the complete corresponding source remains available for as long as required. If any source is missing upstream, host or arrange access to that source separately.

## Licenses and notices

Ventoy-developed code is licensed under **GNU GPL version 3 or later**. Bundled third-party components may use GPLv2, LGPL, MIT, BSD, or other licenses. Existing copyright notices, license files, and applicable disclaimers remain in effect. Modifications to covered scripts remain subject to their applicable licenses.

See the official Ventoy licensing page and the upstream `License/` directory linked above. Preserve all applicable notices when redistributing the image.

## Disclaimer

The modified image is provided **as is**, without warranty, to the extent permitted by applicable law. It is an unofficial modification of Ventoy 1.1.18.
