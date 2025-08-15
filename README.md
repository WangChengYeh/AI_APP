# AI_APP - Enhanced MCP Client PWA

## Overview

AI_APP is a Progressive Web Application (PWA) forked from [AIAW Lite](https://github.com/modelcontextprotocol/awesome-mcp), a lightweight open-source Model Context Protocol (MCP) client with no login requirements. This enhanced version extends the original AIAW Lite capabilities with specialized MCP servers for web-based development workflows.

## Core Features

### Base AIAW Lite Integration
- **Lightweight MCP Client**: Streamlined Model Context Protocol client implementation
- **No Authentication Required**: Zero-friction access without login or registration
- **Progressive Web App**: Installable web application with offline capabilities
- **AI Assistant Interface**: Interactive chat interface for AI-powered assistance
- **Cross-platform Compatibility**: Works on desktop, mobile, and tablet devices
- **Privacy-Focused**: Local-first approach with no user data collection

### Enhanced MCP Server Integrations

#### (A) PWA File System MCP Server
- **File Operations**: Create, read, update, and delete files within the PWA environment
- **Directory Management**: Navigate and manage folder structures
- **File Type Support**: Handle various file formats including text, JSON, and configuration files
- **Persistent Storage**: Utilize browser storage APIs for file persistence
- **Import/Export**: Support file upload and download functionality

#### (B) GitHub Version Control MCP Server
- **Repository Management**: Connect to and manage GitHub repositories
- **Branch Operations**: Create, switch, and merge branches
- **Commit History**: View and manage commit history
- **Pull Request Integration**: Create and manage pull requests
- **Authentication**: Secure GitHub API integration with OAuth
- **Collaboration**: Multi-user repository access and permissions

#### (C) Pyodide (Python on Web) MCP Server
- **Python Runtime**: Full Python interpreter running in the browser via Pyodide
- **Package Management**: Install and manage Python packages
- **Code Execution**: Run Python scripts and interactive sessions
- **Data Science Libraries**: Support for NumPy, Pandas, Matplotlib, and other scientific packages
- **Jupyter Integration**: Notebook-style interface for Python development
- **File System Integration**: Seamless integration with PWA file system

#### (D) Web Shell MCP Server
- **Browser-based Terminal**: Virtual shell environment running in PWA
- **Command Execution**: Execute shell commands within browser sandbox
- **Process Management**: Start, monitor, and terminate processes
- **Environment Variables**: Manage shell environment and PATH
- **Script Execution**: Run shell scripts (.sh, .bat) and command sequences
- **Output Streaming**: Real-time command output and error handling
- **Security Isolation**: Sandboxed execution environment for safety

## Technical Architecture

### Frontend (PWA)
- **Framework**: Modern web technologies (HTML5, CSS3, JavaScript/TypeScript)
- **Service Worker**: Offline functionality and caching
- **Responsive Design**: Adaptive interface for all device sizes
- **Web App Manifest**: PWA installation capabilities

### MCP Protocol Integration
- **Client Implementation**: Full MCP client protocol support
- **Server Communications**: WebSocket and HTTP-based server connections
- **Resource Management**: Efficient handling of MCP resources and tools
- **Security**: Secure communication channels and authentication

### Server Integrations
- **Modular Architecture**: Independent MCP server implementations
- **API Interfaces**: RESTful and WebSocket APIs for server communication
- **Cross-Origin Support**: CORS configuration for web-based access
- **Performance Optimization**: Efficient data transfer and caching

## Installation & Setup

### Prerequisites
- Modern web browser with PWA support
- Internet connection for initial setup
- GitHub account (optional, for version control features only)
- No registration or login required for core functionality

### Deployment Options
1. **Web Hosting**: Deploy to any static web hosting service
2. **Local Development**: Run locally with development server
3. **PWA Installation**: Install as standalone app from browser

## Usage Scenarios

### AI-Powered Code Generation & Execution
**Example: "Write a Python code to simulate the world"**

**Workflow:**
1. **Human Input**: User types command in CLI interface: `"write a Python code to simulate the world"`
2. **AI Code Generation**: AI assistant generates Python code based on the request
3. **File Storage**: Code automatically saved to PWA local file system via MCP File System server
4. **Code Execution**: Python code runs in browser using Pyodide MCP server
5. **Result Display**: Simulation output and visualizations displayed in the interface

**Technical Flow:**
```
CLI Input → AI Processing → PWA File System (save .py file) → Pyodide Execution → Web Shell (optional commands) → Result Output
```

**Benefits:**
- Zero setup time - no Python installation needed
- Immediate feedback and iteration
- Persistent code storage in browser
- Shareable via GitHub integration

### Web Development Workflow
1. Create and manage project files using PWA File System
2. Initialize or connect to GitHub repository
3. Write and test Python scripts using Pyodide
4. Commit and push changes via GitHub integration
5. Collaborate with team members through version control

### Data Science Projects
1. Import datasets through file system
2. Analyze data using Python libraries in Pyodide
3. Create visualizations and reports
4. Version control notebooks and scripts
5. Share results via GitHub

### Prototyping & Experimentation
1. Rapid file creation and editing
2. Instant Python code execution
3. Version control for experimental code
4. Cross-device accessibility

## Development Roadmap

### Phase 1: Core Integration
- [x] AIAW Lite fork setup
- [ ] PWA File System MCP server implementation
- [ ] Basic GitHub integration
- [ ] Pyodide runtime integration
- [ ] Web Shell MCP server implementation

### Phase 2: Enhanced Features
- [ ] Advanced GitHub operations (PR management, issues)
- [ ] Python package management
- [ ] Shell script automation and scheduling
- [ ] File synchronization between servers
- [ ] Performance optimizations

### Phase 3: Advanced Capabilities
- [ ] Real-time collaboration features
- [ ] Advanced Python debugging tools
- [ ] CI/CD pipeline integration
- [ ] Plugin architecture for extensibility

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to this project.

## License

This project is licensed under the same terms as the original AIAW Lite project. See [LICENSE](LICENSE) for details.

## Acknowledgments

- Original AIAW Lite project maintainers and contributors
- Model Context Protocol specification authors
- Pyodide development team
- GitHub API documentation and tools