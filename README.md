<p align="center">
  <img src="graphic/pipewright-logo-k8s-dark.svg" alt="Pipewright" width="380">
</p>

# pipewright

Pipewright is a self-hosted continuous delivery tool for Kubernetes. It runs inside your own cluster and updates your deployments when the conditions in your Git workflows are met.

**Status:** early design, not ready for use yet.

## How it works

1. **Install** Pipewright in your Kubernetes cluster.
2. **Grant access** to deployments in the namespaces you choose.
3. **Set your conditions**, such as CI tests passing and a new image being released and pushed.
4. **Deploy automatically.** When a workflow triggers Pipewright and its conditions are met, Pipewright patches the deployment to the new version.

## License

Licensed under either of the following, at your option:

- [Apache License, Version 2.0](LICENSE-APACHE)
- [MIT License](LICENSE-MIT)
