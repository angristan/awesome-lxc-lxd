# Awesome LXC, LXD and Incus

A curated list of useful LXC, LXD, and Incus tools, libraries, integrations, and learning resources.

LXC is the low-level system container runtime. Incus and LXD build on LXC to manage system containers and virtual machines through a cloud-like API and command-line interface.

## Official projects

- [LXC](https://github.com/lxc/lxc) — Linux system container runtime.
- [LXCFS](https://github.com/lxc/lxcfs) — FUSE filesystem providing container-aware system information.
- [Incus](https://github.com/lxc/incus) — Community-led system container and virtual machine manager.
- [LXD](https://github.com/canonical/lxd) — Canonical's system container and virtual machine manager.

## Interesting reads

- [Comparing LXD vs. LXC](https://discuss.linuxcontainers.org/t/comparing-lxd-vs-lxc/24) — Explains the different roles of the LXC runtime and LXD manager.
- [LXD 2.0 blog post series](https://stgraber.org/2016/03/11/lxd-2-0-blog-post-series-012/) — In-depth introduction to LXD's core concepts by Stéphane Graber.

## Libraries

- [go-lxc](https://github.com/lxc/go-lxc) — Go bindings for liblxc.
- [ruby-lxc](https://github.com/lxc/ruby-lxc) — Ruby bindings for liblxc.
- [python3-lxc](https://github.com/lxc/python3-lxc) — Python 3 bindings for liblxc.
- [php-lxd](https://github.com/turtle0x1/php-lxd) — PHP client library for the LXD REST API.

## Tools

- [distrobuilder](https://github.com/lxc/distrobuilder) — Builds LXC and Incus images from declarative YAML definitions.
- [lxd-compose](https://github.com/MottainaiCI/lxd-compose) — Defines and runs groups of LXD containers.

## User interfaces

- [LxdMosaic](https://github.com/turtle0x1/LxdMosaic) — Web interface for managing multiple LXD and Incus servers.

## Related projects

- [bravetools](https://github.com/bravetools/bravetools) — Builds, deploys, and releases environments with system containers.
- [Mini-Internet](https://github.com/flesueur/mi-lxc) — Builds virtual Internet-like networks with LXC for teaching and research.
