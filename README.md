# depscan sandbox

A playground repo for [depscan](https://github.com/depscan-go/depscan). Open a pull request that changes `service/go.mod` or `web/package-lock.json`, and depscan scans it automatically.

`main` is clean on purpose. The `add-risky-deps` branch adds a known-vulnerable package (axios 0.21.1) and a GPL one (ffmpeg-static).
