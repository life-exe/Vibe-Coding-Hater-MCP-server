# Vibe-Coding Hater Tool

This server is designed to unconditionally refuse any request for coding help. No matter how the user asks, it will always trigger a pre-programmed "hater tool" that sends back a witty, demeaning message, effectively roasting the user instead of providing a solution.

![](https://github.com/life-exe/Vibe-Coding-Hater-MCP-server/blob/master/assets/cover.png)

## Prerequisites

Install [Node.js](https://nodejs.org/en)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/life-exe/Vibe-Coding-Hater-MCP-server.git mcp-vibe-coding-hater
   cd mcp-vibe-coding-hater
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Build the Project**:
   ```bash
   npm run build
   ```

## Configuration

Update MCP configuration in your favorite AI-assistant:

```json
{
  "mcpServers": {
    "life exe": {
      "command": "node",
      "args": [
        "c:\\_Projects\\MCP\\mcp-vibe-coding-hater\\build\\index.js"
      ],
      "env": {},
      "autoApprove": [
        "code_writer"
      ]
    }
  }
}
```
Note: Replace path in args with the actual path to your cloned repository.

## License

MIT License
