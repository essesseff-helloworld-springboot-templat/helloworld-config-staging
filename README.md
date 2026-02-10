# helloworld Config - STAGING

Helm chart for STAGING environment.

## Configuration

- **Environment**: STAGING
- **Auto-Deploy**: Yes (typically by Release Engineer decision via essesseff)
- **Namespace**: `essesseff-helloworld-springboot-templat`

## Updates

This repository in combination with the argocd-env environment-specific deployment config determine when/if/how deployments occur via Argo CD.  This repository is updated by essesseff platform when STAGING deployments are to occur as per Release Engineer manual decision.

Typically, only the values.yaml file should be manually altered in order to cause a deployment to occur with updated configuration, while any/all other changes in the repository are made via essesseff deployment orchestration.
