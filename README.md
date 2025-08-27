# LightDark

A Flutter app demonstrating runtime switching between Light and Dark themes using **Provider** for state management.

---

##  Features

- Toggle between Light and Dark Theme dynamically  
- Uses `Provider` to manage theme state  
- Applies theming across the entire app (backgrounds, buttons, etc.)  
- Clean and modular structure for easy understanding and customization

---

##  Project Structure

├── **components/**
│ ├── box.dart # A styled container widget
│ └── button.dart # Custom button widget used for toggling
├── **pages/**
│ └── home_page.dart # Main screen with theme toggle logic
├── **theme/**
│ └── theme_provider.dart # Contains ThemeProvider using ChangeNotifier
├── main.dart # App entry point with provider setup
