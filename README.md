# Shadcn Component Manager Documentation

The official documentation for the Shadcn Component Manager (SCM).  Built with Mintlify for a modern, interactive documentation experience.

## Overview

This documentation provides comprehensive guides for using SCM, including CLI commands, web interface usage, and component development workflows.

## Features

- Complete CLI command reference
- Web interface documentation  
- Component creation and publishing guides
- Authentication and configuration setup
- Interactive examples and code snippets
- Responsive design for all devices

## Development

### Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation changes locally:

```bash
# Install Mintlify CLI
npm i -g mint

# Run development server
mint dev
```

### Building

```bash
# Build for production
mint build

# Preview production build
mint preview
```

### Publishing Changes

The documentation is automatically deployed when changes are pushed to the main branch. The GitHub App handles deployment to production.

### Troubleshooting

- **Dev environment not running**: Run `mint update` to ensure you have the latest CLI version
- **Page loads as 404**: Make sure you're running in a folder with `docs.json`
- **Changes not reflecting**: Clear cache and restart the dev server

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your documentation changes
4. Test locally with `mint dev`
5. Submit a pull request

### Documentation Standards

- Use clear, concise language
- Include practical examples
- Follow the established structure
- Test all code examples
- Use Mintlify components for consistency

## Related Repositories

- **[CLI Tool](https://github.com/Shadcn-Component-Manager/scm)**: Command-line interface
- **[Registry](https://github.com/Shadcn-Component-Manager/registry)**: Component repository
- **[Web Interface](https://github.com/Shadcn-Component-Manager/web)**: Next.js web application

## License

MIT License - see LICENSE file for details.
