# reruncloud-server
Server resource management for ReRunCloud

## Roles of the server service
- Handle the majority of server management operations
- Communicate with respective services to provision, update and de-provison resources as needed
- Keep track of resource state and ensure that the services are running
- Only store data related to the resource, do not store any customer-related data in server service
- Handle any webhook calls related to server and resources
