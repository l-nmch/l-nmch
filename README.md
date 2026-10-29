# Hi 👋 I'm Léo Nonnenmacher

**Platform Engineer & MLOps** at [Cloudeo](https://www.cloudeo.fr) · trainer · CEO of [Retake](https://retake.fr)

I build cloud and AI infrastructure with a frugal approach (a lot with little, kept secure) and I take apart hardware that was declared dead until it works again.

- 🌍 Based in Strasbourg
- 🚀 Building [Phorge](https://github.com/phorge-fr), an open-source, self-hostable cloud provider
- 🧠 Exploring Crossplane and Upjet providers, LLMs on unusual NPUs and GPUs, and GitOps at homelab scale
- ✉️ [leo@nonnenmacher-logel.fr](mailto:leo@nonnenmacher-logel.fr) · [Blog](https://leo.nonnenmacher-logel.fr) · [LinkedIn](https://www.linkedin.com/in/l%C3%A9o-nonnenmacher/) · [Retake](https://retake.fr)

## Phorge

Every line of configuration, automation and infrastructure logic is public. The roadmap is a [public GitHub project](https://github.com/orgs/phorge-fr/projects/3).

| Repository | What it holds |
| --- | --- |
| [Hangar](https://github.com/phorge-fr/Hangar) | GitOps (Flux) for the Kubernetes clusters: manifests, Crossplane compositions, docs |
| [Network](https://github.com/phorge-fr/Network) | Router configuration as code with OpenTofu |
| [Ansible](https://github.com/phorge-fr/Ansible) | Roles and playbooks for everything that is not Kubernetes |
| [phorge-api](https://github.com/phorge-fr/phorge-api) | The Phorge API: tenants, images, instances, memberships and API keys |

### Crossplane providers

Generated with [Upjet](https://github.com/crossplane/upjet), to manage Phorge's building blocks from Kubernetes.

- [provider-incus](https://github.com/l-nmch/provider-incus): Incus, from lxc/terraform-provider-incus
- [provider-openfga](https://github.com/l-nmch/provider-openfga): OpenFGA, from openfga/terraform-provider-openfga
- [provider-authentik](https://github.com/l-nmch/provider-authentik): authentik

## AI, NPU and homelab

- [hailo-10h-llm-compiler](https://github.com/l-nmch/hailo-10h-llm-compiler): compile your own LLM for the Hailo-10H, from a Hugging Face checkpoint to a self-contained HEF
- [hailo-mnist](https://github.com/l-nmch/hailo-mnist): train a model and deploy it on a Hailo-8L NPU
- [benchy-graph](https://github.com/l-nmch/benchy-graph): display llama-benchy results as graphs
- [GladoCam](https://github.com/l-nmch/GladoCam): real-time face tracking with OpenCV and an ESP8266

More on the [blog](https://leo.nonnenmacher-logel.fr): [LLMs on a Hailo-10H](https://leo.nonnenmacher-logel.fr/en/posts/hailo10h-llm-compile/) and [training an LLM from scratch on a 2020 GPU](https://leo.nonnenmacher-logel.fr/en/posts/llm-from-scratch-t10/).

## Stack

**Platform**

<p align="left">
<a href="https://kubernetes.io/" target="_blank" rel="noreferrer"><img src="./assets/kubernetes.svg" width="36" height="36" alt="Kubernetes" title="Kubernetes" /></a>
<a href="https://k0sproject.io/" target="_blank" rel="noreferrer"><img src="./assets/k0s.svg" width="36" height="36" alt="k0s" title="k0s" /></a>
<a href="https://cilium.io/" target="_blank" rel="noreferrer"><img src="./assets/cilium.svg" width="36" height="36" alt="Cilium" title="Cilium" /></a>
<a href="https://traefik.io/traefik/" target="_blank" rel="noreferrer"><img src="./assets/traefik.svg" width="36" height="36" alt="Traefik" title="Traefik" /></a>
<a href="https://longhorn.io/" target="_blank" rel="noreferrer"><img src="./assets/longhorn.svg" width="36" height="36" alt="Longhorn" title="Longhorn" /></a>
<a href="https://cert-manager.io/" target="_blank" rel="noreferrer"><img src="./assets/cert-manager.svg" width="36" height="36" alt="cert-manager" title="cert-manager" /></a>
<a href="https://linuxcontainers.org/incus/" target="_blank" rel="noreferrer"><img src="./assets/incus.svg" width="36" height="36" alt="Incus" title="Incus" /></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="./assets/docker.svg" width="36" height="36" alt="Docker" title="Docker" /></a>
</p>

**GitOps and automation**

<p align="left">
<a href="https://fluxcd.io/" target="_blank" rel="noreferrer"><img src="./assets/flux.svg" width="36" height="36" alt="Flux" title="Flux" /></a>
<a href="https://www.crossplane.io/" target="_blank" rel="noreferrer"><img src="./assets/crossplane.svg" width="36" height="36" alt="Crossplane" title="Crossplane" /></a>
<a href="https://opentofu.org/" target="_blank" rel="noreferrer"><img src="./assets/opentofu.svg" width="36" height="36" alt="OpenTofu" title="OpenTofu" /></a>
<a href="https://www.ansible.com/" target="_blank" rel="noreferrer"><img src="./assets/ansible.svg" width="36" height="36" alt="Ansible" title="Ansible" /></a>
<a href="https://getsops.io/" target="_blank" rel="noreferrer"><img src="./assets/sops.svg" width="36" height="36" alt="SOPS" title="SOPS" /></a>
<a href="https://docs.renovatebot.com/" target="_blank" rel="noreferrer"><img src="./assets/renovate.svg" width="36" height="36" alt="Renovate" title="Renovate" /></a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="./assets/git.svg" width="36" height="36" alt="Git" title="Git" /></a>
<a href="https://github.com/features/actions" target="_blank" rel="noreferrer"><img src="./assets/github-actions.svg" width="36" height="36" alt="GitHub Actions" title="GitHub Actions" /></a>
</p>

**Identity and observability**

<p align="left">
<a href="https://goauthentik.io/" target="_blank" rel="noreferrer"><img src="./assets/authentik.svg" width="36" height="36" alt="authentik" title="authentik" /></a>
<a href="https://openfga.dev/" target="_blank" rel="noreferrer"><img src="./assets/openfga.svg" width="36" height="36" alt="OpenFGA" title="OpenFGA" /></a>
<a href="https://grafana.com/" target="_blank" rel="noreferrer"><img src="./assets/grafana.svg" width="36" height="36" alt="Grafana" title="Grafana" /></a>
<a href="https://grafana.com/oss/loki/" target="_blank" rel="noreferrer"><img src="./assets/loki.svg" width="36" height="36" alt="Loki" title="Loki" /></a>
<a href="https://prometheus.io/" target="_blank" rel="noreferrer"><img src="./assets/prometheus.svg" width="36" height="36" alt="Prometheus" title="Prometheus" /></a>
</p>

**Code, AI and hardware**

<p align="left">
<a href="https://go.dev/" target="_blank" rel="noreferrer"><img src="./assets/go.svg" width="36" height="36" alt="Go" title="Go" /></a>
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="./assets/python.svg" width="36" height="36" alt="Python" title="Python" /></a>
<a href="https://www.tensorflow.org/" target="_blank" rel="noreferrer"><img src="./assets/tensorflow.svg" width="36" height="36" alt="TensorFlow" title="TensorFlow" /></a>
<a href="https://www.nvidia.com/" target="_blank" rel="noreferrer"><img src="./assets/nvidia.svg" width="36" height="36" alt="NVIDIA" title="NVIDIA" /></a>
<a href="https://rocm.docs.amd.com/" target="_blank" rel="noreferrer"><img src="./assets/amd.svg" width="36" height="36" alt="AMD ROCm" title="AMD ROCm" /></a>
<a href="https://www.raspberrypi.org/" target="_blank" rel="noreferrer"><img src="./assets/raspberrypi.svg" width="36" height="36" alt="Raspberry Pi" title="Raspberry Pi" /></a>
<a href="https://kernel.org/" target="_blank" rel="noreferrer"><img src="./assets/linux.svg" width="36" height="36" alt="Linux" title="Linux" /></a>
</p>

## Activity

Generated daily by [lowlighter/metrics](https://github.com/lowlighter/metrics) from [this workflow](.github/workflows/metrics.yml), nothing external to fail.

![GitHub metrics](./github-metrics.svg)
