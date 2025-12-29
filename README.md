# Secure Event-Driven Azure System (Bicep)

This project demonstrates how to define a secure, event-driven Azure architecture using **Bicep**. The focus is on infrastructure-as-code, secure defaults, and serverless event processing, designed to work within **Azure student subscription limitations**.

## Project Overview
The solution provisions Azure resources using Bicep to support an event-driven workflow where messages are placed on a storage queue and processed asynchronously by serverless components.

## Azure Resources Defined (Bicep)
- Azure Storage Account
- Azure Storage Queue
- Resource Group–scoped deployment
- Secure configuration with no public exposure
- Modular, reusable Bicep structure

## Validation
- Bicep templates successfully compiled using `az bicep build`
- Resource definitions validated through static analysis and linting
- Architecture aligned with Azure best practices for event-driven systems

## Challenges & Resolutions
- **Student subscription restrictions:** Deployment scope adjusted to supported resources
- **Permission limitations:** Focused on template validation rather than full deployment
- **Unused parameters & lint warnings:** Identified and refactored to improve template quality

## Security Considerations
- No hard-coded secrets
- Secure storage configuration
- Ready for managed identity and Key Vault integration
- Least-privilege design approach

## Purpose
This project showcases practical experience with **Azure Bicep**, **IaC principles**, and **secure cloud architecture**, suitable for Azure Cloud Engineer and Infrastructure roles.

## Author
**Olasehinde Victor**
