# WPF Ribbon Simplified Layout – Customization Demo
This sample demonstrates how to build an Office-like Simplified Ribbon experience in a WPF application using the Syncfusion WPF Ribbon control. It shows how to switch between classic and simplified layouts, customize which items appear in the compact view, control item priority and resizing, and preserve the user’s preferred layout between sessions. The goal is to deliver a clean, space-efficient command surface similar to Microsoft Office’s simplified ribbon.

## Features
- Toggle between classic and simplified ribbon layouts
- Compact command presentation with automatic scaling and overflow handling
- Per-group simplified item customization (show/hide, order, and priority)
- Support for common ribbon constructs: tabs, groups, launchers, and split/dropdown buttons
- Quick Access Toolbar (QAT) with optional show-above/below ribbon
- Backstage support for application-level commands
- Keyboard navigation with KeyTips and ScreenTips
- Theme support and style customization to match application branding
- Layout persistence so users return to their preferred mode

## Getting Started
1. Create a new WPF project in Visual Studio (e.g., SimplifiedRibbonDemo).
2. Install the NuGet package: Syncfusion Ribbon for WPF (search for the Syncfusion WPF Ribbon package in NuGet).
3. Add the Syncfusion XML namespace in XAML:
   - xmlns:syncfusion="http://schemas.syncfusion.com/wpf"
4. Add the Ribbon to your Window/Page and define tabs and groups.
5. Enable the simplified layout and configure how items appear in simplified mode.
6. Apply a theme using the Syncfusion theme APIs to match your application.

## Usage Tips
- Provide a clear toggle (button or built-in toggle) to switch between classic and simplified layouts.
- Prioritize the most important commands for simplified mode; move secondary commands to overflow menus.
- Use split and dropdown buttons to consolidate related actions in compact space.
- Keep labels concise in simplified mode; rely on tooltips for clarity.
- Persist the user’s last-selected layout (classic/simplified) and restore it at startup.
- Test with different window sizes and DPI settings to ensure commands scale well.

## About the Sample
This sample provides a focused starting point for adopting the Simplified Ribbon layout in WPF. It demonstrates tabs, groups, primary/secondary command placement, and how to tune the compact presentation without sacrificing usability. Extend it by adding your own commands, data bindings, themes, and persistence logic to deliver a familiar and efficient command surface in your application.
