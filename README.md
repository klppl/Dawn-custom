# Dawn

## Custom Version

This is my customized version of the original Dawn theme with enhanced flexibility and personalization features:

- **Flexible About Section**: Create a `frontpage-about` page for rich homepage content, with automatic fallback to site description
- **Publication Icon Controls**: Toggle visibility and choose alignment (left/center/right) for your avatar/icon
- **Text Alignment Options**: Control how your about content is aligned independently from the icon
- **Custom Footer**: Personalized footer message replacing default Ghost branding
- **Typography Controls**: Customizable font sizes for feed titles, featured posts, and single post titles
- **Icon Shape Options**: Choose from 5 different shapes (square, circle, rounded square, diamond, hexagon)
- **20 Posts Per Page**: Increased from default 5 for more content visibility

Based on the original Dawn theme but redesigned for complete homepage customization through Ghost Admin settings.

# Changelog

## v1.0.3
- **Flexible About Section**: Page-based approach using `frontpage-about` slug with automatic fallback
- **Publication Icon Controls**: Toggle visibility and alignment (left/center/right)
- **Text Alignment**: Independent control for about content alignment
- **Optimized Spacing**: Reduced gaps between sections for better visual flow

## v1.0.2
- **Custom Footer**: Replaced copyright and Ghost branding with personalized message
- **Centered Footer**: Perfect positioning and subtle typography styling

## v1.0.1
- **Typography Controls**: Font size options for feed titles, featured posts, and single post titles
- **Icon Shape Options**: 5 shape choices (square, circle, rounded square, diamond, hexagon)
- **Mobile Responsive**: Auto-scaling for large font sizes on mobile devices
- **20 Posts Per Page**: Increased from default 5 posts

---

A highly functional [Ghost](https://github.com/TryGhost/Ghost) theme that adapts to the reader's preferences. Let them read, search, subscribe, navigate, and more with ease.

**Demo: https://dawn.ghost.io**

# Instructions

1. [Download this theme](https://github.com/TryGhost/Dawn/archive/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/dawn.zip`, which you can then upload to your site.

```bash
yarn zip
```

# Contribution

This repo is synced automatically with [TryGhost/Themes](https://github.com/TryGhost/Themes) monorepo. If you're looking to contribute or raise an issue, head over to the main repository [TryGhost/Themes](https://github.com/TryGhost/Themes) where our official themes are developed.

# Copyright & License

Copyright (c) 2013-2025 Ghost Foundation - Released under the [MIT license](LICENSE).
