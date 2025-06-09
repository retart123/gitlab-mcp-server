# GitLab MCP Server

<div align="center">

# Gitlab Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/gitlab-mcp-server?style=social)](https://github.com/LokiMCPUniverse/gitlab-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/gitlab-mcp-server?style=social)](https://github.com/LokiMCPUniverse/gitlab-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/gitlab-mcp-server?style=social)](https://github.com/LokiMCPUniverse/gitlab-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/gitlab-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/gitlab-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/gitlab-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/gitlab-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/gitlab-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/gitlab-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/gitlab-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/gitlab-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/gitlab-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/gitlab-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/gitlab-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/gitlab-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/gitlab-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/gitlab-mcp-server/graphs/contributors)

</div>

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
