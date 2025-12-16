# Bacon Help Center

This is the help center documentation for [trybacon.ai](https://trybacon.ai), built with [Mintlify](https://mintlify.com).

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:

```bash
npm install
```

### Local Development

Run the development server:

```bash
npm run dev
```

This will start the Mintlify development server, typically at `http://localhost:3000`.

### Building

To build the documentation site:

```bash
npm run build
```

## Project Structure

```
.
├── docs/                    # Documentation files (MDX format)
│   ├── getting-started/     # Getting started guides
│   ├── brand-setup/         # Brand setup and intelligence
│   ├── images/              # Image generation guides
│   ├── videos/              # Video generation guides
│   ├── workspace/           # Workspace management
│   ├── billing/             # Billing and credits
│   ├── modes/               # Autopilot vs Pro mode
│   └── generation/          # Generation methods
├── mint.json                # Mintlify configuration
├── package.json             # npm dependencies
└── README.md                # This file
```

## Deployment

### Deploying to Mintlify

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)

2. Connect your repository to Mintlify:
   - Go to [Mintlify Dashboard](https://mintlify.com/dashboard)
   - Click "New Docs"
   - Connect your repository
   - Mintlify will automatically detect the `mint.json` file

3. Mintlify will automatically deploy your documentation site

### Manual Deployment

If you prefer to deploy manually:

1. Build the documentation:
   ```bash
   npm run build
   ```

2. The build output will be in the `.mintlify` directory

3. Deploy the contents to your hosting provider

## Documentation Structure

The help center is organized into 8 main sections:

1. **Getting Started with Bacon** - Introduction and onboarding
2. **Brand Setup & Brand Intelligence** - Brand profile and assets
3. **How To: Images** - Image ad generation
4. **How To: Videos** - Video ad generation (Video Ads, Veo3, Influencer)
5. **Workspace & Profile Management** - Dashboard navigation and settings
6. **Billing and Credit Utilisation** - Plans, subscriptions, and credits
7. **Pro vs Autopilot Mode** - Mode comparison
8. **Methods of Generation** - URL and upload methods

## Contributing

When adding or editing documentation:

1. Edit the relevant MDX file in the `docs/` directory
2. Use proper markdown formatting
3. Include frontmatter with `title` and `description`
4. Test locally using `npm run dev`
5. Commit and push changes

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Mintlify Components](https://mintlify.com/docs/components)
- [Markdown Guide](https://www.markdownguide.org/)

## Support

For questions about the documentation or Bacon, contact:
- Email: support@trybacon.ai
- Website: https://trybacon.ai

