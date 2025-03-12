## 🛠️ Description
<!--- Describe your changes so that a reviewer can easily identify and understand them -->

## 📸 Screenshot or recording
<!--- Add screenshots of what you changed, if applicable -->

## 🧪 How Has This Been Tested?
<!--- Please describe in detail how you tested your changes. -->
<!--- Consider how your change affects other areas of the code as well -->

## 🖺 Documentation
<!--- Please add the link to Confluence if there is a documentation -->

## 🔗 Related Issue
<!--- Please link to the JIRA issue here: -->

## 📋 PR Checklist
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->

### Testing
- [ ] I have added tests to cover my changes
- [ ] I have considered how my changes can affect other parts of the system, and tested those areas
- [ ] I've verified that my changes fulfill non-functional requirements like performance and accessibility

### Code Format and Style
- [ ] I've run Prettier lint
- [ ] I've addressed all suggestions from SonarQube
- [ ] I haven't left unnecessary logs or comments

### Maintainability
- [ ] Is the code easy to read and understand?
- [ ] Is the code not repeated (DRY Principle)?
- [ ] Is the code method/class structure good?

### Documentation
- [ ] I have updated related documentation if necessary

### Implementation
- [ ] I've considered rendering techniques (like client vs server) and chosen a fitting method 
- [ ] Responsiveness is made without JS usage - only via Tailwind usage or custom CSS implementation

### Best Practices
- [ ] I have proper error handling, especially if making requests to an external endpoint
- [ ] Important Errors and warnings are logged on an adequate logging level

### Architecture
- [ ] Is the separation of concerns-principle followed?
- [ ] Are all relevant parameters configurable and is the feature toggleable if necessary?
