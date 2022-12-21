# class 29
## _API deployment_
#
#### To deploy an API, you create an API deployment and associate it with a stage. A stage is a logical reference to a lifecycle state of your API (for example, dev , prod , beta , v2 ). API stages are identified by the API ID and stage name. They're included in the URL that you use to invoke the API.

#### As the API evolves, you can continue to deploy it to different stages as different versions of the API. You can also deploy your API updates as a canary release deployment. This enables your API clients to access, on the same stage, the production version through the production release, and the updated version through the canary release.

#### To call a deployed API, the client submits a request against an API's URL. The URL is determined by an API's protocol (HTTP(S) or (WSS)), hostname, stage name, and (for REST APIs) resource path. The hostname and the stage name determine the API's base URL.