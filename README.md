# ADDO2021

# How to choose the right CI/CD tooling

Facing with many CI/CD toolings on the market, this page documents how to choose the right CI/CD tool. Listed below are some aspects you should take into considertations. 

## **Cost** - Open sourced vs. Proprietary
| Product | Open sourced (Free) | Proprietary | Price model |
| ------- | ------------------- | --------- | ----|
| Argo CD | &#10004; | |
| AWS CodePipeline | | &#10004; | Per pipeline 
| Azure Pipeline | | &#10004; | Per pipeline & pipeline minute
| Bamboo  | | &#10004; | Per agent
| BuildKite | &#10004; | | Per user
| CircleCI | | &#10004; | Per user & pipeline minute 
| CloudBees | | &#10004; | Per user
| DroneCI  | | &#10004; | Per user
| Flux    | &#10004; | | 
| Flagger | &#10004; | | 
| Github Actions | | &#10004; | Per pipeline minute
| GitLab | &#10004; | | Per user
| Go CD | &#10004; | | 
| Google Cloud Build | | &#10004; | Per pipeline minute
| Harness |  | &#10004; | Per user |
| Jenkins | &#10004; | | 
| Jenkins X | &#10004; | &#10004; | 
| Spinnaker | &#10004; | | 
| Team City | | &#10004; | Per User & Per pipeline minute
| Tekton | &#10004; | |
| Travis CI Enterprise | | &#10004; | Per concurrent job & Per pipeline minute| 

## **Function** - CI vs. CD
| Product | CI | CD |
| ------- | ---- | --------- |
| Argo CD | &#10004; | |
| AWS CodePipeline | &#10004; | &#10004;
| Azure Pipeline | &#10004; | &#10004;
| Bamboo  | &#10004; |
| BuildKite | &#10004; | 
| CircleCI | &#10004; | 
| CloudBees | &#10004; | &#10004;
| DroneCI  | &#10004; | 
| Flux    | | &#10004;
| Flagger | | &#10004;
| Github Actions | &#10004; | 
| GitLab | &#10004; | &#10004;
| Go CD | | &#10004;
| Google Cloud Build | &#10004; | &#10004;
| Harness |  | &#10004;
| Jenkins | &#10004; |
| Jenkins X | &#10004; | 
| Spinnaker | | &#10004;
| Team City | &#10004; | 
| Tekton | &#10004; | 
| Travis CI Enterprise | &#10004; | 

## **Management** - Self-hosted vs. SaaS vs. Hybrid
| Product | Self-hosted | SaaS | Hybrid |
| ------- | ------------------- | --------- | -----|
| Argo CD | | &#10004; |
| AWS CodePipeline | | &#10004;
| Azure Pipeline | | &#10004;
| Bamboo  | &#10004; | | 
| BuildKite | | | &#10004;|
| CircleCI | &#10004; | &#10004; | 
| CloudBees |  | &#10004; | 
| DroneCI  | &#10004; |  | 
| Flux    | &#10004; | |
| Flagger | &#10004; | | 
| Github Actions | | &#10004; | 
| GitLab | &#10004; | &#10004; | 
| Go CD | &#10004; | | 
| Google Cloud Build | | &#10004; | | 
| Harness |  | &#10004; | | 
| Jenkins | &#10004; | | | 
| Jenkins X | &#10004; | | | 
| Spinnaker | &#10004; | |
| Team City | |  &#10004; | &#10004; 
| Tekton | &#10004; | | | 
| Travis CI Enterprise | &#10004; | | 

## **Cloud Native**
| Product | K8S Support | Out of the box CD strategies | Hybrid/Multi-Cloud |
| ------- | ------------------- | --------- | --- |
| Argo CD | &#10004; | &#10004; | &#10004; |
| AWS CodePipeline | Limited | Limited (with step functions) | |
| Azure Pipeline | &#10004; | &#10004; | 
| Bamboo  | | | &#10004;
| BuildKite | &#10004; | | &#10004;
| CircleCI | &#10004; | limited with orbs | &#10004;
| CloudBees | &#10004; | &#10004; | &#10004;
| DroneCI  | &#10004; | | &#10004;
| Flux    | &#10004; | &#10004; | &#10004;
| Flagger | &#10004; | &#10004; | &#10004;
| Github Actions | &#10004; | &#10004; | &#10004;
| GitLab | &#10004; | &#10004; | &#10004;
| Go CD | &#10004; | |  &#10004;
| Google Cloud Build | &#10004; | &#10004; | &#10004; | 
| Harness | &#10004; | &#10004; | &#10004; | 
| Jenkins | | | &#10004; | 
| Jenkins X | &#10004; | &#10004; with istio & flagger | &#10004;| 
| Spinnaker | &#10004; | &#10004; | &#10004;
| Team City | &#10004; | | &#10004; 
| Tekton | &#10004; | &#10004; | &#10004; | 
| Travis CI Enterprise |  |  | &#10004;

## **User Experience**
| Product | UI / Dashboard | Notification Setup | Job Concurrency | Plugin Support | Ease of use | Pipeline as code | Metrics & Reporting |
| ------- | ------------------- | --------- | -----| -- | -- | -- | -- |
| Argo CD | &#10004; | &#10004; | N/A | &#10004; | Easy | YAML | &#10004; |
| AWS CodePipeline | &#10004; | &#10004; with AWS chatbot | &#10004; | &#10004; | Medium | Cloud Formation | Not built-in 
| Azure Pipeline | &#10004; | &#10004; | &#10004; | &#10004; | Easy | YAML | &#10004;
| Bamboo  | &#10004; | &#10004; | &#10004; | &#10004; | Medium | Java-based DSL| &#10004;
| BuildKite | &#10004; | &#10004; | &#10004;| &#10004; | Easy | YAML | &#10004;
| CircleCI | &#10004; | &#10004; | &#10004; higher tiers| &#10004; | Easy | YAML | &#10004;| &#10004;
| CloudBees | &#10004; | &#10004; | &#10004; | &#10004; | Easy | YAML | &#10004;
| DroneCI  | &#10004; | &#10004; | &#10004; | &#10004; | Easy | YAML  | Limited
| Flux    | &#10004; |  &#10004; | N/A | &#10004; | Easy | YAML | &#10004;
| Flagger | | &#10004; | | | Easy | YAML | &#10004;
| Github Actions | &#10004; | &#10004; | &#10004; | &#10004; | Easy | YAML | &#10004;
| GitLab | &#10004; | &#10004; | &#10004; | &#10004; | Easy | YAML | &#10004;
| Go CD | &#10004; | &#10004; | &#10004; | &#10004; | Easy | YAML | &#10004;
| Google Cloud Build | &#10004; | &#10004; | &#10004; | |Easy | YAML | 
| Harness | &#10004; | &#10004; | &#10004; | &#10004; | Easy | YAML | &#10004;
| Jenkins | &#10004; | | partial | Heavily relies on plugin (1500+ plugins) | Medium | Jenkins Pipeline DSL | &#10004;
| Jenkins X | &#10004; | &#10004; | &#10004; | &#10004; | Medium | YAML | &#10004; 
| Spinnaker | &#10004; |  &#10004; | &#10004; | &#10004; | Medium | YAML | &#10004; Limited 
| Team City | &#10004; | &#10004; | &#10004; | not very rich plugin ecosystem | Medium | Kotlin-based DSL | 
| Tekton | &#10004; | &#10004; | &#10004; | &#10004; | Medium | YAML | |
| Travis CI Enterprise| &#10004; | &#10004; | &#10004; | Limited plugins | Medium | YAML | &#10004; | 

## **Security & Governance**
| Product | Pipeline Permission K8S cluster RBAC | User Permission RBAC |Secret Management | Audit Trails |
| ------- | ------------------- | --------- | -----| -- | 
| Argo CD | limited, lacking k8s cluster level | &#10004; | &#10004; | &#10004;
| AWS CodePipeline | limited, lacking k8s cluster level |&#10004;| &#10004; | &#10004;
| Azure Pipeline | &#10004; | &#10004; | &#10004; | &#10004;
| Bamboo  |  | &#10004; | &#10004; | &#10004;
| BuildKite | &#10004; | &#10004; | &#10004; | &#10004;|
| CircleCI | &#10004; | &#10004; | &#10004; Vault/ENV var/ | &#10004;
| CloudBees | &#10004; | &#10004; | &#10004; | &#10004;
| DroneCI  | &#10004; | | &#10004;Vault/KMS/3rd | &#10004;
| Flux    | &#10004; |  | &#10004; | 
| Flagger | &#10004; |  | |
| Github Actions | &#10004; |  | &#10004; |  &#10004;
| GitLab | &#10004; | &#10004; | &#10004;HC Vault| &#10004;
| Go CD | &#10004; | &#10004; | &#10004; | &#10004;
| Google Cloud Build | &#10004; | &#10004; |&#10004; | &#10004; | 
| Harness | &#10004; | &#10004; | &#10004;built-in SM | &#10004;| 
| Jenkins | limited | &#10004; | &#10004; | with plugins | 
| Jenkins X | limited | &#10004; | &#10004; | | 
| Spinnaker | &#10004; | &#10004; | limited | 
| Team City | &#10004; | &#10004; |  &#10004;HC Vault | &#10004; 
| Tekton | &#10004; | | limited | | 
| Travis CI Enterprise| | |&#10004; | 
