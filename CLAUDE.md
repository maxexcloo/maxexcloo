# CLAUDE.md - Development Guide

## Project Overview
**Purpose**: [Brief one-line description]  
**Status**: [Active/Archive/Experimental]

## Commands
```bash
# Development
[dev command or "# No development server required"]    # Start development
[test command or "# No tests configured"]             # Run tests
[lint/format command]                                 # Check/fix code quality

# Build
[build command or "# No build process required"]      # Build for production
```

## Tech Stack
- **Language**: [Language] [version]+ (e.g., "Python 3.12+", "JavaScript (Node.js 22+)")
- **Framework**: [Framework] [version] (or "No framework" if applicable)
- **Testing**: [Testing framework] (or "No testing framework configured" if none)

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
- **Naming**: [Language-specific conventions, e.g., "snake_case for functions, ALL_CAPS for constants (Python)", "camelCase for variables, kebab-case for CSS classes (JavaScript)"]
- **Trailing newlines**: Required in all files

## Project Structure
- **[directory/]**: [Purpose and contents]
- **[main-file.ext]**: [Specific purpose, e.g., "Entry point", "Configuration", "Tests"]

## Project Specs
- **[Architecture/Pattern]**: [How the system is structured, e.g., "Server-side rendering with client-side filtering"]
- **[Performance/Limits]**: [Important constraints, e.g., "5-minute cache expiry, 1000-item limit"]
- **[Key Dependencies]**: [Critical integrations with versions, e.g., "Uses pocketbase==0.15.0 for API communication"]
- **[Unique Behaviors]**: [Special features or implementation details]

## README Guidelines
- **Structure**: Title → Description → Quick Start → Features → Installation → Usage → Contributing
- **Badges**: License (AGPL-3.0) and Status badges in alphabetical order (no version badges)
- **Code examples**: Always include working examples in code blocks
- **Installation**: Provide copy-paste commands that work
- **License**: All projects use AGPL-3.0 License
- **Quick Start**: Get users running in under 5 minutes

## Git Workflow
```bash
# After every change
[format-command] && [lint-command] && [test-command]
git add . && git commit -m "type: description"

# Always commit after verified working changes
# Keep commits small and focused
```

---

*Simple context for AI assistants working on this open source project.*
