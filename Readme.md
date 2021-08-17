# Awesome Sysadmin Tools

A collection of awesome software and cool stuff for sysadmins.

- [CLI tools](#cli-tools)
  - [Shell](#shell)
  - [Git](#git)
  - [Monitoring](#monitoring)
  - [Networking](#networking)
  - [Other](#other-cli-tools)
- [Containers](#containers)
  - [Container Distributions](#container-distributions)
  - [Container tools](#container-tools)
- [Kubernetes](#kubernetes)
  - [Kubernetes Distributions](#kubernetes-distributions)
  - [Kubernetes tools](#kubernetes-tools)
- [Infrastructure](#infrastructure)
  - [Amazon Web Services](#amazon-web-services)
  - [Ansible](#ansible)
  - [Terraform](#terraform)
  - [Diagrams](#diagrams)
- [Security](#security)
  - [2FA](#2fa)
  - [Passwords storage](#passwords-storage)
- [Load testing tools](#load-testing-tools)

## CLI tools

### Shell

- [starship](https://starship.rs) - The minimal, blazing-fast, and infinitely customizable prompt for any shell

### Git

- [lazygit](https://github.com/jesseduffield/lazygit) - A simple terminal UI for git commands
- [pre-commit](https://pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks

### Monitoring

- [htop](https://htop.dev) - An interactive process viewer
- [blktop](https://github.com/amarao/blktop) - top-like monitoring block devices metrics (latency, IOPS and so on)
- [mtr](https://github.com/traviscross/mtr) - combines the functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool

#### Web UI tools

- [SmokePing](https://oss.oetiker.ch/smokeping/) - Graph latency to needed resources
- [LibreSpeed](https://github.com/librespeed/speedtest) - selfhosted speedtest meter

### Networking

- [ngrok](https://ngrok.com) - Expose a local web server to the internet
- [OpenVPN install](https://github.com/angristan/openvpn-install) - OpenVPN installer for Debian, Ubuntu, Fedora, CentOS and Arch Linux.
- [dockvpn](https://github.com/umputun/dockvpn) - OpenVPN for Docker
- [docker-openvpn](https://github.com/kylemanna/docker-openvpn) - OpenVPN for Docker

### Other CLI tools

- [libfaketime](https://github.com/wolfcw/libfaketime) - libfaketime intercepts various system calls that programs use to retrieve the current date and time

## Containers

### Container Distributions

- [LXC](https://linuxcontainers.org/lxc/introduction/) - Linux Containers
- [Docker](https://www.docker.com) - Docker engine
- [CRI-O](https://cri-o.io) - Lightweight container runtime for Kubernetes
- [Containerd](https://containerd.io) - Container runtime

### Container tools

- [ctop](https://github.com/bcicen/ctop) - Top for containers
- [docker-slim](https://github.com/docker-slim/docker-slim) - Minify and Secure Docker containers

## Kubernetes

### Kubernetes Distributions

- [kubeadm](https://github.com/kubernetes/kubeadm) - Kubeadm is a tool built to provide best-practice "fast paths" for creating Kubernetes clusters
- [k3s](https://github.com/k3s-io/k3s) - Lightweight Kubernetes
- [minikube](https://github.com/kubernetes/minikube) - implements a local Kubernetes cluster on macOS, Linux, and Windows
- [kubespray](https://github.com/kubernetes-sigs/kubespray) - Deploy a Production Ready Kubernetes Cluster

### Kubernetes tools

- [k9s](https://github.com/derailed/k9s) - provides a terminal UI to interact with your Kubernetes clusters
- [kubectx](https://github.com/ahmetb/kubectx) - helps you switch between clusters back and forth
- [kubens](https://github.com/ahmetb/kubectx) - helps you switch between Kubernetes namespaces smoothly
- [kubecolor](https://github.com/dty1er/kubecolor) - Colorize your kubectl output
- [kubetail](https://github.com/johanhaleby/kubetail) - Bash script that enables you to aggregate (tail/follow) logs from multiple pods into one stream
- [kube-monkey](https://github.com/asobti/kube-monkey) - kube-monkey is an implementation of Netflix's Chaos Monkey for Kubernetes clusters
- [kubectl-reap](https://github.com/micnncim/kubectl-reap) - is a kubectl plugin that deletes unused Kubernetes resources
- [kubecost](https://kubecost.com) - Kubecost gives you visibility into your Kubernetes resources to reduce spend and prevent resource-based outages
- [kustomize](https://kustomize.io) - Kubernetes native configuration management
- [traefik](https://doc.traefik.io/traefik/) - Traefik is an open-source Edge Router that makes publishing your services a fun and easy experience
- [ingress-nginx](https://github.com/kubernetes/ingress-nginx) Ingress-NGINX is an Ingress controller for Kubernetes using NGINX as a reverse proxy and load balancer

## Infrastructure

### Amazon Web Services

- [chamber](https://github.com/segmentio/chamber) - Chamber is a tool for managing secrets. Currently it does so by storing secrets in SSM Parameter Store, an AWS service for storing secrets.
- [awscreds](https://github.com/DmitriyLyalyuev/awscreds) - Store AWS credentials inside your Keychain

### Ansible

- [ansible](https://github.com/ansible/ansible) - Ansible is a radically simple IT automation system
- [molecule](https://molecule.readthedocs.io/en/latest/) - Molecule project is designed to aid in the development and testing of Ansible roles

### Terraform

- [terraform](https://www.terraform.io) - Terraform is an open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services
- [tflint](https://github.com/terraform-linters/tflint) - TFLint is a Terraform linter focused on possible errors, best practices, etc
- [tfswitch](https://github.com/warrensbox/terraform-switcher) - The tfswitch command line tool lets you switch between different versions of terraform
- [terraform-docs](https://github.com/terraform-docs/terraform-docs) - A utility to generate documentation from Terraform modules in various output formats
- [checkov](https://github.com/bridgecrewio/checkov) - Checkov is a static code analysis tool for infrastructure-as-code

### Diagrams

- [diagrams](https://diagrams.mingrammer.com) - infrastructure diagrams as code

## Security

### 2FA

- [Authy](https://authy.com) - Best Rated 2FA App

### Passwords storage

- [1Password](https://1password.com) - 1Password is the easiest way to store and use strong passwords
- [KeepassXC](https://keepassxc.org) - Cross-Platform Password Manager
- [LastPass](https://www.lastpass.com) - Auto-pilot for all your passwords

## Load testing tools

- [k6.io](https://k6.io) - Open source load testing tool and SaaS for engineering teams
- [Gatling](https://gatling.io) - Load-Test-As-Code: the best way to load test your applications, designed for DevOps and CI/CD
- [Yandex Tank](https://yandex.com/dev/tank/) - Yandex.Tank is a utility for load testing and performance analysis of web services and applications
- [JMeter](https://jmeter.apache.org) - Apache JMeter may be used to test performance both on static and dynamic resources, Web dynamic applications
- [siege](https://github.com/JoeDog/siege) - Siege is an open source regression test and benchmark utility
- [ab](http://httpd.apache.org/docs/2.4/programs/ab.html) - ab is a tool for benchmarking your Apache Hypertext Transfer Protocol (HTTP) server
