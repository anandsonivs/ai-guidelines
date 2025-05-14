# Quick Reference: Legal Compliance Platform Prompts

This quick reference guide provides practical, ready-to-use prompt templates specifically for building a legal compliance platform for individuals and MSMEs in India.

## For Developers

### Compliance Form Components

```
Create a React component for a [compliance type] form that:
1. Collects required information for [specific compliance]
2. Validates inputs according to [regulatory body] guidelines
3. Handles document uploads with proper validation
4. Shows progress through multi-step process
5. Implements proper error handling and validation messages

Requirements:
- Follow accessibility guidelines (WCAG 2.1)
- Support both English and Hindi languages
- Handle offline data persistence
- Include proper form validation with regulatory rules
- Add clear error messages for each validation failure
```

### Document Processing Service

```
Create a service module for processing [document type] that:
1. Validates document format and content
2. Extracts relevant information using OCR
3. Performs regulatory compliance checks
4. Stores processed data securely
5. Generates compliance reports

Include:
- Error handling for invalid documents
- Logging for audit trails
- Data encryption for sensitive information
- Rate limiting for API calls
- Proper error messages for users
```

### Compliance Status Dashboard

```
Create a dashboard component that:
1. Shows compliance status for different regulations
2. Displays upcoming deadlines and requirements
3. Provides status indicators for each compliance item
4. Includes filtering by compliance type and status
5. Shows historical compliance data

Requirements:
- Real-time updates for status changes
- Export functionality for reports
- Mobile-responsive design
- Accessibility compliance
- Performance optimization for large datasets
```

### Payment Integration

```
Create a payment processing module that:
1. Handles multiple payment methods (UPI, cards, net banking)
2. Generates proper invoices with GST details
3. Processes refunds according to compliance rules
4. Maintains payment history and receipts
5. Integrates with accounting systems

Include:
- Proper error handling for failed transactions
- Secure storage of payment information
- Compliance with RBI guidelines
- Audit logging for all transactions
- Support for different tax regimes
```

### Notification System

```
Create a notification service that:
1. Sends reminders for upcoming compliance deadlines
2. Alerts users about document expiry
3. Notifies about regulatory updates
4. Handles multiple notification channels (email, SMS, in-app)
5. Manages notification preferences

Requirements:
- Rate limiting to prevent spam
- Support for multiple languages
- Template management for different notification types
- Delivery status tracking
- Compliance with telecom regulations
```

## For Product Managers

### Compliance Workflow Prototype

```
Create a prototype for [compliance type] workflow that:
1. Demonstrates the complete user journey from start to completion
2. Shows all required documents and information
3. Includes validation steps and error handling
4. Demonstrates payment and document submission flow
5. Shows status tracking and updates

Technical Requirements:
- Use TypeScript with proper interfaces for all data structures
- Follow our project's component architecture pattern
- Implement proper state management (Redux/Context)
- Use our shared UI component library
- Follow our established folder structure
- Include proper error boundaries
- Implement loading states and skeleton screens
- Add proper TypeScript types for all props and state
- Use our standard API service pattern
- Include proper logging and error tracking

Focus on:
- User experience for non-technical users
- Clear guidance at each step
- Handling of common edge cases
- Integration points with existing systems
- Mobile responsiveness
- Code reusability for future compliance types
- Performance considerations
- Accessibility compliance
- Internationalization support
- Offline capabilities

Documentation Requirements:
- Add JSDoc comments for all components and functions
- Document all props and their types
- Include usage examples
- Document integration points
- List all dependencies and their versions
- Document known limitations
- Include testing instructions
```

### Document Verification Flow

```
Create a prototype for document verification that:
1. Shows document upload and validation process
2. Demonstrates OCR and data extraction
3. Includes manual verification steps
4. Shows approval/rejection flows
5. Handles document expiry and renewal

Technical Requirements:
- Use our standard file upload component
- Implement proper file type validation
- Use our shared validation utilities
- Follow our error handling patterns
- Implement proper loading states
- Use our standard API error handling
- Include proper TypeScript types
- Use our shared UI components
- Implement proper state management
- Follow our established folder structure

Code Structure:
- Separate business logic from UI components
- Create reusable utility functions
- Use proper dependency injection
- Implement proper error boundaries
- Use our standard logging pattern
- Follow our testing patterns
- Use our shared constants
- Implement proper caching strategy

Focus on:
- Clear user feedback at each step
- Support for multiple document types
- Error handling for invalid documents
- Progress tracking
- Integration with verification services
- Code reusability for other document types
- Performance optimization
- Security considerations
- Audit trail requirements
- Data persistence strategy
```

### Compliance Calendar

```
Create a prototype for a compliance calendar that:
1. Shows upcoming deadlines for different compliances
2. Allows filtering by compliance type and status
3. Includes reminder settings
4. Shows historical compliance data
5. Provides export functionality

Technical Requirements:
- Use our shared calendar component
- Implement proper date handling
- Use our standard filtering components
- Follow our data fetching patterns
- Implement proper caching
- Use our shared UI components
- Include proper TypeScript types
- Follow our state management pattern
- Use our standard API service
- Implement proper error handling

Code Organization:
- Create reusable filter components
- Implement proper data transformation
- Use our shared utility functions
- Follow our component composition pattern
- Implement proper loading states
- Use our standard error boundaries
- Follow our testing patterns
- Use our shared constants
- Implement proper logging
- Follow our performance patterns

Focus on:
- Clear visualization of deadlines
- Easy navigation between different views
- Mobile-friendly interface
- Integration with notification system
- Export options for reports
- Code reusability for other calendar views
- Performance with large datasets
- Accessibility compliance
- Offline capabilities
- Real-time updates
```

### API Integration Prototype

```
Create a prototype for integrating with [external service] that:
1. Demonstrates authentication flow
2. Shows data fetching and caching
3. Implements error handling
4. Demonstrates rate limiting
5. Shows data transformation

Technical Requirements:
- Use our standard API service pattern
- Implement proper error handling
- Use our shared authentication utilities
- Follow our caching strategy
- Implement proper logging
- Use our standard retry mechanism
- Include proper TypeScript types
- Use our shared constants
- Follow our testing patterns
- Implement proper monitoring

Code Structure:
- Create reusable API hooks
- Implement proper data transformation
- Use our shared utility functions
- Follow our error handling patterns
- Implement proper loading states
- Use our standard error boundaries
- Follow our testing patterns
- Use our shared constants
- Implement proper logging
- Follow our performance patterns

Focus on:
- Clean separation of concerns
- Code reusability for other APIs
- Performance optimization
- Error handling
- Security considerations
- Rate limiting
- Caching strategy
- Monitoring requirements
- Documentation needs
- Testing approach
```

### Form Builder Prototype

```
Specifically check for:
1. Regulatory compliance requirements
2. Data security and privacy measures
3. Error handling for edge cases
4. Accessibility compliance
5. Performance considerations
6. Integration with existing systems
```

### Document Processing Review

```
Review this document processing implementation:

[paste code]

Check for:
1. Proper validation of document formats
2. Security of sensitive information
3. Error handling for invalid documents
4. Performance with large files
5. Integration with verification services
6. Audit trail requirements
```

### Payment System Review

```
Review this payment processing code:

[paste code]

Verify:
1. Compliance with RBI guidelines
2. Security of payment information
3. Proper error handling
4. Integration with accounting systems
5. Support for different payment methods
6. Audit logging requirements
```

## Troubleshooting Prompts

### Compliance Validation Issue

```
This compliance validation is failing:

[paste code]

Error: [describe issue]

Analyze:
1. Regulatory requirements being violated
2. Data validation issues
3. Integration problems
4. User input handling
5. Error reporting
```

### Document Processing Error

```
Document processing is failing:

[paste code]

Issue: [describe problem]

Check:
1. Document format validation
2. OCR processing
3. Data extraction
4. Storage issues
5. Integration problems
```

### Payment Processing Problem

```
Payment processing is failing:

[paste code]

Error: [describe issue]

Verify:
1. Payment gateway integration
2. Transaction validation
3. Error handling
4. Security measures
5. Compliance requirements
```

## Tips for Better Results

1. **Specify regulatory requirements** - Mention specific laws and guidelines
2. **Include language requirements** - Specify support for English and Hindi
3. **Consider Indian context** - Account for local business practices
4. **Address security concerns** - Focus on data protection
5. **Include compliance checks** - Ensure regulatory adherence
6. **Consider scalability** - Plan for growing user base
7. **Document everything** - Maintain audit trails
8. **Test thoroughly** - Verify all compliance scenarios

Remember to:
- Keep up with regulatory updates
- Document all compliance requirements
- Test with real-world scenarios
- Consider offline capabilities
- Plan for audit requirements 