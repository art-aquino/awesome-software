# Awesome Software

## Operating Systems

__Container Specific Operating Systems__:

- [LinuxKit by Docker](https://github.com/linuxkit/linuxkit) is a toolkit for building custom minimal, immutable Linux distributions. Build you own container OS!
- [Photon OS from VMware](https://vmware.github.io/photon/) is a Linux based, open source, security-hardened, enterprise grade appliance operating system that is purpose built for Cloud and Edge applications.
- [k3OS by Rancher](https://github.com/rancher/k3os) is a Linux distribution designed to remove as much OS maintenance as possible in a Kubernetes cluster. It is specifically designed to only have what is needed to run k3s. Additionally the OS is designed to be managed by kubectl once a cluster is bootstrapped. Nodes only need to join a cluster and then all aspects of the OS can be managed from Kubernetes. Both k3OS and k3s upgrades are handled by the k3OS operator.
- [Bottlerocket by AWS](https://aws.amazon.com/bottlerocket/) is a Linux-based open-source operating system that is purpose-built by Amazon Web Services for running containers. Bottlerocket includes only the essential software required to run containers, and ensures that the underlying software is always secure. With Bottlerocket, customers can reduce maintenance overhead and automate their workflows by applying configuration settings consistently as nodes are upgraded or replaced. Bottlerocket is now generally available at no cost as an Amazon Machine Image (AMI) for Amazon Elastic Compute Cloud (EC2).
- [Fedora CoreOS by RedHat](https://getfedora.org/en/coreos?stream=stable) is an automatically-updating, minimal operating system for running containerized workloads securely and at scale. It is currently available on multiple platforms, with more coming soon.
- [Flatcar by Microsoft](https://www.flatcar.org) is a community Linux distribution designed for container workloads, with high security and low maintenance.
- [Talo OS](https://www.siderolabs.com/platform/talos-os-for-kubernetes/) is an API driven Kubernetes operating system.

## Terminal

- [Textualize](https://www.textualize.io) brings beautiful output in the terminal and Jupyter notebook with this powerful Python library. Tables, panels, progress bars, trees, syntax highlighting, pretty printing, and much more.

## Misc CLI Tools

- [SOPS](https://github.com/mozilla/sops) is an editor of encrypted files that supports YAML, JSON, ENV, INI and BINARY formats and encrypts with AWS KMS, GCP KMS, Azure Key Vault, age, and PGP.

## Networking

- [Caddy](https://caddyserver.com/docs/) is a powerful, extensible platform to serve your sites, services, and apps, written in Go. If you're new to Caddy, the way you serve the Web is about to change.
- [Caddy Forward Auth](https://github.com/firecow/caddy-forward-auth) is a minimal forward authentication service that provides OAuth/SSO login and authentication for the Caddy reverse proxy/load balancer.
- [Caddy Authz](https://github.com/casbin/caddy-authz) is an authorization middleware based on [Casbin](https://github.com/casbin/casbin)
- [Traefik](https://traefik.io) is the simplest, most comprehensive cloud-native stack to help enterprises manage their entire network across data centers, on-premises servers and public clouds all the way out to the edge.
- [Traefik Forward Auth](https://github.com/thomseddon/traefik-forward-auth) is a minimal forward authentication service that provides OAuth/SSO login and authentication for the traefik reverse proxy/load balancer.
- [NGINX Proxy Manager](https://nginxproxymanager.com) is a service built on top of NGINX to fill a personal need to provide users with a easy way to accomplish reverse proxying hosts with SSL termination and it had to be so easy that a monkey could do it. [Github Project](https://github.com/NginxProxyManager/nginx-proxy-manager)
- [HAProxy](http://www.haproxy.org) is a free, very fast and reliable reverse-proxy offering high availability, load balancing, and proxying for TCP and HTTP-based applications. It is particularly suited for very high traffic web sites and powers a significant portion of the world's most visited ones.
- [CoreDNS](https://coredns.io) is a DNS server. It is written in Go. It can be used in a multitude of environments because of its flexibility. CoreDNS is licensed under the Apache License Version 2, and completely open source.
- [Netmaker](https://netmaker.readthedocs.io/en/master/) is a platform for creating fast and secure virtual networks with WireGuard.

## Automation

- [Alfred for MacOS](https://www.alfredapp.com) is an award-winning app for macOS which boosts your efficiency with hotkeys, keywords, text expansion and more. Search your Mac and the web, and be more productive with custom actions to control your Mac.

# No Code / Low Code

- [Tines](https://www.tines.com) No-code automation for security teams

## API Tools

- [PAW](https://paw.cloud) is a full-featured HTTP client that lets you test and describe the APIs you build or consume. It has a beautiful native macOS interface to compose requests, inspect server responses, generate client code and export API definitions.

## CI / CD

- [Drone](https://www.drone.io) is a self-service Continuous Integration platform for busy development teams.
- [ArgoCD](https://argo-cd.readthedocs.io/en/stable/) is a declarative, GitOps continuous delivery tool for Kubernetes.

## Data Services

- [Maxmind](https://www.maxmind.com/en/geolite2) provides geolocation ip data for internet security services. Integrates with SSO servies like Authentik.

## Identity and Access / SSO

- [Authentik](https://github.com/goauthentik/authentik) is an open-source Identity Provider focused on flexibility and versatility. You can use authentik in an existing environment to add support for new protocols. authentik is also a great solution for implementing signup/recovery/etc in your application, so you don't have to deal with it.
- [Fusion Auth](https://fusionauth.io/download) is the customer authentication and authorization platform that puts developers in the driver’s seat, with control, flexibility and developer ergonomics.
- [Casdoor](https://casdoor.org) is a UI-first Identity Access Management (IAM) / Single-Sign-On (SSO) platform supporting OAuth 2.0, OIDC, SAML and CAS, integrated with Casbin RBAC and ABAC permission management
- [Casbin](https://github.com/casbin/casbin) is a powerful and efficient open-source access control library
- [Casbin Online Policy Editor](https://casbin.org/editor/)

# Programming Languages

### Nim

[Nim](https://nim-lang.org) is a statically typed compiled systems programming language. It combines successful concepts from mature languages like Python, Ada and Modula.

### Zig 

[Zig](https://ziglang.org) is a general-purpose programming language and toolchain for maintaining robust, optimal, and reusable software.

### Rust

[Rust](https://www.rust-lang.org) is blazingly fast and memory-efficient: with no runtime or garbage collector, it can power performance-critical services, run on embedded devices, and easily integrate with other languages. Rust’s rich type system and ownership model guarantee memory-safety and thread-safety — enabling you to eliminate many classes of bugs at compile-time.

### Go

[Go](https://go.dev) is expressive, concise, clean, and efficient. Its concurrency mechanisms make it easy to write programs that get the most out of multicore and networked machines, while its novel type system enables flexible and modular program construction. Go compiles quickly to machine code yet has the convenience of garbage collection and the power of run-time reflection. It's a fast, statically typed, compiled language that feels like a dynamically typed, interpreted language.

- [Cobra.Dev](https://cobra.dev) is a CLI framework for Go. It contains a library for creating powerful modern CLI applications and a tool to rapidly generate Cobra based applications and command files.

### Python

[Python](https://www.python.org) is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. Its language constructs and object-oriented approach aim to help programmers write clear, logical code for small- and large-scale projects.

## Web Frameworks

### Typescript / JS

[Luigi by SAP](https://luigi-project.io)  is an enterprise ready micro frontend JavaScript framework that enables you to create an administrative user interface driven by local and distributed views. Luigi allows a web application to communicate with the micro frontends which the application contains. To make sure the communication runs smoothly, you can easily configure the settings such as routing, navigation, authorization, and user experience elements. 

- [Luigi Github](https://github.com/SAP/luigi)
- [Luigi Svelte Example](https://github.com/SAP/luigi/tree/master/core/examples/luigi-example-svelte)

### Svelte

[Svelte](https://svelte.dev) is a radical new approach to building user interfaces. Whereas traditional frameworks like React and Vue do the bulk of their work in the browser, Svelte shifts that work into a compile step that happens when you build your app. Instead of using techniques like virtual DOM diffing, Svelte writes code that surgically updates the DOM when the state of your app changes.

- [Svelte Society](https://sveltesociety.dev) is an aggregator for Svelte tools, templates, components and recipes.
- [Best of Svelte](https://bestofsvelte.com) is an aggregator that contains the best Svelte projects and frameworks.
- [SvelteKit](https://kit.svelte.dev) is a framework for building web applications of all sizes, with a beautiful development experience and flexible filesystem-based routing. Unlike single-page apps, SvelteKit doesn't compromise on SEO, progressive enhancement or the initial load experience — but unlike traditional server-rendered apps, navigation is instantaneous for that app-like feel.
- [Luigi](https://luigi-project.io) works with [Svelte](https://github.com/SAP/luigi/tree/master/core/examples/luigi-example-svelte).
- [Framework7 Svelte](https://framework7.io/svelte/) is a framework for building full featured iOS, Android & Desktop apps. Framework7 Svelte brings components-syntax, structured data and data bindings to Framework7 with power and simplicity of [Svelte](https://github.com/SAP/luigi/tree/master/core/examples/luigi-example-svelte).
- [Svelte Preprocess Markdown](https://github.com/AlexxNB/svelte-preprocess-markdown) allows you to write Svelte components in Markdown syntax.
- [Sveltin](https://sveltin.io) is a CLI created to boost the developers productivity working on SvelteKit powered static websites.
- [LayerCake](https://layercake.graphics) is a graphics framework for Svelte. It uses the measurements of your target div and your data extents to create scales that stay synced on layout changes. Use these scales to organize multiple, mostly-reusable Svelte components, whether they be SVG, HTML, Canvas or WebGL. Since they all share the same coordinate space, you can build your graphic one layer at a time. It can also be used to easily create responsive graphics server-side that work without JavaScript.

### Svelte UI Frameworks

- [Svelte Material UI](https://sveltematerialui.com)
- [Notus Svelte](https://demos.creative-tim.com/notus-svelte/)
- [Svelte Three](https://svelthree.dev)
- [Svelte Mapbox](https://github.com/beyonk-adventures/svelte-mapbox)
- [Svelte Grid](https://svelte-grid.vercel.app)
 
### Nim

[Jester](https://github.com/dom96/jester) is a [sinatra-like](http://sinatrarb.com) web framework for __Nim__. Jester provides a DSL for quickly creating web applications in Nim.

### Go

[Fiber](https://gofiber.io) is a Go web framework built on top of Fasthttp, the fastest HTTP engine for Go. It's designed to ease things up for fast development with zero memory allocation and performance in mind.

[Gearbox](https://gogearbox.com)

### Rust

[Actix](https://actix.rs)

## Development Environments

- [Open VSCode Server](https://github.com/gitpod-io/openvscode-server) provides a version of VS Code that runs a server on a remote machine and allows access through a modern web browser. It's based on the very same architecture used by Gitpod or GitHub Codespaces at scale.
- [Nimbus](https://www.usenimbus.com) delivers cloud dev environments pre-configured for your project on-demand. This means more coding and less waiting and configuring.
- [Gitpod](https://www.gitpod.io) spins up fresh, automated dev environments
for each task, in the cloud, in seconds.

## Source/Version Control Tools

- [Gitlabber](https://github.com/ezbz/gitlabber) is a CLI utility that can clone all projects in Gitlab root or groups.

## Containers and Kubernetes Tools

### CLI Utilities

- [Kustomize](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/) is a standalone tool to customize Kubernetes objects through a kustomization file.
- [kubectx](https://github.com/ahmetb/kubectx) is a tool to switch between contexts (clusters) on kubectl faster.kubens (also part of same repo) is a tool to switch between Kubernetes namespaces (and configure them for kubectl) easily.
- [krew](https://github.com/kubernetes-sigs/krew) is a tool that makes it easy to use kubectl plugins. Krew helps you discover plugins, install and manage them on your machine. It is similar to tools like apt, dnf or brew.
- [KSOPS](https://github.com/viaduct-ai/kustomize-sops) A Flexible Kustomize Plugin for SOPS Encrypted Resource

### Backups
- [Velero](https://github.com/vmware-tanzu/velero) gives you tools to back up and restore your Kubernetes cluster resources and persistent volumes. You can run Velero with a public cloud platform or on-premises.

## Virtual Desktops / Environments

- [KASM VNC](https://github.com/kasmtech/KasmVNC) has open-sourced the Workspace docker images, which include containerized full desktops and apps and base images intended for developers to create custimized streaming containers. These containers can be used standalone or within the Kasm Workspaces Platform which provides a full Enterprise feature set.
