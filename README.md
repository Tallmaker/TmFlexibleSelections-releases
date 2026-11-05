# Tm Flexible Selections releases

This repository hosts public downloads of Tm Flexible Selections, a filter extension for Qlik Cloud
Analytics: one object holds the filters for many fields, each in the display that fits it. The
source code is maintained separately.

## Download

Open the [Releases](https://github.com/Tallmaker/TmFlexibleSelections-releases/releases) page and
choose the version you need. Download the asset named `tmflexibleselections-<version>.zip`.

Do not use GitHub's automatic "Source code" archives. Those archives contain only this distribution
repository, not the Qlik extension.

Every release includes:

- `tmflexibleselections-<version>.zip`, the extension archive to upload to Qlik Cloud
- `tmflexibleselections-<version>.zip.sha256`, the SHA-256 checksum for that archive
- `release-demo-<version>.qvf` and its `.sha256`, a separate demo app with invented data

On macOS, verify a download from the directory that holds both files:

```sh
shasum -a 256 -c tmflexibleselections-<version>.zip.sha256
```

## Install

Upload the versioned ZIP as an extension in the target Qlik Cloud tenant, then add Tm Flexible
Selections to a sheet and add fields in its Fields section. Import the demo app separately if you
want a working example.

A license comes as a separate license extension. Without one, the object works and shows a small
License tab.
