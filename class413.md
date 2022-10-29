# class 13
## _Serverless Functions_
#
#### Serverless computing means that developers van to run their applications without connecting to a local server, instead; they will be connecting with a **cloud** provider of servers.  Serverless does not mean servers are no longer needed, just that they are not user-specified or controlled.

#
#### The use of serverless functions offers several significant benefits: It frees developers to focus on application development and better-quality application code, as infrastructure concerns, such as redundant code deployments and autoscaling, are handled by the serverless provider. 
#

#### To use serverless functions, all a developer has to do is write the function code and deploy it to a managed environment. A typical serverless function process would look like this:


* ***Writing a function***: The developer writes a function that fulfills a specific purpose in the application code, such as a form mailer.

* ***Defining an event***: The developer defines an event that will trigger the cloud-native service provider to execute the function. An HTTP request is a common example.

* ***Triggering an event***: A user triggers the event with the click of a button or some similar action.

* ***Deploying and executing a function***: The cloud service provider starts a new instance of the function if one isn’t already running.

* ***Passing the result to the client***: The result of the executed function within the application is displayed to the user.