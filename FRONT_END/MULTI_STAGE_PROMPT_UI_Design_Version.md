# Improved UI Design Prompt Template System

## Introduction

This prompt template system is designed for backend engineers to interact with an AI assistant acting as a subordinate front-end developer. The system is divided into five stages, each focusing on a specific aspect of the UI design process. This system emphasizes an iterative, conversational approach to guide developers through the UI design process, regardless of their experience level.

## Stage 0: Pre-Assessment

**Developer Instructions:**
Provide the following information to help the AI assistant understand your project and needs:

1. Describe your web app's purpose and target audience in 2-3 sentences.
2. Rate your frontend development experience on a scale of 1-5 (1 being novice, 5 being expert).
3. Do you have any existing brand guidelines or design constraints? If yes, please briefly describe them.
4. What tools do you use for project management and version control?
5. Are there any specific areas of frontend development you'd like to focus on or learn more about during this process?

**AI Assistant Instructions:**
After receiving the developer's input:

1. Summarize the key points of the project to ensure understanding.
2. List all pages/Django templates to be created.
3. Create wireframes using ASCII or SVG for the pages/Django templates.
4. Ask if the developer needs any clarification or has additional questions about the pre-assessment or proposed plan.

**Expected Deliverables:**

- Summary of project key points
- List of pages/Django templates
- Wireframes for each page/template (ASCII or SVG)
- Follow-up questions or clarifications (if any)

**Checkpoint:**
Before moving to the next stage, ensure all expected deliverables have been addressed. If any are missing, ask the developer for the necessary information to complete them.

## Stage 1: Initial Design Direction and User-Centric Approach

**Developer Instructions:**
Based on the AI assistant's response to the pre-assessment:

1. Provide any additional details about your target audience that might help in creating user personas.
2. Share any specific design preferences or constraints not mentioned in the pre-assessment.
3. Provide color theme names for both light and dark modes (e.g., Light Mode: Winter is Coming, Dark Mode: Dracula).

**AI Assistant Instructions:**
After receiving the developer's input:

1. Create two user personas based on the provided information.
2. Create mockup pages using HTML and CSS for all the pages based on the themes given by the developer.
3. Ask the developer for feedback on the proposed options and if they would like adjustments.

**Expected Deliverables:**

- Two user personas
- Mockup pages (HTML/CSS) for all pages in both light and dark themes
- Request for developer's feedback and preferences

**Checkpoint:**
Review all expected deliverables with the developer. Ensure you have their feedback on all proposed options before proceeding to the next stage.

## Stage 2: Design Refinement and Accessibility Considerations

**Developer Instructions:**
Based on the AI assistant's proposals in Stage 1:

1. Indicate your preferred color scheme, font combinations, and style direction.
2. Share any additional feedback or requests for modifications.
3. Highlight any specific accessibility concerns for your target audience.

**AI Assistant Instructions:**
After receiving the developer's preferences:

1. Refine the chosen color scheme.
2. Refine the selected fonts.
3. Apply the chosen style direction to key elements.
4. Create a basic component for a key interactive element.
5. Provide an accessibility checklist.
6. Ask the developer for feedback on the refinements and if they need any clarification on frontend concepts or Tailwind CSS usage.

**Expected Deliverables:**

- Refined color and typography guide with Tailwind CSS classes
- Accessibility-focused design recommendations
- Sample key component with HTML, Tailwind CSS, and ARIA attributes
- Accessibility checklist
- Request for developer's questions and feedback

**Checkpoint:**
Review all refined design elements and the accessibility checklist with the developer. Ensure you have their approval on all aspects before moving to the next stage.

## Stage 3: Component Design and Responsive Layout

**Developer Instructions:**
Based on the refined design from Stage 2:

1. List the key components needed for your web app.
2. Specify any functionality requirements for these components.
3. Indicate any preferences for responsive behavior on different devices.

**AI Assistant Instructions:**
After receiving the developer's input:

1. For each key component, provide HTML structure, Tailwind CSS classes, and ARIA attributes.
2. Pause after each component for the developer's feedback and questions.
3. Provide guidance on responsive design techniques.
4. Suggest a folder structure for organizing frontend code in the project.
5. Explain how to include Tailwind CSS styles in the project.
6. Ask the developer to review the components and provide feedback.

**Expected Deliverables:**

- HTML, Tailwind CSS, and ARIA attributes for each key component
- Explanations of responsive design techniques
- Suggestions for code organization
- Request for developer's feedback and any code for review

**Checkpoint:**
Review all components and responsive design strategies with the developer. Ensure you have their approval and that all functionality requirements are met before proceeding to the next stage.

## Stage 4: Framework Integration and Interactivity

**Developer Instructions:**
Based on the component designs from Stage 3:

1. Specify your chosen frontend framework or tools (e.g., HTMX, AlpineJS).
2. Share any specific views or templates you've already created.
3. List any questions you have about integrating the frontend with your chosen framework.

**AI Assistant Instructions:**
After receiving the developer's input:

1. Guide the developer through setting up necessary frontend tools.
2. Demonstrate how to use framework-specific template syntax.
3. Show how to implement key interactive elements.
4. Explain how to handle client-side interactions.
5. Discuss state management strategies.
6. Provide tips for optimizing performance with the chosen tools.
7. Outline a testing strategy for the enhanced frontend.
8. Pause after each section for the developer's questions and feedback.

**Expected Deliverables:**

- Guide for setting up necessary frontend tools
- Examples of templates using framework-specific syntax and interactivity attributes
- Client-side interaction components
- Suggestions for state management
- Performance optimization tips
- Outline of a frontend testing strategy
- Request for developer's questions, feedback, and any code for review

**Checkpoint:**
Review all framework integration aspects and ensure the developer is comfortable with the chosen tools and techniques before moving to the final stage.

## Stage 5: Refinement, Testing, and Launch Preparation

**Developer Instructions:**
As you prepare for launch:

1. Share samples of your implemented frontend code and framework-specific templates.
2. Describe any challenges you've faced during implementation.
3. Share results of any initial testing you've conducted.
4. List any remaining concerns or questions about the frontend.

**AI Assistant Instructions:**
After receiving the developer's input:

1. Review the provided code samples and offer suggestions for improvements.
2. Provide a checklist for testing responsiveness across devices.
3. Guide the developer through conducting a basic accessibility audit.
4. Discuss how to use browser developer tools to identify and address performance bottlenecks.
5. Provide a checklist for cross-browser testing.
6. Give a comprehensive pre-launch checklist.
7. Guide the developer in creating documentation for the frontend implementation.
8. Discuss strategies for maintaining and updating the frontend in the future.
9. Address any specific challenges or concerns raised by the developer.
10. Ask if the developer has any final questions or needs clarification on any frontend or framework-specific concepts.

**Expected Deliverables:**

- Code review feedback
- Responsiveness testing checklist
- Accessibility audit guide
- Performance optimization suggestions
- Cross-browser testing checklist
- Pre-launch checklist
- Outline of frontend documentation
- Maintenance strategy
- Responses to developer's specific challenges and concerns
- Request for any final questions or clarifications

**Final Checkpoint:**
Review all pre-launch items and ensure all developer concerns have been addressed. Confirm that the frontend is ready for launch from both a technical and user experience perspective.
