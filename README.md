# Advanced Shopify Theme

A modern, customizable Shopify theme with a focus on performance, accessibility, and user experience.

## Features

- Responsive design that works on all devices
- Customizable sections that can be added, removed, and reordered
- Modern hero section with background image and overlay options
- Featured collection section with customizable layout
- Newsletter signup with customizable content
- Social media integration
- Flexible header with navigation and search
- Footer with multiple menu areas and social links
- Built with accessibility in mind

## Theme Structure

```
├── config/
│   └── settings_schema.json   # Theme settings configuration
├── layout/
│   └── theme.liquid          # Main theme layout
├── sections/
│   ├── featured-collection.liquid  # Featured collection section
│   ├── footer.liquid              # Footer section
│   ├── header.liquid              # Header section
│   └── hero.liquid               # Hero section
└── templates/
    └── index.json               # Homepage template
```

## Customization

### Theme Settings

The theme includes the following customizable settings:

- Colors
  - Primary color
  - Secondary color
  - Accent color
- Typography
  - Heading font
  - Body font
- Layout
  - Container width (1200px, 1400px, or 1600px)

### Sections

#### Hero Section
- Background image
- Section height (small, medium, large, full)
- Heading text
- Content text
- Button label and link
- Text alignment
- Overlay color and opacity

#### Featured Collection Section
- Collection selection
- Title
- Products per row (2-4)
- Number of products to display
- Option to show/hide prices

#### Header Section
- Logo upload and width
- Menu selection
- Search toggle
- Sticky header option

#### Footer Section
- Newsletter signup (optional)
  - Heading
  - Text content
- Two customizable menu areas
- Social media links
- Copyright text

## Development

### Prerequisites

- [Shopify CLI](https://shopify.dev/themes/tools/cli)
- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)

### Local Development

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
shopify theme serve
```

### Deployment

1. Create a new theme in your Shopify store
2. Push the theme to your store:
```bash
shopify theme push
```

## Best Practices

- Keep section settings focused and relevant
- Use semantic HTML for better accessibility
- Follow Shopify's [theme requirements](https://shopify.dev/themes/store/requirements)
- Test thoroughly on different devices and browsers
- Optimize images for performance
- Use CSS custom properties for consistent styling

## Support

For support, please [create an issue](https://github.com/your-username/your-theme/issues) in the repository.

## License

This theme is licensed under the MIT License. See the LICENSE file for details. 