# Contributing to Unraid Templates

Thank you for your interest in contributing to this Unraid Community Applications template repository!

## Guidelines

### Template Requirements

All templates must adhere to the [Unraid Community Applications policies](https://forums.unraid.net/topic/87144-ca-application-policies-privacy-policy/):

1. **Security**: No code injection or additional bash commands in templates
2. **Descriptions**: No HTML-like tags in descriptions (use `variable` instead of `<variable>`)
3. **Quality**: Templates must include reasonable descriptions and proper categorization
4. **Open Source**: Applications must be open source or from reputable sources

### Template Structure

- Place XML templates in the `templates/` directory
- Place icons in the `icons/` directory (PNG format, reasonable size)
- Use descriptive names for both template files and icons
- Follow existing naming conventions

### Required Template Elements

- **Name**: Clear, descriptive application name
- **Repository**: Valid Docker repository URL
- **Overview**: Comprehensive description of the application
- **Category**: Appropriate categorization
- **Icon**: Link to icon in this repository
- **Support**: Link to application support/issues
- **WebUI**: If applicable, proper WebUI URL format

### Testing

Before submitting:

1. Test the template in a local Unraid environment
2. Verify all links work correctly
3. Ensure the application starts and functions as expected
4. Check that the WebUI (if applicable) is accessible

### Submission Process

1. Fork this repository
2. Create a new branch for your template
3. Add your template and icon files
4. Update the README.md to include your application in the "Available Applications" section
5. Submit a pull request with a clear description of the changes

### Template Updates

- Keep templates up to date with upstream changes
- Test updates before submitting
- Document any breaking changes in pull request descriptions

## Questions?

If you have questions about contributing, please:

- Check the [Unraid Community Applications policies](https://forums.unraid.net/topic/87144-ca-application-policies-privacy-policy/)
- Open an issue in this repository
- Ask in the Unraid Community Forums
