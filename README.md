# UX Accelerator Hub

> A strategic toolkit of Gemini experiences and specialized AI tools designed to accelerate UX strategy, streamline research planning, improve content consistency, and enhance design clarity across all Cloudflare products.

## Overview

The UX Accelerator Hub is a centralized platform that provides Cloudflare UX teams with quick access to custom-built AI tools and Gemini experiences. These resources help accelerate workflows in UX research, content creation, information architecture, and design decision-making.

## Features

### UX Gems 💎

Custom Gemini experiences tailored for specific UX workflows:

1. **Core Dash IA AI** - Analyzes new Cloudflare solutions to determine optimal placement within the dashboard's navigation groups
2. **Empty State Content** - Generates empty state content following Cloudflare One's standard template and guidelines
3. **ZeroTrust IA AI** - Helps product managers and designers find the best placement for new features within Zero Trust navigation
4. **Final Video Tech Review** - Scrutinizes video content against Cloudflare Developer documentation standards
5. **Video Series Brainstorm** - Creates video concepts for users of all experience levels to understand Cloudflare products
6. **Meeting Notes → UXR Plan** - Transforms stakeholder meeting notes or transcripts into draft UXR plans with research objectives and questions
7. **Interim High-Level Research Observations** - Provides interim findings for ongoing research to keep stakeholders engaged
8. **Page Description Generator** - Generates page descriptions that guide users on what they can accomplish with product features

### AI Tools 🔧

Specialized AI-powered tools for content evaluation and analysis:

1. **PCX CLUE Index** - Evaluates UI, API, and email content against UX content best practices and Cloudflare's internal style guide
2. **CloudSpeaker** - Analyzes public sentiment data about Cloudflare and provides Workers AI-powered summaries

## Getting Started

### Viewing the Hub

Simply open the `index.html` file in your web browser to access the UX Accelerator Hub interface.

Alternatively, you can deploy this to any static hosting service like:
- GitHub Pages
- Cloudflare Pages
- Netlify
- Vercel

### Using the Tools

Click any card in the hub to launch the respective tool or Gemini experience. All tools open in a new tab for easy navigation between multiple resources.

## Design System

The UX Accelerator Hub uses Cloudflare's brand colors and design principles:

- **Primary Colors**: Cloudflare Orange variants (#F6821F, #FF6633, #FBAD41)
- **Typography**: Inter font family
- **Framework**: Tailwind CSS for responsive design
- **Icons**: Lucide icons for consistent visual language

## Technology Stack

- HTML5
- Tailwind CSS (via CDN)
- Lucide Icons
- Google Fonts (Inter)

## Contributing

To add a new tool or gem to the hub:

1. Clone this repository
2. Edit `index.html` to add a new card in the appropriate section (UX Gems or AI Tools)
3. Follow the existing card structure for consistency
4. Use appropriate Lucide icons
5. Commit your changes and push to the repository

### Card Template

```html
<a href="YOUR_TOOL_URL" target="_blank" class="tool-card bg-white p-6 rounded-xl shadow-card hover:shadow-card-hover transform hover:scale-[1.01] transition-all duration-300 block">
    <div class="flex items-center mb-3">
        <i data-lucide="icon-name" class="icon-gem w-6 h-6 mr-3"></i>
        <h4 class="text-xl font-semibold text-neutral-dark" style="font-weight: 600;">Tool Name</h4>
    </div>
    <p class="text-gray-600 text-sm font-light">Tool description goes here.</p>
</a>
```

## Maintenance

This hub is maintained by the Cloudflare UX Teams. For questions, suggestions, or issues, please reach out to the UX team.

## License

Internal use only - Cloudflare UX Teams

## Acknowledgments

Built by Cloudflare UX Teams to accelerate content iteration and enhance design clarity across all Cloudflare products. Leverage AI responsibly.
