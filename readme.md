## PillrSDK
A .NET SDK to help solve everyday build and deploy problems all from your local machine.

### Current features are:
-
- Cache every build along with meta and telemetry data
- Cloud deployment capabilities through the Azure Kudu service
- Communication channels such as email, sms and Slack
- An expressive console user interface 
- A growing MSBuild task library
- And many more to come...

### Future features are:
-
- Version management in adherence to the [Semantic Versioning](https://semver.org) specification
- Automated git repo management with the following:
    1. Every project has a git repo unlesss opted out.
    2. Creates a remote Github repo.
    3. Commit messages adhere to the [Conventional Commits](https://conventionalcommits.org/) specification
    4. And much more...
- Full infrastructure deployment using well-known IAC technologies
- Documentation generation from source code comments using open source tools like Docfx
- Integration with web techonologies such as Tailwind and Bitly
- A comprehensive template library
- Web interface as an alternative to console

### Projects
|Name|Description|
|:-|:-|
|[Data.lib](./src/Data.lib/readme.md)|The data access layer.|
|[Data.User.lib](./src/User.Data.lib/readme.md)|The user data library.|
|[Server.lib](./src/Server.lib/readme.md)|The Pillr server library.|
|[Server.Client.lib](./src/Server.Client.lib/readme.md)|The client library for the server.|
|[Tasks.lib](./src/Tasks.lib/readme.md)|The task library for the Sdk.|
|[Utils.lib](./src/Utils.lib/readme.md)|The Pillr utility library.|
