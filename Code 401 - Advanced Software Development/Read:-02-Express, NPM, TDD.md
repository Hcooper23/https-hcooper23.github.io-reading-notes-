## An introduction to NodeJS and Express

- Explain middleware, answer as though I were a non-technical recruiter.

Middleware: In the context of software development, middleware refers to a layer of software components that sit between different parts of an application's system. It acts as a bridge, facilitating communication and handling requests between various components, such as web servers, databases, and application frameworks. Middleware helps to streamline the flow of data and information between these components, allowing them to work together smoothly.

- Express the most popular ____ ____.

The most popular middleware: One of the most popular middleware frameworks in the JavaScript ecosystem is Express.js. It is a lightweight and flexible web application framework for Node.js that provides a set of features to build robust and scalable web applications.

- Express is “unopinionated.” What does that mean?

Express is "unopinionated": When we say that Express is "unopinionated," it means that Express does not enforce strict rules or conventions on how you should structure your application. It gives developers a lot of freedom and flexibility in designing the application architecture and choosing the tools and libraries they prefer. This allows developers to have more control over the development process and make decisions based on the specific needs of their project.

- What is a module and why is modularity useful to us as developers?

Module and modularity: In software development, a module is a self-contained unit of code that performs a specific functionality. It can be a single file or a collection of files that work together to provide a particular feature or service. Modularity refers to the practice of breaking down a large software system into smaller, manageable modules. This approach offers several benefits to developers, such as reusability, maintainability, and the ability to work on different modules independently without affecting others. Modularity also promotes code organization and makes it easier to collaborate with other developers.

## What is NPM?

- What version of npm are you running on your machine?

9.6.4

- What command would you type to install a library/package called ‘jshint’ into your node project?

npm install jshint

## What is TDD?

- Explain why tests are important. Please explain as though I were your non technical elder.

Tests are important because they help ensure the quality and reliability of software, even for someone who is not technically inclined. Let me explain why testing is valuable to you as my non-technical elder: Confidence in the software: Tests provide a sense of confidence that the software is functioning correctly. By running tests, we can verify that the different parts of the software are working as intended. This gives you peace of mind knowing that the software is more likely to perform as expected and reduces the chances of encountering unexpected errors or issues. Bug detection and prevention: Tests act as a safety net to catch bugs and issues before they reach the end-users. When we write tests, we simulate different scenarios and inputs to ensure that the software behaves correctly. By identifying and addressing issues early in the development process, we can prevent potential problems that might otherwise arise during actual usage. Code maintainability and refactoring: Writing tests encourages good software design and modularity. Tests serve as documentation for the expected behavior of the code. When we need to make changes or improvements to the software, having tests in place allows us to verify that the existing functionality remains intact. This makes it easier to refactor or modify the code without introducing unintended bugs or breaking existing features.

- What are three expected benefits of testing

Bug detection and prevention: Tests help catch bugs and issues early, reducing the chances of encountering unexpected errors and improving the overall quality of the software.

Code stability and maintainability: Tests act as a safety net during code changes, allowing developers to refactor and improve the codebase with confidence that existing functionality remains intact.

Collaboration and teamwork,: Tests serve as documentation for the expected behavior of the code, making it easier for team members to understand and work with the codebase. They promote collaboration and improve communication between developers.

- Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

Over-reliance on tests: Sometimes developers get too focused on writing tests and spend too much time on tests instead of actual code implementation.

Incomplete coverage: It is possible to unintentionally overlook certain scenarios or edge cases when writing tests, resulting in incomplete test coverage and leaving potential bugs undetected.

Lack of test maintenance: As the codebase evolves, the tests need to be updated regularly. If teams neglect to maintain and update tests, they can become outdated, leading to false positives or false negatives.

Inadequate communication: When working in a team, it is essential to have effective communication about the purpose and scope of tests. Lack of clear communication can result in duplicate or conflicting tests, wasting time and effort.

## CI/CD

- What are three benefits of Continuous Integration?

Early detection of integration issues: CI involves automatically merging code changes from multiple developers into a shared repository several times a day. By doing so, CI quickly identifies any conflicts or integration issues that may arise when different code changes are combined. This allows developers to address these issues early on, preventing them from accumulating and becoming harder to resolve later.

Faster feedback loop: With CI, automated tests are triggered after each code change is merged. This provides rapid feedback on the quality and functionality of the software. By catching bugs and issues early in the development process, CI enables faster iteration and reduces the time spent on debugging and fixing problems.

Continuous quality assurance: CI promotes a culture of quality and encourages developers to write comprehensive tests that are automatically executed. This helps ensure that the software meets the required standards and functionality with each code change. CI also facilitates the use of code analysis tools that can identify potential code smells, security vulnerabilities, or performance bottlenecks.

What is the difference between Continuos Delivery and Continuous Deployment?

Continuous Delivery (CD): CD focuses on automating the software release process to make it reliable and efficient. It ensures that the software can be delivered to production environments at any time. However, the decision of when to release the software to users is still a manual one. In CD, the software is ready for deployment, but the actual deployment process may require human intervention.

Continuous Deployment (CD): CD takes the automation further by automatically deploying the software to production environments once it passes the necessary tests and quality checks. In this case, there is no manual intervention required for the deployment process. The software is deployed as soon as it is ready, allowing for rapid and frequent releases.

Explain how GitHub fits into this process assuming the listener comes from a non-technical background

GitHub is a web-based platform for version control and collaboration, primarily used for managing and sharing source code. It plays a vital role in supporting the CI/CD process. In conclusion, GitHub acts as a central code repository, facilitates code reviews, integrates with CI/CD tools, and provides collaboration and project management features to support the development and delivery of software in a collaborative and efficient manner.

## Things I want to know more about
