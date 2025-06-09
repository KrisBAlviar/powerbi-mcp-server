# Power BI MCP Server

A Model Context Protocol (MCP) server for integrating Power BI with GenAI applications.

## Overview

Business analytics and data visualization

## Features

- Comprehensive Power BI API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install powerbi-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/powerbi-mcp-server.git
cd powerbi-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to Power BI API requirements.

## Quick Start

```python
from powerbi_mcp import PowerBiMCPServer

# Initialize the server
server = PowerBiMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
