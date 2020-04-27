![MANUela Logo](./docs/images/logo.png)

# MANUela - MANUfacturing Edge Lightweight Accelerator

**Purpose**: Show an exemplary horizontal solution blueprint for IoT Edge use cases applicable to different verticals.

This project is build and maintained by a group of solution architects at Red Hat. It originated from SAs responsible for diverse manufacturing customers in Germany and has grown to include other verticals as well.

Your feedback is welcome - enter your feedback, issues, and enhancement requests [here](https://github.com/sa-mw-dach/manuela/issues).

**Red Hatters**: Please track any demo in the [spreadsheet](https://docs.google.com/spreadsheets/d/17846bqUPEbXUmJ2i6KUYJ_k0yiJWmVW4flhKb83WDA4/edit#gid=0) so we can understand how it is used.


## Documentation

### Getting Started
- You have little time to waste? Check out the [QUICKSTART](./docs/QUICKSTART.md).
- You want to understand the concepts behind MANUela? Check out the [Concepts](./docs/concepts.md).
- You want to set up a new demo environment from scratch? Check out the [BOOTSTRAP](./docs/BOOTSTRAP.md).

### Use Cases 
You want to run the demo on an existing environment? Check out the individual horizontal modules below.
- Gitops app deployment [preparation](./docs/module-app-deployment.md#Demo-preparation) - [demo execution](./docs/module-app-deployment.md#Demo-execution)
- Gitops configuration management [preparation](./docs/module-configuration-management.md#Demo-preparation) - [demo execution](./docs/module-configuration-management.md#Demo-execution)
- Code change [preparation](./docs/module-code-change.md#Demo-preparation) - [demo execution](./module-code-change.md#Demo-execution)
-  CI/CD pipeline & gitops staging [preparation](./docs/module-ci-cd-pipeline.md#Demo-preparation) - [demo execution](./docs/module-ci-cd-pipeline.md#Demo-execution)
- Machine learning [preparation](./docs/module-machine-learning.md#Demo-preparation) - [demo execution](./docs/module-machine-learning.md#Demo-execution)
- Infrastructure operator development [preparation](./docs/module-infrastructure-operator-development.md#Demo-preparation) - [demo execution](./docs/module-infrastructure-operator-development.md#Demo-execution)
- Enterprise Container [preparation](./docs/module-enterprise-container.md#Demo-preparation) - [demo execution](./docs/module-enterprise-container.md#Demo-execution)
- Multi Cluster Management [preparation](./docs/module-multicluster.md#Demo-preparation) - [demo execution](./docs/module-multicluster.md#Demo-execution)

### References
- TODO: GitOps for large scale manufacturing
- TODO: Agile software development for industry production systems


## Intended audience
Everyone who needs to showcase IoT Edge use cases for the various verticals. New modules or enhancements to existing ones are always welcome.
The idea is to have a lot of modules / topics covered by an integrated, holistic story line. You could do a single demo with all topics, but that will probably last a day. You always can pick just the topics that are relevant to your current situation and perform only these parts of the demo.
While you can setup your own demo environment, you can always ask the MANUela team if you could use their existing environment (aka stormshift).


## Topics covered
- How to handle multiple clusters - from central datacenter via remote edge (e.g. factory sites) to far edge (single devices)
- GitOps - How to use this approach to keep in control of configuration and operations
- How to ***distribute*** workload across clusters?
- How to ***build and deploy*** workload across clusters using modern CI/CD
- How to ***move*** workload across clusters?
- IoT Edge
- See and experience Hybrid Cloud in action
- OpenShift Multi-Cluster Management
- IoT Data Ingest 
- AI/ML- How to train models in the public cloud with data from the private cloud, and bring the executable model back  to on prem.


## (Red Hat) Technology involved
- OpenShift V4
- OpenShift Container Storage V4
- AMQ (MQTT Message broker)
- AMQ Streams (Kafka Event Broker, coming soon)
- Tekton Pipelines
- ArgoCD for gitops
- Code Ready Workspaces (Development Environment)
- Red Hat Virtualization (Optional, to provide multiple clusters)
- Open Data Hub for machine learning use cases
- cloud.redhat.com as preview to multi cluster managment capabilities
- Runtimes, esp. Quarkus, NodeJS....

CAVEAT: Some of the technologies involved are bleeding edge, and so implementation details might change if a better tool is found for a particular purpose.  


## Why the name "MANUela"?
There is some strange German humor [behind the scenes](https://www.youtube.com/watch?v=ZiY5FBI_5D8), which neither the author of this text nor other reviewers are able to explain.


## Other repos
There are also further MANUela-linked projects for GitOps, ArgoCD and some demo apps to be deployed within the demo.
You can check them out in this Github directory https://github.com/sa-mw-dach .
