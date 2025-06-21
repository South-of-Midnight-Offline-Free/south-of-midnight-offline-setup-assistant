# 🤝 Contributing to South of Midnight Offline Setup Assistant

We love contributions from the gaming community! Whether you're fixing bugs, adding features, improving documentation, or helping with translations, your help makes this project better for everyone.

## 🎮 Ways to Contribute

### 🐛 Bug Reports
Found something broken? Help us fix it!

**Before submitting:**
- Check if the issue already exists in our [Issues](https://github.com/South-of-Midnight-Offline-Free/south-of-midnight-offline-setup-assistant/issues)
- Try to reproduce the bug with a clean installation
- Gather system information (OS, graphics card, game version)

**When reporting:**
- Use a clear, descriptive title
- Include step-by-step reproduction instructions
- Attach screenshots or videos if helpful
- Mention your system specifications
- Include relevant log files if available

### 💡 Feature Requests
Have an idea for improvement?

**Good feature requests include:**
- Clear description of the problem you're solving
- Detailed explanation of your proposed solution
- Examples of how it would work
- Why other users would benefit from this feature

### 🔧 Code Contributions
Ready to get your hands dirty?

**We need help with:**
- 🎮 Game compatibility improvements
- 🖥️ UI/UX enhancements
- ⚡ Performance optimizations
- 🛠️ Configuration tools
- 🔧 Bug fixes
- 📝 Code documentation

### 📝 Documentation
Help make our guides better!

**Documentation needs:**
- 📖 User guides and tutorials
- 🛠️ Technical documentation
- 🌍 Translations to other languages
- 📺 Video tutorials
- 💡 FAQ entries

## 🚀 Getting Started

### Development Setup
1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/south-of-midnight-offline-setup-assistant.git
   cd south-of-midnight-offline-setup-assistant
   ```
3. **Set up development environment**:
   - Install Visual Studio 2022 or Visual Studio Code
   - Install .NET 6.0 SDK or later
   - Install Git for version control

### Development Workflow
1. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. **Make your changes**
3. **Test thoroughly**:
   - Test on different Windows versions
   - Test with different hardware configurations
   - Verify offline functionality works
4. **Commit with clear messages**:
   ```bash
   git commit -m "feat: add controller vibration support"
   ```
5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Create a Pull Request**

## 📋 Pull Request Guidelines

### Before Submitting
- [ ] Code follows our style guidelines
- [ ] All tests pass
- [ ] Documentation is updated if needed
- [ ] Commit messages are clear and descriptive
- [ ] PR description explains what and why

### PR Description Template
```markdown
## 🎯 What does this PR do?
Brief description of changes...

## 🔧 Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update
- [ ] Code refactoring

## 🧪 Testing
- [ ] Tested on Windows 10
- [ ] Tested on Windows 11
- [ ] Tested with different game versions
- [ ] All existing functionality still works

## 📸 Screenshots
Add screenshots if relevant...

## 📋 Checklist
- [ ] My code follows the project's style guidelines
- [ ] I have performed a self-review of my code
- [ ] I have commented my code where necessary
- [ ] I have updated documentation accordingly
- [ ] My changes generate no new warnings
```

## 🎨 Coding Standards

### Code Style
- Use **C# conventions** for naming and formatting
- Follow **PascalCase** for classes and methods
- Use **camelCase** for variables and parameters
- Add **XML documentation** for public methods
- Keep lines under **120 characters**

### Git Commit Messages
Use conventional commits format:
```
type(scope): description

feat(launcher): add HDR display support
fix(config): resolve controller detection issue
docs(readme): update installation instructions
style(ui): improve button styling consistency
refactor(core): simplify configuration loading
```

**Types:**
- `feat`: New features
- `fix`: Bug fixes
- `docs`: Documentation changes
- `style`: Code formatting changes
- `refactor`: Code restructuring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

## 🧪 Testing Guidelines

### Testing Requirements
- **Manual testing** on Windows 10 and 11
- **Compatibility testing** with different South of Midnight versions
- **Hardware testing** with various graphics cards
- **Controller testing** with Xbox and PlayStation controllers
- **Edge case testing** for unusual configurations

### Test Scenarios
1. **Fresh Installation**: Test with new South of Midnight installation
2. **Existing Installation**: Test with existing game installation
3. **Different Locations**: Test with game installed in various directories
4. **Multiple Monitors**: Test with multi-monitor setups
5. **Various Resolutions**: Test with different screen resolutions
6. **Controller Types**: Test with different controller brands

## 🌍 Internationalization

### Adding Translations
We welcome translations to make the assistant accessible globally!

**Supported Languages:**
- English (en-US) - Complete
- Spanish (es-ES) - Looking for contributors
- French (fr-FR) - Looking for contributors
- German (de-DE) - Looking for contributors
- Portuguese (pt-BR) - Looking for contributors
- Russian (ru-RU) - Looking for contributors

**How to Contribute Translations:**
1. Copy `Localization/en-US.json`
2. Create new file for your language (e.g., `es-ES.json`)
3. Translate all strings while keeping formatting placeholders
4. Test the translation in the application
5. Submit as a Pull Request

## 📞 Getting Help

### Communication Channels
- 💬 **Discord**: [Join our community](https://discord.gg/southofmidnight)
- 🐛 **GitHub Issues**: For bug reports and feature requests
- 📧 **Email**: support@southofmidnight-offline.com
- 📖 **Wiki**: [Documentation and guides](https://github.com/South-of-Midnight-Offline-Free/south-of-midnight-offline-setup-assistant/wiki)

### Mentorship
New to open source? We're here to help!
- Tag maintainers in issues with questions
- Join our Discord for real-time help
- Look for issues labeled `good first issue`
- Don't hesitate to ask for clarification

## 🏆 Recognition

### Contributors
All contributors are recognized in:
- README.md contributors section
- Release notes for significant contributions
- Discord contributor role
- Special mentions in major releases

### Contribution Types
We recognize all types of contributions:
- 💻 **Code**: Features, fixes, and improvements
- 📖 **Documentation**: Guides, tutorials, and explanations
- 🐛 **Testing**: Bug reports and quality assurance
- 💡 **Ideas**: Feature suggestions and feedback
- 🌍 **Translation**: Making the tool accessible globally
- 🎨 **Design**: UI/UX improvements and graphics
- 📢 **Community**: Helping other users and spreading awareness

## 📜 Code of Conduct

### Our Pledge
We pledge to make participation in our project a harassment-free experience for everyone, regardless of:
- Age, body size, disability, ethnicity
- Gender identity and expression
- Level of experience, education, socio-economic status
- Nationality, personal appearance, race, religion
- Sexual identity and orientation

### Our Standards
**Positive behavior includes:**
- Being respectful and inclusive
- Gracefully accepting constructive criticism
- Focusing on what's best for the community
- Showing empathy towards other community members

**Unacceptable behavior includes:**
- Harassment, trolling, or insulting comments
- Public or private harassment
- Publishing others' private information without permission
- Other conduct which could be considered unprofessional

### Enforcement
Project maintainers will:
- Remove, edit, or reject contributions that don't align with our standards
- Temporarily or permanently ban contributors for inappropriate behavior
- Report serious violations to relevant authorities if necessary

## 🎉 Thank You!

Every contribution, no matter how small, makes this project better. Thank you for being part of the South of Midnight offline gaming community!

---

**Ready to contribute?** 
1. Check our [Issues](https://github.com/South-of-Midnight-Offline-Free/south-of-midnight-offline-setup-assistant/issues) for `good first issue` labels
2. Join our [Discord](https://discord.gg/southofmidnight) to say hello
3. Fork the repository and start coding!

*Happy gaming and happy coding!* 🎮✨ 