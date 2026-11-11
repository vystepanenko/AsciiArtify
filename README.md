# AsciiArtify

AsciiArtify is a startup building an ML-powered service that turns images into ASCII art.

This repository holds the infrastructure for the Proof of Concept: a hands-on comparison of local
Kubernetes tools (minikube, kind, k3d) with a Hello World demo on the recommended one, and a GitOps
PoC with Argo CD on k3d.

- [Concept: local Kubernetes for the PoC](doc/Concept.md)
- [PoC: GitOps with Argo CD on k3d](doc/POC.md) — install Argo CD and access its UI
- [Demo manifest](demo/hello-world.yaml)
- [Argo CD Application for the demo](argocd/hello-world-app.yaml)

![AsciiArtify Hello World on k3d](.data/demo.gif)
