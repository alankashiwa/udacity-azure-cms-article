# Azure VM v.s. App Services Deployment

## The Article CMS

### Current Status

- A simple web app
- Not many users expected
- Less concerns about security
- Cost is important for such a personal projects

Based on the above features of the current app, I'll choose to deploy the app to to App Service because of the lower cost and easy deployment of App service. The management of the app is also easy because App Service allows me to set up CI/CD pipeline easily utilizing GitHub or other services.

### Assess app changes that would change your decision.

If the app grows very popular, and the user base increases significantly, then security and scability will become more important. In this case, I will consider shift to VMs so that I will be able to set up a scale set and customize security settings on VMs.
