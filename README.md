# GCPAssociateCloudEngineer
Notes to pass the GCP associate cloud engineer certification

## Resources
1. [A Cloud Guru - GCP certified associate cloud engineer](https://learn.acloud.guru/course/gcp-certified-associate-cloud-engineer)
2. [GCP - AWS products mapping](https://cloud.google.com/free/docs/aws-azure-gcp-service-comparison)
3. [Every product in the Google Cloud family described in <=4 words](https://github.com/priyankavergadia/google-cloud-4-words)

## Introduction

### 1. Pricing

- Provisioned: "Make sure you can handle X"
- Usage: "Handle whatever I use and charge me for that"
- Network
  - Ingress: free
  - Egress: charged (sometimes free depending on destination service / location of that service)

### 2. Security

- Separation of dutiies / physical security
- Everything encrypted at rest
- Strong key / identity management
- Network encryption
- Distrust the network: BeyondCorp

### 3. Resource Quotas

- Scope
  - regional
  - global

- Changes
  - automatic
  - by request (response in 24 - 48h)

### 4. Organization

- Project = AWS account
- Project own ressources
- Resources can be shared with others projects
- Projects can be grouped et controlled in a hierarchy
