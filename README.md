# Renovate Linuxserver Issue

Repo to reproduce the problem I have using renovate and a custom regex versioning.

## Problem

I have a repository where I am using renovate, which is not updating a dependency anymore.

Renovate updated the version `4.7.5.7809-ls185` to `4.7.5.7809-ls186` on Aug 21, but did not suggest any updates after that, even though new versions were released as shown below.

- Current version: [`4.7.5.7809-ls186`](https://github.com/linuxserver/docker-radarr/pkgs/container/radarr/120262380?tag=4.7.5.7809-ls186)
- Next version: [`4.7.5.7809-ls187`](https://github.com/linuxserver/docker-radarr/pkgs/container/radarr/124456979?tag=4.7.5.7809-ls187)
- Latest version: [`5.0.3.8127-ls190`](https://github.com/linuxserver/docker-radarr/pkgs/container/radarr/135296920?tag=5.0.3.8127-ls190)

The regex does not seem to be the problem as shown here: https://regex101.com/r/NUMmB6/1
