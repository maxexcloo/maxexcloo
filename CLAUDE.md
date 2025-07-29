# CLAUDE.md - Development Guide

## Project Overview
**Purpose**: [Brief one-line description]  
**Status**: [Active/Archive/Experimental]

## Commands
```bash
# Development
[dev command]    # Start development
[test command]   # Run tests
[lint command]   # Check code quality

# Build
[build command]  # Build for production
```

## Tech Stack
- **Language**: [Primary language and version]
- **Framework**: [Main framework]
- **Testing**: [Testing framework]

## Code Standards

### Organization
- **Config/Data**: Alphabetical and recursive (imports, dependencies, object keys)
- **Documentation**: Sort sections, lists, and references alphabetically when logical
- **Files**: Alphabetical in documentation and directories
- **Functions**: Group by purpose, alphabetical within groups
- **Variables**: Alphabetical within scope

### Quality
- **Comments**: Minimal - only for complex business logic
- **Documentation**: Update README.md and docs with every feature change
- **Formatting**: Run formatter before commits
- **KISS principle**: Keep it simple - prefer readable code over clever code
- **Naming**: [Project-specific conventions]
- **Trailing newlines**: Required in all files

## Project Structure
- **[key-directory/]**: [Purpose]
- **[main-file.ext]**: [Entry point]

## Project Specs
- **[Spec 1]**: [Project-specific requirement or constraint]
- **[Spec 2]**: [Unique behavior or implementation detail]
- **[Spec 3]**: [Business logic or domain-specific rule]

## README Guidelines
- **Structure**: Title → Description → Quick Start → Features → Installation → Usage → Contributing
- **Badges**: Include relevant status badges (build, version, license)
- **Code examples**: Always include working examples in code blocks
- **Installation**: Provide copy-paste commands that work
- **Quick Start**: Get users running in under 5 minutes

## Git Workflow
```bash
# After every change
[format] && [lint] && [test]
git add . && git commit -m "type: description"

# Always commit after verified working changes
# Keep commits small and focused
```

---

*Simple context for AI assistants working on this open source project.*
