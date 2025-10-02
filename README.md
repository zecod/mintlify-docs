# NeoSpeech API Documentation

Official documentation for the NeoSpeech Text-to-Speech API. Convert text into natural-sounding speech with 50+ voices in 90+ languages.

## About

This repository contains the complete API documentation for NeoSpeech, including:

- **API Reference** - Complete endpoint documentation for speech generation, streaming, voices, models, and balance
- **Guides** - Best practices, error handling, streaming implementation, and rate limit management
- **Examples** - Code samples in cURL, JavaScript/Node.js, Python, and Java
- **Concepts** - Authentication, models, voices, and rate limits explained

## Quick Links

- **Live Documentation**: [docs.neospeech.io](https://docs.neospeech.io)
- **Dashboard**: [neospeech.io](https://neospeech.io)
- **API Base URL**: `https://api.neospeech.io/v1`

## Features Documented

- 🎙️ **Text-to-Speech** - Convert up to 5,000 characters per request
- 🔊 **50+ Voices** - Multiple languages, genders, and styles
- 🎚️ **5 Audio Models** - From premium quality (aurora-4) to ultra-fast (turbo-3, mini-2)
- ⚡ **Real-time Streaming** - Progressive audio delivery for low-latency applications
- 🔐 **API Authentication** - Secure bearer token authentication
- 📊 **Balance Monitoring** - Track credit usage and limits

## Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the development server at the root of the documentation (where `mint.json` is located):

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Documentation Structure

```
mintlify-docs/
├── api/                    # API endpoint documentation
│   ├── balance.mdx
│   ├── models.mdx
│   ├── streaming.mdx
│   ├── text-to-speech.mdx
│   └── voices.mdx
├── concepts/               # Core concepts and explanations
│   ├── authentication.mdx
│   ├── models.mdx
│   ├── rate-limits.mdx
│   └── voices.mdx
├── examples/               # Code examples by language
│   ├── curl.mdx
│   ├── javascript.mdx
│   └── python.mdx
├── guides/                 # How-to guides and best practices
│   ├── best-practices.mdx
│   ├── error-handling.mdx
│   ├── rate-limits.mdx
│   └── streaming.mdx
├── ai-tools/               # AI coding assistant setup guides
│   ├── claude-code.mdx
│   ├── cursor.mdx
│   └── windsurf.mdx
├── introduction.mdx        # Getting started
├── quickstart.mdx          # Quick start guide
└── mint.json               # Mintlify configuration
```

## Publishing Changes

Changes are automatically deployed to production when pushed to the `main` branch via the Mintlify GitHub app integration.

## Contributing

When contributing to the documentation:

1. Follow the existing structure and formatting
2. Test changes locally with `mint dev` before committing
3. Include code examples in multiple languages where applicable
4. Keep examples concise and functional
5. Update navigation in `mint.json` if adding new pages

## Troubleshooting

- **Dev environment not running**: Run `mint update` to get the latest CLI version
- **Page loads as 404**: Ensure you're in the folder with `mint.json` and the page is listed in navigation
- **Changes not reflecting**: Clear browser cache or restart the dev server

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [NeoSpeech Website](https://neospeech.io)
- [API Status](https://status.neospeech.io)

## Support

For API support and questions:
- Email: support@neospeech.io
- Documentation issues: Open an issue in this repository
