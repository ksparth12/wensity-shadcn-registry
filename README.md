# Wensity shadcn Registry

Public, free-only shadcn registry artifacts for Wensity components.

The private Wensity product repository is not mirrored here. This repo contains only generated JSON registry payloads for free components. Wensity Pro components remain available through the authenticated Wensity CLI.

## Usage

Until the `@wensity` namespace is accepted into shadcn's public registry index, add this registry to `components.json`:

```json
{
  "registries": {
    "@wensity": "https://raw.githubusercontent.com/ksparth12/wensity-shadcn-registry/main/{name}.json"
  }
}
```

Then install a free component:

```bash
npx shadcn@latest add @wensity/liquid-multimodal-input
```

After shadcn accepts the public registry index PR, the same command works without manual `components.json` configuration.

## Components

- `liquid-multimodal-input` - Liquid Multimodal Input
- `stream-reveal-typography` - Stream Reveal Typography
- `generative-skeleton-mesh` - Generative Skeleton Mesh
- `voice-aurora-wave` - Voice Aurora Wave
- `model-context-switcher` - Model Context Switcher
- `magnetic-prompt-suggestions` - Magnetic Prompt Suggestions
- `dynamic-island-toast` - Dynamic Island Toast
- `parallax-tilt-card-3d` - 3D Parallax Tilt Card
- `infinite-marquee` - Infinite Marquee
- `apple-sticky-scroll-sequence` - Apple-Style Sticky Scroll
- `morphing-shape-background` - Morphing Shape Background
- `scrubbable-video-reveal` - Scrubbable Video Reveal
- `page-transition-viewport` - Page Transition Viewport
- `interactive-beam-connections` - Interactive Beam Connections

## Source

Generated from Wensity's public shadcn endpoints:

- Registry index: https://wensity.com/r/registry.json
- Component payloads: https://wensity.com/r/<component>.json

## License

Free registry artifacts in this repo are MIT licensed. Wensity Pro components are not included.
