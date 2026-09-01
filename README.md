# Awesome-Platform-Engineering-Portal

Edit
Top Platform Engineering Portal Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Internal Developer Portals, Service Catalogs, Developer Self-Service, Golden Paths, Platform Engineering & Software Delivery
Last updated: September 2026

This repository tracks notable SaaS/hosted platforms and open-source projects for Platform Engineering Portals and Internal Developer Platforms (IDPs). These tools provide developers with centralized service catalogs, ownership information, documentation, templates, scorecards, infrastructure self-service, deployment workflows and standardized "golden paths" for building and operating software.

Examples include Humanitec, Port, Cortex, OpsLevel, Roadie, Harness IDP, Mia-Platform, Qovery, Akuity, Kraken, Backstage, Atlassian Compass, Spotify Portal, StackGen, Facets.cloud, Massdriver, Northflank and Appvia (the category leaders).

Open-source emphasis: This section is heavily expanded with major open-source internal developer portals, developer catalogs, platform orchestration frameworks, Kubernetes platforms, GitOps systems, infrastructure provisioning tools, service-template frameworks and self-service building blocks. The open-source ecosystem is particularly important in platform engineering because many production IDPs are assembled from multiple composable projects rather than purchased as a single monolithic product. Backstage remains the best-known open-source portal framework, while projects such as Crossplane, Kratix, KubeVela, OpenChoreo and Score provide complementary platform-building capabilities.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **Humanitec** | Platform engineering platform centered on internal developer platforms, workload specifications, and infrastructure orchestration for providing developers with standardized self-service environments. | **Teams Plan:** $1,979/month (includes 5 users, 1 project with up to 5 environments, email support) | **14-day free trial** & interactive 10-minute sandbox environment (no credit card required) |
| **Humanitec Portal** | Humanitec's developer portal offering complements its Platform Orchestrator with catalog, platform, and self-service capabilities for internal developer platforms. | **Teams Plan:** $1,979/month (bundled with Platform Orchestrator; Pro tier at $4,950/month) | **14-day free trial** with access to portal components and sandbox environment |
| **Port** | Commercial no-code internal developer portal for building software catalogs, scorecards, dashboards, and self-service actions around an organization's engineering ecosystem. | **Basic Plan:** $30/seat/month billed annually (Standard tier at $40/seat/month) | **Free forever** for up to 15 seats and 10,000 catalog entities (full platform features, no credit card required) |
| **Cortex** | Internal developer portal focused on service catalogs, ownership, engineering standards, scorecards, and service maturity. | **Standard Tier:** Starting at ~$30–$50/developer/month (~$30,000/year minimum contract via AWS Marketplace / direct) | **14 to 30 days free trial** / proof-of-concept environment upon demo request |
| **OpsLevel** | Developer portal and service catalog platform focused on ownership, service maturity, engineering standards, and automated catalog maintenance. | **Teams Tier:** Starting at ~$350–$600/developer/year (~$29–$50/dev/month; typical min. contract ~$15,000/year for 25–50 devs) | **14 to 30 days free trial** / guided proof-of-concept with interactive demo sandbox upon request |
| **Roadie** | Managed Backstage platform providing a hosted software catalog, templates, TechDocs, scorecards, and integrations without requiring teams to operate their own Backstage infrastructure. | **Teams Plan:** $24/developer/month (billed for active contributing developers; viewers/read-only users are free) | **14-day free trial**; **Roadie Local** is free forever for teams with up to 15 users |
| **Harness IDP** | Commercial internal developer portal integrated with the broader Harness software delivery platform for self-service workflows, CI/CD, and platform engineering. | **Developer 360:** Starting at ~$25–$40/developer/month per IDP user (or unit-based Harness Flex Subscription Units) | **14-day free trial** with access to core platform modules upon signup |
| **Mia-Platform** | Developer platform focused on creating and operating cloud-native applications through templates, reusable components, governance, and self-service workflows. | **Standard Plan:** Starting at ~$5,000/month (~$60,000/year base platform license for enterprise deployments) | **14 to 30 days free trial** / guided proof-of-concept upon scheduling a consultation |
| **Qovery** | Developer platform combining application deployment, environment management, infrastructure automation, and developer self-service. | **Team Plan:** Usage-based compute billing starting with base resources + $0.016/deployment min overage (historically $49/user/month) | **14-day free trial** including 10 users, 100 environments, and 5,000 deployment minutes (no credit card required) |
| **Akuity** | GitOps-focused platform built around Argo technologies for managing Kubernetes applications, environments, and progressive delivery workflows. | **Pro Plan:** $495/month (includes 1 Argo CD control plane, 1 Kargo control plane, 50 apps, 50 stages, 25M AI tokens) | **14-day free trial** of Pro tier features; **6 months free** for qualified early-stage startups |
| **Kraken** | Platform engineering and software delivery ecosystem supporting infrastructure automation and developer productivity capabilities. | **Cloud Tier:** Starting at $20/user/month for managed cloud instances | **Free forever** for self-hosted Community Edition; **14-day free trial** for cloud-hosted environments |
| **Atlassian Compass** | Developer experience platform and software component catalog designed to provide service ownership, engineering standards, and visibility into software components. | **Standard Plan:** $8/user/month (Premium tier at $25/user/month) | **Free forever** for up to 3 full users (unlimited basic users) and up to 10,000 components |
| **Spotify Portal** | Managed and commercialized Backstage-oriented developer portal capabilities designed around the software catalog and developer experience model pioneered by Backstage. | **Enterprise Subscription:** Starting at ~$20–$35/developer/month (annual agreement via AWS Marketplace) | **30-day evaluation trial** / private offer via AWS Marketplace and sales consultation |
| **StackGen** | Platform engineering platform focused on creating developer environments and self-service workflows from infrastructure and application abstractions. | **Starter Edition:** $1,200/year (~$100/month for up to 5 developers via AWS Marketplace) | **Free forever** Developer Edition for 1 user per organization |
| **Facets.cloud** | Internal developer platform focused on infrastructure provisioning, platform abstractions, and developer self-service for cloud-native teams. | **SaaS Plan:** $799/month (includes 20 Resource Instances; additional RIs at $10/RI/month) | **14-day free trial** with starter quota included (no credit card required) |
| **Massdriver** | Platform engineering product that packages infrastructure and operational expertise into reusable components for developer self-service. | **Business Plan:** $30/seat/month (or base platform tier from $500/month) | **14-day free trial** of Business plan (no credit card required) + 1-month free self-hosted evaluation license |
| **Northflank** | Cloud-native application platform combining service visibility with application builds, deployments, databases, networking, and infrastructure operations. | **Pay-As-You-Go Compute:** Starting from $2.70/month ($0.01667/vCPU-hr, $0.00833/GB-hr RAM; $0 per-seat fee) | **Free forever** Sandbox tier with 2 services, 1 database, 2 cron jobs, and always-on compute |
| **Appvia** | Platform engineering company offering developer self-service and cloud infrastructure management capabilities, including its Wayfinder platform. | **Wayfinder Standard:** Starting at £120/cluster/year (~$150/cluster/year) or ~$25/developer/month | **Free forever** "Free to Start" tier for the first cluster with self-service developer workspaces and no end date |
| **Cycloid** | Platform and developer portal combining infrastructure automation, GitOps workflows, self-service, and governance. | **Starter Plan:** €29/user/month (~$29/user/month, billed annually) | **14-day free trial** / guided demo evaluation available upon request |
| **Configure 8** | Commercial internal developer portal focused on service catalogs, engineering standards, scorecards, and automation. | **Teams Plan:** $24/developer/month (billed per active SCM contributor; non-coding users are free) | **Free forever** for small teams & non-profits; **14-day free trial** for standard organizations |
| **Rely.io** | Managed developer portal platform focused on service catalogs, scorecards, ownership, and developer experience. | **Standard Plan:** Starting at $25/user/month | **14-day free trial** with instant sandbox onboarding and interactive demo environments |
| **Flightdeck** | Managed developer portal platform based on the Backstage ecosystem and designed to reduce self-hosting overhead. | **Managed Plan:** Starting at $20/developer/month (approx. $500/month minimum base) | **14-day free trial** / evaluation sandbox access on signup |
| **Northflank Developer Platform** | Application delivery platform providing a developer-facing abstraction over infrastructure, CI/CD, and cloud operations. | **Micro Tier:** Starting at $2.70/month per micro instance ($0.01667/vCPU-hr; $0 per-seat charges) | **Free forever** Sandbox plan with 2 services, 1 managed database, and 2 cron jobs |
| **Encore** | Code-first developer platform that combines application architecture, infrastructure provisioning, and operational capabilities for backend development. | **Pro Plan:** $39/member/month (plus $99/cloud environment for dedicated AWS/GCP automation) | **Free forever** with unlimited team members, 100,000 requests/day, 1 GB DB storage, 1 GB object storage, and 100k PubSub msgs/day |
| **Platform.sh** | Cloud application platform providing standardized development, deployment, and environment workflows. | **Base Tier:** Starting from $10/user/month + $9/project/month ($19/month first-project credit offset provided) | **15-day free trial** including 1 org, 1 project, 2 running environments, up to 4.5 CPUs, 12 GB RAM, and 20 GB storage (no credit card required) |
| **Red Hat Developer Hub** | Enterprise developer portal product based on the Backstage ecosystem and designed for building standardized internal developer platforms. | **Enterprise Subscription:** Starting at ~$1,500/year (or via Red Hat OpenShift Platform Plus licensing) | **60-day product trial** (self-supported evaluation via Customer Portal) or **30-day Developer Sandbox** access |

Open-Source GitHub Projects

Backstage
The leading open-source framework for building internal developer portals. Backstage provides a centralized software catalog, software templates, TechDocs and a large plugin ecosystem for integrating engineering infrastructure and services.

Backstage Software Catalog
Core open-source catalog capabilities for managing software components, APIs, resources, systems, domains and ownership relationships.

Backstage Software Templates
Open-source scaffolding system for creating standardized projects and implementing reusable golden paths for developers.

Backstage TechDocs
Documentation-as-code system integrated into Backstage for discovering and maintaining engineering documentation.

Janus IDP
Open-source developer portal ecosystem and plugin collection focused on enterprise-ready Backstage distributions and integrations.

Red Hat Developer Hub Plugins
Open-source developer portal components and ecosystem tooling related to Red Hat's Backstage-based developer platform.

OpenChoreo
Open-source developer platform focused on creating a complete modular platform engineering environment with application development, deployment and operational capabilities.

Crossplane
Open-source Kubernetes-native infrastructure control plane that enables platform teams to expose cloud infrastructure through reusable APIs and abstractions.

Crossplane Contrib Providers
Large ecosystem of open-source providers enabling Crossplane to provision and manage cloud infrastructure, databases and external services.

Kratix
Open-source framework for building internal developer platforms through reusable platform capabilities and declarative platform promises.

KubeVela
Open-source application delivery platform that provides higher-level abstractions over Kubernetes for developers and platform teams.

Score
Open-source workload specification designed to provide developers with a portable abstraction for describing application workloads independent of underlying infrastructure.

Score Humanitec Implementation
Open-source implementation and tooling for deploying Score-defined workloads into Humanitec-oriented platform environments.

Radius
Open-source application platform for defining applications, environments, resources and cloud infrastructure using developer-friendly abstractions.

DevLake
Open-source engineering data platform that collects and analyzes software delivery metrics, useful for enriching developer portals with engineering intelligence.

OpenTofu
Open-source infrastructure-as-code tool for provisioning infrastructure that can serve as the automation layer beneath developer self-service portals.

Terraform Community Ecosystem
Widely used infrastructure-as-code ecosystem that remains a major building block for developer self-service, templates and golden paths.

Pulumi
Open-source infrastructure-as-code platform allowing developers to define cloud infrastructure using general-purpose programming languages.

Kubernetes
The foundational open-source container orchestration platform used by many internal developer platforms as the execution layer behind developer portals.

Argo CD
Open-source GitOps continuous delivery platform for Kubernetes that can power deployment actions exposed through developer portals.

Argo Workflows
Open-source workflow engine for Kubernetes suitable for automation pipelines and developer self-service workflows.

Argo Rollouts
Open-source progressive delivery controller supporting canary and blue-green deployments.

Flux CD
Open-source GitOps toolkit for continuously reconciling Kubernetes clusters from Git repositories.

Tekton
Open-source Kubernetes-native CI/CD framework that can act as the execution engine behind portal-triggered software delivery workflows.

Jenkins
Mature open-source automation server that can be integrated with developer portals for builds, deployments and self-service actions.

Spinnaker
Open-source continuous delivery platform supporting multi-cloud deployment pipelines and operational workflows.

Keptn
Open-source cloud-native lifecycle management project focused on automated delivery, observability and operational quality.

OpenGitOps
Open-source standards and principles for implementing GitOps workflows, useful as a foundation for portal-driven infrastructure and deployment automation.

Portainer Community Edition
Open-source container and Kubernetes management platform that can provide a self-service operational interface for development teams.

Rancher
Open-source Kubernetes management platform for managing clusters and workloads across infrastructure environments.

Headlamp
Open-source extensible Kubernetes web UI that can serve as a building block for platform and developer portals.

Lens Desktop Open Source Components
Kubernetes management tooling and ecosystem components useful for developer and platform engineering workflows.

Loft
Open-source ecosystem for virtual Kubernetes clusters and multi-tenancy, supporting isolated developer environments and self-service clusters.

vCluster
Open-source virtual Kubernetes cluster technology for creating isolated development and team environments on shared infrastructure.

DevSpace
Open-source developer tool for cloud-native development and Kubernetes workflows.

Tilt
Open-source local development environment for Kubernetes and microservices that can support standardized developer workflows.

Skaffold
Open-source tool for continuous development and deployment workflows on Kubernetes.

Garden
Open-source development automation platform for building, testing and deploying cloud-native applications.

Dagger
Open-source programmable CI/CD engine enabling reusable software delivery pipelines.

Earthly
Open-source build automation framework for reproducible builds and standardized CI workflows.

JHipster
Open-source application generator that can be integrated into developer portals as a service-template or golden-path engine.

Cookiecutter
Open-source project templating system for creating standardized applications, libraries and infrastructure projects.

Copier
Open-source project templating and scaffolding tool that supports reusable application templates and lifecycle updates.

Yeoman
Open-source scaffolding ecosystem for generating standardized projects and developer workflows.

Docusaurus
Open-source documentation framework frequently used alongside developer portals for engineering documentation and docs-as-code.

MkDocs
Open-source static documentation generator suitable for developer documentation platforms.

OpenAPI Generator
Open-source tool for generating SDKs, clients and server stubs from API specifications, useful in portal-driven API development workflows.

Swagger UI
Open-source API documentation interface that can be integrated into developer portals.

OpenMetadata
Open-source metadata and catalog platform that can complement developer portals by cataloging data assets and ownership.

DataHub
Open-source metadata platform that can extend the catalog concept to data products, pipelines and data infrastructure.

OpenTelemetry
Open-source observability standard and ecosystem that can provide telemetry data displayed through developer portals.

Prometheus
Open-source monitoring system frequently integrated into platform portals to provide service health and operational metrics.

Grafana
Open-source observability and visualization platform that can surface service dashboards inside developer portals.

Loki
Open-source log aggregation system for integrating service logs into internal developer platforms.

Jaeger
Open-source distributed tracing platform useful for service observability within developer portals.

Open Policy Agent
Open-source policy engine for implementing governance and policy-as-code across developer self-service workflows.

Kyverno
Open-source Kubernetes-native policy engine for enforcing platform standards and guardrails.

Backstage Plugin Ecosystem
Extensive open-source collection of plugins for integrating catalogs with CI/CD, Kubernetes, cloud providers, documentation, observability, security and developer tooling.

Additional Strong Open-Source Options

Developer portals and catalogs: Backstage, Janus IDP, Red Hat Developer Hub ecosystem, Apache-style metadata catalogs and custom portal implementations.

Platform orchestration: Crossplane, Kratix, KubeVela, Radius, OpenChoreo and Score-based platform architectures.

Infrastructure provisioning: OpenTofu, Terraform ecosystems, Pulumi, Crossplane providers and Kubernetes APIs.

GitOps and delivery: Argo CD, Flux, Argo Workflows, Argo Rollouts, Tekton, Jenkins and Spinnaker.

Developer environments: vCluster, DevSpace, Tilt, Skaffold and Garden.

Golden paths and scaffolding: Backstage Software Templates, JHipster, Cookiecutter, Copier and Yeoman.

Documentation platforms: Backstage TechDocs, Docusaurus, MkDocs and OpenAPI tooling.

Platform observability: OpenTelemetry, Prometheus, Grafana, Loki and Jaeger.

Policy and governance: Open Policy Agent, Kyverno and policy-as-code frameworks.

Kubernetes operations: Rancher, Portainer Community Edition and Headlamp.

Engineering intelligence: Apache DevLake and integrations with delivery, issue-management and observability systems.

Self-service architectures: Kubernetes + GitOps + Infrastructure-as-Code + Backstage remains one of the most common composable open-source patterns.

Frameworks for building custom systems: A strong fully open-source Platform Engineering Portal can combine Backstage as the developer-facing portal, Crossplane or OpenTofu/Pulumi for infrastructure provisioning, Kubernetes as the runtime platform, Argo CD or Flux for GitOps delivery, Score or KubeVela for workload abstractions, and Prometheus + Grafana + OpenTelemetry for operational visibility.

A practical architecture can therefore be organized as:

Developer Portal → Software Catalog → Golden Paths/Templates → Self-Service Actions → Platform APIs → Infrastructure Provisioning → GitOps/CD → Runtime → Observability

For teams requiring deeper platform abstractions, Backstage + Kratix + Crossplane + Argo CD + Kubernetes provides a powerful open-source foundation. Teams wanting a more application-centric approach can evaluate KubeVela, Radius, OpenChoreo and Score as complementary abstraction layers.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Platform engineering portals vary significantly in scope. Some are primarily software catalogs and developer portals, while others also provision infrastructure, manage Kubernetes environments or orchestrate application delivery.

Open-source projects may require substantial engineering effort for installation, integration, plugin development, upgrades, security hardening and long-term maintenance.

Self-service platforms should implement appropriate access control, policy enforcement, secrets management, infrastructure governance and audit logging.

A developer portal does not automatically constitute a complete Internal Developer Platform; production IDPs usually combine portal, orchestration, infrastructure, delivery, observability and governance layers.

Made for platform engineers, DevOps teams, cloud architects, developer-experience leaders, infrastructure engineers and organizations building internal developer platforms.

Let's make platform engineering more open, composable, self-service and developer-friendly.
