# apple-unityplugins-build

Throwaway CI repo: builds Apple's official Unity plug-ins (`Apple.Core` +
`Apple.GameKit`) on a GitHub-hosted macOS runner, so the resulting `.tgz` UPM
packages can be used from a Windows machine with no Mac.

Run it from the **Actions** tab (`build-apple-unity-plugins` -> Run workflow),
then download the `apple-unity-plugins-gamekit` artifact.

Upstream: https://github.com/apple/unityplugins
