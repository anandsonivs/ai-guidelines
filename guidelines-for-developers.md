# Coding and Prompting Guidelines for Developers

## Introduction
AI is a powerful tech that can significantly boost your coding productivity. This guide will help you leverage any AI based IDE effectively to write production-grade code without requiring you to be an expert prompt engineer.

## Effective Prompting Techniques

### Writing Clear Prompts
- **Be specific and detailed** about what you want to accomplish
- **Include context** about your codebase, requirements, and constraints
- **Specify coding standards** you want the AI to follow

Example good prompt:
```
Create a React component for a product card that displays an image, title, price, and "Add to Cart" button. Use TypeScript with proper interfaces. Follow our project's BEM naming convention for CSS classes. The component should be responsive and accessible.
```

### Multi-Stage Development
1. **Start with architecture**: Ask for high-level design before implementation details
2. **Iterate on solutions**: Request improvements to generated code
3. **Request explanations**: Ask the AI to explain complex code it generates

## Production Code Quality Tips

### Code Quality
- **Request unit tests** alongside implementation
- **Ask for error handling** to make code robust
- **Request documentation** for complex functions

Example:
```
Add comprehensive error handling to this API call function. Include timeout handling, network error catching, and appropriate user feedback.
```

### Performance Optimization
- **Request performance reviews** of generated code
- **Ask for optimization suggestions**
- **Specify performance constraints** in your prompts

### Security Considerations
- **Explicitly request security best practices**
- **Ask for security reviews** of authentication or data handling code
- **Specify compliance requirements** (GDPR, HIPAA, etc.)

## Debugging and Refactoring

### Using AI for Debugging
- **Paste error messages** and stack traces
- **Show before/after state** when explaining bugs
- **Ask for step-by-step debugging approaches**

### Code Refactoring
- **Start with clear refactoring goals**
- **Show before/after examples** of similar refactoring
- **Request incremental changes** for large refactorings

## Integration with Development Workflow

### Version Control
- **Request commit message suggestions**
- **Ask for code review feedback**
- **Generate PR descriptions**

### Working with Team Standards
- **Share team coding standards** with the AI
- **Request code that follows specific patterns** used in your codebase
- **Ask for compatibility checks** with existing code

## Advanced Techniques

### Code Generation from Requirements
- **Share user stories or requirements** and ask for implementation
- **Include acceptance criteria** in your prompts
- **Request feature flags** for new functionality

### Working with External Libraries
- **Specify library versions** when requesting integration code
- **Ask for best practices** when using specific libraries
- **Request migration guidance** between library versions

## Collaborating with Product Managers
- **Understand prototype code** created by PMs
- **Request production-ready versions** of PM prototypes
- **Ask for optimizations** while maintaining the original functionality
- **Request proper integration** of prototype features into the architecture

## Troubleshooting
- **If the AI gives incorrect code**, provide feedback and request corrections
- **For complex tasks**, break them down into smaller, focused prompts
- **When stuck in a loop**, try rephrasing or providing examples

## Best Practices Checklist
- ✅ Include context about your project
- ✅ Specify coding standards and patterns
- ✅ Request tests and documentation
- ✅ Ask for error handling and edge cases
- ✅ Verify security and performance
- ✅ Iterate and refine generated code 