# Softwise Design System

A modern, minimalist design system built with Token Studio for scalable UI development.

![Design System](https://img.shields.io/badge/Design%20System-v1.0-success)
![Token Studio](https://img.shields.io/badge/Token%20Studio-Pro-blue)
![Figma](https://img.shields.io/badge/Figma-Variables-orange)

## 🎨 Overview

The Softwise Design System is a comprehensive token-based design system that enables consistent, accessible, and scalable user interface development. Built with modern minimalist principles and Token Studio's powerful token management capabilities.

### Key Features

- **🌿 Natural Color Palette** - Soft Sage primary colors with semantic token structure
- **📱 Responsive Typography** - Satoshi & Manrope font pairing with fluid scales
- **🌓 Light/Dark Themes** - Automatic theme switching with Figma Variables
- **🎯 Modern Components** - 8+ UI components with interaction states
- **♿ Accessibility First** - WCAG compliant contrast ratios and focus states
- **🔧 Developer Ready** - Token Studio integration for seamless handoff

## 🏗️ System Architecture

### Token Hierarchy

```
📁 Global Tokens
├── 🎨 Colors (Primary, Neutral, Semantic)
├── 📏 Dimensions (Spacing, Sizing, Border Radius)
├── 🔤 Typography (Satoshi, Manrope)
└── ✨ Effects (Shadows, Opacity)

📁 Alias Tokens
├── 🎨 Semantic Colors (Brand, Purpose, Background, Text, State)
├── 📐 Border System (Width, Radius, Style)
├── 📝 Typography Scale (Display, Headlines, Body, Labels)
└── 🌟 Effect System (Elevation, States)

📁 Component Tokens
├── 🔘 Buttons (Primary, Secondary, States)
├── 📝 Inputs (Text, Focus, Error, Disabled)
├── 🎴 Cards (Default, Hover, Interactive)
├── 🧭 Navigation (Header, Menu Items)
├── 📋 Modals (Container, Backdrop, Header)
├── 🔔 Alerts (Info, Success, Warning, Error)
└── 🏷️ Badges (Default, Primary, Success)
```

## 🎨 Color System

### Primary Colors (Sage Palette)
- **Primary 50**: `#F6F9F5` - Lightest background tints
- **Primary 400**: `#ABC8A2` - Brand color (original)
- **Primary 600**: `#6D9A63` - Interactive elements
- **Primary 900**: `#3A5136` - Text on light backgrounds

### Semantic Colors
- **Success**: Green spectrum for positive feedback
- **Warning**: Orange spectrum for caution states
- **Critical**: Red spectrum for error states
- **Info**: Blue spectrum for informational content

## 📝 Typography

### Font Families
- **Display**: Satoshi (Headlines, Large Text)
- **Content**: Manrope (Body, UI Elements)

### Type Scale
```
Display 1    | Satoshi Black  64px  | Hero headlines
Display 2    | Satoshi Bold   56px  | Section heroes
Headline 1   | Satoshi Bold   48px  | Main sections
Headline 2   | Satoshi Bold   40px  | Sub-sections
Headline 3   | Satoshi Medium 32px  | Article titles
Headline 4   | Satoshi Medium 28px  | Card headers
Headline 5   | Satoshi Regular 24px | Small headers
Body Long    | Manrope Regular 16px | Paragraphs
Body Short   | Manrope Regular 16px | Short content
Body Small   | Manrope Regular 14px | Captions
Label Short  | Manrope SemiBold 18px | Form labels
Label Long   | Manrope Medium 16px  | Extended labels
```

## 🌟 Effects & Elevation

### Shadow System
- **Surface**: `xs` - Subtle elevation for basic cards  
- **Card**: `sm` - Standard card elevation  
- **Button**: `sm` - Interactive element elevation
- **Dropdown**: `md` - Menu and dropdown elevation
- **Modal**: `lg` - Dialog and overlay elevation
- **Toast**: `lg` - Notification elevation
- **Floating**: `xl` - Major floating panels
- **Hero**: `2xl` - Hero sections and major layouts

### Interaction States
- **Hover**: Enhanced shadow for interactive feedback
- **Focus**: Accessibility-optimized focus rings
- **Active**: Reduced shadow for pressed states

## 🔧 Component Library

### Buttons
- **Primary**: Sage background with white text
- **Secondary**: Outlined with sage border
- **States**: Default, Hover, Active, Disabled

### Input Fields
- **Text Inputs**: Default, Focus, Error, Disabled states
- **Focus Enhancement**: Thicker borders and shadow rings
- **Error Handling**: Critical color borders with validation

### Cards
- **Default**: Subtle elevation with rounded corners
- **Hover**: Enhanced shadow and border
- **Interactive**: Primary border for selectable cards

### Navigation
- **Header**: Clean layout with subtle shadow
- **Menu Items**: Transparent to primary background states
- **Active State**: Primary background with white text

### Modals
- **Backdrop**: Semi-transparent overlay
- **Container**: High elevation with generous padding
- **Modern Radius**: Larger border radius for contemporary feel

### Alerts
- **4 Types**: Info, Success, Warning, Error
- **Semantic Colors**: Purpose-driven color system
- **Consistent Layout**: Unified padding and typography

### Badges
- **Pill Shape**: Full border radius for modern appearance
- **Compact Design**: Minimal padding for space efficiency
- **Semantic Variants**: Default, Primary, Success

## �� Theme System

### Light Theme (`softwise-colors/light`)
- **Background**: Near-white neutrals
- **Text**: Dark neutrals for high contrast
- **Primary**: Darker sage tones for interaction

### Dark Theme (`softwise-colors/dark`)
- **Background**: Near-black neutrals
- **Text**: Light neutrals for readability
- **Primary**: Lighter sage tones for visibility

## 🚀 Getting Started

### For Designers

1. **Install Token Studio Plugin** in Figma
2. **Import Token Sets** from this repository
3. **Configure Themes** (Light/Dark)
4. **Export to Figma** as Variables and Styles
5. **Build Components** using the token system

### For Developers

1. **Clone Repository**
   ```bash
   git clone [repository-url]
   cd softwise-design-system
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Transform Tokens**
   ```bash
   npm run build-tokens
   ```

## 📁 Repository Structure

```
softwise-design-system/
├── tokens/
│   ├── global/          # Global token definitions
│   ├── alias/           # Semantic aliases
│   ├── components/      # Component tokens
│   └── themes/          # Theme configurations
├── build/               # Generated token files
├── docs/                # Documentation
└── examples/            # Implementation examples
```

## 🛠️ Development Workflow

1. **Token Creation** - Define new tokens in Token Studio
2. **Theme Testing** - Verify light/dark theme compatibility
3. **Figma Export** - Update Variables and Styles
4. **Component Building** - Create UI components in Figma
5. **Developer Handoff** - Export tokens for code implementation

## 📊 Token Statistics

- **Global Tokens**: 150+ foundational values
- **Alias Tokens**: 200+ semantic references
- **Component Tokens**: 100+ UI-specific definitions
- **Total System**: 450+ design decisions managed

## 🎯 Design Principles

### Minimalism
- **Generous White Space** - Increased padding for breathing room
- **Subtle Elevations** - Refined shadow system
- **Clean Typography** - Clear hierarchy with modern fonts

### Accessibility
- **WCAG AA Compliance** - High contrast color combinations
- **Focus Management** - Visible focus states for all interactions
- **Touch Targets** - Minimum 44px touch areas

### Scalability
- **Token-Based** - Single source of truth for all design decisions
- **Theme-Ready** - Seamless light/dark mode switching
- **Component-Driven** - Reusable patterns for consistency

## 🔄 Version History

### v1.0.0 (Current)
- Initial release with complete token system
- 8 component categories implemented
- Light/Dark theme support
- Figma Variables integration

## 🤝 Contributing

1. **Fork** the repository
2. **Create** feature branch (`git checkout -b feature/amazing-component`)
3. **Test** tokens in Token Studio
4. **Commit** changes (`git commit -m 'Add amazing component'`)
5. **Push** to branch (`git push origin feature/amazing-component`)
6. **Create** Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🙏 Acknowledgments

- **Token Studio** for powerful design token management
- **Figma** for Variables and Styles support
- **Satoshi & Manrope** for beautiful typography
- **Design Community** for modern minimalist inspiration

---

**Built with ❤️ by the Softwise Team**

*"Design systems enable teams to build cohesive user experiences at scale."*
