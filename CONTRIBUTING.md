# Contributing to the Sensor Board Project

This guide helps team members contribute effectively to the project.

## Team Members

- **Alex Lennon**: Software Lead
- **Anthony Lennon**: Student Developer
- **Michael Hull**: Hardware Lead
- **Ollie Hull**: Hardware Team

## Development Workflow

### 1. Getting Started
1. Clone the repository
2. Set up your development environment
3. Read the README and docs/project_management/PROJECT_PLAN.md
4. Check the current project status

### 2. Making Changes

#### For Software Changes
1. Create a feature branch: `git checkout -b feature/your-feature-name`
2. Make your changes
3. Write or update tests
4. Update documentation if needed
5. Commit with clear messages
6. Push to your branch
7. Create a pull request or request review

#### For Documentation Changes
1. Create a branch: `git checkout -b docs/your-doc-update`
2. Update the relevant documentation
3. Ensure it aligns with OCR requirements
4. Commit and push
5. Request review

#### For Hardware Changes
1. Coordinate with software team
2. Update hardware specifications
3. Document changes
4. Share schematics/designs

### 3. Code Standards

#### General Principles
- Write clear, readable code
- Follow language-specific style guides
- Comment complex logic
- Write self-documenting code when possible
- Keep functions focused and small

#### Documentation
- Document all public APIs
- Include docstrings/comments
- Update README files when needed
- Keep OCR documentation up to date

#### Testing
- Write tests for new features
- Ensure tests pass before submitting
- Aim for good test coverage
- Test error cases

### 4. Commit Messages

Write clear, descriptive commit messages:

```
Good: "Add temperature sensor reading functionality"
Good: "Fix I2C communication timeout issue"
Good: "Update analysis documentation with stakeholder details"

Bad: "fix"
Bad: "updates"
Bad: "stuff"
```

### 5. Code Review Process

1. Request review from appropriate team member
2. Address feedback promptly
3. Discuss any disagreements
4. Merge after approval

### 6. Documentation Updates

When making code changes:
- Update relevant documentation
- Keep OCR documentation aligned
- Update README if structure changes
- Document new features

## Communication

### Regular Meetings
- Weekly team meetings
- Progress updates
- Issue discussions
- Planning sessions

### Communication Channels
- [To be defined - email, Slack, etc.]

### Reporting Issues
- Use clear descriptions
- Include steps to reproduce
- Provide context
- Suggest solutions if possible

## Learning and Mentoring

### For Anthony (Student)
- Ask questions freely
- Review code with Alex
- Learn from code reviews
- Practice regularly
- Document your learning

### For Mentors
- Provide clear guidance
- Explain decisions
- Encourage questions
- Review code constructively
- Celebrate progress

## Project-Specific Guidelines

### OCR Documentation
- Keep all OCR documentation in `docs/` folder
- Follow the structure for each section
- Update regularly as project progresses
- Ensure alignment with assessment criteria

### Hardware-Software Integration
- Coordinate changes that affect both
- Update specifications when hardware changes
- Test integration regularly
- Document interface changes

### Version Control
- Commit frequently
- Use meaningful branch names
- Keep commits focused
- Write clear commit messages
- Don't commit sensitive data

## Getting Help

- **Technical Questions**: Ask in team meetings or directly
- **Git Issues**: Check Git documentation or ask for help
- **Project Questions**: Review documentation or ask team
- **Learning Questions**: Anthony should ask Alex or team

## Best Practices

1. **Start Small**: Begin with simple tasks
2. **Test Often**: Test as you develop
3. **Document As You Go**: Don't leave documentation to the end
4. **Communicate**: Keep team informed
5. **Review Regularly**: Review code and documentation
6. **Learn Continuously**: Keep learning and improving

## Questions?

If you're unsure about anything:
1. Check the documentation
2. Ask the team
3. Review similar work in the project
4. Don't hesitate to ask for help

Happy coding! 🚀
