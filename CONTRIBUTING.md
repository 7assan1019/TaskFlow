# Contributing to TaskFlow

Thank you for your interest in contributing to TaskFlow! We welcome contributions from everyone.

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Setting up your development environment

1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub, then clone your fork
   git clone https://github.com/yourusername/taskflow.git
   cd taskflow
   ```

2. **Create a branch for your feature**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Open `index.html` in your browser
   - Make your modifications
   - Test thoroughly

4. **Commit and push**
   ```bash
   git add .
   git commit -m "Add: your feature description"
   git push origin feature/your-feature-name
   ```

5. **Create a Pull Request**
   - Go to your fork on GitHub
   - Click "New Pull Request"
   - Fill out the template

## 📋 How to Contribute

### Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates.

**Bug Report Template:**
- **Description**: Clear description of the bug
- **Steps to Reproduce**: Step-by-step instructions
- **Expected Behavior**: What should happen
- **Actual Behavior**: What actually happens
- **Screenshots**: If applicable
- **Browser Information**: Browser name and version
- **Additional Context**: Any other relevant information

### Suggesting Features

We welcome feature suggestions! Please provide:
- **Use Case**: Why would this feature be useful?
- **Description**: Detailed description of the feature
- **Implementation Ideas**: Any thoughts on how it could work
- **Alternatives**: Other solutions you've considered

### Code Contributions

#### What we're looking for:
- Bug fixes
- Performance improvements
- New features that align with the project goals
- Documentation improvements
- Code refactoring and cleanup

#### Code Style Guidelines

**HTML:**
- Use semantic HTML5 elements
- Maintain proper indentation (2 spaces)
- Use meaningful class names and IDs
- Include proper accessibility attributes

**CSS:**
- Follow BEM methodology for class naming
- Use CSS custom properties (variables) for consistent theming
- Mobile-first responsive design
- Maintain consistent spacing and typography

**JavaScript:**
- Use ES6+ features when appropriate
- Write clear, self-documenting code
- Add comments for complex logic
- Use meaningful variable and function names
- Handle errors gracefully

**Example:**
```javascript
// Good
function createTaskElement(task) {
    const element = document.createElement('div');
    element.className = 'task-card';
    
    if (task.completed) {
        element.classList.add('task-card--completed');
    }
    
    return element;
}

// Avoid
function makeDiv(t) {
    var d = document.createElement('div');
    d.className = 'task-card';
    return d;
}
```

## 🧪 Testing

Before submitting your contribution:

1. **Manual Testing**
   - Test in multiple browsers (Chrome, Firefox, Safari, Edge)
   - Test on different screen sizes
   - Verify all features work as expected

2. **Cross-browser Compatibility**
   - Ensure your code works in modern browsers
   - Test responsive design on various devices

3. **Performance Testing**
   - Check that large numbers of tasks don't slow down the app
   - Verify smooth animations and transitions

## 📝 Pull Request Process

1. **Before submitting:**
   - Ensure your code follows the style guidelines
   - Test your changes thoroughly
   - Update documentation if needed
   - Add your changes to the relevant section

2. **Pull Request Template:**
   ```markdown
   ## Description
   Brief description of changes

   ## Type of Change
   - [ ] Bug fix
   - [ ] New feature
   - [ ] Breaking change
   - [ ] Documentation update

   ## Testing
   - [ ] Tested in Chrome
   - [ ] Tested in Firefox
   - [ ] Tested on mobile
   - [ ] All existing features still work

   ## Screenshots
   (If applicable)
   ```

3. **Review Process:**
   - Maintainers will review your PR
   - You may be asked to make changes
   - Once approved, your PR will be merged

## 🎯 Priority Areas

We're particularly interested in contributions for:

- **Accessibility improvements** (ARIA labels, keyboard navigation)
- **Performance optimizations** (faster rendering, better memory usage)
- **Mobile experience** (touch interactions, responsive design)
- **Internationalization** (multi-language support)
- **Data export/import** (JSON, CSV export features)
- **Offline functionality** (Service Workers, PWA features)

## ❓ Questions?

- Check existing issues and discussions
- Create a new issue with the "question" label
- Reach out to maintainers

## 📖 Resources

- [MDN Web Docs](https://developer.mozilla.org/) - Web development reference
- [Web Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)
- [JavaScript Style Guide](https://github.com/airbnb/javascript)

## 🏆 Recognition

Contributors will be:
- Listed in the project's contributor section
- Mentioned in release notes for significant contributions
- Invited to become maintainers for sustained contributions

Thank you for making TaskFlow better! 🚀