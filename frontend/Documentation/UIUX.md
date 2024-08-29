# E-Invoicing Application for SMEs

## Table of Contents

1. [Introduction](#introduction)
2. [Design Principles](#design-principles)
3. [User Research](#user-research)
4. [User Personas](#user-personas)
5. [Information Architecture](#information-architecture)
6. [Wireframes and Mockups](#wireframes-and-mockups)
7. [Design System](#design-system)
8. [Interaction Design](#interaction-design)
9. [Usability Testing](#usability-testing)
10. [Accessibility](#accessibility)
11. [Visual Design](#visual-design)
12. [Prototyping](#prototyping)
13. [Feedback and Iteration](#feedback-and-iteration)
14. [Tools and Resources](#tools-and-resources)
15. [Conclusion](#conclusion)

## Introduction

Welcome to the UI/UX design documentation for the E-Invoicing Application for SMEs. This project aims to support SMEs in supply-chain relationships by providing a seamless e-invoicing solution that adheres to Industry 4.0 principles and UBL 2.1 XML standards, ensuring compliance with Australian and New Zealand specifications.

## Design Principles

### Guiding Principles

Our design process is guided by the following principles:

- **User-Centered Design**: Prioritizing user needs and preferences.
- **Consistency**: Maintaining a consistent look and feel throughout the application.
- **Simplicity**: Keeping the interface simple and uncluttered.
- **Accessibility**: Ensuring the application is usable by people with diverse abilities.

### Brand Guidelines

- **Colors**: Primary: #FFFFFF, #000000, #651FFF. Secondary: #F5F5F5, #FF4081.
- **Typography**: Main font: 'Roboto', serif. Accent font: 'Adamina', serif.
- **Logos and Icons**: [Link to brand assets]

## User Research

### Methods

We conducted user interviews, surveys, and usability tests to understand user needs and pain points.

### Findings

Key insights include the need for simplified navigation, clear feedback mechanisms, and a mobile-friendly interface.

## User Personas

### Persona 1: Alice Johnson

- **Age**: 34
- **Occupation**: Supply Chain Manager at a mid-sized manufacturing company
- **Needs and Goals**:
  - Efficiently manage and track invoices.
  - Ensure compliance with industry standards.
  - Simplify the invoicing process to save time.

### Persona 2: Bob Martinez

- **Age**: 42
- **Occupation**: Owner of a small logistics company
- **Needs and Goals**:
  - Reduce manual errors in invoicing.
  - Automate invoice validation and sending.
  - Ensure data security and integrity.

### Scenarios

#### Scenario 1: Alice needs to create an invoice from a PDF

Alice receives a PDF invoice from a supplier and needs to convert it to a UBL XML format. She uses the application to upload the PDF, which then extracts the necessary data and generates a compliant UBL XML invoice. She reviews the generated invoice for accuracy and saves it for further processing.

#### Scenario 2: Bob wants to validate and send an invoice

Bob has created several invoices that need to be validated according to Australian rules before sending them to clients. He uploads the invoices to the application, which checks for compliance and generates validation reports. Bob reviews the reports, corrects any issues, and uses the application to send the validated invoices via email.

## Information Architecture

### Site Map (examples)

- **Home**: Overview, key features
- **Dashboard**: User statistics, quick actions
- **Invoices**: Create, validate, send
- **Settings**: Profile management, preferences

### Content Inventory

- **Homepage**: Introduction, key features
- **Dashboard**: Summary of recent activity, shortcuts to common tasks
- **Invoices**: Forms for creating, validating, and sending invoices
- **Settings**: User profile, notification settings

## Wireframes and Mockups

### Wireframes

- Homepage:
- Simple navigation with key features highlighted.
- Quick links to create, validate, and send invoices.
- Overview of user statistics and recent activity.

- Dashboard:
- Overview of user.
- Quick actions for creating, validating, and sending invoices.

- Invoices:
- Forms for creating, validating, and sending invoices.
- Clear instructions and tooltips for required fields and also help section created for user to lear the tools.

- Settings:
- User profile management.
- Other settings and account deletion options and user can change the name and profile pic as well.

### Mockups

- HomePage:
- Polished design with primary and secondary colors.
- Brand assets integrated.
- Intuitive layout for easy navigation.

- Dashboard:
- Clean and concise display of user history.
- Accessible quick actions.
- Modern design with consistent typography and colors.

- Invoices:
- User-friendly forms with real-time validation.
- Mobile-friendly design.

- Settings:
- Simple and intuitive user profile management.
- Easy-to-navigate preferences section.

## Design System

### Components

- **Buttons**: Primary, secondary, disabled states
- **Forms**: Input fields, dropdowns, radio buttons
- **Navigation**: Header, footer, sidebar

### Patterns

- **Modals**: Usage guidelines, examples
- **Notifications**: Success, error, information messages

## Interaction Design

### Animations

- **Loading Indicators**: Spinner, progress bar
- **Transitions**: Page transitions, element fade-ins

### Microinteractions

- **Button Hover**: Color change, shadow effect
- **Form Validation**: Real-time error feedback

## Usability Testing

### Test Plan

- **Objectives**: Validate user flows, identify pain points
- **Methods**: Remote testing, in-person sessions

### Findings

- Navigation: Users found the navigation intuitive but suggested adding a search function for quicker access to specific invoices.

- Feedback Mechanisms: Real-time validation and error messages were appreciated, but some users requested more detailed explanations for complex validation errors.

- Mobile Interface: The mobile-friendly design was generally well-received, but a few users noted that some elements were too small and difficult to interact with on smaller screens.

- Invoice Creation: Users found the process straightforward, but some requested a step-by-step guide for first-time users.

- Validation Reports: Users liked the detailed validation reports but suggested an option to download them in different formats (PDF, HTML, JSON).

### Improvements Based on Feedback:

- Search Function: Added a search bar in the navigation for quicker access to invoices.

- Detailed Error Messages: Enhanced error messages with links to more detailed explanations.

- Mobile UI Enhancements: Increased the size of interactive elements and improved the touch response.

- Step-by-Step Guide: Implemented a guided tour for first-time users to help them navigate the invoice creation process.

- Download Options: Added options to download validation reports in multiple formats.

## Accessibility

### Guidelines

We follow WCAG 2.1 guidelines to ensure accessibility:

- **Contrast Ratios**: Minimum 4.5:1 for text
- **Keyboard Navigation**: All interactive elements are keyboard accessible

### Implementations

- **Alt Text**: Descriptive alt text for all images
- **ARIA Roles**: Appropriate use of ARIA roles for dynamic content

## Visual Design

### Color Scheme

- Primary Colors: #FFFFFF, #000000, #651FFF
- Secondary Colors: #F5F5F5, #FF4081

### Typography

- **Headings**: 'Roboto', bold
- **Body Text**: 'Adamina', regular

### Imagery

- **Icons**: Consistent style, provided in SVG format
- **Illustrations**: [Link to illustration library]

## Prototyping

### Tools

- **Figma**: https://www.figma.com/design/fsc91U4aO0bs5JRX0q6LNh/MAIN-COMP3900-Design?node-id=0-1&t=3Hh25P7q9Jrzu9fh-0

### Prototypes

https://www.figma.com/design/fsc91U4aO0bs5JRX0q6LNh/MAIN-COMP3900-Design?node-id=0-1&t=3Hh25P7q9Jrzu9fh-0

## Feedback and Iteration

### Process

- **Collect Feedback**: Regular design reviews, user testing sessions
- **Implement Changes**: Iterate based on feedback

### Iterations

- Iteration 1: Initial Prototype
- Goal: Demonstrate core functionalities (create, validate, send e-invoices).
- Features: Basic invoice creation form, simple validation, basic sending functionality.
- Feedback: Users found the process straightforward but noted a lack of detailed feedback and UI inconsistencies.

- Iteration 2: Enhanced User Interface and Real-time Validation
- Changes:
- Standardized colors, fonts, and button styles for UI consistency.
- Added tooltips and guidance text for the invoice creation form.
- Implemented real-time validation and enhanced error messages with detailed explanations.
- Feedback: Improved intuitiveness and user-friendliness; issues with mobile responsiveness were noted.

- Iteration 3: Responsiveness and Final Tweaks
- Changes:
- Ensured all features were accessible on smaller screens.
- Added download options for validation reports (PDF, HTML, JSON).
- Final tweaks for overall user experience improvement.
- Feedback: Positive reception due to responsiveness and detailed validation reports.

## Tools and Resources

### Design Tools

- **Figma**: https://www.figma.com/design/fsc91U4aO0bs5JRX0q6LNh/MAIN-COMP3900-Design?node-id=0-1&t=3Hh25P7q9Jrzu9fh-0
- **Sketch**: [Link to Sketch files]
- **Adobe Creative Suite**: [Link to assets]

## Conclusion

This documentation serves as a comprehensive guide to the UI/UX design process for the E-Invoicing Application for SMEs. By following the outlined principles and guidelines, we aimed to deliver a user-friendly, compliant, and efficient solution for small and medium-sized enterprises. The user-centered design approach ensured that the application meets the needs of our target users, providing a seamless experience in creating, validating, and sending e-invoices.

### Key Achievements

- User-Centered Design: Prioritized user needs through extensive research and usability testing.

- Consistent and Simple Interface: Maintained a consistent look and feel, ensuring a simple and uncluttered user interface.

- Accessibility: Adhered to WCAG 2.1 guidelines, ensuring the application is usable by people with diverse abilities.

- Mobile-Friendly Design: Ensured the application works well on various devices, enhancing usability for users on the go.

- Iterative Improvements: Continuously improved the design based on user feedback, leading to a more refined and user-friendly application.

### Future Directions

- Enhanced Features: Explore additional features like advanced reporting, analytics, and integration with other business tools.

- Ongoing Feedback Loop: Maintain an ongoing feedback loop with users to continually refine and improve the application.

### Summary

This documentation serves as a comprehensive guide to the UI/UX design process for the E-Invoicing Application for SMEs. By following the outlined principles and guidelines, we aim to deliver a user-friendly, compliant, and efficient solution for small and medium-sized enterprises.
