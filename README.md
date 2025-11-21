# 🥾 b00t MCP Server

Forked from [Nasdanika-Demos/mcp-server](https://github.com/Nasdanika-Demos/mcp-server) by [PromptExecution](https://github.com/promptexecution).

Demonstrates filesystem aesthetic navigation for b00t datum ontology integration.

Built on top of Nasdanika [AI](https://docs.nasdanika.org/ai/index.html) and [CLI](https://docs.nasdanika.org/core/cli/index.html) capabilities.

Key features:

* Declarative assembly - developers focus on implementing individual capabiliies which are then assembled into a server
* [Generated documentation](https://elasticdotventures.github.io/mcp-server/)
* STDIO and SSE transport
* SSE transport implemented on top of [Reactor Netty](https://projectreactor.io/docs/netty/release/reference/about-doc.html) with a minimal number of dependencies
* Observability with Open Telementry

To generate a help site:

```
nsd help site --page-template="page-template.yml#/" --root-action-icon=https://docs.nasdanika.org/images/nasdanika-logo.png --root-action-location=https://github.com/promptexecution --root-action-text="🥾 b00t @ PromptExecution" docs
```

## MCPHub Certification

Nasdanika Demo MCP Server is certified by [MCPHub](https://mcphub.com/mcp-servers/Nasdanika-Demos/mcp-server). 
This certification ensures that Nasdanika Demo MCP Server follows best practices for Model Context Protocol implementation.
