# Google Cloud Datastore Sample

This sample demonstrates how to invoke view grantable roles for a resource
using Google Cloud IAM APIs in C#.

This sample requires [.NET Core 2.0](https://www.microsoft.com/net/core) or
later.  That means using [Visual Studio 2017](https://www.visualstudio.com/), 
or the command line. 

## Links

- [Cloud IAM Docs](https://cloud.google.com/iam/docs/)

## Build and Run

1.  **Follow the instructions in the [root README](../../../README.md)**.

1.  Enable APIs for your project.
    [Click here](https://console.cloud.google.com/flows/enableapi?apiid=iam.googleapis.com&showconfirmation=true)
    to visit Cloud Platform Console and enable the Google Cloud IAM API.

1.  From the command line:

    ```bash
    dotnet restore
    dotnet run [Full-Resource-Name]
    ```

    Where `[Full-Resource-Name] is the name of the resource to list grantable
    roles for. For example, "//cloudresourcemanager.googleapis.com/projects/".

    The application should print a list of Cloud IAM roles.

## Contributing changes

* See [CONTRIBUTING.md](../../../CONTRIBUTING.md)

## Licensing

* See [LICENSE](../../../LICENSE)