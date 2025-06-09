# GitLab MCP Server

A Model Context Protocol (MCP) server for integrating GitLab with GenAI applications.

## Overview

DevOps platform with CI/CD integration

## Features

- Comprehensive GitLab API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install gitlab-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/gitlab-mcp-server.git
cd gitlab-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to GitLab API requirements.

## Quick Start

```python
from gitlab_mcp import GitlabMCPServer

# Initialize the server
server = GitlabMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
