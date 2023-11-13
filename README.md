# README

This repository contains example application deployment on aws using terraform. The repository contains different languages and different deployment strategy. Some of the folder contains CI/CD to deploy he applications. 


## Project's layout
```
.
|-- react-application
|-- ruby-application-eks

```


| Folder | Description |
|--------|-------------|
| [react-application](react-application/) |Simple test application to run on AWS S3, AWS Cloudfront, AWS IAM using terraform |
| [ruby-application-eks](ruby-application-eks) | Contains Argo CD Application manifests, each suffix with its own environment, Helm charts that will be deployed with Argo CD application manifests e.g dev, prod 


### Platform
**Tested with**
- Ubuntu Linux 22.04
- Bash shell, version 5.x
- kubectl, version v1.25.0


