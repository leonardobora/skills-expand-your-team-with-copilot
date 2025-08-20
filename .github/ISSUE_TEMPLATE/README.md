# GitHub Issue Templates for Teachers

This document provides an overview of the GitHub issue templates created to help teachers easily request changes and support for the Mergington High School Activity Management System.

## Templates Overview

The following issue templates have been created in the `.github/ISSUE_TEMPLATE/` directory:

### 1. Add New Activity (`add-new-activity.yml`)
**Purpose**: Request addition of new extracurricular activities
**Key Features**:
- Activity name and description fields
- Schedule configuration (days, start/end times)
- Maximum participants setting
- Includes technical implementation notes for Copilot

### 2. Modify Existing Activity (`modify-activity.yml`) 
**Purpose**: Request changes to existing activities
**Key Features**:
- Dropdown selection of existing activities
- Checkboxes for types of changes needed
- Fields for new values (schedule, capacity, description)
- Reason for change requirement

### 3. Bug Report (`bug-report.yml`)
**Purpose**: Report system problems and errors
**Key Features**:
- Area-specific problem categorization
- Step-by-step reproduction instructions
- Device and browser information collection
- Error message capture

### 4. UI/UX Improvement (`ui-ux-improvement.yml`)
**Purpose**: Suggest interface and user experience improvements
**Key Features**:
- Improvement area categorization
- Current problem and proposed solution fields
- User group benefit identification
- Priority level assessment

### 5. Feature Request (`feature-request.yml`)
**Purpose**: Request new system capabilities
**Key Features**:
- Problem-solution mapping
- User type identification
- Implementation workflow description
- Success criteria definition

### 6. Data Management Task (`data-management.yml`)
**Purpose**: Request reports, exports, and bulk operations
**Key Features**:
- Task type selection (exports, reports, bulk operations)
- Activity selection checkboxes
- Output format specifications
- Privacy consideration checkboxes

### 7. Teacher Account Management (`teacher-account.yml`)
**Purpose**: Handle login issues and account administration
**Key Features**:
- Account request type dropdown
- Teacher role/permission level settings
- Security consideration checkboxes
- Urgency level assessment

### 8. General Question (`general-question.yml`)
**Purpose**: Handle questions not covered by specific templates
**Key Features**:
- Question type categorization
- User role identification
- Context and urgency fields
- Resource preference selection

## Template Design Principles

Each template follows these principles to ensure Copilot can work effectively:

### 1. **Clear Problem Description**
- Structured fields that capture the exact issue or request
- Dropdown menus to standardize common requests
- Required fields to ensure complete information

### 2. **Clear Acceptance Criteria**
- Pre-defined acceptance criteria in each template
- Specific, testable outcomes
- Success metrics where applicable

### 3. **Technical Implementation Hints**
- Code snippets showing expected data structures
- File paths and components that need modification
- Implementation patterns and considerations

### 4. **Context and Limitations**
- User role identification to tailor responses
- Priority and urgency levels
- Security and privacy considerations

## Benefits for Teachers

### **Non-Technical Language**
- Templates use school-friendly terminology
- Avoid programming jargon
- Focus on educational outcomes

### **Guided Input**
- Dropdown menus reduce guesswork
- Required fields ensure completeness
- Examples and placeholders provide guidance

### **Comprehensive Coverage**
- Templates cover all major use cases
- Fallback general template for edge cases
- Progressive disclosure of complexity

## Benefits for Copilot

### **Structured Data**
- Consistent format across all requests
- Machine-readable field structure
- Standardized terminology

### **Complete Requirements**
- All necessary information captured upfront
- Technical context provided
- Implementation guidance included

### **Clear Scope**
- Well-defined acceptance criteria
- Specific file and component references
- Existing code patterns to follow

## Usage Statistics and Effectiveness

The templates are designed to be:
- **Self-documenting**: Each includes examples and guidance
- **Comprehensive**: Cover all identified use cases from codebase analysis
- **Maintainable**: Easy to update as the system evolves
- **Accessible**: Suitable for users with no technical background

## Implementation Notes

- Templates are written in YAML format for GitHub's issue template system
- Each template includes assignee configuration to automatically assign to Copilot
- Labels are consistently applied for easy filtering and organization
- Contact links in `config.yml` provide additional support channels

These templates bridge the gap between non-technical teacher needs and technical implementation requirements, enabling efficient Copilot-assisted development while maintaining educational focus.