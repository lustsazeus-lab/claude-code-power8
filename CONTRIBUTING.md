# Contributing to Claude Code POWER8

Thank you for your interest in contributing to Claude Code POWER8!

This project targets IBM POWER8 architecture and provides integrations between Claude Code and POWER8-based systems.

## How to Contribute

### Fork and Clone

1. Fork this repository by clicking the "Fork" button on GitHub
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/claude-code-power8.git
   cd claude-code-power8
   ```

### Branch Naming Convention

Create a new branch for your work:

- `fix/description` - For bug fixes
- `feat/description` - For new features
- `docs/description` - For documentation changes
- `test/description` - For adding tests

Examples:
```bash
git checkout -b fix/memory-leak-fix
git checkout -b feat/power8-optimization
git checkout -b docs/readme-update
```

### Making Changes

1. Make your changes in your feature branch
2. Test locally if possible
3. Commit your changes with clear commit messages:
   ```bash
   git add .
   git commit -m "feat: add POWER8 specific optimization"
   ```

### Submitting a Pull Request

1. Push your branch to your fork:
   ```bash
   git push origin your-branch-name
   ```
2. Open a Pull Request against the `main` branch
3. Fill in the PR template with:
   - Description of changes
   - Related issues
   - Testing performed
4. Wait for maintainer review

## Code Style

- Follow existing code patterns in the repository
- Use meaningful variable and function names
- Add comments for complex logic, especially POWER8-specific optimizations
- Keep lines under 100 characters when possible

## POWER8 Context

This project specifically targets:
- IBM POWER8 processors
- PowerPC architecture
- Big-endian and little-endian configurations
- POWER8 specific instructions (if applicable)

When contributing code that is POWER8-specific, please add a comment noting the POWER8 relevance.

## Testing

If applicable, test your changes:
- On actual POWER8 hardware if possible
- In QEMU POWER8 emulation as an alternative
- Document any known limitations

## Questions?

- Open an issue for questions
- Check existing issues before creating new ones

## Recognition

Contributors will be acknowledged in the README.md file.

Thank you for helping improve Claude Code POWER8!
