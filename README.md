# Mosaic AI API Documentation

⚠️ **PREVIEW DOCUMENTATION** - These endpoints describe the new Mosaic API architecture that will be deployed soon.

This repository contains the API documentation for [Mosaic AI](https://mosaic.so), a platform for AI-powered video editing workflows.

## 📚 Documentation Structure

- [API Overview](overview/introduction.mdx) - Authentication, rate limits, and conventions
- [Video Upload](overview/video-upload.mdx) - 3-step video upload process
- [Agent Operations](overview/agent-operations.mdx) - Running and tracking AI agents
- [Triggers](overview/triggers.mdx) - Automatic processing with YouTube monitoring
- [Webhooks](overview/webhooks.mdx) - Real-time notifications

## 🚀 API Overview

The Mosaic API enables you to:

1. **Upload videos** - Simple 3-step process with pre-signed URLs
2. **Run AI agents** - Process videos with pre-built workflows
3. **Set up triggers** - Automatically process new YouTube videos
4. **Receive webhooks** - Get real-time updates on processing status

Base URL: `https://api.mosaic.so`

## 🔧 Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview documentation locally:

```bash
npm i -g mintlify
```

Run the development server:

```bash
mintlify dev
```

The documentation will be available at `http://localhost:3000`.

## 🤝 Support

- 💬 [Discord Community](https://discord.gg/26SAZzBTaP)
- 📧 Email: [adish@mosaic.so](mailto:adish@mosaic.so)
- 🌐 Dashboard: [app.mosaic.so](https://app.mosaic.so)

## 🛠️ Troubleshooting

- **Mintlify dev isn't running** - Run `mintlify install` to re-install dependencies
- **Page loads as 404** - Ensure you're running the command in the directory containing `docs.json`
- **API authentication issues** - Verify your API key starts with `mk_`