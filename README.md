# Try Out Development Containers: Nuxt.js

This is a sample project that lets you try out the **[VS Code Remote - Containers](https://aka.ms/vscode-remote/containers)** extension in a few easy steps.

> **Note:** If you're following the quick start, you can jump to the [Things to try](#things-to-try) section. 

## Setting up the development container

Follow these steps to open this sample in a container:

1. If this is your first time using a development container, please follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. If you're not yet in a development container:
   - Clone this repository.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and try things out!

## Things to try

One you have this sample opened in a container, you'll be able to work with it like you would locally.

Some things to try:

1. **Terminal:** Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>\^</kbd> and type `yarn create nuxt-app .` and answering questions from the terminal window.
2. **Edit:**
   - Open `pages/index.vue`
   - Try adding some code and check out the language features. To format code press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>I</kbd> . It is also possible to go to definition of a custom element by clicking one. Notice that `vscode-eslint`, `vue-peek` and the `vetur` extension are already installed in the container.
3. **Run:**
   - Type `yarn run dev` from the terminal window.
   - Then open a local browser and go to `http://localhost:3000` and note you can connect to the Nuxt App in the container.
4. **Debug with Breakpoints:**
   - Open `Chrome DevTools` Sources tab with <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>I</kbd> in Chrome.
   - Add a breakpoint in `webpack:///pages/index.vue` (e.g. on line 29).
   - Press <kbd>F5</kbd> to reload the page.
   - Once the breakpoint is hit, try hovering over variables, examining locals, and more.
   - Notice: Debug on VSCode is a bug. 

microsoft/vscode-chrome-debug#832

## Contributing

This project welcomes contributions and suggestions.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## License

Licensed under the MIT License. See LICENSE in the project root for license information.
