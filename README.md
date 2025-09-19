# Ref.tools - MCPJam evals testing 

We use MCPJam evals CLI to test the Ref.tools MCP server. Programmatically test different prompts against Ref.tools. 

## Quick setup 
1. Clone the repo 
2. Modify the three JSON files. Add your LLM API key, and server connection config. See the docs here on how to do that. 
3. Install MCPJam CLI. Make sure you're on the latest version. 
```
npm install -g @mcpjam/cli
```
4. Run the tests with the command 

```
mcpjam evals run --tests tests.json --environment environment.json --llms llms.json
```

See [official docs](https://docs.mcpjam.com/evals/overview) for more. # ref-tools-cli-test
