# Development and Prompting Guidelines for Product Managers

## Introduction
AI can be a powerful tool for product managers to create functional prototypes without extensive coding experience. This guide will help you use any AI-based tool to create prototype code that developers can later refine and integrate into production systems.

## Creating Reusable Prototypes

### Prototype Planning
1. **Define the prototype scope** clearly
2. **Document requirements** for the prototype
3. **Identify integration points** with existing systems
4. **Set expectations** with the development team

### Creating a Developer-Friendly Foundation

#### Project Structure
- **Request a clean project structure** that follows standard conventions
- **Keep code organized** in logical folders (e.g., components, services, utils)
- **Use descriptive file names** that reflect functionality

Example prompt:
```
Create a basic React project structure for an e-commerce prototype with product listing and cart functionality. Include folders for components, services, and utilities. Use TypeScript.
```

#### Documentation
- **Add comments** that explain your intentions
- **Create a README.md** that explains the prototype's purpose and functionality
- **Document assumptions and limitations**

## Communication with Developers

### Alignment Strategies
- **Share prototype code** early and often
- **Request developer feedback** on approach
- **Document technical decisions** and their rationale
- **Establish handover expectations**

### Creating Handover Documentation
- **Document the prototype's purpose and functionality**
- **List all features and their implementation status**
- **Identify known issues or limitations**
- **Provide context on design decisions**

## Effective Prototyping Techniques

### User Interface Prototypes
- **Request common design patterns** that developers recognize
- **Use standard component libraries** when possible
- **Focus on functionality over perfection**

Example prompt:
```
Create a React component for a user profile page that displays user information, settings, and activity history. Use Material-UI components and follow standard React patterns for state management.
```

### Data Handling
- **Use consistent data structures**
- **Request proper data validation**
- **Implement simple error handling**

Example prompt:
```
Generate a function that fetches product data from a mock API and handles loading, error, and success states. Store the data in a format that would be compatible with our existing systems.
```

### State Management
- **Use simple, understandable state management**
- **Document the data flow** in your prototype
- **Keep business logic separate** from UI components

## Writing Reusable Code

### Modularity
- **Request modular components** with clear responsibilities
- **Avoid hardcoding values** that might change
- **Use configuration objects** for customization

### Code Reusability
- **Separate business logic** from presentation
- **Create utility functions** for common operations
- **Use consistent naming conventions**

Example prompt:
```
Create a reusable form component that handles validation, submission, and error states. Make it configurable so we can use it for different types of forms throughout the application.
```

### Developer-Friendly Patterns
- **Request standard coding patterns** familiar to developers
- **Use typed interfaces** (in TypeScript)
- **Follow separation of concerns**

## Advanced Topics

### API Interactions
- **Create simple API service layers**
- **Use mock data consistently**
- **Document API assumptions**

Example prompt:
```
Create a service layer for interacting with our product API. Include functions for fetching products, categories, and handling search. Use mock data for now but structure it so developers can easily replace it with real API calls.
```

### Authentication Flows
- **Implement simple authentication flows**
- **Document security considerations**
- **Separate authentication logic** from business logic

### Complex Interactions
- **Break down complex features** into smaller components
- **Focus on the happy path** first, then edge cases
- **Document interaction assumptions**

## Handover Best Practices

### Code Refinement
- **Review with AI before handover**
- **Request code cleanups** and organization
- **Remove unused code and comments**

Example prompt:
```
Review this prototype code for any inconsistencies, unused variables, or hard-to-understand patterns. Suggest improvements that would make it easier for developers to understand and integrate.
```

### Developer Briefing
- **Prepare to explain design decisions**
- **Highlight areas needing refinement**
- **Identify reusable vs disposable components**

## Prototype to Production Transition

### Expectation Setting
- **Understand that code will be refactored**
- **Focus on demonstrating functionality** over perfect code
- **Identify components that should remain in production**

### Technical Debt Documentation
- **Document known shortcuts taken**
- **Identify performance concerns**
- **Note areas that need security reviews**

## Best Practices Checklist
- ✅ Create a clear project structure
- ✅ Document your prototype thoroughly
- ✅ Use consistent naming and patterns
- ✅ Separate concerns (UI, logic, data)
- ✅ Communicate regularly with developers
- ✅ Focus on creating understandable, reusable code 