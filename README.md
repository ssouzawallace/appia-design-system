# AppiaCare — Design System

![AppiaCare logo](assets/logo.png)

A cross-platform design system for AppiaCare's mobile and web applications, built on [Material Design 3](https://m3.material.io) principles.

---

## Table of Contents

- [Overview](#overview)
- [Design Foundation](#design-foundation)
  - [Material Design 3](#material-design-3)
  - [Alternative Design Systems](#alternative-design-systems)
- [AppiaCare Design Specifications](#appiacare-design-specifications)
  - [Screen Examples](#screen-examples)
  - [Color Palette](#color-palette)
  - [Elevations](#elevations)
  - [Contrast](#contrast)
- [Developer Resources](#developer-resources)

---

## Overview

AppiaCare's design system provides a shared visual language and component library that ensures consistency across Android, iOS, and Web platforms. It is not tied to any single platform — it is a set of principles and reusable patterns.

---

## Design Foundation

### Material Design 3

AppiaCare is built on [Material Design 3](https://m3.material.io), Google's latest open-source design system. Material 3 enables personal, adaptive, and expressive experiences through dynamic color, enhanced accessibility, and design tokens. Components are designed to work across Android, iOS, and Web.

### Alternative Design Systems

The following design systems were evaluated during the creation of AppiaCare's system and serve as complementary references:

#### Microsoft Fluent 2 Design System

[Fluent 2](https://www.microsoft.com/design/fluent/) brings principled design, technology innovation, and customer needs together into a shared, open design system across platforms.

#### Apple Human Interface Guidelines

Apple's [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines) provide unified design guidance across all Apple platforms (iOS, macOS, watchOS, tvOS, visionOS). The [design principles](https://developer.apple.com/design/human-interface-guidelines/design-principles) emphasize:

- **Familiarity** — People should feel at home in your app, with intuitive interactions that match their expectations from the platform.
- **Consistency** — A coherent visual language and predictable behavior help people understand and trust your app.
- **Direct Manipulation** — Fluid motion and responsive interfaces help people interact with content naturally.

---

## AppiaCare Design Specifications

Full design specifications are available in [Figma](https://www.figma.com/file/VGyJJPy7HHfHLGCe1BZ90e/Appia-Design-System).

Key benefits of using the design system:

- **Consistency** — Uniform appearance and behavior across all platforms.
- **Efficiency** — Reusable components reduce development time and effort.
- **Accessibility** — Tested contrast ratios and readable typography ensure usability for all users.

### Screen Examples

![Login screen from the AppiaCare patient app](assets/mobile-login-screen.png)

### Color Palette

![AppiaCare color palette](assets/palette.png)

### Elevations

![AppiaCare Material elevation levels](assets/elevations.png)

### Contrast

Contrast is used to establish visual hierarchy and guide user attention. Examples include:

| Contrast Type | Purpose |
|---|---|
| Dark / Light | Background and surface differentiation |
| Bold / Regular | Typographic emphasis |
| Urgent / Not Urgent | Priority signaling |
| Primary / Secondary Actions | Action hierarchy in UI |

![AppiaCare contrast examples](assets/contrast.png)

---

## Developer Resources

Platform-specific implementation guides for Material Design 3 components:

| Platform | Documentation | Status |
|---|---|---|
| Android (Jetpack Compose) | [m3.material.io/develop](https://m3.material.io/develop) | Recommended |
| Flutter | [m3.material.io/develop](https://m3.material.io/develop) | Active |
| Web | [m3.material.io/develop](https://m3.material.io/develop) | Maintenance mode |

> **Note:** Google's recommended path for Android is now Jetpack Compose. The older MDC-Android (Views) library is in maintenance mode. For multi-platform apps, Flutter has active Material 3 support. The official Material Web library is also in maintenance mode — community alternatives like [Lit Material](https://github.com/bohdaq/lit-material) are actively developed.
