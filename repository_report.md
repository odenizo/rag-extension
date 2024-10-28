# Repository Report

## File Tree Structure

```
.
├── agent
│   └── service.go
├── config
│   └── info.go
├── copilot
│   ├── endpoints.go
│   └── messages.go
├── data
│   ├── app_configuration.md
│   ├── payload_verification.md
│   ├── request_format.md
│   └── response_format.md
├── embedding
│   └── datasets.go
├── main.go
├── oauth
│   └── handler.go
├── README.md
├── LICENSE.txt
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── SUPPORT.md
└── go.mod
```

## Directory and File Descriptions

### agent
- [service.go](./agent/service.go): Contains the implementation of the `Service` struct and its methods for handling chat completions.

### config
- [info.go](./config/info.go): Defines the `Info` struct and a function to create a new instance of it using environment variables.

### copilot
- [endpoints.go](./copilot/endpoints.go): Contains functions for making HTTP requests to the Copilot API for chat completions and embeddings.
- [messages.go](./copilot/messages.go): Defines the structures for chat requests, messages, and embeddings.

### data
- [app_configuration.md](./data/app_configuration.md): Provides information on configuring a Copilot app.
- [payload_verification.md](./data/payload_verification.md): Describes payload verification for requests.
- [request_format.md](./data/request_format.md): Details the request format for the agent.
- [response_format.md](./data/response_format.md): Details the response format for the agent.

### embedding
- [datasets.go](./embedding/datasets.go): Provides functions for creating embeddings, generating datasets, and finding the best dataset based on embeddings.

### main.go
- [main.go](./main.go): Contains the main function that sets up the HTTP server and routes for the agent and OAuth service.

### oauth
- [handler.go](./oauth/handler.go): Provides the implementation of the OAuth service for handling authorization and callback endpoints.

### Root Directory Files
- [README.md](./README.md): Provides a description of the project, prerequisites, installation instructions, usage, and how to access the agent in chat.
- [LICENSE.txt](./LICENSE.txt): Contains the MIT License.
- [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md): Contains the Contributor Covenant Code of Conduct.
- [SECURITY.md](./SECURITY.md): Provides security information.
- [SUPPORT.md](./SUPPORT.md): Provides support information.
- [go.mod](./go.mod): Contains the module definition and dependencies for the project.
