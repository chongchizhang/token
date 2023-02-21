## What is design token
Design tokens are a methodology for expressing design decisions in a platform-agnostic way so that they can be shared across different disciplines, tools, and technologies. They help establish a common vocabulary across organisations. 

## Why do we need design token
There is a growing ecosystem of tools for design system maintainers and consumers that incorporate design token functionality, or would benefit from doing so:

- [Design tools](https://second-editors-draft.tr.designtokens.org/format/#dfn-design-tool) have begun allowing designers to label and reference shared values for design properties like colors and sizes.

- [Translation tools](https://second-editors-draft.tr.designtokens.org/format/#dfn-translation-tool) exist that can convert source design token data into platform-specific source code that can directly be used by developers.

- Documentation tools can display design token names rather than the raw values in design specs and style guides.

It is often desirable for design system teams to integrate such tools together, so that design token data can flow between design and development tools.

## How to use design token
- For designers
    - Basic: 
        1. Use Figma text style and color style
        2. Use Global Library components, which already contain design tokens
    - Advanced
        1. Download [Tokens Studio for Figma](https://www.figma.com/community/plugin/843461159747178978/Tokens-Studio-for-Figma-(Figma-Tokens))
        2. Visit Zoom Design System GitLab Token [repository](https://git.zoom.us/design/system/tokens)
        2. Follow [GitLab Sync steps on Tokens Studio Figma Docs](https://docs.tokens.studio/sync/gitlab)
- For developers
    - Visit [Zoom Artifacory on JFrog](https://artifacts.corp.zoom.us/ui/packages)
    - Search for "@zoom/design-token"
    - Install the design token npm package

Visit [Design Tokens WCG](https://tr.designtokens.org/format/) for detailed introduction