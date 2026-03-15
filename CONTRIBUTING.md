# Contributing to This Project

Thank you for your interest in contributing! This document provides guidelines and instructions.

## 📋 Code of Conduct
- Be respectful and inclusive
- Provide constructive feedback
- Report issues professionally
- Respect others' time and effort

## 🐛 Reporting Issues
- Check if issue already exists
- Provide clear, descriptive title
- Include steps to reproduce
- Specify your environment (OS, version, etc.)
- Add screenshots/logs if applicable

**Issue Template:**
```
## Description
Brief description of the issue

## Steps to Reproduce
1. Step 1
2. Step 2
3. Step 3

## Expected Behavior
What should happen

## Actual Behavior
What actually happens

## Environment
- OS: 
- Version:
- Browser: (if applicable)
```

## ✨ Suggesting Enhancements
- Use a clear descriptive title
- Provide detailed description
- List some examples/use cases
- Explain why this enhancement would be useful

## 🔧 Development Setup

### Prerequisites
- Git
- [Your tech stack requirements]

### Steps
```bash
# Fork and clone the repo
git clone https://github.com/YOUR_USERNAME/project.git
cd project

# Add upstream
git remote add upstream https://github.com/sauravsinhadev/project.git

# Install dependencies
npm install
# or
pip install -r requirements.txt

# Create feature branch
git checkout -b feature/your-feature-name
```

## 📝 Coding Standards
- Follow the existing code style
- Write meaningful variable names
- Add comments for complex logic
- Ensure code is well-formatted

### Python
- Follow PEP 8 guidelines
- Use type hints
- Write docstrings for functions

### JavaScript
- Use ESLint configuration
- Use meaningful variable names
- Write comments for complex logic

## ✅ Testing
- Write tests for new features
- Ensure all tests pass before submitting PR
- Maintain or improve code coverage

```bash
# Run tests
npm test
# or
pytest
```

## 📤 Submitting Changes

### Step-by-step
1. **Create a branch** from the latest `main`
   ```bash
      git checkout -b feature/amazing-feature
         ```

         2. **Make your changes** with clear, atomic commits
            ```bash
               git commit -m "Add amazing feature"
                  ```

                  3. **Keep your branch updated**
                     ```bash
                        git fetch upstream
                           git rebase upstream/main
                              ```

                              4. **Push your branch**
                                 ```bash
                                    git push origin feature/amazing-feature
                                       ```

                                       5. **Open a Pull Request** with:
                                          - Clear title
                                             - Detailed description
                                                - Reference related issues (#123)
                                                   - Screenshots/demos if applicable

                                                   ### Commit Message Guidelines
                                                   - Use present tense: "Add feature" not "Added feature"
                                                   - Use imperative mood: "Move cursor to..." not "Moves cursor to..."
                                                   - Limit to 50 characters for subject
                                                   - Reference issues: "Fixes #123"

                                                   **Example:**
                                                   ```
                                                   Add dark mode toggle feature

                                                   - Implement theme switcher component
                                                   - Add localStorage persistence
                                                   - Update documentation
                                                   - Add unit tests

                                                   Fixes #456
                                                   ```

                                                   ## 🔍 Pull Request Review
                                                   - Respond to feedback promptly
                                                   - Make requested changes in new commits
                                                   - Keep discussions respectful and professional

                                                   ## 📚 Documentation
                                                   - Update README if adding new features
                                                   - Add docstrings to functions
                                                   - Update CHANGELOG.md
                                                   - Comment complex algorithms

                                                   ## 🎉 Recognition
                                                   Contributors will be recognized in:
                                                   - README.md
                                                   - Commit history
                                                   - Release notes (for significant contributions)

                                                   ## ❓ Questions?
                                                   - Open an issue with the `question` label
                                                   - Check existing documentation
                                                   - Review past issues for similar questions

                                                   ---

                                                   Thank you for contributing! 🙏