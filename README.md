# TSNet Releases

Public release repository for TSNet Server and TSNet Client.

Release assets are built and signed locally from the private `TSNet` source repository, then uploaded with `RELEASE_GITHUB.cmd`.

This repository intentionally does **not** contain the private RSA release-signing key. Each GitHub Release contains the installers, signed update manifests, update ZIP packages, SHA-256 checksums, and the public signing key.

Do not upload customer configuration, databases, logs, or private signing credentials here.
