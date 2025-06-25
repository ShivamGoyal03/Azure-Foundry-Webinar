# What is Azure AI Foundry?

[Official Documentation](https://learn.microsoft.com/en-us/azure/ai-foundry/what-is-azure-ai-foundry?WT.mc_id=%3Fwt.mc_id%3DMVP_452430)

Azure AI Foundry is a unified platform for building, deploying, and managing enterprise-grade AI applications. It combines production-ready infrastructure with user-friendly interfaces, enabling organizations to confidently build and operate AI solutions.

## Why Use Azure AI Foundry?
- **Enterprise-Grade Platform:** Build generative AI applications with security, scalability, and compliance in mind.
- **End-to-End Lifecycle:** Explore, build, test, and deploy using cutting-edge AI tools and ML models, all grounded in responsible AI practices.
- **Collaboration:** Work with your team throughout the full application lifecycle, from experimentation to production.
- **Model Flexibility:** Access a wide variety of models and services, including OpenAI, Mistral, Meta, and more.
- **Seamless Scaling:** Easily transform proof-of-concepts into production-ready applications, with continuous monitoring and refinement.

## How Does It Work?
- **Projects:** The core workspace for development. Projects can be managed in the Azure AI Foundry portal or via SDKs in your preferred environment.
- **Project Types:**
  - **Foundry Project:** Built on an Azure AI Foundry resource. Simple setup, direct access to agents and models, ideal for most users.
  - **Hub-Based Project:** Hosted by an Azure AI Foundry hub. Offers advanced features, team-managed resources, and additional Azure dependencies.
- **Navigation:** The portal provides intuitive navigation, with breadcrumbs and a customizable left pane to organize your workflow.
- **Management Center:** Streamlines governance, resource management, quotas, and access control for teams and admins.

## Key Capabilities
- Build, test, and deploy generative AI applications using leading models
- Collaborate across teams for the full AI application lifecycle
- Scale from proof-of-concept to production with continuous monitoring and responsible AI practices
- Flexible project management and resource governance

## Feature Comparison
| Capability                        | Foundry Project | Hub-Based Project |
|------------------------------------|:--------------:|:----------------:|
| Agents                            |      ✅ (GA)    |  ✅ (Preview)     |
| Azure OpenAI models                |  ✅ (Native)    |  Via connections |
| Project files (upload & experiment)|      ✅         |                  |
| Project-level isolation            |      ✅         |       ✅         |
| Evaluations                        |      ✅         |       ✅         |
| Playground                         |      ✅         |       ✅         |
| Prompt flow                        |                |       ✅         |
| Managed compute                    |                |       ✅         |
| Required Azure dependencies        |        -        | Storage, Key Vault|

## Typical Workflow
1. **Define and Explore:** Set project goals, test models and services for your use case.
2. **Build and Customize:** Develop solutions, fine-tune models, and integrate with your data.
3. **Observe and Improve:** Monitor, debug, and refine your application for production.

## Access and Pricing
- The platform is free to explore; costs are incurred at the deployment level and for underlying Azure services.
- Available in most Azure regions.
- You can browse the portal without signing in, but an Azure account is required for full functionality.

## Resources
- [What is Azure AI Foundry? (Official Documentation)](https://learn.microsoft.com/en-us/azure/ai-foundry/what-is-azure-ai-foundry?WT.mc_id=%3Fwt.mc_id%3DMVP_452430)
- [Quickstart: Get Started with Azure AI Foundry (Code)](https://learn.microsoft.com/azure/ai-foundry/quickstarts/get-started-code?tabs=azure-ai-foundry&pivots=fdp-project&WT.mc_id=%3Fwt.mc_id%3DMVP_452430)
- [How To: Get Started with AI Templates](https://learn.microsoft.com/azure/ai-foundry/how-to/develop/ai-template-get-started?WT.mc_id=%3Fwt.mc_id%3DMVP_452430)

For more, continue to the hands-on guide in [`day-2/README.md`](../day-2/README.md) where you'll learn how to create and test your first AI agent using Azure AI Foundry.