"# Calculator" 

1. Create a repository.
2. Clone the repository in the folder that you want to make your project in.
3. Make tsconfig file in the project by "tsc –init" command in terminal.
4. For package.json file type "npm init" command.
5. Run "npm i inquirer -S" command to install the inquirer package as a runtime dependency (-S or --save).
6. Run "npm i @types/node -D" command to install type definitions for Node.js as a development dependency (-D or --save-dev).
7. Run "npm i @types/inquirer -D" command to install type definitions for the inquirer package as a development dependency.
8. In your package.json file after “main”:”index.js” add-> “type”:”module”.
9. In tsconfig.json update “target”:”ESNext” and “module”:”NodeNext” and uncomment “moduleResolution”:”NodeNext”.
10. Write code in index.ts after import inquirer from “inquirer”.
11. Transpile it by running "tsc" command in your terminal.
12. Run yout project by "node index" or "node index.js" command.
13. Now make it an npm tool.
14. In your index.ts file in the first line type "#! /usr/bin/env node".
15. Run "npm login" in your terminal.
16. Run "npm publish"
17. To access your project from any device type "npx name-of-package" or "npm i name-of-package" in your command prompt.