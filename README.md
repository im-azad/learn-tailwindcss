<p align="center">
  <h3 align="center">Tailwind CSS</a></h3>
</p>

## Setup tailwind css on your project.

To run the project follow the below steps:

1.  Node project initialization .
    ```sh
    npm init -y
    ```
2.  Tailwind css install on developer dependency mood.

    ```sh
    npm i -D tailwindcss
    ```

3.  Configure your template paths. Create your tailwind.config.js file this CLI.
    Add the paths to all of your template files in your tailwind.config.js file.
    ```sh
    npx tailwindcss init
    ```
4.  Create src and output folder. Create a src/tailwind.css file on src folder.
    Add the Tailwind directives to your CSS
    Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.
    ```sh
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
5.  Then create a .vscode/setting.json file to control vscode customs sitting.

    ```sh
     {
       "css.validate": false,
       "tailwindCSS.emmetCompletions": true
     }
    ```

6.  Start the Tailwind CLI build process on package.json file

    ```sh
      "scripts": {
          "build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w"
        },
    ```

    Link up output/tailwind.css in main html file.

7.  Run your tailwindcss with build command.

    ```sh
    npm run build
    ```

8.  Right click on the editor and click "Open with Live Server". You need to install the Live Server VS Code Plugin before that.

9.  Project should be up and running in your browser.

<!-- CONTACT -->

## Contact

Abul Kalam Azad - [me.azad99@gmail.com](mailto:me.azad99@gmail.com)
