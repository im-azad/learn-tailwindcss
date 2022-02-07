<p align="center">
  <h3 align="center">Lesson - 2 : Tailwind CSS</a></h3>
</p>

## How to run this branch

This branch contains the lesson-2 source code shown in the Tutorial Series. To run the project follow the below steps:

1. Node project initialization.
    ```sh
    npm init -y
    ```
2. Tailwind css install on developer dependency mood.
    ```sh
    npm i -D tailwindcss
    ```
3. Create your tailwind.config.js file this CLI.
    ```sh
    npx tailwindcss init
    ```
4. Configure your template paths
   Add the paths to all of your template files in your tailwind.config.js file.
    ```sh
    npx tailwindcss init
    ```
5. Create src and output folder. Create a src/tailwind.css file on src folder.
   Add the Tailwind directives to your CSS
   Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.
    ```sh
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
6. Start the Tailwind CLI build process on package.json file
    ```sh
      "scripts": {
          "build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w"
        },
    ```
    OR Run the CLI tool to scan your template files for classes and build your CSS.
    ```sh
    npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
    ```
    Link up output/tailwind.css in main html file.
7. Run your tailwindcss wit build command.

    ```sh
    npm run build
    ```

8. Right click on the editor and click "Open with Live Server". You need to install the Live Server VS Code Plugin before that.
9. Project should be up and running in your browser.

<!-- CONTACT -->

## Contact

Abul Kalam Azad - [me.azad99@gmail.com](mailto:me.azad99@gmail.com)
