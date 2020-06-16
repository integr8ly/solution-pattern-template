# Solution Pattern Template

A template that can be used to bootstrap new Solution Patterns. Content goes under the `/walkthroughs` folder.

## Adding Managed Services
If you would like to include managed services with your Solution Pattern, you can add them to the walkthrough.json file under `Dependencies`.
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
