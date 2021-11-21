# Serverless and Amplify

## Intro to Serverless

### Serverless:

- Is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers.

- A serverless application runs in stateless compute containers that are event-triggered, ephemeral (may last for one invocation), and fully managed by the cloud provider.

- Serverless applications are event-driven cloud-based systems where application development rely solely on a combination of third-party services, client-side logic and cloud-hosted remote procedure calls (Functions as a Service).

### Traditional vs. Serverless Architecture

Serverless Architecture it made it easier to deal with the application infrastructure, as it saved time and effort in debugging and updating servers and avoiding errors, and it contains many features in addition to allowing the programmer to focus on building the project's features and not be concerned with errors that may occur in the traditional way.

### Advantages of using Serverless:

1) Reduces cost.
2) Setting up environments are easy.

### Disadvantages of using serverless:

1) Can not directly access APIs through the usual IP because serverless functions are accessed only as private APIs. So at this point, the Traditional Architecture is better than serverless.

2) It is not good for complex or long-running functions because it has a 300-second timeout limit. So at this point, the Traditional Architecture is better than serverless.


### Functions as a Service FaaS

FaaS is an implementation of Serverless architectures where engineers can deploy an individual function or a piece of business logic.

Principles of FaaS:

- Complete management of servers.

- Invocation based billing.

- Event-driven and instantaneously scalable.

### properties of FaaS:

- With Serverless, everything is stateless.

- Ephemeral.

- Functions can be invoked directly.

- Scalable by default.

- Fully managed by a Cloud vendor.

### Create a GraphQL API

1) Run the command ```amplify init``` on the terminal.

2) Then ```amplify add api``` command.

3) After that select the following options:

- Select GraphQL

- When asked if you have a schema, say No

- Select one of the default samples; you can change this later

- Choose to edit the schema and it will open the new schema.graphql in your editor

4) At the end push it by run ```amplify push```.


