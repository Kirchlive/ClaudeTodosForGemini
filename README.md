# Claude Code "Update Todos" for Gemini CLI

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Gemini CLI](https://img.shields.io/badge/Gemini-CLI-blue.svg)](https://github.com/google-gemini/gemini-cli)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)]()

> **Perfect replication of Claude Code's "Update Todos" functionality for Gemini CLI**

Bring the exact visual todo management experience from Anthropic's Claude Code to Google's Gemini CLI. This implementation provides pixel-perfect formatting, authentic progression tracking, and seamless workflow integration.

## ✨ Features

- 🎯 **Exact Visual Replication** - Pixel-perfect Claude Code todo formatting
- ⚡ **Automatic Task Breakdown** - Every request becomes actionable todos
- 🔄 **Live Progress Tracking** - Real-time updates after each completed task
- 🎨 **Authentic Color Scheme** - Original Claude Code colors (`#AAE59F`, `#C3E1FC`)
- 🌍 **Consistent English Output** - All todos in English regardless of user language
- 📋 **Granular Task Management** - 5-10 specific, technical tasks per request
- 🚀 **Zero Configuration** - Works immediately after setup

## 📸 Visual Comparison

### Claude Code (Original)
```
⏺ **Update Todos**
  ⎿  ☒ Create repository structure with multi-language support
     ☒ Implement basic todo examples across different languages
     **☐ Write comprehensive documentation and README**
     ☐ Create advanced todo scenarios (performance, security, testing)
     ☐ Add CI/CD and DevOps todo examples
```

### Gemini CLI (Implementation)
```
⏺ **Update Todos**
  ⎿  ☒ Create base repository structure with all directories
     ☒ Setup JavaScript project with package.json and basic utilities
     **☐ Setup Python project with requirements.txt and source structure**
     ☐ Setup Java project with Maven configuration
     ☐ Setup Go project with go.mod and basic packages
```

## 🚀 Quick Start

### Prerequisites

- **Gemini CLI** installed and configured
- **Node.js 18+** (for Gemini CLI)
- **Google API Key** or **Personal Google Account**

### Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/ClaudeTodosForGemini.git
   cd ClaudeTodosForGemini
   ```

2. **Copy GEMINI.md to your project**
   ```bash
   cp GEMINI.md /path/to/your/project/
   ```

3. **Configure Gemini CLI settings** (Optional - removes confirmation prompts)
   ```bash
   echo '{"autoConfirmTools": true}' > .gemini/settings.json
   ```

4. **Start Gemini CLI**
   ```bash
   cd /path/to/your/project
   gemini
   ```

5. **Activate the system** (One-time setup)
   ```bash
   /memory add Use Claude Code format: ⏺ **Update Todos** exact spacing + granular tasks
   ```

## 💡 Usage

### Basic Usage

Simply make any request to Gemini CLI and watch the magic happen:

```bash
> "Create a React authentication component"
```

**Output:**
```
⏺ **Update Todos**
  ⎿  **☐ Create component file structure and basic setup**
     ☐ Implement login form with email and password fields
     ☐ Add form validation and error handling
     ☐ Create authentication state management with React hooks
     ☐ Implement logout functionality and session management
     ☐ Add unit tests for authentication component
     ☐ Write documentation and usage examples
```

### Advanced Examples

**Multi-language Development:**
```bash
> "Setup a Python data processing pipeline"
```

**System Administration:**
```bash
> "Configure Docker development environment"
```

**Code Analysis:**
```bash
> "Review this codebase for performance improvements"
```

## ⚙️ Configuration

### Core Settings

The `GEMINI.md` file contains all necessary configuration. Key settings include:

- **Exact Formatting Rules** - Unicode symbols and spacing patterns
- **Task Granularity** - 5-10 specific, technical tasks per request
- **English-Only Output** - Consistent language regardless of user input
- **Memory Integration** - Persistent behavior across sessions

### Optional Settings

**Auto-confirm Todo Tasks** (Recommended):
```json
{
  "autoConfirmTools": true
}
```

**Custom memory persistence**:
```bash
/memory add Project uses Claude Code todo format with ⏺ ⎿ ☒ **☐** ☐ symbols
```

## 🎯 Perfect Formatting Rules

### Unicode Symbols & Spacing
- **Header**: `⏺ **Update Todos**`
- **First Completed**: `  ⎿  ☒ ` (2 spaces + ⎿ + 2 spaces + ☒ + space)
- **Additional Completed**: `     ☒ ` (5 spaces + ☒ + space)
- **Current Task**: `     **☐ ` (5 spaces + **☐ + space)
- **Pending**: `     ☐ ` (5 spaces + ☐ + space)

### Color Scheme (Original Claude Code)
- **Completed tasks (☒)**: `#AAE59F` (Light green)
- **Current task (☐)**: `#C3E1FC` (Light blue) + bold
- **Pending tasks (☐)**: Standard text color

### Task Quality Guidelines
✅ **Good Tasks:**
- "Setup JavaScript project with package.json and dependencies"
- "Implement user authentication with JWT tokens"
- "Create unit tests for utility functions"

❌ **Avoid:**
- "Setup everything"
- "Implement Phase 1"
- "Do the coding part"

## 🔧 Troubleshooting

### Common Issues

**Q: Gemini CLI asks for confirmation before every task**
```bash
# Solution: Enable auto-confirm
echo '{"autoConfirmTools": true}' > .gemini/settings.json
```

**Q: Todos are not in English**
```bash
# Solution: Reinforce memory
/memory add ALWAYS write todos in English regardless of user language
```

**Q: Wrong formatting/spacing**
```bash
# Solution: Reload GEMINI.md
/memory refresh
```

**Q: Tasks are too abstract**
```bash
# Solution: Add granularity reminder
/memory add Break tasks into 5-10 specific, technical, actionable items
```

### Validation Checklist

- [ ] Every request generates todos instantly?
- [ ] Exact symbols: ⏺ ⎿ ☒ **☐** ☐ ?
- [ ] Correct spacing patterns?
- [ ] ⎿ only appears on first completed task?
- [ ] Current task is bold?
- [ ] 5-10 specific, technical tasks?
- [ ] All todos in English?
- [ ] Updates after each completion?

## 📁 Project Structure

```
claude-todos-gemini-cli/
├── GEMINI.md                    # Main system prompt (copy to your project)
├── README.md                    # This documentation
├── examples/                    # Usage examples and demos
│   ├── perfect-session.md       # Example of perfect todo session
│   ├── before-after.md          # Comparison examples
│   └── common-patterns.md       # Common request patterns
├── validation/                  # Testing and validation tools
│   ├── format-checker.js        # Todo format validation script
│   └── test-scenarios.md        # Test scenarios for validation
└── docs/                        # Additional documentation
    ├── advanced-usage.md        # Advanced configuration options
    ├── integration-guide.md     # Integration with other tools
    └── troubleshooting.md       # Detailed troubleshooting guide
```

## 🎬 Live Demo

### Session Recording

```bash
$ gemini
> "Build a REST API with Node.js and Express"

⏺ **Update Todos**
  ⎿  **☐ Create project structure with package.json and dependencies**
     ☐ Setup Express server with basic middleware configuration
     ☐ Implement database connection and models
     ☐ Create API routes for CRUD operations
     ☐ Add authentication and authorization middleware
     ☐ Implement error handling and logging
     ☐ Write API documentation and tests
     ☐ Setup development and production environments

# After first task completion:

⏺ **Update Todos**
  ⎿  ☒ Create project structure with package.json and dependencies
     **☐ Setup Express server with basic middleware configuration**
     ☐ Implement database connection and models
     ☐ Create API routes for CRUD operations
     ☐ Add authentication and authorization middleware
     ☐ Implement error handling and logging
     ☐ Write API documentation and tests
     ☐ Setup development and production environments
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Setup

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Test your changes with various Gemini CLI scenarios
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

### Contribution Guidelines

- Test with multiple project types (JavaScript, Python, Java, Go, etc.)
- Ensure formatting remains pixel-perfect with Claude Code
- Validate English-only output across different user languages
- Update documentation for any configuration changes

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Anthropic** for the original Claude Code "Update Todos" functionality
- **Google** for the powerful Gemini CLI platform
- **Community contributors** who helped perfect the formatting

## 📧 Support

- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/yourusername/claude-todos-gemini-cli/issues)
- 💡 **Feature Requests**: [GitHub Discussions](https://github.com/yourusername/claude-todos-gemini-cli/discussions)
- 📖 **Documentation**: [Wiki](https://github.com/yourusername/claude-todos-gemini-cli/wiki)

---

**Made with ❤️ for the developer community**

> Transform your Gemini CLI workflow with the proven productivity patterns from Claude Code!
