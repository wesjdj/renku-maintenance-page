# RenkuLab Maintenance Page

A Hugo-based maintenance page for RenkuLab, designed to be displayed when renkulab.io is under maintenance.

## Features

- **Official Renku branding** - Uses the official logo and color scheme
- **Responsive design** - Works on desktop and mobile devices
- **GitHub Pages deployment** - Automated deployment via GitHub Actions
- **Easy configuration** - All content managed through `hugo.toml`
- **Status page integration** - Links to https://renkulab.statuspage.io/

## Configuration

All text content is managed through the `hugo.toml` file. Key parameters:

- `maintenanceTitle` - Main heading
- `maintenanceSubtitle` - Subtitle text
- `additionalInfoTitle` - Additional information section title
- `additionalInfoText` - Main explanation text
- `unavailableServices` - Array of service status items
- `whatYouCanDoTitle` - Action items section title
- `whatYouCanDo` - Array of actionable items
- `closingMessage` - Final message to users
- `statusPageUrl` - Link to status page
- `footerMessage` - Footer text

## Development

1. Install Hugo: `brew install hugo`
2. Run development server: `hugo server`
3. Build for production: `hugo`

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## Usage

This maintenance page should be displayed when renkulab.io is experiencing planned maintenance or outages. It provides users with:

- Clear information about service unavailability
- Link to the status page for real-time updates
- Professional branding consistent with RenkuLab