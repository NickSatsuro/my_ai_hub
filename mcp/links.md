## Links to MCP 

### Figma MCP (original)
To work with Figma (import design to LLM context)
Problems: working not on all platforms (Cursor and Claude only)
https://github.com/figma/mcp-server-guide

### Figma Developer MCP 
To work with Figma (import design to LLM context)
Work on custom terminal agents like Opencode
Problems: dont copy your layout

Docs: https://github.com/figma/mcp-server-guide

Use in Opencode
```json
{
    "$schema": "https://opencode.ai/config.json",
    "mcp": {
      "Framelink MCP for Figma": {
        "type": "local",
        "command": ["npx", "-y", "figma-developer-mcp", "--figma-api-key=PASTE_HERE_FIGMA_KEY", "--stdio"]
      }
    }
  }
```
