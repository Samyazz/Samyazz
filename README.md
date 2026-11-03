### Samyazz

System architect at [Zerops](https://zerops.io). Before that, eleven years at a Czech datacenter provider: datacenter support, Linux sysadmin, operations team lead and solution architect for customers. Plenty of those years went into databases that didn't come back the way they were supposed to, which is roughly how my current project started.

**[Karakoram](https://github.com/KarakoramDev/Karakoram)** is an open-source (Apache-2.0) control plane for databases and stateful services on infrastructure you run yourself, on Zerops, Dokploy or Nomad and without Kubernetes. It handles PostgreSQL, MySQL/PXC, MongoDB, Elasticsearch, RabbitMQ and a few more, including backups, point-in-time recovery, failover and rolling upgrades. Docs are at [karakoram.dev](https://karakoram.dev).

Smaller things I've been working on:

- [cloud-hypervisor#9135](https://github.com/cloud-hypervisor/cloud-hypervisor/pull/9135): separate burst rate and depth for the disk and network rate limiter, so a VM on a shared host can burst above its IOPS or bandwidth limit at a capped peak rate for a bounded time, without raising the bucket size and allowing bursts at full device speed (draft, waiting on the design discussion in #9134)
- [convex-on-zerops](https://github.com/Samyazz/convex-on-zerops): self-hosted Convex backend and dashboard on Zerops, running the official binary without Docker
- [terraform-provider-zerops](https://github.com/zeropsio/terraform-provider-zerops): the Terraform and OpenTofu provider for Zerops, which I wrote
- [alchemy](https://github.com/zeropsio/alchemy): the Zerops provider for Alchemy v2, also mine, covering projects, services, databases, storage and routing as TypeScript infrastructure-as-code
- [pulumi-zerops](https://github.com/zeropsio/pulumi-zerops): the Pulumi provider and WebApp component for Zerops, which I wrote as well, usable from Python, Go, .NET, Java, Node.js and YAML
- the provider pages in the [Zerops docs](https://github.com/zeropsio/docs/pulls?q=author%3ASamyazz)

Also on Reddit as [u/Samyazz](https://www.reddit.com/user/Samyazz) and on X as [@samyazz_dev](https://x.com/samyazz_dev).
