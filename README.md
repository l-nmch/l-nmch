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

<p align="left">
<a href="https://kubernetes.io/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/kubernetes-colored.svg" width="36" height="36" alt="Kubernetes" /></a>
<a href="https://opentofu.org/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/opentofu/opentofu-icon.svg" width="36" height="36" alt="OpenTofu" /></a>
<a href="https://linuxcontainers.org/incus/" target="_blank" rel="noreferrer"><img src="https://linuxcontainers.org/static/img/containers.small.png" width="36" height="36" alt="Incus" /></a>
<a href="https://fluxcd.io/" target="_blank" rel="noreferrer"><img src="./assets/flux.svg" width="36" height="36" alt="Flux" /></a>
<a href="https://www.crossplane.io/" target="_blank" rel="noreferrer"><img src="./assets/crossplane.svg" width="36" height="36" alt="Crossplane" /></a>
<a href="https://www.ansible.com/" target="_blank" rel="noreferrer"><img src="./assets/ansible.svg" width="36" height="36" alt="Ansible" /></a>
<a href="https://goauthentik.io/" target="_blank" rel="noreferrer"><img src="./assets/authentik.svg" width="36" height="36" alt="authentik" /></a>
<a href="https://openfga.dev/" target="_blank" rel="noreferrer"><img src="./assets/openfga.svg" width="36" height="36" alt="OpenFGA" /></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/docker-colored.svg" width="36" height="36" alt="Docker" /></a>
<a href="https://go.dev/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/go-colored.svg" width="36" height="36" alt="Go" /></a>
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a>
<a href="https://www.tensorflow.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tensorflow-colored.svg" width="36" height="36" alt="Tensorflow" /></a>
<a href="https://www.raspberrypi.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/raspberrypi-colored.svg" width="36" height="36" alt="Raspberry Pi" /></a>
</p>

## Activity

Generated daily by [lowlighter/metrics](https://github.com/lowlighter/metrics) from [this workflow](.github/workflows/metrics.yml), nothing external to fail.

![GitHub metrics](./github-metrics.svg)
