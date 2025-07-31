# CLAUDE.md - Development Guide

## Project Overview
**Purpose**: [Brief one-line description of project purpose and main functionality]
**Status**: [Active/Archive/Experimental]
**Language**: [Language version]+ (e.g., "JavaScript (Node.js 22+)", "Python 3.12+", "Go")

## Code Standards

### Organization
- **Config/Data**: Alphabetical and recursive (imports, dependencies, object keys)
- **Documentation**: Sort alphabetically and recursively when it makes logical sense
- **Files**: Alphabetical in documentation and directories
- **Functions**: Group by purpose, alphabetical within groups
- **Variables**: Alphabetical within scope

### Quality
- **Comments**: Minimal - only for complex business logic
- **Documentation**: Update ARCHITECTURE.md and README.md with every feature change
- **Error handling**: [Specific error handling approach]
- **Formatting**: Run [specific formatter command] before commits
- **KISS principle**: Keep it simple - prefer readable code over clever code
- **Naming**: [Language-specific conventions]
- **Testing**: [Testing approach]
- **Trailing newlines**: Required in all files

## Commands
```bash
# Build
[build command]    # Description of build process

# Development
[dev command]      # Start development or validation cycle
[test command]     # Run test suite

# Format
[fmt command]      # Code formatting

# Check
[check command]    # All validation (fmt + lint + test)
```

## Development Guidelines

### Contribution Standards
- **Code Changes**: Follow sorting rules and maintain [specific requirements]
- **Documentation**: Keep all docs synchronized and cross-referenced
- **Feature Changes**: Update README.md and ARCHITECTURE.md when adding features

### Documentation Structure
- **ARCHITECTURE.md**: Technical design and implementation details
- **CLAUDE.md**: Development standards and project guidelines
- **README.md**: Tool overview and usage guide

## [Interface/API/Command] Standards
- **[Clear responses/output]**: [Specific requirements]
- **[Consistent endpoints/flags]**: [Specific requirements]
- **[Error messages]**: [Specific requirements]
- **[Health checks/Exit codes]**: [Specific requirements]

## Development Workflow Standards

### Environment Management
- **Option 1 - Node.js**: Use npm scripts in package.json
- **Option 2 - Python**: Use uv scripts (dependencies in script headers)
- **Option 3 - Go**: Use mise (.mise.toml) or native go commands
- **Option 4 - Multi-lang**: Use mise for mixed-language projects

## Error Handling Standards
- **Contextual errors**: [Specific approach]
- **Graceful degradation**: [Specific approach]
- **Informative messages**: [Specific approach]
- **User-friendly output**: [Specific approach]

### Required Development Tasks
- **build**: [Description of build task]
- **check**: All validation (fmt + lint + test)
- **dev**: Development validation cycle
- **fmt**: Code formatting
- **lint**: Code quality checks
- **test**: Run test suite

## Project Structure
- **[main-directory/]**: [Purpose and contents]
- **[main-file.ext]**: [Specific purpose]
- **[other-directory/]**: [Purpose and contents]
- **[other-file.ext]**: [Specific purpose]

## README Guidelines
- **Badges**: Include relevant status badges (license, status, language, docker)
- **Code examples**: Always include working examples in code blocks
- **Installation**: Provide copy-paste commands that work
- **Quick Start**: Get users running in under 5 minutes
- **Structure**: Title → Badges → Description → Quick Start → Features → Installation → Usage → Contributing

## Tech Stack
- **Backend**: [Backend technologies]
- **Frontend**: [Frontend technologies, if applicable]
- **Client**: [Client technologies, if applicable]
- **Testing**: [Testing approach and frameworks]

---

*Development guide for the [project-name] open source project.*
