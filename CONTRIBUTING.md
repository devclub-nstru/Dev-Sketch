# Dev-Sketch Contributing Guidelines

## About Dev-Sketch
Dev-Sketch is an open-source collaborative platform for real-time drawing, coding, and communication. Contributors play a key role in enhancing its features and ensuring an optimal experience for users.

## Tech Stack
- **Frontend:** React, Next.js
- **Backend:** Node.js, Express
- **Database:** PostgreSQL (Prisma ORM)
- **WebSockets & RTC:** Websockets, WebRTC

## Contribution Workflow

### Branch Strategy
- `main`: Stable production-ready code
- `develop`: Integration branch for features
- `feature/*`: Individual feature development
- `hotfix/*`: Critical bug fixes

### Getting Started
1. **Fork & Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/dev-sketch.git
   ```
2. **Create a Feature Branch:**
   ```bash
   git checkout -b feature-name
   ```
3. **Implement Changes & Commit:**
   ```bash
   git commit -m "Fix: [Short Description of Fix]"
   ```
4. **Push & Submit a Pull Request (PR):**
   ```bash
   git push origin feature-name
   ```
   - Clearly describe the changes in your PR.
   - Reference the issue number.
   - Request a review from a maintainer.

## Code Quality & Standards

### TypeScript & React Best Practices
- Use strict mode and TypeScript best practices.
- Follow clean code principles.
- Use functional components and hooks.
- Implement proper prop validation.
- Optimize performance using React.memo and useCallback.

### Node.js & Express Best Practices
- Follow RESTful API design principles.
- Implement middleware for authentication & security.
- Use environment variables for sensitive data.
- Optimize database queries for performance.

### Performance & Security Considerations
- Minimize re-renders using React optimizations.
- Implement rate limiting for API requests.
- Use caching for frequently accessed data.
- Conduct regular security audits.
- Enforce HTTPS and validate user input.

## Code Review Checklist

### General
- Code follows style guidelines.
- Proper error handling is implemented.
- No unnecessary comments or unused code.

### Performance
- Efficient state management.
- Optimized WebSocket handling.
- No redundant API calls.

### Security
- No hardcoded credentials.
- Proper authentication and input validation.
- Adherence to security best practices.

## Continuous Integration
- Automated testing on PRs.
- Linting and formatting checks.
- Dependency security scanning.

## Documentation Standards
- Keep `README.md` updated.
- Document complex components and APIs.
- Maintain a clear `CHANGELOG.md`.

## Community & Collaboration Guidelines
Dev-Sketch encourages open-source collaboration in a respectful and productive environment.

### Guidelines
- No issue hoarding—work on one issue at a time.
- Respect others' contributions.
- Provide constructive PR reviews.
- Encourage and help newcomers.
- Follow ethical coding practices.

### Imposter Syndrome Disclaimer
We welcome all contributions, whether it’s code, documentation, or feedback. If you’re hesitant to contribute, remember that everyone starts somewhere. Feel free to ask questions, and we’ll help you along the way.

### Need Help?
If you have any questions, reach out to the maintainers or ask in our community discussion forums.

Happy Coding! 🚀
