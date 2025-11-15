# Contributing to AI Product Studio

Thank you for your interest in contributing to AI Product Studio! This document provides guidelines and information for contributors.

## 🤝 How to Contribute

### Reporting Bugs
1. Check if the bug has already been reported in [Issues](https://github.com/Dinu-Sri/ai-product-studio/issues)
2. If not, create a new issue with:
   - Clear, descriptive title
   - Steps to reproduce the bug
   - Expected vs actual behavior
   - Screenshots (if applicable)
   - System info (OS, Python version, GPU)

### Suggesting Features
1. Check existing [Issues](https://github.com/Dinu-Sri/ai-product-studio/issues) for similar suggestions
2. Create a new issue with:
   - Clear description of the feature
   - Use case and benefits
   - Possible implementation approach (optional)

### Pull Requests
1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Test thoroughly
5. Commit with clear messages: `git commit -m "Add feature: description"`
6. Push to your fork: `git push origin feature/your-feature-name`
7. Create a Pull Request with detailed description

## 🛠️ Development Setup

### Prerequisites
```bash
Python 3.8+
Git
```

### Local Development
```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/ai-product-studio.git
cd ai-product-studio

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
```

## 📝 Code Style

- Follow PEP 8 style guide
- Use meaningful variable and function names
- Add docstrings for functions and classes
- Comment complex logic
- Keep functions focused and modular

## 🧪 Testing

Before submitting PR:
- Test on your local machine
- Test with different image types and sizes
- Test batch processing
- Verify no memory leaks with large images
- Check GPU and CPU modes work

## 📋 Areas for Contribution

### High Priority
- Additional AI model integrations
- Performance optimizations
- Memory usage improvements
- Cross-platform testing (Linux, macOS)
- Documentation improvements

### Features Welcome
- New shadow types/effects
- Additional image filters
- Export format options
- Keyboard shortcuts
- Plugin system
- CLI interface

### Good First Issues
- UI improvements
- Bug fixes
- Documentation updates
- Translation support
- Code refactoring

## 📜 License

By contributing, you agree that your contributions will be licensed under the MIT License.

## 💬 Questions?

Feel free to:
- Open an issue for discussion
- Comment on existing issues
- Contact the maintainer

## 🙏 Thank You!

Every contribution, no matter how small, is appreciated and helps make AI Product Studio better for everyone!

---

**Maintainer**: Dinu-Sri ([@Dinu-Sri](https://github.com/Dinu-Sri))
