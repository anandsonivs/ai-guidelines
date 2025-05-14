# Effective Prompts

This quick reference guide provides practical, ready-to-use prompt templates for both developers and product managers working with any AI-based tool.

## For Developers

### Component Creation

```
Create a [Framework] component for [Purpose] that:
1. Takes these props: [list props with types]
2. Handles these states: [loading/error/success/etc.]
3. Follows these accessibility guidelines: [WCAG/ARIA/etc.]
4. Uses [styling approach]
5. Includes unit tests for key functionality

Also include:
- Error handling for edge cases
- Documentation for props and usage
- Performance considerations
```

### API Integration

```
Create a service module to interact with the [API Name] that:
1. Handles authentication using [auth method]
2. Provides functions for: [list key operations]
3. Implements proper error handling and retries
4. Uses [TypeScript/JSDoc] for type safety
5. Follows our project's error handling pattern

Include:
- Timeout handling
- Rate limiting consideration
- Logging for debugging
```

### Data Transformation

```
Create a utility function that transforms data from [source format] to [target format].

Source format example:
[JSON example]

Target format example:
[JSON example]

Requirements:
- Handle missing or null fields gracefully
- Validate output matches expected schema
- Include unit tests for edge cases
- Document the transformation logic
```

### Performance Optimization

```
Review this code for performance issues:

[paste code]

Specifically look for:
1. Unnecessary re-renders
2. Expensive operations in loops
3. Memory leaks
4. Blocking operations
5. Unoptimized data structures

Then refactor it to address these issues while maintaining the same functionality.
```

### Testing Implementation

```
Create unit tests for this function using [Jest/Mocha/etc.]:

[paste function]

Include tests for:
1. Happy path with valid inputs
2. Edge cases (null, empty, invalid values)
3. Error handling scenarios
4. Any side effects that should occur
5. Performance considerations if applicable

Use mocks for external dependencies.
```

## For Product Managers

### Feature Prototype

```
Create a prototype for a [feature type] that:
1. Demonstrates the core user flow of [describe flow]
2. Uses [UI framework] components
3. Implements basic validation and error states
4. Uses mock data that resembles our actual data structure
5. Separates UI components from business logic

Focus on demonstrating functionality rather than perfect implementation.
```

### Data Visualization

```
Create a prototype data visualization component that:
1. Displays [data type] in a [chart type]
2. Handles loading, empty, and error states
3. Includes basic filtering capabilities
4. Uses mock data resembling our actual structure
5. Follows basic accessibility guidelines

The visualization should demonstrate [key insight] from the data.
```

### Form Implementation

```
Create a reusable form component for [purpose] that:
1. Collects these fields: [list fields with types]
2. Validates input according to these rules: [list rules]
3. Handles submission with loading state
4. Displays appropriate error messages
5. Uses [UI framework] components

Make it configurable so it can be adapted for similar forms later.
```

### API Mock and Usage

```
Create a mock API service for [feature] that:
1. Simulates these endpoints: [list endpoints]
2. Returns realistic mock data
3. Includes simulated delays and occasional errors
4. Provides documentation of the API contract
5. Can be easily replaced with real API calls later

Include examples of how components would use this service.
```

### User Authentication Flow

```
Create a prototype authentication flow that:
1. Demonstrates [login/signup/password reset] screens
2. Shows the user journey from unauthenticated to authenticated
3. Handles basic validation and error states
4. Uses mock authentication service
5. Follows standard security practices

Focus on the user experience rather than actual authentication implementation.
```

## Collaboration Prompts

### Code Review

```
Review this code from a prototype and suggest improvements:

[paste code]

Specifically looking for:
1. Opportunities for better code organization
2. Reusable patterns that could be extracted
3. Potential performance or maintainability issues
4. Improvements for developer experience
5. Documentation needs
```

### Prototype-to-Production Planning

```
Given this prototype implementation of [feature]:

[paste prototype code]

Outline a plan for transforming it into production code, including:
1. Components that can be reused directly
2. Parts that need complete reimplementation
3. Additional considerations for production (security, performance, etc.)
4. Testing strategy
5. Integration points with existing systems
```

### Technical Documentation

```
Generate documentation for this [component/feature]:

[paste code or description]

Include:
1. Purpose and functionality overview
2. Usage examples
3. Props/parameters/configuration options
4. Known limitations
5. Future improvement opportunities
```

## Troubleshooting Prompts

### Bug Analysis

```
Analyze this code for potential bugs:

[paste code]

Error/unexpected behavior: [describe issue]

Provide:
1. Likely cause of the issue
2. Step-by-step debugging approach
3. Potential fix
4. How to prevent similar issues
```

### Performance Issue

```
This code is experiencing performance issues:

[paste code]

Symptoms: [describe performance problem]

Analyze potential causes and suggest optimizations that maintain the same functionality.
```

### Integration Problem

```
I'm having trouble integrating this prototype code:

[paste prototype code]

With this existing system:

[paste existing code or description]

Specifically: [describe integration challenge]

Suggest an approach to bridge these implementations.
```

## Tips for Better Results

1. **Be specific about standards** - Mention coding standards, patterns, and conventions
2. **Provide examples** - Show examples of desired output format or style
3. **Include context** - Briefly explain the wider system or requirements
4. **Specify constraints** - Mention performance needs, browser support, etc.
5. **Request documentation** - Always ask for comments or docs for complex code

Remember to save successful prompts that produce good results for future reuse! 