# Portfolio Website

## Overview

This is a personal portfolio website built with vanilla HTML, CSS, and JavaScript. It's designed as a single-page application (SPA) that showcases personal information, skills, projects, and contact details. The website features a modern, responsive design with dark/light theme switching capabilities and smooth navigation between sections.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single-Page Application (SPA)**: All content is contained within a single HTML file with JavaScript-driven navigation
- **Component-Based Sections**: Modular section design (Home, About, Skills, Projects, Contact) for easy maintenance
- **Mobile-First Responsive Design**: CSS Grid and Flexbox layout system that adapts to different screen sizes
- **Progressive Enhancement**: Core functionality works without JavaScript, with enhanced features layered on top

### Styling Architecture
- **CSS Custom Properties (Variables)**: Centralized theme management using CSS variables for consistent design tokens
- **Dual Theme System**: Light and dark theme support with automatic persistence via localStorage
- **Component-Scoped Styles**: CSS organized by component/section for maintainability
- **External Font Integration**: Google Fonts (Inter) and Font Awesome icons for typography and iconography

### JavaScript Architecture
- **Vanilla JavaScript**: No framework dependencies for lightweight performance
- **Module Pattern**: Organized into logical functions for theme management, navigation, and user interactions
- **Event-Driven**: DOM event listeners handle user interactions like navigation clicks and theme toggling
- **Local Storage Integration**: Theme preferences persist across browser sessions

### Navigation System
- **Smooth Scrolling**: JavaScript-enhanced navigation between page sections
- **Mobile Hamburger Menu**: Responsive navigation that collapses on smaller screens
- **Fixed Header**: Persistent navigation bar with offset calculations for smooth scrolling

### User Experience Features
- **Theme Persistence**: User theme preference saved and restored automatically
- **Accessible Navigation**: Keyboard and screen reader friendly navigation patterns
- **Contact Form Integration**: Ready for backend contact form processing
- **Skill Progress Visualization**: Animated progress bars for skills display

## External Dependencies

### Content Delivery Networks (CDNs)
- **Google Fonts**: Inter font family for modern typography
- **Font Awesome 6.0.0**: Icon library for UI elements and visual enhancement

### Browser APIs
- **Local Storage API**: For persisting user theme preferences
- **DOM API**: For dynamic content manipulation and event handling
- **CSS Custom Properties**: For theme switching and design token management

### Potential Backend Integration Points
- **Contact Form**: Ready for email service integration (e.g., EmailJS, Formspree, or custom backend)
- **Analytics**: Prepared for Google Analytics or similar tracking service integration
- **Content Management**: Structure supports headless CMS integration for dynamic content updates