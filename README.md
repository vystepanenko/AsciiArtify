# AsciiArtify

AsciiArtify is a startup building an ML-powered service that turns images into ASCII art.

This repository holds the infrastructure for the product: a hands-on comparison of local Kubernetes
tools (minikube, kind, k3d) with a Hello World demo on the recommended one, a GitOps PoC with Argo
CD on k3d, and the MVP, where Argo CD deploys the product from its Git repository and syncs every
change automatically.

- [Concept: local Kubernetes for the PoC](doc/Concept.md)
- [PoC: GitOps with Argo CD on k3d](doc/POC.md) — install Argo CD and access its UI
- [MVP: the product deployed through Argo CD](doc/MVP.md) — auto-sync from the
  [`go-demo-app` fork](https://github.com/vystepanenko/go-demo-app), with demo
- [Demo manifest](demo/hello-world.yaml)
- [Argo CD Application for the demo](argocd/hello-world-app.yaml)
- [Argo CD Application for the product](argocd/asciiartify-app.yaml)

![AsciiArtify Hello World on k3d](.data/demo.gif)
