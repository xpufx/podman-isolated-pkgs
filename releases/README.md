# Generic Linux Standalone Releases

Self-contained binary tarballs of isolated upstream Podman and its OCI stack (crun, conmon, netavark, aardvark-dns).

### Installation
```bash
# Download tarball (e.g. for amd64)
curl -LO https://xpufx.github.io/podman-isolated-pkgs/releases/podman-isolated-6.1.0-linux-amd64.tar.gz

# Extract and run installer
tar -xzf podman-isolated-6.1.0-linux-amd64.tar.gz
sudo ./install.sh
```

Installs to `/opt/podman/releases/<version>/` with `/usr/bin/podman6` entrypoint.
