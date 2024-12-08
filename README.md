# ShareNote Frontend

## Introduction
ShareNote's frontend is a modern, responsive web application built with Angular and Tailwind CSS. It provides an intuitive interface for students to share and discover study notes, manage their profiles, and interact with other users.

## Features
- User profile management and customization
- Note upload and management interface
- Dark/light theme support
- Responsive design for all devices
- File preview and download capabilities
- Advanced search and filtering options
- Social features (likes, follows, downloads)

## Technology Stack
- Angular 17
- Tailwind CSS
- TypeScript
- Angular CLI
- RxJS

## Project Overview
The frontend follows Angular's recommended project structure with dedicated folders for components, services, and shared utilities. Key areas include:
- Core components for note management and user profiles
- Shared services for API communication
- Responsive navigation system
- Dark mode implementation
- File handling utilities

## Getting Started

### Prerequisites
- Node.js (Latest LTS version)
- npm package manager
- Angular CLI (`npm install -g @angular/cli`)

### Local Development Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd share-note-frontend
```

2. Install dependencies:
```bash
npm install
```


3. Start the development server:
```bash
ng serve
```

Navigate to http://localhost:4200/. The application will automatically reload if you change any of the source files.

## Development Commands
### Create New Components
```bash
ng generate component component-name
```

You can also generate other Angular artifacts:
```bash
ng generate directive|pipe|service|class|guard|interface|enum|module
```

### Build
```bash
ng build
```

The build artifacts will be stored in the dist/ directory.

## Key Components

### User Interface
- Navigation bar with theme switching
- Home page with featured notes
- Profile management interface
- Note creation and editing tools
- Search and filter components

### Services
- API communication
- Authentication
- File handling
- State management
- Theme service

## Styling
The project uses Tailwind CSS for styling, providing:
- Consistent design system
- Responsive layouts
- Dark/light theme support
- Custom utility classes

## Development Guidelines

### Component Structure
- Standalone components where possible
- Clear separation of concerns
- Reactive forms for user input
- Proper type definitions

### State Management
- Service-based state management
- Reactive patterns using RxJS
- Local storage integration
- Efficient cache handling

## Further Help
- [Angular Documentation](https://angular.io/docs)
- [Angular CLI Documentation](https://angular.io/cli)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [RxJS Documentation](https://rxjs.dev/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Angular Material Components](https://material.angular.io/components/categories)


