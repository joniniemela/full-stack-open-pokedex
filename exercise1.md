There are several tools being used to check code. The specific tools are same as we would use manually to check code validity and test it properly. In this case which includes Javascript/Typescript fullstack application with React frontend we use tools listed below. We just basically automate the process of running these tools in CI setup.

Tools for linting include:

- ESLint with proper config and commands in CI to execute check and fix
- Prettier for code formatting

Tools for testing include:

- Proper tests inside code and commands executed regarding that in CI process
- Jest for frontend React testing in JS/TS
- Cypress for testing user-level functionality

Tools for building include:

- Typescript compiler with proper config for building production-ready version

Alternative options for setting up CI environment includes for example:

- Octopus Deploy → Best for complex deployments
- Bitrise → Used in mobile application development
- Google Cloud Build → Has advanced collaborative features and native google services integrations

This setup is best in a cloud-based environment, because the steps involved in making all the linting, tests and builds does not draw a significant amount of system resources from the automation setup. Web-based application compiling is usually a light process and cloud-based solutions should cover that in small to medium scale projects. It is also way more cost efficient in this scale, as we don’t have to invest any capital into on-premises hardware for that project.