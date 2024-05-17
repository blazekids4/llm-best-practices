# Azure OpenAI Service Model Deprecations and Retirements

<https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/model-retirements>

Azure OpenAI Service models are continually refreshed with newer and more capable models. As part of this process, older models are deprecated and retired. This document provides information about the models that are currently available, deprecated, and retired.

## Terminology

### Retirement

When a model is retired, it's no longer available for use. Azure OpenAI Service deployments of a retired model always return error responses.

### Deprecation

When a model is deprecated, it's no longer available for new customers. It continues to be available for use by customers with existing deployments until the model is retired.

### Preretirement Notification

Azure OpenAI notifies customers of active Azure OpenAI Service deployments for models with upcoming retirements. Notifications are sent as follows:

- At least 60 days before retirement
- At least 30 days before retirement
- At retirement

Retirements are done on a rolling basis, region by region.

## Notification Recipients

Azure OpenAI notifies the following roles for each subscription with a deployment of a model with an upcoming retirement:

- Owner
- Contributor
- Reader
- Monitoring contributor
- Monitoring reader

## How to Get Ready for Model Retirements and Version Upgrades

To prepare for model retirements and version upgrades, we recommend that customers:

- Evaluate their applications with the new models and versions.
- Update their applications to use the new models and versions before the retirement date.
