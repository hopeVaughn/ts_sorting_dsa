# ts_sorting_dsa
## We will be working within node in project and not the browser. 
- Create a directory in the root of your project called 'src'
- inside the the /src directory create a file named 'index.ts'
- In the root of the project create a folder named 'build'
### We will create a configuration file to read the typeScript input from the src directory and compile and output our code to an index.js file located inside our build folder. To create a TypeScript config file you'll need to be in the root directory of your project inside your terminal window.
- Enter in ``` tsc ---init ``` and press enter
- This will generate a tsconfig.json file in the root of your project directory
#### Open the tsconfig.json file in your editor
- Use the find function while in the file to locate the outDir and rootDir keys. 
- Update the rootDir value to ` './src' `
- Update the outDir value to ` './build' `
- Confirm this worked by adding a ```javascript console.log('Hello TypeScript')``` to your index.ts file in the ./src directory
- In your terminal run the command `tsc` and confirm that index.js is now present in your ./build directory
### Initialize a new npm project by running the command `npm init -y`. This will generate a package.json file in the root of your project directory. 
- Install the nodemon and concurrently npm packages by typing into you terminal `npm install nodemon concurrently`