# DevOpsUdacityProject2

Repository containing the project 2 for the Cloud DevOps nanodegree course in Udacity. This project is based on the resources provided by Udacity in <a href="https://github.com/udacity/nd9991-c2-Infrastructure-as-Code-v1/tree/master/supporting_material">this repository</a>.

Networking configuration for CloudFormation can be found in the file "network.yml" and the configuration for the servers of the project is found in the file "servers.yml"

## Running the project

To run the project, you have to firs deploy the networking infrastructure and then the server infrastructure.

### Networking infrastructure

Inside the root folder you must use the following command:

```bash
./create <stack_name> servers.yml server-parameters.json
```

### Server infrastructure

Inside the root folder you must use the following commands:

```bash
./create <stack_name> network.yml network-parameters.json
```