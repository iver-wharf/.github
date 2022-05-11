<h1 align="center">Wharf</h1>
<h3 align="center">Self-hosted CI/CD solution</h3>

## Documentation

- [**iver-wharf.github.io**](https://github.com/iver-wharf/iver-wharf.github.io): Main documentation of Wharf. [Go to site](https://wharf.iver.com).
- [**rfcs**](https://github.com/iver-wharf/rfcs): Approved and pending design decisions using Request For Comments (RFC) process. [Go to site](https://wharf.iver.com/rfcs).
- [**wharf-notes**](https://github.com/iver-wharf/wharf-notes): Architectural notes. Scratchpad of ideas. [Go to site](https://wharf.iver.com/wharf-notes).

## Running Wharf

- [**wharf-demo**](https://github.com/iver-wharf/wharf-demo): Setting up an AKS hosted Wharf instance, intented for demos.
- [**wharf-docker-compose**](https://github.com/iver-wharf/wharf-docker-compose): Run Wharf via Docker Compose.
- [**wharf-helm**](https://github.com/iver-wharf/wharf-helm): Install Wharf in Kubernetes.

## Components

- [**wharf-api**](https://github.com/iver-wharf/wharf-api): REST & gRPC backend API, providing simple CRUD functionality.
- [**wharf-cmd**](https://github.com/iver-wharf/wharf-cmd): Execution engine accessed via REST/gRPC APIs or CLI.
- [**wharf-web**](https://github.com/iver-wharf/wharf-web): Web frontend for wharf-api written in Angular.

## Libraries

- [**wharf-api-client-go**](https://github.com/iver-wharf/wharf-api-client-go): REST & gRPC client to talk to wharf-api.
- [**wharf-collect-licenses-js**](https://github.com/iver-wharf/wharf-collect-licenses-js): Collect license texts from `node_modules`
- [**wharf-core**](https://github.com/iver-wharf/wharf-core): Core and utility Go libraries used by Wharf.
- [**wharf-messagebus-go**](https://github.com/iver-wharf/wharf-messagebus-go): AMQP abstraction.

## Addons

- [**wharf-jenkinsfiles**](https://github.com/iver-wharf/wharf-jenkinsfiles): Jenkinsfiles and seed jobs for using Jenkins as execution engine. Deprecated in favor of [wharf-cmd](https://github.com/iver-wharf/wharf-cmd)
- [**wharf-provider-azuredevops**](https://github.com/iver-wharf/wharf-provider-azuredevops): Interface for importing Wharf projects from Azure DevOps.
- [**wharf-provider-github**](https://github.com/iver-wharf/wharf-provider-github): Interface for importing Wharf projects from GitHub.
- [**wharf-provider-gitlab**](https://github.com/iver-wharf/wharf-provider-gitlab): Interface for importing Wharf projects from GitLab.