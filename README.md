# Awesome LXC, LXD and Incus

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of useful LXC, LXD, and Incus tools, libraries, integrations, and learning resources.

## Contents

- [Packages and Host Platforms](#packages-and-host-platforms)
- [Images and Image Building](#images-and-image-building)
- [Libraries and SDKs](#libraries-and-sdks)
- [Infrastructure as Code and Orchestration](#infrastructure-as-code-and-orchestration)
- [Tools and Development Workflows](#tools-and-development-workflows)
- [User Interfaces](#user-interfaces)
- [Operations](#operations)
- [Community and Learning](#community-and-learning)
- [Historical Reads](#historical-reads)
- [Official Resources](#official-resources)
- [Contributing](#contributing)

## Packages and Host Platforms

- [zabbly/incus](https://github.com/zabbly/incus) — Signed Incus packages for supported Debian and Ubuntu releases.
- [copr-lxc4](https://github.com/ganto/copr-lxc4) — Fedora COPR packages for LXC, LXCFS, LXD, and Incus.
- [pve-container](https://git.proxmox.com/?p=pve-container.git) — Proxmox VE container manager and runtime built on LXC.
- [vpsadminos](https://github.com/vpsfreecz/vpsadminos) — NixOS and ZFS-based host operating system for unprivileged LXC containers.
- [incus-docker](https://github.com/cmspam/incus-docker) — Runs Incus and its web UI inside privileged Docker or Podman containers.

## Images and Image Building

- [Ubuntu Cloud Images](https://cloud-images.ubuntu.com/releases/) — Official stable Ubuntu images used by the `ubuntu:` remote.
- [incus-windows](https://github.com/antifob/incus-windows) — Toolset for creating Windows images for Incus virtual machines.
- [polar](https://github.com/upmaru/polar) — Simple Streams image server for LXD and Incus.
- [simplestreams-builder](https://github.com/MottainaiCI/simplestreams-builder) — Builds LXC, LXD, and Incus-compatible Simple Streams trees.
- [lxd-openwrt](https://github.com/mikma/lxd-openwrt) — Builds OpenWrt root filesystems as LXD system container images.
- [talos-incus](https://github.com/windsorcli/talos-incus) — Publishes signed Talos Linux VM images through an Incus Simple Streams remote.

## Libraries and SDKs

- [lxc-rs](https://github.com/sanpii/lxc-rs) — Rust bindings for the native `liblxc` API.
- [php-lxd](https://github.com/turtle0x1/php-lxd) — PHP client library for the LXD REST API.

## Infrastructure as Code and Orchestration

- [terraform-provider-lxd](https://github.com/terraform-lxd/terraform-provider-lxd) — Manages LXD resources with Terraform or OpenTofu.
- [community.general.incus](https://docs.ansible.com/ansible/latest/collections/community/general/incus_connection.html) — Runs Ansible tasks directly inside Incus instances.
- [community.general.lxd](https://docs.ansible.com/ansible/latest/collections/community/general/lxd_connection.html) — Runs Ansible tasks directly inside LXD instances.
- [packer-plugin-lxc](https://github.com/hashicorp/packer-plugin-lxc) — Builds native LXC container images with Packer.
- [packer-plugin-incus](https://github.com/bketelsen/packer-plugin-incus) — Builds reusable Incus images with Packer provisioners.
- [packer-plugin-lxd](https://github.com/hashicorp/packer-plugin-lxd) — Builds reusable LXD images with Packer provisioners.
- [incus-apply](https://github.com/abiosoft/incus-apply) — Declarative configuration management for Incus resources.
- [Proxmox-GitOps](https://github.com/stevius10/Proxmox-GitOps) — GitOps and infrastructure-as-code framework for Proxmox LXC containers.
- [proxmox-lxc-autoscale](https://github.com/fabriziosalmi/proxmox-lxc-autoscale) — Dynamically adjusts CPU and memory allocations for Proxmox LXC containers.

## Tools and Development Workflows

- [lxd-compose](https://github.com/MottainaiCI/lxd-compose) — Defines and runs groups of LXD or Incus instances.
- [colima](https://github.com/abiosoft/colima) — Runs Docker, containerd, Kubernetes, or Incus on macOS and Linux with minimal setup.
- [incant](https://github.com/lnussbaum/incant) — Defines reproducible Incus development environments in YAML.
- [blincus](https://github.com/ublue-os/blincus) — Creates rapid Incus-based development environments.
- [code-on-incus](https://github.com/mensfeld/code-on-incus) — Runs isolated development agents with root, systemd, Docker, and network threat controls.
- [incus-spawn](https://github.com/Sanne/incus-spawn) — CLI and TUI for disposable Incus development sandboxes.
- [lincubate](https://github.com/popey/lincubate) — Runs development agents in sandboxed LXD containers.
- [vibebin](https://github.com/jgbrwn/vibebin) — Creates Incus-backed coding and hosting environments on self-hosted servers.
- [crabbox](https://github.com/openclaw/crabbox) — Creates Incus-backed SSH leases for remote development and test workloads.
- [containarium](https://github.com/FootprintAI/Containarium) — Provides SSH-native isolated environments with an LXC backend, eBPF egress controls, and GPU support.
- [edi](https://github.com/lueschem/edi) — Builds reproducible embedded OS artifacts and LXD-based digital twins.
- [bravetools](https://github.com/bravetools/bravetools) — Builds, deploys, and releases environments with system containers.
- [garm](https://github.com/cloudbase/garm) and [garm-provider-incus](https://github.com/cloudbase/garm-provider-incus) — Autoscale ephemeral GitHub Actions and Gitea runners on Incus.
- [ssh2incus](https://github.com/mobydeck/ssh2incus) — SSH gateway for accessing Incus instances.
- [mi-lxc](https://github.com/flesueur/mi-lxc) — Builds virtual Internet-like networks with LXC for teaching and research.

## User Interfaces

- [incus-ui-canonical](https://github.com/zabbly/incus-ui-canonical) — Frequently rebased Incus-compatible fork of Canonical's LXD UI.
- [lxconsole](https://github.com/PenningLabs/lxconsole) — Multi-server web console supporting LXD and Incus.
- [LxdMosaic](https://github.com/turtle0x1/LxdMosaic) — Web interface for managing multiple LXD and Incus servers.
- [kapsule](https://github.com/KDE/kapsule) — Incus container management with KDE Plasma integration.
- [ararat-web](https://github.com/hyecompany/ararat-web) — Incus-native web control plane currently in public beta.
- [oneclickvirt](https://github.com/oneclickvirt/oneclickvirt) — Multi-hypervisor management panel with Incus and LXD support.
- [xpipe](https://github.com/xpipe-io/xpipe) — Desktop interface for discovering and accessing local or remote LXD and Incus instances.

## Operations

- [incusbackup](https://github.com/ScottiBYTE/incusbackup) — Web-based scheduled backup and restore across multiple Incus remotes.
- [incusAutobackup](https://github.com/rbnhln/incusAutobackup) — Replicates Incus instances and volumes between source and target hosts.
- [Incus Grafana dashboard](https://grafana.com/grafana/dashboards/19727-incus/) — Dashboard for Incus server, project, and instance metrics.

## Community and Learning

- [LXC on Libera.Chat](https://web.libera.chat/#lxc) — Real-time `#lxc` community channel.
- [Zabbly on YouTube](https://www.youtube.com/@TheZabbly) — Incus demos, release announcements, and tutorials.
- [ArchWiki: LXC](https://wiki.archlinux.org/title/Linux_Containers), [Incus](https://wiki.archlinux.org/title/Incus), and [LXD](https://wiki.archlinux.org/title/LXD) — Distribution-specific installation and operations guides.
- [Creating an Incus server](https://docs.rockylinux.org/latest/books/incus_server/00-toc/) — Long-form Incus deployment guide for Rocky Linux.

## Historical Reads

These resources explain foundational concepts but may contain outdated commands or project details.

- [Comparing LXD vs. LXC](https://discuss.linuxcontainers.org/t/comparing-lxd-vs-lxc/24) — Early explanation of the different roles of the LXC runtime and LXD manager.
- [LXD 2.0 blog post series](https://stgraber.org/2016/03/11/lxd-2-0-blog-post-series-012/) — In-depth introduction to LXD's original core concepts by Stéphane Graber.

---

## Official Resources

### Projects

- [Linux Containers](https://linuxcontainers.org/) — Home of the LXC, LXCFS, Incus, and distrobuilder projects.
- [lxc](https://github.com/lxc/lxc) — Linux system container runtime, command-line tools, and `liblxc` library.
- [lxcfs](https://github.com/lxc/lxcfs) — FUSE filesystem providing container-aware system information.
- [incus](https://github.com/lxc/incus) — Community-led system container and virtual machine manager.
- [incus-os](https://github.com/lxc/incus-os) — Immutable operating system dedicated to running Incus.
- [lxd](https://github.com/canonical/lxd) — Canonical's system container and virtual machine manager.
- [microcloud](https://github.com/canonical/microcloud) — Automated private cloud built from LXD, Ceph, and OVN.

### Documentation

**LXC**

- [LXC documentation](https://linuxcontainers.org/lxc/documentation/) — Upstream configuration, API, and usage documentation.
- [Getting started with LXC](https://linuxcontainers.org/lxc/getting-started/) — Introduction to installing and creating unprivileged containers.
- [LXC man pages](https://linuxcontainers.org/lxc/manpages/) — Command and `lxc.container.conf` reference.
- [liblxc C API](https://linuxcontainers.org/lxc/apidoc/) — Generated native API reference.

**Incus**

- [Incus documentation](https://linuxcontainers.org/incus/docs/main/) — Official tutorials, how-to guides, explanations, and reference material.
- [First steps with Incus](https://linuxcontainers.org/incus/docs/main/tutorial/first_steps/) — Guided introduction to creating and managing instances.
- [Try Incus online](https://linuxcontainers.org/incus/try-it/) — Interactive tutorial in a disposable hosted environment.
- [Incus REST API](https://linuxcontainers.org/incus/docs/main/rest-api/) — API behavior, authentication, extensions, and endpoints.
- [Incus CLI reference](https://linuxcontainers.org/incus/docs/main/reference/manpages/) — Complete `incus` command reference.

**LXD**

- [LXD documentation](https://documentation.ubuntu.com/lxd/latest/) — Canonical's official tutorial, how-to, explanation, and reference hub.
- [First steps with LXD](https://documentation.ubuntu.com/lxd/latest/tutorial/first_steps/) — Guided CLI and web UI introduction.
- [LXD REST API](https://documentation.ubuntu.com/lxd/latest/restapi_landing/) — API, OpenAPI specification, extensions, and events.
- [LXD CLI reference](https://documentation.ubuntu.com/lxd/latest/reference/manpages/) — Complete `lxc` command reference.

### Images and Image Building

- [Linux Containers image server](https://images.linuxcontainers.org/) — Continuously built and tested images for LXC and Incus.
- [Canonical LXD image server](https://images.lxd.canonical.com/) — Multi-distribution image catalog used by LXD's `images:` remote.
- [distrobuilder](https://github.com/lxc/distrobuilder) — Builds LXC and Incus images from declarative YAML definitions.
- [distrobuilder documentation](https://linuxcontainers.org/distrobuilder/docs/latest/) — Tutorials and reference for custom LXC and Incus images.
- [lxd-imagebuilder](https://github.com/canonical/lxd-imagebuilder) — Builds LXD container and VM images and Simple Streams catalogs.
- [lxd-imagebuilder documentation](https://canonical-lxd-imagebuilder.readthedocs-hosted.com/) — Tutorials and reference for `lxd-imagebuilder`.

### SDKs and Integrations

- [go-lxc](https://github.com/lxc/go-lxc) — Go bindings for `liblxc`.
- [python3-lxc](https://github.com/lxc/python3-lxc) — Python 3 bindings for `liblxc`.
- [Incus Go client](https://pkg.go.dev/github.com/lxc/incus/client) — Official Go SDK shipped with Incus.
- [LXD Go client](https://pkg.go.dev/github.com/canonical/lxd/client) — Official Go SDK shipped with LXD.
- [pylxd](https://github.com/canonical/pylxd) — Official Python client for the LXD REST API.
- [terraform-provider-incus](https://github.com/lxc/terraform-provider-incus) — Manages Incus instances, projects, profiles, networks, and storage.
- [cluster-api-provider-incus](https://github.com/lxc/cluster-api-provider-incus) — Provisions Kubernetes clusters on Incus, LXD, and MicroCloud.
- [incus-deploy](https://github.com/lxc/incus-deploy) — Ansible, Terraform, and scripts for deploying Incus clusters with Ceph and OVN.
- [lxd-csi-driver](https://github.com/canonical/lxd-csi-driver) — Exposes LXD storage to Kubernetes workloads.
- [incus-compose](https://github.com/lxc/incus-compose) — Runs Compose-spec workloads natively on Incus.
- [lxd-ui](https://github.com/canonical/lxd-ui) — Canonical's official browser interface, included with LXD.

### Backup and Migration

- [Back up an Incus server](https://linuxcontainers.org/incus/docs/main/backup/) — Official snapshot, export, recovery, and host-level backup guidance.
- [Back up an LXD server](https://documentation.ubuntu.com/lxd/latest/backup/) — Official instance, volume, and server backup guidance.
- [Incus migration overview](https://linuxcontainers.org/incus/docs/main/migration/) — Server-to-server, LXC, physical machine, and virtual machine migration guides.
- [Import machines into Incus](https://linuxcontainers.org/incus/docs/main/howto/import_machines_to_instances/) — Imports filesystems and raw, QCOW2, OVA, or VMDK images with `incus-migrate`.
- [Migrate LXC containers to Incus](https://linuxcontainers.org/incus/docs/main/howto/migrate_from_lxc/) — Converts local LXC containers with `lxc-to-incus`.
- [Migrate LXD to Incus](https://github.com/lxc/incus/blob/stable-7.0/doc/howto/server_migrate_lxd.md) — Version-pinned `lxd-to-incus` guide; check its compatibility table before migrating.
- [Migrate LXD instances](https://documentation.ubuntu.com/lxd/latest/howto/instances_migrate/) — Copies, moves, and live-migrates instances between LXD servers.
- [Import machines into LXD](https://documentation.ubuntu.com/lxd/latest/howto/import_machines_to_instances/) — Converts physical machines and foreign VM disks with `lxd-convert`.

### Monitoring and Security

- [Incus metrics](https://linuxcontainers.org/incus/docs/main/metrics/) — Exposes native Prometheus metrics for servers and instances.
- [LXD metrics](https://documentation.ubuntu.com/lxd/latest/metrics/) — Exposes native Prometheus metrics for servers and instances.
- [LXC security](https://linuxcontainers.org/lxc/security/) — Threat model, privileged versus unprivileged containers, and vulnerability reporting.
- [Incus security](https://linuxcontainers.org/incus/docs/main/explanation/security/) — Isolation, daemon access, networking, and supported-release guidance.
- [Incus security advisories](https://github.com/lxc/incus/security) — Reporting policy and published advisories.
- [LXD security](https://documentation.ubuntu.com/lxd/latest/explanation/security/) — Security architecture and operational considerations.
- [Hardening LXD](https://documentation.ubuntu.com/lxd/latest/howto/security_harden/) — Production hardening checklist.
- [LXD security advisories](https://github.com/canonical/lxd/security/advisories) — Canonical's published vulnerability record.

### Community

- [Linux Containers Forum](https://discuss.linuxcontainers.org/) — Official support forum for Incus, LXC, LXCFS, and distrobuilder.
- [Linux Containers tutorials](https://discuss.linuxcontainers.org/c/tutorials/16) — Community-reviewed tutorials across the Linux Containers projects.
- [LXD on Ubuntu Community Hub](https://discourse.ubuntu.com/c/project/lxd/126) — Official LXD support and discussion forum.
- [LXD community tutorials](https://discourse.ubuntu.com/c/project/lxd/tutorials/146) — Community-authored LXD tutorials.
- [LXD on YouTube](https://www.youtube.com/channel/UCuP6xPt0WTeZu32CkQPpbvA) — Canonical's LXD videos and tutorials.

## Contributing

Contributions are welcome. Please read [the contribution guidelines](CONTRIBUTING.md) before opening a pull request.
