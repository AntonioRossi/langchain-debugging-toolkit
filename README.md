# Langchain Debugging Toolkit

Welcome to the Langchain Debugging Toolkit, your go-to platform for a seamless, interactive, and insightful debugging experience with the Langchain library. This is a well-structured TypeScript Node project with a bare minimum setup aimed to get you started in no time.

Whether you're a beginner getting your feet wet or a seasoned developer keen on rapidly prototyping and testing with Langchain, this project is for you!

## Key Features

- **Quick & Easy Setup:** You can get started in minutes, not hours.
- **Interactive Debugging:** With Visual Studio Code's powerful debugging functionality, interact directly with the Langchain library.
- **Minimalistic Approach:** Uses only essential libraries to reduce setup complexity and potential version conflicts.
- **Security-conscious:** Designed with careful attention to keep your sensitive data, such as session IDs, secure.

## Getting Started

Starting with the Langchain Debugging Toolkit is as simple as 1-2-3:

1. Clone this repository.
```bash
git clone https://github.com/yourusername/langchain-debugging-toolkit.git
```
2. Move into the project directory.
```bash
cd langchain-debugging-toolkit
```
3. Install the dependencies.
```bash
yarn install
```

4. Substiture the code in the file `index.ts` with the example you want to work with.

5. Follow the instruction in the documentation website for installing additional tools (i.e. vector stores) and configure the API keys for the services you want to use (i.e. openai).

6. Begin your debugging journey by simply adding your breakpoints and start a debug session in visual studio code!

## Code Structure

- **index.ts:** Houses the main script where Langchain model and memory are initialized and tested.
- **task.json:** Defines a TypeScript transpilation task in watch mode.
- **launch.json:** Contains configurations for launching and attaching to a Node.js process.
- **tsconfig.json:** Specifies root files and compiler options for project compilation.
- **package.json:** Enumerates project dependencies and relevant scripts.

## Contributing

Community contributions are not just welcomed but are heartily appreciated. If you've got an idea for improvement, found a bug that needs squashing, or have a refined code implementation, we're all ears. Remember, great projects are the result of many small contributions stacked together.

Refer to our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) to ensure a positive and collaborative environment.

## License

This project is licensed under the terms of the [MIT license](https://opensource.org/license/mit/).

We look forward to seeing you debug and develop with us. Happy Coding!
