# Developer-PM Collaboration Guidelines

This guide focuses on establishing effective collaboration between developers and product managers, ensuring prototype code can be seamlessly transformed into production-ready implementations.

## Shared Understanding

### Establishing Common Ground
- **Agree on prototype goals** and limitations upfront
- **Define what "production-ready" means** for your team
- **Establish a shared technical vocabulary**
- **Document coding standards** for both prototypes and production code

### Setting Expectations
- **PM-created code is valuable but will need refinement**
- **Prototypes demonstrate functionality, not final implementation**
- **Developers will refactor while maintaining core functionality**
- **Some components may be reused directly, others reimplemented**

## Collaboration Workflow

### Phase 1: Prototype Planning
1. **PMs define prototype scope** and functionality
2. **Developers provide technical guidance** on approach
3. **Together identify potential reusable components**
4. **Set up shared repository/project** structure

### Phase 2: Prototype Development
1. **PMs create functional prototype** using the guidelines
2. **Regular check-ins with developers** for technical guidance
3. **Developers provide feedback** on implementation approach
4. **PMs document decisions and limitations**

### Phase 3: Handover
1. **PMs complete documentation** of prototype
2. **Walkthrough session** between PM and developers
3. **Identify components for direct reuse** vs reimplementation
4. **Developers provide initial assessment** of technical debt

### Phase 4: Production Implementation
1. **Developers refine reusable components**
2. **Implement production-grade versions** of prototype features
3. **Regular reviews with PMs** to ensure functionality maintained
4. **Document improvements and changes** from prototype

## Effective Communication Techniques

### Code Reviews
- **PMs request AI-assisted code reviews** before handover
- **Developers provide constructive feedback** focusing on patterns
- **Use code comments to explain rationale**, not just implementation
- **Maintain a teaching mindset** to build shared understanding

### Documentation Standards
- **README.md** explaining purpose and functionality
- **Component documentation** describing inputs, outputs, and behavior
- **Known limitations** documented clearly
- **Future improvement ideas** captured

### Regular Sync Meetings
- **Review prototype progress** together
- **Address technical questions** early
- **Identify potential roadblocks** or complex areas
- **Maintain shared understanding** of project goals

## Developing Better Together

### Shared Prompt Library
- **Create a team prompt library** for common patterns
- **Document successful prompts** that generate good code
- **Standardize approach to component creation**
- **Share techniques that produce reusable code**

Example:
```
# Component creation prompt template
Create a [framework] component for [purpose] that handles [functionality].
Follow these standards:
- Use TypeScript with proper interfaces
- Follow our [naming convention] for classes and variables
- Include error states and loading indicators
- Add accessibility attributes
- Separate business logic from presentation
```

### Collaborative Debugging
- **Use Cursor or any AI-based IDE to explain complex code** segments
- **Generate documentation together**
- **Create test cases collaboratively**
- **Troubleshoot issues in real-time**

## Reusable Code Patterns

### What Makes Code Reusable
- **Clean separation of concerns**
- **Clear interfaces and typing**
- **Limited external dependencies**
- **Consistent error handling**
- **Good documentation**

### Patterns to Encourage
- **Service/API abstraction layers**
- **UI component libraries** with style guides
- **Utility functions** for common operations
- **Consistent state management** approaches

### Review Checklist for Handover
- ✅ Code follows agreed standards
- ✅ Documentation explains purpose and usage
- ✅ External dependencies are documented
- ✅ Known limitations are clearly stated
- ✅ Test cases or examples are provided
- ✅ Code is organized in logical structure

## Case Studies

### Example: E-commerce Feature Prototype to Production

#### PM Prototype Approach
```
I used Cursor to create a product recommendation component that:
- Displays similar products based on viewing history
- Shows pricing and availability
- Handles loading and error states
- Uses mock data in a format matching our API
```

#### Developer Production Approach
```
We were able to reuse:
- The component structure and UI elements
- The data transformation logic
- The loading/error state handling

We improved:
- Performance optimization for large product sets
- Integration with actual backend services
- Caching and state management
```

## Troubleshooting Common Issues

### Code Quality Gaps
- **Identify specific patterns** to improve, not general criticism
- **Create reusable snippets** for common patterns
- **Use AI to explain** why certain approaches are preferred

### Communication Breakdowns
- **Return to documented requirements** and goals
- **Use AI to explain technical concepts** to PMs
- **Have PMs explain business requirements** to developers

### Integration Challenges
- **Document specific integration points** during prototype phase
- **Create adapter patterns** to bridge prototype and production code
- **Maintain test cases** that verify same behavior in both versions

## Measuring Success

### Key Metrics
- **Development time saved** through code reuse
- **Reduced back-and-forth** on requirements clarification
- **Faster prototype-to-production** transition
- **Improved code quality** in initial implementations
- **Higher satisfaction** from both developers and PMs

### Continuous Improvement
- **Regular retrospectives** on collaboration process
- **Update guidelines** based on learnings
- **Share successful patterns** across teams
- **Document case studies** of effective collaboration 