# Solution Pattern Template

A template that can be used to bootstrap new Solution Patterns. Content goes under the `/walkthroughs` folder.

## Adding Managed Services
Managed services can be provisioned on-demand when a user starts a Solution Pattern. This provides the user with access to either a personal instance of the service, or their own log in for a multi-tenant service (e.g. 3scale). If you would like to include managed services with your Solution Pattern, you can add them to the walkthrough.json file under `Dependencies`. <br>

Example:

```
"managedServices": [
  {
    "name": "amqonline"
  },
  {
    "name": "fuse"
  }
],
```
