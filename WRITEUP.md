# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I chose APP Service because it is simpler, cost effective (specially with the free and basic plans) and is a scalable solution to deploy this CMS app. It is simple to integrate with Github, requires minimal infraestructure and supports environment variables. This decision made it ideal to develop a lightweight CMS with moderate traffic and development needs. As for why I did not choose VM, although it offers more scalability and control, it comes with higher costs and greater complexity.
However, if the app would have required custom OS configurations, background services, low control of the environment, handle very high traffic or need advanced network configurations, the VM would have been more appropiate because of it´s flexibility.
