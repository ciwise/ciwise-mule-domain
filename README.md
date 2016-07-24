# ciwise-mule-domain

This project is a Mule domain project that will hold global resources for other Mule applications. A common resource is the HTTP-Listener that would use a common port e.g. 8081. This resource could then be used in many other applications where a listener is required. All URI paths must be unique but the different applications would all use port 8081 and the running application deployments would behave as one. This makes things much easier for the deployment of enterprise Mule applications.

## Status

As of 07-23-2016, no resources have been specified, however this will change in the future. And, when resources change, this status will be provided here for anyone's reference.
